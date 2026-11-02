# Git cheat sheet

| Goal | Command |
|---|---|
| New branch | `git switch -c feature/name` |
| Stage and commit | `git add -p && git commit -m "msg"` |
| Co-authored commit | add `Co-authored-by: Name <email>` as the last line of the message |
| Undo last commit, keep changes | `git reset --soft HEAD~1` |
| Update branch from main | `git fetch && git rebase origin/main` |
| Show what changed | `git diff --staged` |
