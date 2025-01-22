# Versioning Guide

A concise guide to versioning systems with practical examples.

---

## Why Versioning?
- Track changes.
- Manage compatibility.
- Facilitate collaboration.

---

## Types of Versioning

### 1. Semantic Versioning (SemVer)
- **Format:** `MAJOR.MINOR.PATCH`
- **Usage:**
  - `MAJOR`: Breaking changes.
  - `MINOR`: New features, no breaking changes.
  - `PATCH`: Bug fixes.
- **Examples:**
  - `1.0.0`: Initial release.
  - `1.1.0`: Added a feature.
  - `1.1.1`: Fixed a bug.

### 2. Calendar Versioning
- **Format:** `YYYY.MM.DD`
- **Examples:**
  - `2023.01.01`: New Year's release.
  - `2023.06.15`: Mid-year update.

### 3. Build-Based Versioning
- **Usage:** Attach build numbers or commit hashes.
- **Examples:**
  - `v1.0-build45`
  - `commit: a1b2c3d`

---

## Best Practices
- Keep it consistent.
- Use `CHANGELOG.md` for version details.
- Prefix pre-releases: `v1.0.0-alpha`, `v1.0.0-beta`.
- Automate: Tools like `semantic-release`.
- Extension (VS Code): Tools like `AutoVersion`. 
- Tag in Git:
  ```bash
  git tag -a v1.0.0 -m "Version 1.0.0"
  git push origin v1.0.0
  ```