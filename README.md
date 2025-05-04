# README for microservices

## Steps to test

* Ensure the main branch is checked out
* Make a small code change e.g add a System.Println("test") to a microservice
* run git status
* add/commit the changes e.g. 
```
git add services/microservicez/src/main/java/com/example/microservicez/MicroservicezApplication.java
```
* run git push
* go to the GitHub repo https://github.com/emilyjspencer/cicd-microservices-extended
* click on the latest commit 
* watch as it runs tests from the CI pipeline
* click on the Actions tab - there should be workflows under it 
* CI pipeline for microservice x y z
* CD pipeline for Microservice x y z