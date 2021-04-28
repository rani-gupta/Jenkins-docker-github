# Integration of Github,Docker and Jenkins
###Task to do:
JOB-1 :If Developer push to dev branch then Jenkins will fetch from dev and deploy on dev-docker environment.
JOB-2 :If Developer push to master branch then Jenkins will fetch from master and deploy on master-docke environment.both dev-docker and master-docker environment are on different docker containers.
JOB-3 :Manually the QA team will check (test) for the website running in dev-docker environment. If it is running fine then Jenkins will merge the dev branch to master branch and trigger job2.

###To know how to do this check out my blog:
https://medium.com/@raniagrawal2001/integration-of-jenkins-and-docker-and-github-254b14ac3c8f?sk=8e0809cdb5f2dd4ff6370cdfbc4f0282
