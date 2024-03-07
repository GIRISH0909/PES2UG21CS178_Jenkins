FROM jenkins/jenkins:lts
#FROM ubuntu:20.04
# if we want to install via apt
USER root
RUN apt-get update && apt-get install -y make && apt-get install -y g++ --fix-missing
# drop back to the regular jenkins user - good practice
USER jenkins





docker run -p 8080:8080 -p 50000:50000 -it jenkins:pes2ug21cs178
c59e93bd1cfa43d488d9e4c729fdbdb6