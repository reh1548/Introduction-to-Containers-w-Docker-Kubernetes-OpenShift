# Introduction to Containers w/ Docker, Kubernetes & OpenShift by IBM
This repository contains the Labs and the Final Project of the [Introduction to Containers w/ Docker, Kubernetes &amp; OpenShift Course](https://www.coursera.org/learn/ibm-containers-docker-kubernetes-openshift) offered by **IBM** on **Coursera**.

## :file_folder: [Week 1: Understanding the Benefits of Containers](https://github.com/evgenyzorin/IBM-Docker-Kubernetes-OpenShift/tree/main/Week%201)
### Containers and Containerization
Start your first week by learning about container concepts, features, use cases, and benefits. Building on your new knowledge of containers, you’ll learn what Docker does and discover why Docker is a winner with developers. You’ll learn what Docker is, become acquainted with Docker processes, and explore Docker’s underlying technology. Learn about how developers and organizations can benefit from using Docker and see which situations are challenging for using Docker. Next, learn how to build a container image using a Dockerfile, how to create a running container using that image, become familiar with the Docker command line interface (CLI), and explore frequently used Docker commands. You’ll become knowledgeable about Docker objects, Dockerfile commands, container image naming, and learn how Docker uses networks, storage, and plugins. Then, assimilate this knowledge when you see Docker architecture components in action and explore containerization using Docker. At the end of this first week, you’ll pull an image from a Docker Hub registry. You’ll run an image as a container using Docker, build and tag an image using a Dockerfile, and push that image to a registry. 
### Learning Objectives
- Build a container image and store it in a container registry.
- Describe features, benefits, and use cases of containers vs virtual machines.
- Define Docker and list commonly used Docker CLI commands.
- Explain container registries and how they differentiate and are interacted with.
- Compare and contrast containers and images.
- Use Docker to pull an image, run it, and push it to a registry.
- List commonly used Dockerfile instructions and describe image building and tagging.
- Describe Docker architecture components and containerization.
- Explain how Docker works as a container runtime.
- Describe the IBM Cloud Container Registry service.

## :file_folder: [Week 2: Understanding Kubernetes Architecture](https://github.com/evgenyzorin/IBM-Docker-Kubernetes-OpenShift/tree/main/Week%202)
### Kubernetes Basics
In week two, learn what container orchestration is. Then, explore how developers can use container orchestration to create and manage complex container environment development lifecycles. Kubernetes is currently the most popular container orchestration platform. You’ll examine key Kubernetes architectural components, including control plane components and controllers. Explore Kubernetes objects, and learn how specific Kubernetes objects such as Pods, ReplicaSets, and Deployments work. Then, learn how developers use the Kubernetes command line interface (CLI), or “kubectl” to manipulate objects, manage workloads in a Kubernetes cluster, and apply basic kubectl commands. You’ll be able to differentiate the benefits and drawbacks of using imperative and declarative commands. At the end of this module, you will use the kubectl CLI commands to create resources on an actual Kubernetes cluster. At the end of this week, you’ll use the Kubernetes CLI to create a Kubernetes pod, create a Kubernetes deployment, create a ReplicaSet and see Kubernetes load balancing in action.
### Learning Objectives
- Monitor Kubernetes load balancing.
- Create a ReplicaSet to maintain replicas.
- Create Kubernetes Pods using imperative and declarative configurations.
- Utilize the kubectl CLI.
- Describe how Kubernetes objects like Pods, ReplicaSets, and Deployments function.
- Explain imperative and declarative commands in Kubernetes and their pros and cons.
- List basic kubectl commands.
- Describe Kubernetes CLI (kubectl) and its functionalities.
- Explain Kubernetes objects.
- Identify tools, platforms, and services in the Kubernetes ecosystem.
- Describe Kubernetes and its popularity as a container orchestration platform.
- List components of Kubernetes control planes and nodes and their functions.
- Describe the architecture of a Kubernetes cluster.
- Summarize container orchestration and its advantages.

## :file_folder: [Week 3: Managing Applications with Kubernetes](https://github.com/evgenyzorin/IBM-Docker-Kubernetes-OpenShift/tree/main/Week%203)
### Managing Applications with Kubernetes
In week three, you’ll explore ReplicaSets, autoscaling, rolling updates, ConfigMaps, Secrets, and service bindings, and learn how you can use these capabilities to manage Kubernetes applications. You’ll learn how ReplicaSets scale applications to meet increasing demand, and how autoscaling creates dynamic demand-based scaling. You’ll see how to use rolling updates to publish application updates and roll back changes without interrupting the user experience. You’ll learn how to use ConfigMaps and Secrets to provide configuration variables and sensitive information to your deployments and to keep your code clean. At the end of the week, you’ll scale and update applications deployed in Kubernetes.
### Learning Objectives
- Explain different deployment strategies and their appropriate use cases.
- Describe binding an external service to a deployment.
- Explain what a Secret is, creation methods, and its use for sensitive information.
- Define ConfigMap and creation methods.
- Discuss rolling updates for application changes.
- Describe autoscaling and its dynamic application scaling.
- Explain creating a ReplicaSet via CLI and YAML.
- Describe how ReplicaSet scales your application.

## :file_folder: [Week 4: The Kubernetes Ecosystem](https://github.com/evgenyzorin/IBM-Docker-Kubernetes-OpenShift/tree/main/Week%204)
### The Kubernetes Ecosystem: OpenShift, Istio, etc.
In week four, you’ll learn more about the growing Kubernetes ecosystem and explore additional tools that work well with Kubernetes to support cloud-native development. You’ll gain an understanding of the similarities and differences between Red Hat ® OpenShift® and Kubernetes and see what OpenShift architecture looks like. You’ll learn about OpenShift builds and BuildConfigs, and OpenShift build strategies and triggers. You'll also discover how operators can deploy whole applications with ease. Finally, you’ll examine how the Istio service mesh manages and secures traffic and communication between an application’s services. At the end of the week, you’ll use the oc CLI to perform commands on an OpenShift cluster. And you’ll use the OpenShift build capabilities to deploy an application from source code stored in a Git repository.
### Learning Objectives
- Examine BuildConfig and ImageStream.
- Build and deploy an application using s2i.
- Utilize the oc CLI.
- Describe Istio's capabilities and their significance for microservices.
- Explain the concept of operators and their automation role in clusters.
- Discuss OpenShift build strategies and build triggers.
- Describe the relationship between Red Hat OpenShift and Kubernetes, highlighting similarities and differences.

## :file_folder: [Week 5: Final Assignment - Build and Deploy a Guestbook App](https://github.com/evgenyzorin/IBM-Docker-Kubernetes-OpenShift/tree/main/Week%205)
### Final Assignment: Final Project - Build and Deploy a Guestbook App
For the Final Project, you will put into practice the tools and concepts learned in this course, and deploy a simple guestbook application with Docker and Kubernetes.The entire application will be deployed and managed on OpenShift.
### Learning Objectives
- Evaluate peers' guestbook app on GitHub using rubric and grading scheme.
- Submit GitHub repository URL to share project.
- Autoscale the guestbook app.
- Deploy a multi-tier version of the guestbook application.
- Use OpenShift image streams for updating.
- Build and deploy a simple guestbook application.
