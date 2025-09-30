# A02 — Git + GitHub + WebStorm Tutorial
Seungyeop Hong (UCID: sh864)

**Repository URL:** https://github.com/sh864/A02

---

## Part 1 — Directions on Using WebStorm with Git & GitHub

> Include URLs for any downloads you used.

**Downloads**
- Git: https://git-scm.com/downloads  
- WebStorm: https://www.jetbrains.com/webstorm/download/  
- GitHub: https://github.com/

### A. Create your **Repository**
1. Sign in to GitHub → **New** repository.
2. Name it **A02** (capital **A** matters).
3. Keep it Public (unless told otherwise).
4. Click **Create repository**.

### B. Clone the repo to WebStorm
1. Open WebStorm → *Get from VCS* → paste your repo URL.
2. Click **Clone**. This creates a local copy of your **Repository** and adds a **Remote** (origin) that points back to GitHub.

### C. Make a change and **Commit** it
1. In WebStorm, create or edit files (e.g., `README.md`).
2. VCS → **Commit** (or press Ctrl/Cmd+K).
3. Write a clear message (examples below) and click **Commit**.

### D. **Push** your commit to GitHub
1. VCS → **Push** (or Ctrl/Cmd+Shift+K).
2. Confirm to send your commits to the **Remote**.

### E. Update your local copy (**Pull** and **Fetch**)
- **Fetch** gets new metadata from the server without merging.
- **Pull** gets changes *and* merges them into your current branch.
1. VCS → Git → **Fetch** to check for changes.
2. VCS → Git → **Pull** to bring them into your local **Repository**.

### F. Work on a **Branch**
1. VCS → Git → **Branches** → **New Branch** (e.g., `feature-tutorial`).
2. Make edits and **Commit** on this branch.
3. When ready, switch to `main` and **Merge** the feature branch into `main`.

### G. Handle a **Merge Conflict**
1. If files were changed in two places, Git shows a **Merge Conflict**.
2. WebStorm opens a 3-way merge tool → choose which changes to keep.
3. Mark conflicts resolved → **Commit** the merge.

### H. Example commit messages (use these styles)
- `Task: Create Repository`
- `Feature: added workflow for using github`
- `Fix: changed readme.md for definition of terms`

---

## Part 2 — Glossary (bold ONLY the glossary word)
- **Branch** — A movable pointer to a line of commits so you can develop features independently.
- **Clone** — Make a local copy of a remote repository.
- **Commit** — A saved snapshot of your changes with a message.
- **Fetch** — Download refs and metadata from the remote without merging changes.
- **GIT** — The distributed version control system that tracks changes to files.
- **Github** — The hosting service for Git repositories and collaboration tools.
- **Merge** — Combine changes from one branch into another.
- **Merge Conflict** — When Git can’t auto-merge because the same lines changed in two places.
- **Push** — Send your local commits to the remote repository.
- **Pull** — Fetch + merge remote changes into your current branch.
- **Remote** — A server-side repo (e.g., `origin`) your local repo syncs with.
- **Repository** — The project folder tracked by Git containing history, branches, and files.

---

## References
- Git Downloads and Docs — https://git-scm.com/  
- GitHub Guides — https://docs.github.com/  
- WebStorm Git Integration — https://www.jetbrains.com/help/webstorm/using-git-integration.html
