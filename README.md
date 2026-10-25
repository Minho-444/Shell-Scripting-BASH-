<div align="center">

# Shell Scripting with Bash

**A structured, hands-on record of my journey learning Bash, from fundamentals to real-world automation.**

<br>

![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

![Status](https://img.shields.io/badge/status-learning-brightgreen?style=flat-square)
![Commits](https://img.shields.io/github/commit-activity/m/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME?style=flat-square&color=blue)
![Last Commit](https://img.shields.io/github/last-commit/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME?style=flat-square&color=orange)
![Stars](https://img.shields.io/github/stars/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME?style=flat-square&color=yellow)

</div>

---

## Table of Contents

- [Overview](#overview)
- [Learning Objectives](#learning-objectives)
- [Curriculum](#curriculum)
- [Repository Structure](#repository-structure)
- [Getting Started](#getting-started)
- [Code Conventions](#code-conventions)
- [Learning Log](#learning-log)
- [Resources](#resources)
- [Contact](#contact)

---

## Overview

This repository documents my progress in **Shell Scripting with Bash**. Each
module contains concise notes, practical exercises, and small projects that
reinforce the concepts covered. The goal is to build a solid foundation in
command-line workflows and use it to automate real tasks on Linux systems.

## Learning Objectives

- Navigate and manage Linux systems efficiently from the command line
- Write clean, portable, and maintainable Bash scripts
- Process text and data using standard UNIX tools
- Automate repetitive tasks and system administration workflows
- Apply debugging and error-handling best practices

---

## Curriculum

| Module | Topic | Status |
|:------:|-------|:------:|
| 01 | Terminal fundamentals and navigation | ![Done](https://img.shields.io/badge/-Completed-2ea44f?style=flat-square) |
| 02 | Variables, quoting, and user input | ![Progress](https://img.shields.io/badge/-Completed-2ea44f?style=flat-square) |
| 03 | Conditionals (`if`, `case`) | ![Planned](https://img.shields.io/badge/-Completed-2ea44f?style=flat-square) |
| 04 | Loops (`for`, `while`, `until`) | ![Planned](https://img.shields.io/badge/-In%20Progress-f0ad4e?style=flat-square) |
| 05 | Functions and scope | ![Planned](https://img.shields.io/badge/-Planned-6c757d?style=flat-square) |
| 06 | Arrays and string manipulation | ![Planned](https://img.shields.io/badge/-Planned-6c757d?style=flat-square) |
| 07 | File handling and permissions | ![Planned](https://img.shields.io/badge/-Planned-6c757d?style=flat-square) |
| 08 | Pipes, redirection, and streams | ![Planned](https://img.shields.io/badge/-Planned-6c757d?style=flat-square) |
| 09 | Text processing: `grep`, `sed`, `awk` | ![Planned](https://img.shields.io/badge/-Planned-6c757d?style=flat-square) |
| 10 | Process management and cron automation | ![Planned](https://img.shields.io/badge/-Planned-6c757d?style=flat-square) |
| 11 | Error handling and debugging | ![Planned](https://img.shields.io/badge/-Planned-6c757d?style=flat-square) |
| 12 | Capstone projects | ![Planned](https://img.shields.io/badge/-Planned-6c757d?style=flat-square) |

---

## Repository Structure

```text
.
├── 01-basics/
│   ├── hello.sh
│   └── notes.md
├── 02-variables/
├── 03-conditionals/
├── 04-loops/
├── 05-functions/
├── 06-arrays-strings/
├── 07-files-permissions/
├── 08-pipes-redirection/
├── 09-text-processing/
├── 10-automation/
├── projects/
├── LICENSE
└── README.md
```

---

## Getting Started

### Prerequisites

- A Linux or macOS environment (or WSL on Windows)
- Bash 4.0 or later
- Git

Check your Bash version:

```bash
bash --version
```

### Installation

```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME
```

### Running a Script

```bash
chmod +x 01-basics/hello.sh
./01-basics/hello.sh
```

### Example

```bash
#!/usr/bin/env bash
set -euo pipefail

name="World"
echo "Hello, ${name}!"
```

---

## Code Conventions

All scripts in this repository follow these guidelines:

- Start with a portable shebang: `#!/usr/bin/env bash`
- Enable strict mode where appropriate: `set -euo pipefail`
- Quote variable expansions: `"${variable}"`
- Use lowercase names for local variables and uppercase for constants
- Validate scripts with [ShellCheck](https://www.shellcheck.net/) before committing

---

## Learning Log

| Date | Summary |
|------|---------|
| YYYY-MM-DD | Wrote the first script; studied the shebang and execution permissions |
| YYYY-MM-DD | Covered variables, quoting rules, and reading user input |

---

## Resources

- [GNU Bash Reference Manual](https://www.gnu.org/software/bash/manual/)
- [Bash Guide for Beginners (TLDP)](https://tldp.org/LDP/Bash-Beginners-Guide/html/)
- [Google Shell Style Guide](https://google.github.io/styleguide/shellguide.html)
- [Explainshell](https://explainshell.com/)
- [ShellCheck](https://www.shellcheck.net/)

---

## Contact

<div align="center">


[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/youness-444/)
[![Codeforces](https://img.shields.io/badge/Codeforces-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white)](https://codeforces.com/profile/minoh_444)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/YOUR_LINKEDIN/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/YOUR_GITHUB_USERNAME)

</div>

---

<div align="center">
<sub>Released under the MIT License. Feedback and suggestions are welcome through issues and pull requests.</sub>
</div>
