# Daily Commits Bot

This repository automatically performs a **daily commit** using **GitHub Actions**.
It helps maintain a continuous GitHub contribution streak and serves as a simple time log of activity.

---

## ⚙️ How It Works

* A scheduled workflow runs **once a day** (using a cron job on GitHub Actions).
* It appends the current UTC date and time to `daily-log.txt`.
* Then, it commits and pushes the change automatically.
* The process requires **no local machine** — it runs entirely in the cloud.

---

## 🧩 Workflow Overview

File path:

```
.github/workflows/daily-commit.yml
```

Workflow tasks:

1. Check out the repository
2. Append the date to `daily-log.txt`
3. Commit changes
4. Push automatically

You can customize:

* The **commit schedule** (in UTC)
* The **commit message format**
* The **file name** (e.g., one file per day)

---

## 🕹 Example Commit Message

```
Automated daily commit: 2025-10-22
```

---

## 📦 Tech Stack

* **GitHub Actions** (for automation)
* **Bash** (for logging and commits)
* **Git** (for version control)

---

## 🧠 Why This Repo?

This project was created to:

* Keep GitHub contribution graphs active
* Track daily progress, even on non-coding days
* Demonstrate practical use of GitHub Actions and cron schedules

---

## 📄 License

MIT License — feel free to fork or reuse this setup.

---

*Built for personal automation and consistency.*
