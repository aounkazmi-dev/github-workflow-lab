# ⚙️ GitHub Automation Lab

> A hands-on project exploring scheduled GitHub Actions, Python automation, and automated Git workflows.

## 💡 Overview

This project is a practical experiment with **GitHub Actions** and **Python-based automation**.

It demonstrates how scheduled workflows can execute scripts, modify repository files, create commits, and synchronize changes back to GitHub automatically.

The project is designed as a lightweight environment for learning:

- GitHub Actions
- Scheduled workflows with CRON
- Python scripting
- Git automation
- Automated file updates
- CI/CD workflow concepts

---

## ✨ Features

- 🔁 **Scheduled Automation**  
  GitHub Actions runs the automation workflow at predefined times.

- 🐍 **Python-Based Workflow**  
  A Python script handles the repository update and commit logic.

- 📅 **Scheduled Execution**  
  Uses CRON schedules to trigger automated workflow runs.

- 📝 **Automated File Updates**  
  The script updates selected repository files during execution.

- 🔄 **Automated Git Operations**  
  Changes are staged, committed, synchronized, and pushed automatically.

- 📊 **Execution Tracking**  
  Local tracking files record automation activity and execution state.

---

## ⚙️ How It Works

The project uses a Python script executed through a GitHub Actions workflow.

### Workflow

```text
Scheduled GitHub Actions Trigger
            ↓
     Checkout Repository
            ↓
       Setup Environment
            ↓
        Run commit.py
            ↓
      Update Repository Files
            ↓
        Create Commits
            ↓
       Pull Latest Changes
            ↓
          Push Changes
```

The workflow is defined in:

```text
.github/workflows/activity.yml
```

The main automation logic is implemented in:

```text
commit.py
```

---

## 🗂️ Project Structure

```text
github-automation-lab/
├── commit.py
├── daily_log.txt
├── progress.md
├── inspiration.txt
├── commit_log.txt
├── .commit_tracker.json
└── .github/
    └── workflows/
        └── activity.yml
```

---

## 🚀 Getting Started

### Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/github-automation-lab.git
cd github-automation-lab
```

### Enable GitHub Actions

After pushing the project to your repository:

1. Open the **Actions** tab.
2. Select the automation workflow.
3. Make sure workflows are enabled.
4. Use **Run workflow** to manually test it.

The workflow can also execute automatically according to its configured schedule.

---

## 🧪 Learning Goals

This project was built to gain practical experience with:

- GitHub Actions
- CRON scheduling
- Python automation
- Git commands from scripts
- Automated commits
- Repository synchronization
- CI/CD concepts
- Workflow debugging

---

## 🤝 Contributing

Ideas and improvements are welcome.

Potential improvements include:

- Better scheduling logic
- More robust error handling
- Improved logging
- Additional automation tasks
- Workflow optimization

---

## 📄 License

This project is licensed under the MIT License.

See the `LICENSE` file for details.

---

> Built as a practical learning project for GitHub Actions and repository automation.
