# github-actions-cicd-to-elasticbeanstalk

The Workflow in ./github/workflows/main.yml also follows setup for parallel builds. Just to test if the parallel builds are working or not. Otherwise having parallel builds for CI & CD pipeline is not quite logical.
So, you need to re-run the jobs once-again to build successfully i.e CD pipeline to get the artifacts from s3 bucket and deploy it to the elastic beanstalk environments.
