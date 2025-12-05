# 📚 Learning Notes & Git Automation Sandbox

## 🚀 Project Overview
This repository serves as a central hub for my notes on EVM architecture and Solidity development, and simultaneously functions as an **experimental sandbox** for mastering Git automation and custom version control strategies.

The primary objective is to develop a robust, granular progress tracking pipeline for continuous integration and versioning of personal knowledge and development insights.

## 🛠 Technical Focus
* **Core:** Markdown (Documentation and Knowledge Base)
* **Automation:** Bash / Shell Scripting (for CI/CD testing and workflow automation)
* **VCS:** Advanced Git (Exploring high-frequency commit strategies and merge conflict resolution)

## ⚙️ Functionality and Use Case
The repository contains custom scripts and utilities designed to automate routine developer tasks, specifically:

1.  **Automated Logging:** Generating time-stamped activity logs and data points within files like `activity_log.txt`.
2.  **Stress Testing:** Simulating high-frequency commits to analyze the integrity and readability of the `git log` history. This helps validate CI/CD pipeline triggers.
3.  **Micro-Versioning:** Ensuring granular data persistence and capturing the history of micro-tasks that are often overlooked in standard commits.

## 📦 Automation Script Usage
The internal automation script is utilized to simulate active development and verify the consistency of the change history under a high commit load.

```bash
# Execute the automated synchronization and logging script
./sync_progress.sh
