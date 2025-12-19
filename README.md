# 📘 Git Commands – Complete README Guide

This README contains a **complete list of Git commands**, organized from **basic to advanced**, written in **simple and clear language**. Perfect for **students, beginners, and developers**.

---

## 🔹 1. Git Setup & Configuration

```bash
git --version
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
git config --list
git help
git help <command>
```

---

## 🔹 2. Create & Initialize Repository

```bash
git init
git clone <repository-url>
```

---

## 🔹 3. File & Folder Tracking

```bash
git status
git add <file>
git add .
git add -A
git rm <file>
git rm --cached <file>
git mv <old-name> <new-name>
```

---

## 🔹 4. Commit Commands

```bash
git commit -m "message"
git commit -am "message"
git commit --amend
```

---

## 🔹 5. Branching

```bash
git branch
git branch <branch-name>
git branch -d <branch-name>
git branch -D <branch-name>
git checkout <branch-name>
git checkout -b <branch-name>
git switch <branch-name>
git switch -c <branch-name>
```

---

## 🔹 6. Merging & Rebasing

```bash
git merge <branch-name>
git merge --abort
git rebase <branch-name>
git rebase --abort
git rebase --continue
```

---

## 🔹 7. Remote Repositories

```bash
git remote
git remote -v
git remote add origin <url>
git remote remove origin
git push
git push origin <branch>
git push -u origin <branch>
git pull
git pull origin <branch>
git fetch
```

---

## 🔹 8. Logs & History

```bash
git log
git log --oneline
git log --graph
git log --author="name"
git show
git blame <file>
```

---

## 🔹 9. Undo & Reset

```bash
git reset
git reset --soft HEAD~1
git reset --mixed HEAD~1
git reset --hard HEAD~1
git restore <file>
git restore --staged <file>
git revert <commit-id>
```

---

## 🔹 10. Stash Commands

```bash
git stash
git stash save "message"
git stash list
git stash apply
git stash pop
git stash drop
git stash clear
```

---

## 🔹 11. Diff & Compare

```bash
git diff
git diff --staged
git diff <branch1> <branch2>
```

---

## 🔹 12. Tags

```bash
git tag
git tag <tag-name>
git tag -a <tag-name> -m "message"
git show <tag-name>
git push origin <tag-name>
```

---

## 🔹 13. Cleaning & Maintenance

```bash
git clean -f
git clean -fd
git gc
git fsck
```

---

## 🔹 14. Submodules

```bash
git submodule add <url>
git submodule init
git submodule update
git submodule update --remote
```

---

## 🔹 15. Advanced / Rare Commands

```bash
git cherry-pick <commit-id>
git reflog
git archive
git bisect
git worktree
```

---

## 🔹 16. Git Ignore

Create a `.gitignore` file to ignore files/folders:

```bash
node_modules/
.env
*.log
```

---

## 🔹 17. Useful Shortcuts

```bash
git status -s
git log --pretty=oneline
git checkout -
```

---

## ✅ Conclusion

This README serves as a **Git command cheat sheet** and **learning guide**. You can use it for:

* Exams
* Interviews
* Daily development work
* Teaching & sharing

⭐ **Star this repository if you find it helpful!**
