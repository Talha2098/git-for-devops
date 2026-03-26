# Git Commands Guide

## 1. Create Project Directory

```bash
mkdir git-for-devops
ls
cd git-for-devops
pwd
```

## 2. Create and View a File

```bash
vim hello-dosto.txt
cat hello-dosto.txt
ls
ls -l
```

## 3. Initialize a Git Repository

```bash
git init
ls -a
```

## 4. Check Repository Status

```bash
git status
```

## 5. Create New Files

```bash
touch nibba.txt nibbi.txt
ls
```

## 6. Add Files to Staging Area

```bash
git add nibbi.txt
git add nibba.txt
```

## 7. Commit Changes

```bash
git commit -m "adding nibba nibbi"
```

## 8. Delete a File

```bash
rm hello-dosto.txt
ls
```

## 9. Configure Git User Information

```bash
git config --global user.name "talha2098"
git config --global user.email "talhamunir2098@gmail.com"
```

## 10. Modify a File and Commit Changes

```bash
vim nibbi.txt
git status
git add nibbi.txt
git commit -m "added new changes to nibbi"
```

## 11. View Commit History

```bash
git log
```

## 12. Modify Another File and Commit

```bash
vim nibba.txt
git add nibba.txt
git commit -m "added nibba changes"
```

## 13. View Branches

```bash
git branch
```

## 14. Create a New Branch

```bash
git checkout -b dev
```

## 15. Work on a New Branch

```bash
touch nibbu.txt
git status
git add nibbu.txt
git commit -m "adding nibbu"
```

## 16. Switch Branch

```bash
git checkout master
```

## 17. View Logs on Different Branch

```bash
git log
```

## 18. Switch Back to Development Branch

```bash
git checkout dev
git log
```

## 19. View Commit History in One Line

```bash
git log --oneline
```

## 20. Create Another Branch from Current Branch

```bash
git checkout -b from-dev
```

## 21. Return to Master Branch

```bash
git checkout master
git log --oneline
```

---

*This file documents basic Git commands used during practice and learning DevOps workflows.*
