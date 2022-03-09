# TS-CICD

This a repo for files used in creating CI/CD Pipeline.

## _CICD pipeline for Typescript using Docker & jenkins & github_
## _What did i use to create this pipeline_
- ##### Docker
- ##### Jenkins
- ##### Github

## _Files Used:_

| File | Description |
| ------ | ------ |
| Dockerfile-node | A Docker file to compile Typescript code to javascript one and run it on server (Using `Multi-Stage build` in order to keep the image size down|
| Dockerfile-jenkins | [https://github.com/boda175/Ts-CICD-Pipeline-Files/blob/master/Dockerfile-jenkins][PlGh] Docker file to create Jenkins server and install Docker on it.|
| docker-compose-jenkins | [https://github.com/boda175/Ts-CICD-Pipeline-Files/blob/master/docker-compose-jenkins.yaml][PlGd] docker compose file to provision the jenkins server |
| Jenkinsfile | [https://github.com/boda175/Ts-CICD-Pipeline-Files/blob/master/Jenkinsfile][PlOd] A file that contains the definition of a jenkins pipeline (It stores the entire workflow as a code)|


```sh
Note: i have used 'Webhook' to trigger the Jenkins pipeline when some events occuers like 'Push' 'Commit' ...etc
```



