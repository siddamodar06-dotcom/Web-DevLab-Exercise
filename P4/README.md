# P4: GitHub README and version tags

## Goal
Document the portfolio repository and mark a version with a Git tag.

## Step
1. Write a `README.md` that names the project and explains what it contains.
2. Stage and commit the README.
3. After the version you want to mark is on `main`, create a version tag.
4. Push the commit and tag to GitHub.

## Practice commands
```bash
git add README.md
git commit -m "Document portfolio project"
git tag -a v1.0 -m "Portfolio version 1.0"
git push origin main
git push origin v1.0
```
