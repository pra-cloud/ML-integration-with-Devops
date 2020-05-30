# ML-integration-with-Devops

The goal of any Machine Learning Project is to train a model with high accuracy, for getting high accuracy we need best parameters (bias & weight). But the biggest challenges are:

1.	We have to keep eye on the machine learning model whether model gave the desired accuracy or not. If not then we tweak the machine learning model architecture by manually adding some layers like convolutional layer, pulling layer, dense layer, etc. This consume time, energy and delay in project.
2.	 If system fail/terminate due to any reason so at that time all the hard word we have done is vanished.

So for all this challenges we can take the help DevOps. When Machine Learning is integrated with DevOps our manual work become automated, work become so easy that you have to just give one command it will do all your task. Now you don’t have to monitor anything DevOps will notify you when task is completed and now you can engage yourself in other work.

In this practical you will come to know how we can integrate Machine Learning with Devops tools i.e. GitHub, Jenkins, Docker.For the practical I am using Base OS REHL – 8 on top of my windows using virtualization technology. Jenkins and Docker is installed in REHL – 8. There is a network connectivity between windows and RHEL – 8 so I am going to use Jenkins in windows chrome. I am using MNIST dataset for this practical.

# Agenda : 
-	Creating docker container using Dockerfile. 
-	When we launch this image, it should automatically starts train the model in the containe.
-	Tweak the machine learning model architecture if desired accuracy not got. 
-	Notify the developer when desired accuracy got
-	Keep monitoring if container fails due to any reason start/launch the container again where the last trained model left.

## Step 1:
- Python code is going to run in docker container in Centos. So saving all python script with .py extension and creating container image that has Python3, keras, numpy, tensorflow, etc. using Dockerfile. Finally uploaded/push on GitHub.




```
vim Dockerfile
```



- hfg **roiugoiu** *gurgpounfnufc*




