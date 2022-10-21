# Oreilly1021

- `git clone <URL>`: "downloads" the repo to the current repository
- `git init`
- git commit
- git diff
- git push origin main 
- git push
- difference between git push Vs git push origin main
- git log --oneline --graph
- What is origin?
- Recommend to type `git push origin main`
- What is the difference between `HEAD` and `main`
- HEAD is telling you where you are and branch name is telling you the sequence of commits
- `git branch <branch_name>`: creates a branch
- `git branch -a`: list all the branches on the computer
- `git switch <NAME>`: switches to a <NAME> branch (similar to `git checkout <NAME>` on previous versions)
- `gir diff -- stage`
- Your `HEAD` points to the current branch. If you switch the branches,  `HEAD` points to that branch
- It is recommended to push your working branch to remote and then raise a pull request instead of merging on the local.
- `git push origin my_first_branch`
- `merge request` or `pull request` are there the same
- QQQ: Why was I unable to push my branch to GitHub at first
  - What exactly is Origin and can I set origin to a my current branch?
- Pushing to the pull requests updates the pull requests
- You can delete the branch after the pull request is approved (on the remote)
- But on our local branch still has the `my_first_branch`
  - So how do we syncronize with remote. Use `git pull origin main`
    - This will ensure everthing is in Sync
    - `git fetch --prune`: brings the log files/meta data from origin without & the files
    - `git branch -d my_first_branch`