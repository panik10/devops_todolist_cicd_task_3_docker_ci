# Django ToDo List Application

This project is an advanced to-do list web application with the basic features of most web apps, such as accounts/login, API, and interactive UI. 
To complete this task, you will need:

- CSS | [Skeleton](http://getskeleton.com/)
- JS  | [jQuery](https://jquery.com/)

## Summary

In this task, I extended the GHActions workflow by adding Docker build and push functionality:

    Added a new docker-ci job that runs only on the main branch.

    The job includes the following steps:

        - Logs in to DockerHub using credentials stored in GitHub Secrets.

        - Builds a Docker image using the provided Dockerfile.

        - Tags the image with the current commit SHA.

        - Pushes the image to my DockerHub registry.

    The PR description includes a reference to a successful workflow run that completed the docker-ci job.
