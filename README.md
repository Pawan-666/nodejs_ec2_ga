### Run it locally
```sh
npm init -y
npm install
node server.js
curl localhost:8080
```

### Push it on github
```sh
git init
git add .
git remote add origin git@github.com:Pawan-666/nodejs_ec2_ga.git
git branch -M main
git push -u origin main
```

### Add DOCKER_USERNAME, DOCKER_PASSWORD in repo secrets

### Create a repo name cicd-pipeline on dockerhub/ecr

```
docker push 666docker1234/cicd-pipeline:tagname
```

### Create a new ec2 instance
```
sudo apt update -y && sudo apt upgrade -y
```

### Set up linux runner on github

### Install docker on the instance

### Make a commit to test the both ci and cd pipeline

