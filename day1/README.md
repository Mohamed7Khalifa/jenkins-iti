## Lab 1
### 1- install jenkins with docker image
```bash
    docker run -p 8008:8080 -d --name jenkins jenkins/jenkins:lts
```
### 2- install role based authorization plugin
![image info](Screenshot/lab1-q2.png)
### 3- create new user
![image info](Screenshot/lab1-q3.png)
### 4- create read role and assign it to the new user
![image info](Screenshot/lab1-q4-1.png)

![image info](Screenshot/lab1-q4-2.png)
### 5- create free style pipeline and link it to private git repo(inside it create directory and create file with "hello world")
![image info](Screenshot/lab1-q5-1.png)

![image info](Screenshot/lab1-q5-2.png)

![image info](Screenshot/lab1-q5-3.png)

#################
## Lab 2

### 1- create declarative in jenkins GUI pipeline for your own repo to do "ls"
![image info](Screenshot/lab2-q1-1.png)

![image info](Screenshot/lab2-q1-2.png)

### 2- create scripted in jenkins GUI pipeline for your own repo to do "ls"
![image info](Screenshot/lab2-q2-1.png)

![image info](Screenshot/lab2-q2-2.png)

### 3- create the same with jenkinsfile in your branches as multibranch pipeline
![image info](Screenshot/lab2-q3-1.png)

![image info](Screenshot/lab2-q3-2.png)
