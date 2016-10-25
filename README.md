# -GitHub-for-Developers\n
Command line history form  GitHub for Developers 25/26-10-16

25 Oktober:
git --version
git config --global --list
git config --global user.name "Firstname Lastname"
git config --global user.email "me@example.com"
git config --global core.editor "atom --wait"
git config --global core.autocrlf input
git config --global push.default simple
git config --list

git clone https://github.com/githubteacher/dev-oct-25-emea.git
ls
cd dev-oct-25-emea
ls

git branch --all
git checkout githubteacher-ichenhausen
git branch --all
touch githubteacher-ichenhausen.md
git status
git add githubteacher-ichenhausen.md
git status
git commit
git push
git pull
atom .
git status
git add --all
git status
git commit -m "Add things to do and places to eat"
git push

git pull
ls
git branch --all
git branch --merged
git branch -d githubteacher-ichenhausen
git branch -D githubteacher-ichenhausen
git pull --prune
git branch --all

git log
git log --oneline
git log --oneline --graph
git log --oneline --graph --decorate
git log --oneline --graph --decorate --all

git config --global alias.lol "log --oneline --graph --decorate --all"
git lol

git pull --prune
git config --global fetch.prune true
git pull
:warning: Note:

"git config --global core.autocrlf input" is for Unix/Mac
"git config --global core.autocrlf true" is for Windows

26 Oktober:
