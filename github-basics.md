# GitHub Basics: For a First-Time App Builder

_A plain-language intro to GitHub for someone with no software background who wants to
build an app with an AI coding tool (like Claude Code). Written with engineering analogies._

## The one-sentence version

GitHub is cloud storage for code that also remembers every version of every file, forever,
and lets you (and AI tools) safely experiment without losing work.

## The mental model (in engineering terms)

Think of how you'd manage a critical well-design spreadsheet. You'd want: a master copy, a
full history of every change and who made it, the ability to try a risky revision on a copy
without touching the master, and a backup offsite in case your laptop dies. GitHub is that
system, built for code.

## The core pieces

### 1. Git vs. GitHub (they're different)
- **Git** is the tool on your computer that tracks changes to files. It runs locally.
- **GitHub** is the website that stores your Git project in the cloud and adds collaboration,
  backup, and sharing.
- Analogy: Git is the software that logs the changes; GitHub is the shared server room where
  the logbook lives.

### 2. Repository ("repo")
A repo is one project's folder, plus its entire change history. Your app = one repo. It holds
all your files and a complete timeline of edits.

### 3. Commit
A commit is a saved snapshot with a note describing what changed, like signing and dating a
revision of a drawing. "Added login screen." You don't save every keystroke; you commit at
meaningful checkpoints. Every commit is recoverable, so you can always roll back.

### 4. Push and pull
- **Push** = upload your local commits to GitHub (back them up / share them).
- **Pull** = download changes from GitHub to your computer.
- Your code lives in two places: local (your laptop) and remote (GitHub). Push/pull keep them
  in sync.

### 5. Branch
A branch is a parallel copy where you try something without risking the working version. Your
stable version lives on the **main** branch. Want to add a feature? Make a branch, experiment,
and if it works, **merge** it back into main. If it breaks, throw the branch away. Main stays
safe the whole time. This is the single most valuable habit.

### 6. Public vs. private
A repo can be **private** (only you and people you invite see it, even the name is hidden) or
**public** (anyone can see it). For your own app, start **private**.

## The workflow you'll actually live in

1. Create a repo (once per project).
2. Work on the code (your AI tool will do most of the writing).
3. **Commit** at good stopping points, with a short message.
4. **Push** to GitHub so it's backed up.
5. For anything risky, do it on a **branch**, then merge when happy.

Repeat. That's 90% of daily use.

## Why this matters when building with an AI coding tool

- **Safety net:** AI tools write and change lots of files fast. Commits let you undo any change
  that made things worse, instantly. Without Git, a bad edit can be unrecoverable.
- **The tool speaks Git natively:** it can commit, branch, and push for you. You mostly need to
  understand *what* it's doing and approve it.
- **Backup:** if your laptop dies, `push` means your whole app is safe on GitHub.
- **A clear history** helps you, and the AI, understand how the project got to its current state.

## What to install / set up (in order)

1. **A GitHub account** at github.com (free).
2. **Git** on your computer (the AI tool's setup will usually handle or prompt this).
3. **Your AI coding tool**, then point it at a folder and let it create your first repo.
4. Learn just five words by feel: **repo, commit, push, pull, branch.** That's enough to start.

## Vocabulary cheat-sheet

| Term | Plain meaning |
|---|---|
| Repository (repo) | Your project + its full history |
| Commit | A saved, labeled snapshot |
| Push | Upload commits to GitHub |
| Pull | Download changes from GitHub |
| Branch | A safe parallel copy to experiment on |
| Merge | Fold a branch's changes back into main |
| Clone | Copy a GitHub repo down to your computer |
| main | The primary, stable version |

## What you can safely ignore at first

Pull requests, forks, merge conflicts, CI/CD, issues. They matter for teams; solo-with-an-AI,
you can pick them up later.

## The mindset shift

Commit often and push often. In engineering you don't rely on one un-backed-up copy of a well
plan; same discipline here. Commits are cheap insurance, and they make experimenting fearless.
