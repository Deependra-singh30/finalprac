mkdir labpractice
cd labpractice

git --version

git config --global user.name "Your Name"
git config --global user.email "your_email@gmail.com"
git config --list

git init

touch student.txt
git add student.txt
git commit -m "first"

git status
git log
git log --oneline
git log --graph --all --oneline

git branch -M main

git remote add origin https://github.com/username/repository.git

git push -u origin main

git branch
git checkout -b feature1

nano marks.txt

git add marks.txt
git commit -m "Added marks"

git checkout main
git merge feature1

git log

git branch -d feature1
git remote -v





docker

sudo docker run -it -p 1234:80 --name sample -d nginx

docker ps

mkdir website
cd website

nano index.html

sudo docker cp index.html sample:/usr/share/nginx/html/index.html

docker ps
