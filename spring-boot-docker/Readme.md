1. Create spring boot docker image and push it to docker hub
   1. Create simple spring boot project
   2. Add DockerFile with properties like FROM, EXPOSE, ADD and ENTRYPOINT
   3. Install Docker desktop
   4. Create, Run and Push docker image with below steps 
      1. Build docker image - "docker build -t spring-boot-docker.jar ."
      2. Check creation of image - "docker image ls"
      3. Run docker image in docker engine - "docker run -p 8080:8080 spring-boot-docker.jar"
      4. Push docker image to hub
         1. login to docker hub from docker desktop
         2. create new image with tag - "docker tag spring-boot-docker.jar arjuna1112/spring-boot-docker.jar"
         3. push image - "docker push arjuna1112/spring-boot-docker.jar"
         4. pull image - "docker pull arjuna1112/sprin-boot-docker.jar"