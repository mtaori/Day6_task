**### Project 01

### Deploying a Node.js App Using Minikube Kubernetes

#### Overview

This project guides you through deploying a Node.js application using Minikube Kubernetes. You'll use Git for version control, explore branching and fast-forward merges, and set up Kubernetes services and deployment pods, including ClusterIP and NodePort service types.

#### Prerequisites

* Minikube installed
* kubectl installed
* Git installed
* Node.js installed ([https://nodejs.org/en/download/package-manager/all#debian-and-ubuntu-based-linux-distributions](https://nodejs.org/en/download/package-manager/all#debian-and-ubuntu-based-linux-distributions))

#### Project Steps

### 1. Set Up Git Version Control

1.1. Initialize a Git Repository

Create a new directory for your project:

mkdir nodejs-k8s-project

cd nodejs-k8s-project

**

![](https://lh7-us.googleusercontent.com/docsz/AD_4nXfxQQfoOpBngSsxERhRaxxgNNCISZrhWNQjAtfbEM6QL7FBFHGCi0s9FkdqysV7nxqNVkrFTlHGLvymt86hIWvSuxL-vY3zxnWypZWEeSlzlJbqEITHUfNYaBHSAgYD44xkg5kND8NlJZQj-UjEkr7AygLd?key=VAl51T7aZdwkh4FLsU5uMg)

**Initialize a Git repository:

git init

1.2. Create a Node.js Application

Initialize a Node.js project:

npm init -y

Install Express.js:

npm install express

**

![1721105205012](images/Day6readme/1721105205012.png)


![1721105769128](images/Day6readme/1721105769128.png)



**1.3. Commit the Initial Code

Add files to Git:

git add .

Commit the changes:

git commit -m "Initial commit with Node.js app"**
