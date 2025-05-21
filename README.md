# LEARNING GIT

## Commads
Commands I used to do this task:
ls
mkdir learninggit
ls
cd learninggit/
git status
git branch
git config --help
git config --list
git config user.name "Mirzomumin"
git config user.email "mirzomumin@list.ru"
git config --list --show-origin
ls 
cd learninggit/
ls
ls -a
mkdir docs folder ignored_folder
ls
cd learninggit/
ls
tocuh docs/file_1.txt docs/file_2.txt docs/file_3.txt
touch docs/file_1.txt docs/file_2.txt docs/file_3.txt
cp docs/* folder/
ls folder/
cp docs/* ignored_folder/
ls
ls docs
ls folder/
ls ignored_folder/
git status
touch .gitignore
echo "ignored_folder" > .gitignore 
cat .gitignore 
git status
git add .
git commit -m "feat(project structure): define initial project"
git status
git branch
git branch -m main
git branch
git checkout -b feature/ui main
git checkout main 
git branch feature/api
ls
cd learninggit/
ls
ls
cd learninggit/
ls
git log
git branch
ls
git branch
git checkout feature/api 
ls
ls docs/
vim docs/file_1.txt
cd learninggit/
git branch
ls
vim docs/file_1.txt 
git branch
git status
git add .
git log
git commit -m "feat(first text): add the first text in file"
git branch
ls
vim docs/file_1.txt 
git status
git add .
git commit -m "feat(second text) add the second text in file"
git branch
git checkout main 
git branch
git merge --no-ff feature/api -m "Merge branch 'feature/api' into main"
git branch
git remote add origin git@github.com:mirzomumin/learninggit.git
git push -u origin main
git remote --help
git remote remove origin 
git remote --help
git remote -v
git remote add origin https://github.com/mirzomumin/learninggit.git
git push -u origin main
ls
git branch
cd learninggit/
ls
git branch
git log 
git branch
git checkout feature/ui 
git branch
ls
vim docs/file_2.txt 
git status
git add docs/file_2.txt 
git commit -m "feat(second file): add a text in the send file of docs folder"
ls
rm folder/file_1.txt 
git branch
git status
git add folder/
git commit -m "fix(folder file): remove the first file of the folder directory"
git branch
git checkout man
git checkout main 
git rebase feature/ui 
git checkout feature/ui 
ls
vim docs/file_1.txt 
git branch
git status
git commit -m "feat(docs file): add a text into docs file"
git add .
git commit -m "feat(docs file): add a text into docs file"
git branch
git checkout main 
git rebase feature/ui 
git status
vim docs/file_1.txt 
git add .
git rebase --continue 
vim docs/file_1.txt
git add .
git rebase --continue
git branch
git tag -a v1.0.0 -m "add v1.0.0"
git log
git tag -l
git log --pretty=online
git log --pretty=oneline
git branch
git status
ls
ls folder/
vim folder/file_3.txt 
git status
git add .
git commit -m "feat(bug): add bug text into file of folder directory"
git revert HEAD
git status
vim folder/file_2.txt 
git add .
git commit -m "feat(bug): add second bug text into file"
git reset --help
git reset --hard HEAD~
git log
git branch
ls
vim docs/file_3.txt 
git status
git stash
git status
git stash pop
git add .
git commit -m "feat(stash text): add stash text into file"
git status
git remote add origin https://github.com/mirzomumin/learninggit.git
git push -u origin main
git checkout feature/ui 
git push origin feature/ui 
git push origin feature/api 
