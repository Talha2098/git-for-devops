Git Commands for DevOps Practice
1. Create Project Directory

mkdir git-for-devops
cd git-for-devops
pwd

2. Create & View Files

vim hello-dosto.txt
cat hello-dosto.txt
touch nibba.txt nibbi.txt

3. Initialize Git Repository

git init

4. Check Repository Status

git status
ls
ls -a

5. Remove Files

rm hello-dosto.txt

6. Add Files to Staging Area

git add nibba.txt
git add nibbi.txt

7. Commit Changes

git commit -m "adding nibba nibbi"
git commit -m "added new changes to nibbi"
git commit -m "added nibba changes"
git commit -m "adding nibbu"

8. Configure Git User

git config --global user.name "talhamunir2098"
git config --global user.email "talhamunir2098@gmail.com
"

9. Modify Files

vim nibbi.txt
vim nibba.txt

10. View Commit History

git log
git log --oneline

11. Branching

git branch
git checkout -b dev
git checkout -b from-dev
git checkout -b from-master

12. Switch Branches

git checkout dev
git checkout master
git switch dev

13. Working with New Files in Branch

touch nibbu.txt
git add nibbu.txt
git commit -m "adding nibbu"

14. Verify Branch Work

git status
git log

15. Terminal Utilities

clear
doing new things
history
ls
