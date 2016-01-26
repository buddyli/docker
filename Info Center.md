#Info Center

##Docker guide center
https://docs.docker.com/engine/userguide/

##Docker manual document
https://docs.docker.com/engine/userguide/dockerrepos/

##Docker file best practice
https://docs.docker.com/engine/articles/dockerfile_best-practices/

#Commands

#Issues
###1. Got 403 forbidden error while run docker login on Windows
https://github.com/docker/hub-feedback/issues/473
Specify index registry but not use the default one, then input username, password and email, can login successfully now.
######$: docker login  https://index.docker.io/v1/

###2. Got "/bin/sh -c *** returned non-zeor code:1" while doing docker build based on Dockerfile
Run apt-get install with -y option, assume install all packages automatically.
