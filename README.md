# INSAne

> **TODO:** One-sentence description of what INSAne does and who it's for.

A team project for Software Engineering (CS 202).

---

## Table of Contents

- [Overview](#overview)
- [Team](#team)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Development Workflow](#development-workflow)
- [Documentation](#documentation)

---

## Overview

**TODO:** Fill in once scope is locked.

**Problem.** What problem are we solving?

**Solution.** How does INSAne solve it?

**Scope.** What is in scope for this semester, and what is explicitly out of scope?

### Features

- [ ] Feature 1
- [ ] Feature 2
- [ ] Feature 3

---

## Team

| Name | GitHub | Role |
|------|--------|------|
| Alice Dao| [@alicemdao](https://github.com/alicemdao) | |
| Suhail Tailor | [@stailor-creator](https://github.com/stailor-creator) | |
| | | |
| | | |

---

## Tech Stack

**TODO:** Replace with what we actually pick.

| Layer | Technology |
|-------|-----------|
| Frontend | React.js |
| Backend | Node.js |
| Database |PostgreSQL |
| Cloud Hosting| AWS (for now) |
| CI/CD | GitHub Actions |
|External APIs | Google Maps JavaScript & Geocoding API|

---

## Getting Started

### Prerequisites

**TODO:** List required tooling and versions (e.g. Node 20+, Python 3.11+, Docker).

### Setup

```bash
# Clone the repo
git clone https://github.com/alicemdao/INSAne.git
cd INSAne

# Install dependencies
# TODO: add install command
```

### Running locally

```bash
# TODO: add run command
```

### Running tests

```bash
# TODO: add test command
```

---

## Project Structure

```
INSAne/
├── docs/          # Requirements, UML diagrams, sprint notes
├── src/           # Application source
├── tests/         # Test suite
└── README.md
```

**TODO:** Update as the structure takes shape.

---

## Development Workflow

We follow an Agile workflow with short sprints.

### Branching

- `main` — always deployable. No direct commits.
- `dev` — integration branch for the current sprint.
- `feature/<short-name>` — one branch per task.
- `fix/<short-name>` — bug fixes.

### Making a change

```bash
git checkout dev
git pull
git checkout -b feature/login-page

# ... make changes ...

git add .
git commit -m "Add login page form validation"
git push -u origin feature/login-page
```

Then open a Pull Request into `dev`. **At least one teammate reviews before merge.**

### Commit messages

Write them in the imperative mood, describing what the commit does:

```
Add user authentication endpoint
Fix off-by-one error in pagination
Update README with setup instructions
```

### Definition of Done

A task is done when it is implemented, tested, reviewed by a teammate, merged into `dev`, and the docs are updated if behavior changed.

---

## Documentation

Course deliverables — to be added to the repo as they're written.

- [ ] Requirements specification
- [ ] UML class diagrams
- [ ] UML sequence diagrams
- [ ] UML state diagrams
- [ ] Sprint retrospectives

---

## License

**TODO:** Add a license, or note that this is coursework and not licensed for reuse.
