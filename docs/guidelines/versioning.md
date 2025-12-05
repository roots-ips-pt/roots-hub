# Versioning your releases

🚧 *This is a draft. May be adjusted as needed.*

## 1. Purpose

This document describes [Semantic Versioning 2.0.0](https://semver.org/spec/v2.0.0.html) (SemVer) - a unified versioning scheme to be used across projects in the ROOTS organization. 

It establishes common principles for numbering releases, communicating changes clearly, and maintaining consistency between repositories.

> [!NOTE]
> SemVer may not be applicable to all kinds of projects, see section 7.

## 2. Why Have a Unified Versioning Scheme?

A consistent versioning strategy:

* Simplifies maintenance of multiple projects.
* Improves communication with users and contributors.
* Makes automation (CI/CD, deployments, changelog generation) more reliable.
* Sets common expectations for what a version number communicates.

## 3. Recommended Scheme: Semantic Versioning (SemVer)

Projects SHOULD follow [Semantic Versioning 2.0.0](https://semver.org/spec/v2.0.0.html) (SemVer):

```
MAJOR.MINOR.PATCH
```

### MAJOR Version

Incremented when:

* Breaking changes are introduced.
* Public APIs change in incompatible ways.
* Functionality is removed.

### MINOR Version

Incremented when:

* Backwards‑compatible features are added.
* Functionality is extended without breaking existing usage.
* Deprecated features remain but are scheduled for removal.

### PATCH Version

Incremented when:

* Backwards‑compatible bug fixes are released.
* Small internal improvements are made.

## 4. Pre‑release Versions

Use pre‑release tags for unstable or under‑development releases:

```
1.4.0-alpha
1.4.0-beta.1
1.4.0-rc.2
```

Recommended tags:

* `alpha` — initial unstable version
* `beta` — feature-complete but testing continues
* `rc` — release candidate

## 5. Version Tags in GitHub

Every release MUST be tagged using the full SemVer string:

```
v1.2.3
v2.0.0-rc.1
```

## 6. Alignment With Changelog 📜

The version number MUST match an entry in the project’s `CHANGELOG.md`.


## 7. Applicability to Different Types of Projects

* **Libraries / Frameworks**: SemVer strictly applied.
* **Applications**: SemVer recommended; if APIs are not exposed, MAJOR version may evolve more slowly.
* **Documentation‑only projects**: SemVer MAY be used; MINOR for new sections, PATCH for corrections.
* **Configurations or infrastructure repos**: SemVer MAY apply, but only if releases are published.

If SemVer is not applicable, maintainers must explicitly define an alternative scheme in that project’s README.

## 8. Deprecation Policy

To ensure predictable evolution:

* Deprecated features must be documented.
* Removal of deprecated items MUST occur in a MAJOR release.

## 9. Related Documentation

* [Changelog Guidelines](./changelog.md)
* [Commit Messages Guidelines](./commit-messages.md)