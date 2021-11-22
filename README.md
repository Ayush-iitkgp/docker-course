This repositoy contains the code while learning from Udemy course (https://adfintech.udemy.com/course/docker-fast-track)[https://adfintech.udemy.com/course/docker-fast-track]

## Docker Commands
1. Build a docker container
`docker image build . -t image-name:tag`

2. Run the docker container
`docker container run image-name:tag`

3. Pass the parameters as CMD while running the  docker container
`docker container run image-name:tag CMD`

4. Run the docker container in the background using -d tag
`docker container run image-name:tag`

5. Check the running docker containers
`docker container ls`

6. Stop a particular docker container
`docker container stop container-id`

7. Build a docker file with a different name using -f tag
`docker build -f docker-file-name . -t image-name:tag`

8. Build a docker image from a remote URL
`docker build URL -t image-name:tag`