# Docker-
   Building image from Dockerfile and creating container:
   
              $ sudo docker build -t testsql.
              $ docker run -d -it -p 3306:3306 --name=testsql testsql
