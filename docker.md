1. Login to a docker artifactory
   _docker -u login user_name docker_url_
   **Example**:
   _docker -u login abhay.mishra docker-dev.somedomain.com_
2. Tag a docker image
   _docker tag test-service:0.1 docker-dev.somedomain.com/testservice/test-service:v0.0.1.325d906_
3. Push docker image to a remote repository
   _docker push docker-dev.somedomain.com/testservice/test-service:v0.0.1.325d906_
4. List all docker images
   _docker images_
5. Show running docker images
   _docker ps_
6. Build docker image from a docker file
   _docker build -t test_service:0.1 -f path_to_Dockerfile.testservice ._ 
7. Run a docker image
   _docker run -p port:port docker_image_id ._
   