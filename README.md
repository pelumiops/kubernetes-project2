# CI/CD Pipeline for Deploying Applications on Google Kubernetes Engine (GKE)


## Introduction

In the modern software development landscape, Continuous Integration/Continuous Deployment (CI/CD) pipelines play a pivotal role in automating the process of building, testing, and deploying applications. In this blog post, we’ll deep dive into the implementation of a robust CI/CD pipeline to deploy applications on Google Kubernetes Engine (GKE) using Google Cloud Build and Cloud Deploy services.

## Requirements

To achieve our goal, we have the following requirements:
- Deployment of two simple Flask applications (app1 & app2) on the GKE clusters.
- Automation of the entire deployment process, triggered by a developer’s code push.
- Dev-cluster deployment precedes production deployment, allowing for review before promoting to the prod-cluster.


## Technical Stack Summary

This CI/CD pipeline leverages several key components:
- Google Kubernetes Engine (GKE): Google’s managed Kubernetes service, providing a scalable and reliable platform for deploying containerized applications.
- Cloud Build: A fully managed continuous integration and continuous delivery platform that allows developers to build, test, and deploy applications on Google Cloud Platform.
- Cloud Deploy: A service for continuous delivery that automates the deployment of containerized applications to Google Kubernetes Engine and other platforms.
- GitHub: A popular version control platform where developers collaborate, manage, and version control their codebase.




