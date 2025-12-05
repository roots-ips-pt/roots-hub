# Contributing to This Project

Thank you for your interest in contributing!  

Whether you are reporting a bug, improving documentation, proposing new ideas, or submitting code, your help is greatly appreciated.

This document provides guidelines to ensure a smooth and inclusive contribution process.

---

## 💬 Ways You Can Contribute

You do *not* need to be a developer to contribute — all skills are welcome.

### **1. Report Issues**

You can report:
- Bugs or unexpected behavior
- Documentation errors
- Feature requests or improvement suggestions
- Questions or clarifications

Before submitting, please check existing issues to avoid duplicates.

(TODO: *Issue Forms* -> select template)

---

### **2. Suggest Features or Enhancements**
If you have an idea for a new feature, open a **Feature Proposal Issue**.  
Provide as much context as possible so the maintainers can evaluate the idea.

(TODO: *Issue Forms* -> select template)

---

### **3. Improve Documentation**

Documentation contributions are highly valuable.  
You can help by:
- Fixing typos or unclear sections
- Adding examples or tutorials
- Improving readme or internal docs

---

### **4. Contribute Code**
We welcome pull requests. To keep things consistent:

#### **Pull Request Guidelines**
1. Check existing issues or create one before starting work.
2. Fork the repository and create a feature branch:
   ```bash
   git checkout -b feature/my-contribution
    ```

3. Follow the coding style of the project and folder structure.
4. Add or update documentation if needed.
5. Add tests if applicable.
6. Ensure all existing tests pass before submitting the PR.

Submit your PR with a clear description of:

* What was changed
* Why it was needed
* Any limitations or follow-up work

---

## 🤝 Code of Conduct

By participating in this project, you agree to follow the ROOTS Code of Conduct.

Please read it here:
👉 **[Code of Conduct](../../community/code-of-conduct.md)**

---

## 🙌 Thank You

Every contribution — small or large — makes a difference.
We’re excited to collaborate with you!


V2
===

Aqui está o **CONTRIBUTING.md consolidado**, completo e pronto para colocar em `docs/templates/CONTRIBUTING.md`.
Foi escrito para ser genérico, aplicável a qualquer projeto ROOTS (software, hardware, documentação ou misto).

---

# **CONTRIBUTING.md**

### *ROOTS – Open Source & Technology Community*

### *General Contribution Guidelines*

Thank you for your interest in contributing to a ROOTS project!
We welcome contributions from **students, staff, alumni, and the broader open-source community**.
This document explains how to contribute effectively and consistently.

Our goals are:

* to keep contributions **accessible**,
* to maintain **high quality**,
* and to ensure that anyone—regardless of experience level—can participate.

---

# 🧭 **How to Contribute**

ROOTS projects accept multiple types of contributions:

* **Bug reports**
* **New feature proposals**
* **Documentation improvements**
* **Code contributions**
* **Hardware contributions**
* **Testing, UX, design, translation or research**

Before contributing:

1. **Read the project’s README**
2. **Read the project’s Code of Conduct**
3. **Check open Issues and Discussions**
4. **Search for existing Pull Requests**

If nothing exists for your topic, feel free to open a new Issue (see template).

---

# 📝 **Submitting an Issue**

When opening an Issue:

* Use the *Issue Template* if available (usually `.github/ISSUE_TEMPLATE`).
* Be clear and objective.
* Provide steps to reproduce (if applicable).
* Add screenshots, logs or minimal examples.
* Suggest a solution if you have one.

Issues should belong to one of these categories:

* **Bug report**
* **Feature request / enhancement**
* **Project proposal discussion**
* **Documentation improvement**
* **Hardware-related issue**

---

# 🔀 **Submitting a Pull Request (PR)**

1. Fork the repository
2. Create a feature branch (`feature/xyz`, `fix/abc`, etc.)
3. Make your changes
4. Write or update tests if applicable
5. Update documentation if needed
6. Submit a Pull Request with a clear description

PR Guidelines:

* Keep changes focused and minimal
* Reference related Issues
* Follow any existing coding standards for the project
* Be open to feedback and review
* Avoid mixing refactoring with feature changes unless required

