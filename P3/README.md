# P3: Feature-branch Git workflow

## Goal
Make a change on a separate branch, push that branch, and propose it for review with Pull Request.

## Steps
1. Start from the repository's main branch and update it with `git pull`.
2. Create and switch to a feature branch.
3. Make a small change to `index.html`.
4. Stage and commit the change.
5. Push the feature branch to GitHub.
6. Open a Pull Request from the feature branch into `main` and review it with your team.

## Practice commands
```bash
git switch main
git pull
git switch -c feature/update-portfolio
git add P2/index.html
git commit -m "Update portfolio page"
git push -u origin feature/update-portfolio
```
