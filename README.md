mkdir new-project
cd new project
git init
echo "init" > README.md
git add README.md
git commit -m "init"
git branch -M main
git remote add origin https://github.com/Dmytro-Olshanskyi/new-project.git
git -b checkout development main
git commit -m "Add instruction to README.md"
git checkout main
git merge development
#git branch -d development