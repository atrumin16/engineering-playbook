# GitHub Achievements Automation and Reference Toolkit

A reference implementation, documentation set, and automation toolkit for understanding, auditing, and unlocking GitHub profile achievements.

[![License](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](LICENSE)
[![CI](https://img.shields.io/badge/CI-Active-107c41?style=flat-square)](#)
[![Status](https://img.shields.io/badge/Status-Maintained-0047AB?style=flat-square)](#)

---

## Overview

GitHub profile achievements recognize contribution patterns, collaboration practices, and developer activity across public repositories. This repository documents the exact unlock conditions, badge multipliers, and automation workflows for each achievement.

---

## Achievement Matrix and Tiers

| Achievement | Description | Unlock Condition | Tiers |
| :--- | :--- | :--- | :--- |
| **Pull Shark** | Merged pull requests | Merge pull requests into the default branch | Bronze: 2 PRs<br>Silver: 16 PRs (x16)<br>Gold: 128 PRs (x128) |
| **Pair Extraordinaire** | Co-authored commits | Co-author a commit within a merged pull request | Bronze: 1 PR<br>Silver: 10 PRs<br>Gold: 24 PRs |
| **YOLO** | Merged without review | Merge a pull request directly without code reviews | Single Tier |
| **Quickdraw** | Fast response resolution | Close an issue or pull request within 5 minutes of opening | Single Tier |
| **Galaxy Brain** | Accepted discussions answer | Provide an answer in a Q&A discussion marked as accepted | Bronze: 2 answers<br>Silver: 8 answers<br>Gold: 16 answers |
| **Starstruck** | Repository popularity | Maintain a repository that reaches star milestones | Bronze: 16 stars<br>Silver: 128 stars<br>Gold: 512 stars |
| **Public Sponsor** | Open-source patronage | Sponsor an open-source maintainer via GitHub Sponsors | Single Tier |

---

## Technical Specifications

### 1. Co-Authored Commits (Pair Extraordinaire)

To register co-authorship on GitHub, commits must include a `Co-authored-by:` trailer separated from the main commit message by an empty line:

```text
feat(component): implement edge caching layer

Co-authored-by: The Octocat <octocat@github.com>
```

When the pull request containing this commit is merged into the default branch, GitHub automatically attributes co-authorship to both accounts.

### 2. Fast Merges (YOLO & Pull Shark)

Pull requests opened and merged without approval reviews qualify for the YOLO badge. Reaching 2 merged pull requests awards the baseline Pull Shark badge, while reaching 16 pull requests upgrades the badge to the Silver tier (`x16`).

---

## Maintainer

Alberto Trujillo Mingorance  
- Website: [alberto.trujillomingorance.com](https://alberto.trujillomingorance.com)  
- GitHub: [@atrumin16](https://github.com/atrumin16)