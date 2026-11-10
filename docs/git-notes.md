# Git Notes: Interview Answers

1. **What is Git?** A distributed version control system that tracks changes to files, lets many people collaborate, and keeps a full history that can be branched, merged and reverted.
2. **Merge vs rebase?** `merge` combines branches and keeps history as it happened, adding a merge commit. `rebase` replays your commits on top of another branch, giving a clean linear history but rewriting commits (avoid on shared branches).
3. **What is a pull request?** A request on GitHub to merge one branch into another. It enables code review, discussion and checks before merging.
4. **Resolving merge conflicts?** Run the merge, open the files with `<<<<<<<`, `=======`, `>>>>>>>` markers, choose or combine the correct code, remove the markers, then `git add` the files and `git commit`.
5. **What are Git tags?** Named pointers to specific commits, usually used to mark releases (e.g. `v1.0.0`).
6. **What is a Git workflow?** An agreed way of using branches and merges in a team, e.g. Git Flow (main/dev/feature), GitHub Flow, or trunk-based development.
7. **Explain git stash.** Temporarily saves uncommitted changes and restores a clean working directory. `git stash` saves, `git stash pop` brings the changes back.
8. **Use of .gitignore?** Lists files and folders Git should not track, such as secrets (`.env`), logs, caches and build output.
