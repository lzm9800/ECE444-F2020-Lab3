## To run with docker
make sure the current working directory is ECE444-F2020-Lab3. The location of the Dockerfile is under \ECE444-F2020-Lab3\

Run commands: 

docker build -t helloworld-app:latest .

docker run -it --name hellowworld-app --rm -p 5000:5000 helloworld-app

## Docker screenshots:

### Docker image
![image](https://user-images.githubusercontent.com/43189674/96208949-952ada00-0f3c-11eb-9265-a2c30e96d760.png)

### Docker running
![image](https://user-images.githubusercontent.com/43189674/96208969-a07e0580-0f3c-11eb-9f57-5ca918f822fd.png)

### My web application
![image](https://user-images.githubusercontent.com/43189674/96209005-abd13100-0f3c-11eb-97d3-96b180c7a182.png)

### Docker application
![image](https://user-images.githubusercontent.com/43189674/96208921-83e1cd80-0f3c-11eb-807e-72e562648a32.png)

## Docker VS Virtual Machine
The main difference between Docker and Virtual Machine is that Docker will exist as an application and is efficient, while Virtual Machine uses much more resources. A virtual machine is also much more difficult to maintain since it can be prone to error. Docker image on the other hand is immutable and is much smaller, so it can be shared easily and the docker container will run in an isolated environment. 

