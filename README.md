# Kubernetes
  * System for running many different containers over multiple different machines.
  * When you need to run many different containers with different images. 
#### Working with Kubernetes
  * Development 
    * minikube
      * Minikube is a commond line tool which sole purpose is going to be to set up a tiny little kubernetes cluster(with master and different load balancing nodes)(inside a node there can be mutliple containers)
  * Production 
    * Managed Solutions 
      * Amazon Elastic Container Service for Kubernetes (EKS)
      * Google Cloud Kubernetes Engine (GKE)
    * Do it yourself 
#### Minikube
  * Minikube will create a kubernetes cluster in your local machine. Behind the scene, it is going to create a Virtual Machine whose sole purpose is to run certain number of containers. 
  * We will make only use of minikube in the local environment.
#### Kubectl
  * We will use kubectl to interact with virtual machine created by minikube.
  * kubectl is a program that is used to interact with the kubernetes cluster in general and manage what different nodes are doing and what different containers are they running. 
  
#### Note: When we installed a Docker for Mac or Windows, it was technically creating a virtual machine at the same time. That's essentially, same thing that's happening in the world of kubernetes, the only difference is Docker for Mac or Windows installed the virtual machine for you and all the associated software with it. But in the world of kubernetes not quite so automatic. 
