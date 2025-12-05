# Commit Messages Guidelines

🚧 *This is a draft. May be adjusted as needed.*

> [!IMPORTANT]
> Commit messages are written in english, according to the group's language policy.

## 1. Purpose

This document defines how commit messages must be written in all ROOTS projects.

Following a unified convention ensures:

* Readable project history
* Automated changelog generation
* Correct semantic versioning
* Proper linking and automatic closure of GitHub issues
* Clear understanding of the intent of each change

These rules apply to all contributors, including maintainers.

---

## 2. Commit Message Format (Required)

A commit message consists of **three parts**:

```
<type>[!]: <short summary>
<blank line>
<body> (optional)
<blank line>
<footer> (optional)
```

Example:

```
feat: add LED animation engine

Implements the new animation pipeline that will be used by all
display-based devices.

closes #24
```

---

## 3. Allowed Commit Types

The types and their meanings:

| Type         | Meaning                                                                   |
| ------------ | ------------------------------------------------------------------------- |
| **feat**     | A new user-visible feature                                                |
| **fix**      | A bug fix                                                                 |
| **docs**     | Documentation-only changes                                                |
| **refactor** | Code restructuring, no functional change                                  |
| **test**     | Adding or updating tests                                                  |
| **chore**    | Maintenance tasks (dependencies, CI, config)                              |
| **perf**     | Performance improvements                                                  |
| **build**    | Build system or tooling changes                                           |
| **hw**       | Hardware-specific contributions (schematics, PCB, enclosure, BOM changes) |

These types align with SemVer and changelog categories.

---

## 4. Breaking Changes

If a commit introduces a breaking change, use **one** of the following:

### Option A — Exclamation mark after type

```
feat!: overhaul the communication protocol
```

### Option B — BREAKING CHANGE block in footer

```
refactor: remove legacy LED driver

BREAKING CHANGE: The old driver class has been removed.
```

Breaking changes trigger a **MAJOR** version bump.

---

## 5. Summary Line Rules

The first line must follow these rules:

* ≤ 72 characters
* Written in the imperative mood

  * “add support for…”, not “added support for…”
* Describe what the change does, not how

Correct examples:

* `fix: correct buffer overflow in frame parser`
* `docs: update API usage examples`
* `hw: add PCB v0.4 draft with new power stage`

Incorrect:

* `fixed buffer`
* `minor changes`
* `update stuff`

---

## 6. Body (Optional but Recommended)

Use the body to explain:

* *Why* the change was made
* Relevant design decisions
* Limitations or trade-offs
* Links to related discussions

Wrap lines to 80 characters when possible.

Example:

```
fix: handle null tokens in parser

The previous implementation assumed all tokens were non-null,
which caused a crash when loading user-generated text files.
```

---

## 7. Footer (Optional, Structured)

### 7.1 Issue Linking & Automatic Closing

Use GitHub keywords to link commits to issues or pull requests:

```
closes #123
fixes #45
resolves #78
```

Rules:

* Must be at the **start of a footer line**
* Multiple issues allowed (one per line)

### 7.2 Metadata

Footers may include structured sections such as:

```
Co-authored-by: Name <email>
Signed-off-by: Name <email>
BREAKING CHANGE: ...
```

---

## 8. Relation to Semantic Versioning

Commits help determine the next version bump:

| Commit Type                                         | Version Impact                           |
| --------------------------------------------------- | ---------------------------------------- |
| **feat**                                            | MINOR                                    |
| **fix**                                             | PATCH                                    |
| **feat!**, BREAKING CHANGE                          | MAJOR                                    |
| **docs**, **chore**, **refactor**, **test**, **hw** | No version bump unless behaviour changes |

All user-visible changes must also be reflected in the **CHANGELOG**.

---

## 9. Examples

### Feature

```
feat: add user profile management screen
closes #140
```

### Bug fix with explanation

```
fix: prevent crash when Wi-Fi reconnects

The previous state machine did not reset after reconnection,
leading to undefined behaviour.
```

### Breaking change

```
refactor!: replace configuration file format with JSON
```

### Hardware change

```
hw: update buck converter footprint for Rev B board
```

## 10. Related Documentation

* [Versioning Guidelines](./versioning.md)
* [Changelog Guidelines](./changelog.md)