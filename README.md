# Git & GitHub Practice Repository

A hands-on version control lab covering core Git fundamentals, branching, and the GitHub pull request workflow used in team development.

## About This Repository
A terminal-first practice environment, moving from basic file tracking to syncing with GitHub and merging through a pull request. This was solo practice, with no team collaboration yet.

## Skills Practised
- **Core version control:** initialising a repository (`git init`), staging (`git add`), checking status (`git status`) and committing with descriptive messages (`git commit`)
- **History and inspection:** reading history (`git log --oneline --graph`), comparing changes (`git diff`) and restoring files (`git restore`)
- **Branching and merging:** creating and switching branches (`git branch`, `git switch`) and merging them into the main branch (`git merge`), including a fast-forward merge
- **Remote sync with GitHub:** connecting a remote (`git remote add origin`), setting up a credential helper, pushing (`git push -u`) and pulling (`git pull`)
- **Pull request workflow:** developing on a feature branch, then opening and merging a pull request on GitHub (PR #1)

## How I Learned This
I followed a structured Git curriculum with an AI coding agent acting as tutor. The agent worked under written rules in [AGENTS.md](AGENTS.md): explain before showing commands, let me type the commands myself, and never run destructive commands without confirmation. Progress is tracked in [PROGRESS.md](PROGRESS.md).

## Next Steps
`.gitignore`, `git stash`, and resolving merge conflicts, which I haven't practised yet.

## Repository Contents
| File | Description |
|------|-------------|
| `README.md` | This overview |
| `hello.txt` | Practice file for commits, diffs and restore exercises |
| `git-memoir.txt` | Quick-reference cheat sheet for daily Git commands |
| `PROGRESS.md` | Curriculum tracker and completed milestones |
| `AGENTS.md` | Rules for the AI tutor used in this repository |

---

Maintained by Nicholas ([@nickq1986](https://github.com/nickq1986))
