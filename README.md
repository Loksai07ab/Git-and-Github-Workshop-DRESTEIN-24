# Git-and-Github-Workshop-DRESTEIN-24
NAME: LOKSAI S 
REGISTER NUMBER : 212223050027  
DEPARTMENT :  EEE
YEAR : II

1. Setup and Initialize: 
mkdir git-workshop
cd git-workshop

2. Initialize a Git Repository:
git init

3. Create and Modify Files:
echo 'Hello, Git Workshop!' > hello.txt

4. Check the Status of Your Repository:
git status

5. Stage and Commit Changes:
(i)git add hello.txt
(ii)git commit -m 'Add hello.txt with welcome message'

6. Branching:
(i)git branch update-content
(ii)git checkout update-content
    git checkout -b update-content

7. Make Changes on the Branch:
(i)echo 'This is a simple Git assignment.' >> hello.txt
(ii)git add hello.txt
    git commit -m 'Update hello.txt with additional message'

8. Merge Changes:
(i)git checkout main
(ii)git switch main
    git merge update-content

9. View Commit History:
(i)git log
(ii)git log --oneline
    git log --graph --oneline --all

10. Undo and Reset (Practice Safely):
(i)git checkout -- hello.txt
(ii)git reset --hard <commit_hash>
    git reset --soft <commit_hash>

11. Push to a Remote Repository (Optional): 
(i)git remote add origin <remote_repository_URL>
(ii)git push origin main
