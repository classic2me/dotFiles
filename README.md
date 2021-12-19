https://github.com/classic2me/dotFiles.git


echo "# dotFiles" >> README.md

# init a working-copy
git init

git add README.md

git commit -m "first commit"

git branch -M main

git remote add origin https://github.com/classic2me/dotFiles.git

git push -u origin main


git remote add origin https://github.com/classic2me/dotFiles.git

git branch -M main

git push -u origin main


# update the file
git status

git add README.md

git commit -m "modified README.md"

git status

git pull origin main

git push origin main

# sync a local directory with an existing git repo
git init

git remote add origin https://github.com/classic2me/dotFiles.git

git fetch origin

git reset origin/master

git status
