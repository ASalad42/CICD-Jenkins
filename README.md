
# CI/CD & Jenkins

CI CD is the blueprint to devops strategies and reason for **faster software releases**. CI/CD facilitates an effective process for getting **products to market faster**, continuously delivering code into production, and ensuring an **ongoing flow of new features and bug fixes via the most efficient delivery method.**
- In short, CI is a set of practices performed as developers are writing code, and CD is a set of practices performed after the code is completed.
- The CI/CD pipeline is part of the broader DevOps framework
- **It is the backbone of DevOps practices and automation**, It plays vital, challenging and exciting role in DevOps culture, growing numbers of companies releasing software in minutes with the adoption of CICD practices.

To put it simply, the continuous integration is part of both continuous delivery and continuous deployment. The main difference is the deployment step, in **continuous delivery the deployment is done manually** and in **continuous deployment it happens automatically**
- CI/CD exist to automate the deployments and building of software

Working Diagram:

![image](https://user-images.githubusercontent.com/104793540/187963750-f3c11787-1e12-4fd6-ab3f-927099002c47.png)

## Integral Part of DevOps Lifecycle 

![image](https://user-images.githubusercontent.com/104793540/188126158-d84a579b-2683-482c-8b8a-375f62405ed0.png)

- **Continuous development**
- **Continuous integration**
- Continuous testing
- **Continuous deployment**
- Continuous monitoring
- Continuous feedback
- Continuous operations

### Tools

![image](https://user-images.githubusercontent.com/104793540/188125966-6be213fd-23cf-4847-99e2-fa1de237ee7a.png)

## Continuous Integration (CI)
Developers merge/commit code to master branch multiple times a day, fully automated build and test process which gives feedback within few minutes, by doing so, you avoid the integration hell that usually happens when people wait for release day to merge their changes into the release branch.

CI: Automation 


## Continuous Delivery
Continuous Delivery ensures that you can release new changes to your customers quickly in a sustainable way. This means that on top of having automated your testing, you also have automated your release process and you can deploy your application at any point of time by clicking on a button. **In continuous Delivery the deployment is completed manually.**


## Continuous Deployment 
Continuous Deployment goes one step further than continuous delivery, with this practice, **every change that passes all stages of your production pipeline is released to your customers, there is no human intervention**, and only a failed test will prevent a new change to be deployed to production.

## CI/CD Pipline 

![image](https://user-images.githubusercontent.com/104793540/187894786-00bf110b-5b88-4612-8e1f-fb10a230eec4.png)


### Benifts 
- Faster software releases 
- Reduce cost (less overall manual work due to automation) 
- Fault isolations 
- Robustness (increased test reliability)
- Easier updates 

## Jenkins 


Jenkins is an open-source automation server in which the central build and CI process take place, It is a Java-based program with packages for Windows, macOS, & Linux.
Build automation server > builds your jobs and automates > lots of plugins

![image](https://user-images.githubusercontent.com/104793540/187895244-e8d9c5da-eb4b-471a-b555-6b502e94b0f1.png)

### Installing Prerequisites
- create ec2 server
- install docker (Before you install Docker Engine for the first time on a new host machine, you need to set up the Docker repository. Afterward, you can install and update Docker from the repository.)
- https://docs.docker.com/engine/install/ubuntu/ - install docker engine 
