## 001 github_basics new repo

1. create new repo in github

2. use following commands to push repo
```bash
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/devdanishai/mern-app.git
git push -u origin main
git status
```
3. for new commit
```bash
git add filename.txt
git commit -m "updated filename.txt"
git push -u origin main
git status
```

---
## 002 existing repo
```bash
git remote add origin https://github.com/devdanishai/mern-app.git
git branch -M main
git push -u origin main
```
