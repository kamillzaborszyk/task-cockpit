# Publish to GitHub

## GitHub CLI

```powershell
cd task-cockpit-repository
gh auth login
gh repo create task-cockpit --private --source=. --remote=origin --push
git push origin --tags
```

After reviewing the repository for private data, change visibility to public in GitHub settings or run:

```powershell
gh repo edit --visibility public
```

## Without GitHub CLI

Create an empty repository on GitHub, then run:

```powershell
git remote add origin https://github.com/YOUR-USER/task-cockpit.git
git push -u origin main
git push origin --tags
```
