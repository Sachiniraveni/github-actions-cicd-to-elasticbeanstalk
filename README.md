[![Build Status](https://github.com/JS-DevTools/npm-publish/workflows/CI-CD/badge.svg)](https://github.com/JS-DevTools/npm-publish/actions)
<p>
[![Dependencies](https://david-dm.org/JS-DevTools/npm-publish/status.svg)](https://david-dm.org/JS-DevTools/npm-publish)



# github-actions-cicd-to-elasticbeanstalk

The Workflow in ./github/workflows/main.yml also follows setup for parallel builds. Just to test if the parallel builds are working or not. Otherwise having parallel builds for CI & CD pipeline is not quite logical.
So, you need to re-run the jobs once-again to build successfully i.e CD pipeline to get the artifacts from s3 bucket and deploy it to the elastic beanstalk environments.


1. Mandatory to have an s3 bucket and Elastic beanstalk environment up and running.

The code has newer vesion of the application, it will build it and save the artifacts to the s3 and then deploy it to the EB.
