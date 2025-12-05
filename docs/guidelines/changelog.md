# Changelogs

🚧 *This is a draft. May be adjusted as needed.*

> [!IMPORTANT]
> The Changelog is written in English, according to the group's language policy.

# 1. Purpose

A Changelog serves to clearly and neatly record **all relevant changes** made to a project over time. Each repository contains a `CHANGELOG.md` file.

> [!TIP]
> The content of this file is closely related to the [versioning system](./versioning.md) and [commit policy](./commit-messages.md) used.

Below are some motivational aspects for its use in open-source projects:

* **Transparency for users and contributors** — Allows one to quickly see what changed between releases without having to review commits or pull requests.
* **Efficient communication** — Helps communicate fixes, new features, improvements, and breaking changes.
* **Documented history** — Maintains an official record of the project’s evolution, useful for debugging, audits, and reviews.
* **Facilitates updates** — Helps users decide whether they should update and what to expect from each version.
* **Good maintenance practice** — It is a widely adopted standard in the open-source community, promoting consistency and professionalism.

---

## 2. General format

The *changelog* format should follow the recommendations of [Keep a Changelog](https://keepachangelog.com/).

Below is the general format of a file. Note the use of sections (`##`) for versions and subsections (`###`) for the type of changes.

```markdown
## [Unreleased]
### Added
- ... 

### Changed
-  

### Fixed
-  

### Deprecated
-  

### Removed
-  

### Security
-  

---

## [1.0.0] - 2026-08-14
### Added
- ...

### Changed
-  
(...)
---

(...other releases...)

---

## [0.1.0] - 2025-10-01
### Added
- ...
(...)
```

---

## 3. Conventions

The types of changes follow these categories:

* **Added** — New features.
* **Changed** — Modifications to existing features.
* **Fixed** — Bug fixes.
* **Deprecated** — Features that are discontinued but still present.
* **Removed** — Features that have been removed.
* **Security** — Security vulnerability fixes.

---

## 4. How to update the *changelog*?

Whenever you make a significant change:

1. Update the **[Unreleased]** section.
2. When releasing a new version:

   * Create a new header `## [x.y.z] - YYYY-MM-DD`
   * Move the relevant entries from **[Unreleased]** to that version.
   * Clear the **[Unreleased]** section.

## 5. Related Documentation

* [Versioning Guidelines](./versioning.md)
* [Commit Messages Guidelines](./commit-messages.md)

