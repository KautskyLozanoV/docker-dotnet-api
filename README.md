# Containerizing an ASP.NET Core API

This repository contains the code from the [ASP.NET Core with GitOps Series](https://www.red-gate.com/simple-talk/sysadmin/containerization/asp-net-core-with-gitops-dockerizing-an-api-on-aws-ec2/).

The [DockerDotnetApi](https://github.com/Mirch/docker-dotnet-api/tree/master/DockerDotnetApi) folder contains a sample ASP.NET Core WebAPI project, with a single endpoint used for testing purposes.
The [aws](https://github.com/Mirch/docker-dotnet-api/tree/master/aws) folder contains configuration files for interacting with AWS resources. (not published yet)
The [infrastructure](https://github.com/Mirch/docker-dotnet-api/tree/master/infrastructure) folder contains the Infrastructure as Code file for deploying a Kubernetes cluster on EKS, and all the additional resources. (not published yet)
The [Dockerfile](https://github.com/Mirch/docker-dotnet-api/blob/master/Dockerfile) is used for creating the Docker container that is deployed throughout the series.

## The series so far

The README file will be updated as the articles get published.
So far, the series consists of:

1. [Dockerizing an API on AWS EC2](https://www.red-gate.com/simple-talk/sysadmin/containerization/asp-net-core-with-gitops-dockerizing-an-api-on-aws-ec2/)

You can use the **master** branch to follow this tutorial, even though it contains more files than necessary. The only ones you are concerned with for now are the **Dockerfile** and the ASP.NET project files.
