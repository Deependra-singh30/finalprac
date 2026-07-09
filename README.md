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
sudo docker run -it -p 1234:80 --name sample -d nginx

docker ps



alpine

Complete Workflow
mkdir deep

cd deep

nano student.sh

student.sh

#!/bin/bash

echo "Deep"
chmod +x student.sh

./student.sh

nano Dockerfile

Dockerfile

FROM alpine

COPY student.sh /student.sh

RUN chmod +x /student.sh

CMD ["/student.sh"]




sudo docker pull alpine

sudo docker run -it alpine sh



touch info.txt

echo "Welcome to Alpine Linux" > info.txt

cat info.txt

exit






