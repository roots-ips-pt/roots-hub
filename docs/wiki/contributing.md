# How to contribute to ROOTS

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

