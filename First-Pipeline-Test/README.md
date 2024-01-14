# A simple jenkins pipeline to verify if the docker agent configuration is working as expected.

* From Ubuntu navigate to jenkins using command
```
sudo su - 
usermod -aG docker jenkins
usermod -aG docker ubuntu
systemctl restart docker

```

![image](https://github.com/komalagra/Jenkins-Project/assets/39221080/ba9bbb35-5de9-4448-bed4-33f697ca27ff)

* Enter sudo user pass and then enter the below command
 ```
su - jenkins

``` 

![image](https://github.com/komalagra/Jenkins-Project/assets/39221080/6d030150-f0f5-4f86-9587-510d694cf6bc)

![image](https://github.com/komalagra/Jenkins-Project/assets/39221080/98e2c5e3-32c0-4c84-b88b-e2704520aea1)

* check the docker agent
 ```
docker ps
```
![image](https://github.com/komalagra/Jenkins-Project/assets/39221080/27d48f28-8ce7-40d4-9a3e-20d75b0c40c5)





