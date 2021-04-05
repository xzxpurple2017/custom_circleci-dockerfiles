# custom_circleci-dockerfiles

These are custom Docker images used for the CircleCI build pipelines. 
They contain no secrets or private information. 
Usually, the images contain extra packages necessary for build and release, such as AWS CLI, Kubectl, Helm, etc...

When building new images, please base it off of the official CircleCI Dockerfiles. 
In the future, it may be helpful to attach this to a CI/CD pipeline to build these public images. 

## Docker Hub repository
* https://hub.docker.com/r/phdam8/circleci_node

## Other useful links:
* Original CircleCI Dockerfiles: https://github.com/CircleCI-Public/circleci-dockerfiles
* CircleCI custom image docs: https://circleci.com/docs/2.0/circleci-images/
