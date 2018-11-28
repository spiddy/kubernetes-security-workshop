# kubernetes-security-workshop

# Table of contents
1. [Introduction](#introduction)
2. [Setup](#setup)
    1. [Azure](setup/azure.md)
    2. [Minikube](setup/minikube.md)
    3. [Play with Kubernetes](setup/play-with-k8s.md)
3. [Kubernetes architecture overview ](#overview)
4. [Securing Kubernetes components ](#components)
5. [Introduction to Apparmor ](#apparmor)
6. [Securing our pods](#pods)
7. [Rbac, namespaces and cluster roles](#roles)
8. [Introduction to knative](#knative)
9. [Securing application communication with knative](#secknative)

## Introduction <a name="introduction"></a>
This is the Kubernetes security workshop, we have three ways to run this workshop depending on the setup you have. You can run it on the cloud in Azure, locally via Minikube or on a low resource machine in Play with Kubernetes. 

## Setup <a name="setup"></a>
There are three methods to set up this workshop either to use in the classroom or after the workshop at your own pace. They are as follows  
[Azure](setup/azure.md)  
[Minikube](setup/minikube.md)  
[Play with Kubernetes](setup/play-with-k8s.md)

Then familarise yourself with the application that we are going to [deploy](code/webapp/Dockerfile)  
All the code lives [here](https://github.com/scotty-c/kubernetes-security-workshop/tree/master/code/webapp)

## Kubernetes architecture overview <a name="overview"></a>
This module walks through the Kubernetes components and gives us a solid foundation for the rest of the workshop.    
To run through the lab start [here](kubernetes-architecture/architecture.md)

## Securing Kubernetes components <a name="components"></a>

## Introduction to Apparmor <a name="apparmor"></a>

## Securing our pods <a name="pods"></a>
In this module we will look at how to secure a Kubernetes deployment using our web application with pod security context.  
To run through the lab start [here](securing-our-pods/securing.md)

## Rbac, namespaces and cluster roles <a name="roles"></a>

## Introduction to knative <a name="knative"></a>

## Securing application communication with knative <a name="secknative"></a>