---

# 📚 **Documentation Contributions**

Documentation is just as important as code or hardware.

Documentation contributions may include:

* Improving README
* Writing tutorials
* Adding diagrams or examples
* Fixing typos or clarifying unclear sections
* Translating documentation when appropriate

For **major documentation changes**, open an Issue first to discuss direction.

---

# 💻 **Software Contributions**

If the project is software-based:

* Follow the project’s coding style (e.g., linting rules, naming conventions)
* Include tests when possible
* Keep functions/classes small and readable
* Submit minimal reproducible examples when raising issues
* Avoid introducing new dependencies without discussion

If unsure, open a Discussion or Issue before coding.

---

# 🔧 **Hardware Contributions**

ROOTS supports projects that include electronics, microcontrollers, mechanical parts, and integrated hardware/software solutions.
If your contribution involves hardware, follow these additional guidelines:

## **Documentation Requirements**

Provide clear documentation for any new hardware component or design:

* Schematics (PDF + source files)
* Block/system diagrams
* Bill of Materials (BOM)
* Wiring instructions
* Photos or PCB renders
* Firmware usage instructions

Good documentation ensures replicability.

## **Preferred File Formats**

* Schematics/PCBs: **KiCad** (source + PDF/PNG)
* 3D models: **STL**, **STEP**
* Firmware: full source code
* Never upload copyrighted datasheets — link them instead.

## **Safety Considerations**

If your hardware involves any risk:

* Include warnings
* Describe safe operating conditions
* Avoid high-voltage or hazardous designs
* Highlight limitations clearly

## **Testing & Validation**

Before submitting:

* Prototype and test if possible
* Provide images/videos of results
* Document known issues
* If untested, state this clearly so others can help

## **Repository Structure**

Maintain a clean directory structure, for example:

```
/hardware
  /schematics
  /pcb
  /3d-models
  /firmware
  /bom
  /docs
```

## **Collaboration with Non-Technical Members**

Hardware projects benefit from:

* Industrial design
* UX/UI
* Testing and QA
* Documentation
* Community management

All contributions are valued.

---

# 🌍 **Non-Technical Contributions**

ROOTS encourages participation from contributors with skills beyond development:

* **Design** (UI, UX, graphic design, branding)
* **Testing & QA**
* **Project management**
* **Marketing & community engagement**
* **Technical writing**
* **Event organization**

These contributions are essential to keeping projects healthy and reachable.

---

# 🧹 **Commit Messages**

We recommend using the **Conventional Commits** style:

```
feat: add new X functionality
fix: correct bug in Y
docs: improve installation guide
refactor: simplify module Z
test: add missing tests for W
```

If a commit addresses an *Issue*, the commit message should reference the issue identifier. Sintax:

```console
(Any text) #ISSUE_NUMBER
```

For example, `fix: correct the login bug as reported in #14.`

---

# 📦 **Versioning**

All ROOTS projects are encouraged to follow **Semantic Versioning (SemVer)**:

```
MAJOR.MINOR.PATCH
```

* `0.x` for early development
* `1.0.0` for the first stable version
* Major version increments for breaking changes

See `docs/versioning.md` for the full policy.

---

# 🤝 **Feedback and Collaboration**

ROOTS values open dialogue and collaboration.
If you are unsure about anything, want help, or wish to propose something large:

➡️ Open a **Discussion**
➡️ Ask in an existing Issue
➡️ Or contact the maintainers listed in the repository

There are no “silly questions” — everyone starts somewhere.

---

# 🙏 **Thank You**

Your contribution—big or small—helps grow the ROOTS community and expand open-source participation at ESTSetúbal and beyond.
We appreciate your time, effort, and creativity.



V3
==

# `CONTRIBUTING.md`

*(ROOTS Standard Template)*

## 1. Introduction

Thank you for your interest in contributing to this ROOTS project.
All ROOTS repositories follow a shared contribution model to ensure consistency, transparency, and maintainability.

This document provides the essential rules. For detailed guidance, please refer to the documents listed in section **8 – Related Documentation**.

---

## 2. Ways to Contribute

You may contribute in several ways:

