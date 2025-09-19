# Project Structure

This document describes the structure of the JobPilot.Ai repository to help contributors and users understand where to find and place files.

## Root Directory

- `README.md` — Project overview, badges, and general information
- `CONTRIBUTING.md` — Contribution guidelines
- `CODE_OF_CONDUCT.md` — Community standards and behavior
- `LICENSE` — Project license (MIT)
- `SECURITY.md` — Security policy and vulnerability reporting
- `PROJECT_STRUCTURE.md` — This file
- `.github/` — GitHub-specific files (issue templates, PR templates, workflows)

## Source Code

- `src/` — Main application source code (if present)
- `public/` — Static assets (images, icons, etc.)
- `tests/` — Test files and test utilities

## GitHub Directory

- `.github/ISSUE_TEMPLATE/` — Issue templates for bug reports and feature requests
- `.github/PULL_REQUEST_TEMPLATE.md` — Pull request template

## Adding New Files

- Place new features in the appropriate subdirectory under `src/`
- Add documentation in the root or `docs/` directory
- Add tests in the `tests/` directory

## Notes

- Keep the root directory clean and organized
- Update this file if you add significant new folders or files

---

For more details, see the [README.md](README.md) and [CONTRIBUTING.md](CONTRIBUTING.md).
