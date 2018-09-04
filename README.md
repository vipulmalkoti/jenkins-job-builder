# jenkins-job-builder

This repository contains basic job structures of how a Jenkins job created using JJB looks like.
JJB uses YAML code to create, maintain, update, delete jenkins jobs. Its gives you various advantages over the use of a jenkins UI :
1- The job is easier to backup
2- The jobs become more portable onto any jenkins server
3- Once you have a lot of jobs running on you CI server, its easier to use JJB to maintain and update these jobs.

Use "pip install jenkins-job-builder" to install JJB on your machine and create an ini file (present in the repo) generally to "/etc/jenkins_job_builder/jenkins.ini"