### 2.1. 📝 Reporting Issues

Use the project’s *Issues* section to report:

* Bugs
* Documentation gaps
* Feature requests
* Hardware-related problems (if applicable)

Before creating a new issue, please search existing issues to avoid duplicates.

Use the provided labels

### 2.2. 🔀 Submitting Code or Hardware Contributions

Contributions may include:

* New features;
* Bug fixes;
* Documentation improvements;
* Schematics, PCB layouts, enclosure models, or other hardware artefacts.

Every change must be reviewed through a *Pull Request* (PR).

For **major changes**, open an *Issue* first to discuss direction.


---

## 3. Contribution Workflow

1. **Open an Issue** (unless trivial).
2. **Discuss with maintainers** to align scope and approach.
3. Fork the repository and **create a branch** following the naming convention:

   ```
   feature/<short-description>
   fix/<short-description>
   docs/<short-description>
   hw/<short-description>     # for hardware-specific contributions
   ```
4. **Write code, documentation, or hardware designs** respecting project guidelines.
5. **Follow commit message rules** (see section 5).
6. **Update the CHANGELOG** if the change is user-visible.
7. **Submit a Pull Request** using the project’s PR template.
8. Address review comments until approval.

---

## 4. Coding, Documentation & Hardware Standards

Each project may define its own technical conventions.
Global ROOTS requirements:

### **4.1. Code**

* Keep changes minimal and focused.
* Include tests when applicable.
* Respect project linting/formatting rules.

### **4.2. Documentation**

* Update relevant docs when behaviour changes.
* Use English in all documentation.

### **4.3. Hardware (if applicable)**

* Submit source files (e.g., KiCad, FreeCAD), not only exports.
* Include BOM and fabrication notes when relevant.
* Document testing procedures for any functional hardware.

---

## 5. Commit Message Rules

ROOTS uses structured commit messages to enable automation (issue-closing, changelog extraction, semantic versioning hints).

### **5.1. Structure**

```
<type>: <short description>

[optional body]
[optional footer]
```

### **5.2. Allowed Types**

* **feat:** user-visible feature
* **fix:** bug fix
* **docs:** documentation changes
* **refactor:** internal restructuring
* **test:** adding or updating tests
* **chore:** maintenance
* **hw:** hardware-specific contributions

### **5.3. Issue Closing Keywords**

To allow GitHub automation, start the footer of your commit with:

```
closes #12
fixes #34
resolves #56
```

These must appear **at the beginning of a line**, not mixed with other text.

### **5.4. Consistency with Versioning**

Commit types provide hints for SemVer:

* `feat:` → **MINOR** bump
* `fix:` → **PATCH** bump
* `feat!:` or commits mentioning breaking changes → **MAJOR** bump

Details in `docs/processes/versioning.md`.

---

## 6. Pull Requests

A Pull Request must:

* Reference at least one Issue
* Contain only related changes
* Pass CI checks
* Update documentation and CHANGELOG when required
* Include hardware files in source form (if applicable)

Maintainers may request changes before merging.

---

## 7. Communication & Decision-Making

ROOTS promotes open discussion.
Use:

* **Issues** for bugs or feature ideas
* **Discussions → Project Proposals** for new project ideas
* **Pull Requests** for concrete contributions

Major decisions follow the ROOTS governance model (if defined).

---

## 8. Related Documentation

Each project should include or link to the following ROOTS documents:

* **Project Proposal Workflow**
  `docs/processes/project-proposal-workflow/project-proposal.md`

* **Versioning Guidelines (SemVer)**
  `docs/processes/versioning.md`

* **Changelog Template**
  `docs/templates/CHANGELOG.md`

* **Commit Message Guidelines**
  `docs/processes/commit-message-guidelines.md`

* **Issue Template**
  `.github/ISSUE_TEMPLATE/ISSUE.md`

These documents contain examples, special cases, and rationale.

---

## 9. Code of Conduct

All contributors must follow the ROOTS Code of Conduct.
(Insert link once defined.)

---

## 10. License

Unless otherwise stated, contributions to ROOTS projects are made under the project’s license.
Ensure you understand the implications before submitting a PR.


