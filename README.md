GIT

gh auth logout
gh auth login
git remote update
git rm --cached -f Project

git init
echo "#Project" >> README.md
git add README.md
git add . 
git commit -m "commit"
git remote add origin https://github.com/BrightProgrammer7/yourRepository.git
git remote -v
git pull origin main
git push -u origin main
git push --force origin main

git init
cd .git

git branch -m main 
git fetch origin
git branch -u origin/main main
git remote set-head origin -a

git config --list
git config --global --list

git remote set-url origin https://github.com/BrightProgrammer7/Repo.git
git config --global user.email abdelilahk627@gmail.com
git config --global user.name BrightProgrammer7 github
git config --global remote.origin.url https://github.com/BrightProgrammer7/yourRepository.git
git config --global --unset-all core.editor
git config --global --remove-section user 

git config --local --list
git config --local --remove-section core
git config --local --remove-section remote.origin

 
git add README.md .
git commit -m 'add changes'
git push -u origin main


rmdir /q /s .git

git checkout 123abc
git tag v1.0
git checkout v1.0

git remote add origin https://github.com/BrightProgrammer7/Repo.git
git remote -v
git push -u origin master

git branch -m main
git branch -d master
git fetch origin 
git branch -u origin/main main
git remote set-head origin -a
git merge --abort

git branch
git branch main
git checkout main
git merge main

git status
git log --graph --all --oneline
git show HEAD

git remote -v
git clone https://github.com/BrightProgrammer7/Repository.git
git remote show origin

git fetch origin main
git merge origin/main main
git pull origin main

git diff
git branch --set-upstream-to=<remote>/<branch> master
git rebase
git reset --soft --mixed --hard


git remote rm origin
git remote add origin

git credential-manager uninstall
git credential-manager install

 git remote set-url [--push] <name> <newurl> [<oldurl>]
   or: git remote set-url --add <name> <newurl>
   or: git remote set-url --delete <name> <url>

    --push                manipulate push URLs
    --add                 add URL
    --delete              delete URLs

npm config edit
