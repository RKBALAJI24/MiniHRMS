# 🌱 Git & GitHub — Beginner Guide

## 1. What is the difference?
| | Git | GitHub |
|---|---|---|
| What | A tool on **your computer** that tracks changes to your code | A **website** that stores your Git projects online |
| Like | Saving versions of a document on your laptop | Uploading those versions to Google Drive |
| Works offline? | ✅ Yes | ❌ Needs internet |

**Why it matters for you:**
- Every company uses Git. *"Do you know Git?"* is asked in almost every interview.
- Your GitHub profile becomes your **portfolio** — recruiters can see you actually write code.

## 2. Key words
| Word | Meaning |
|---|---|
| **Repository (repo)** | A project folder tracked by Git (your `F:\MiniHRMS` is one) |
| **Commit** | A saved snapshot of your code, with a message describing the change |
| **Staging (`git add`)** | Choosing which changed files go into the next commit |
| **Push** | Upload your commits from your computer → GitHub |
| **Pull** | Download the latest commits from GitHub → your computer |
| **Clone** | Copy a GitHub repo to your computer for the first time |
| **Branch** | A separate line of work (e.g., a new feature) without disturbing `main` |
| **Remote / origin** | The GitHub address of your repo |

## 3. The daily cycle (memorize this!)
```
  Edit code  →  git add .  →  git commit -m "message"  →  git push
  (work)        (select)       (save snapshot)            (upload)
```

## 4. Most-used commands
| Command | What it does |
|---|---|
| `git status` | Shows what changed (use it often!) |
| `git add .` | Stage all changed files |
| `git add README.md` | Stage one file |
| `git commit -m "Add Employee class"` | Save a snapshot |
| `git push` | Upload to GitHub |
| `git pull` | Download latest changes |
| `git log --oneline` | See commit history |
| `git diff` | See exactly what lines changed |
| `git checkout -b feature/leave` | Create & switch to a new branch |
| `git switch main` | Go back to main branch |

## 5. Good commit messages
✅ `Add Employee CRUD with Razor views`
✅ `Fix leave balance calculation`
❌ `changes`
❌ `asdf`

## 6. Common interview questions (Week 1–2 practice)
1. What is the difference between Git and GitHub?
2. What is the difference between `git pull` and `git fetch`?
3. What is a branch? Why do teams use branches?
4. What is a merge conflict and how do you resolve it?
5. What is a pull request?
