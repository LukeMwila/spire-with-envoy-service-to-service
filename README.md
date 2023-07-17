# SPIRE Integration with Envoy (Service to Service)

This respository contains the source code for an example of how to use SPIRE with Envoy. This particular setup consists of 3 microservices that each have an Envoy proxy. These 3 microservices are fronted by an Envoy edge proxy. 

![Alt text](./tech-arch-diagram.png?raw=true "Architecture Diagram for SPIRE and Envoy Deployment in Amazon EKS")

## Prerequisites
* Kubernetes Cluster
* [SPIRE Deployment](https://spiffe.io/docs/latest/try/getting-started-k8s/)

## Video
You can watch a walk-through on this topic by viewing the video below. 

[![Alt text](./video-thumbnail.jpg?raw=true "Video Thumbnail")](https://youtu.be/7qANSe9ajbE)