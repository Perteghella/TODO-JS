# DOCKER

cd /app

docker build -f Dockerfile-22 -t todo:22 .
docker scout quickview 

docker run -d -p 3000:3000 --name todo-app-22 todo:22

## GIT

git init
git remote add origin https://github.com/Perteghella/TODO-JS.git
git branch -M main

