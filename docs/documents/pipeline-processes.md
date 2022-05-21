
# Udagram CirceCI Pipeline

## Pipeline Process
1. Front-End Installation
    - Install all needed packages for the frontend project to run smoothly, the frontend project based on angular
2. Back-End Installation
    - Install all needed packages for the backend project, it is based on node and expressjs
3. Front-End Building
    - BUild the project to generate the production-ready asset files to be hosted.
4. Back-End Building
    - BUild the project to generate the production-ready asset files to be hosted.
4. Front-End Test
    - run unit tests
5. Back-End Test
    - run unit tests
6. Back-End Deployment
    - Deploy the asset files that generated from **Building Backend Step** into AWS (eleasticBeansTalk).
7. Front-End Deployment
    - Deploy the asset files that generated from **Building Frontend Step** into AWS (Bucket S3).
