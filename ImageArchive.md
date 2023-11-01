### Task 2: Image and Container Operations

## Create Image Archive


## Run Nginx Container:
> docker pull nginx

### 1. Bind the container's port 80 to the local port 80.


> docker run -p 80:80 nginx

-p 80:80 maps port 80 of the host machine to port 80 of the container. This allows you to access the Nginx web server running inside the container via http://localhost.


### 2. Run the container in detached mode and name it "nginx_container".

> docker run -d -p 80:80 --name my_nginx nginx

-d runs the container in detached mode (in the background).

--name my_nginx assigns a custom name "my_nginx" to the container for easy reference.
nginx at the end is the name of the image you want to run the container from.

### 3. Verify that the web server is running and accessible from the local machine.


![Alt text](lab8_2.png)


