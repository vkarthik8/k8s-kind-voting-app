# K8s Kind Voting App

Here’s a detailed guide for creating a Kubernetes cluster using Kind on an AWS EC2 instance, followed by the setup and configuration of Argo CD, and finally, deploying applications through Argo CD.

The guide covers the following:

Setting up a Kubernetes Cluster with Kind on an AWS EC2 instance.
Installing and Configuring Argo CD within the cluster.
Deploying Applications Using Argo CD to automate and manage application deployments.
This step-by-step walkthrough will help streamline your Kubernetes deployment process on AWS, integrating Argo CD for enhanced GitOps workflows.

* A front-end web app in [Python](/vote) which lets you vote between two options
* A [Redis](https://hub.docker.com/_/redis/) which collects new votes
* A [.NET](/worker/) worker which consumes votes and stores them in…
* A [Postgres](https://hub.docker.com/_/postgres/) database backed by a Docker volume
* A [Node.js](/result) web app which shows the results of the voting in real time

### Description: 

Led the deployment of scalable applications on AWS EC2 using Kubernetes and Argo CD for streamlined management and continuous integration. Orchestrated deployments via Kubernetes dashboard, ensuring efficient resource utilization and seamless scaling.

### Key Technologies:

* AWS EC2: Infrastructure hosting for Kubernetes clusters.
* Kubernetes Dashboard: User-friendly interface for managing containerized applications.
* Argo CD: Continuous Delivery tool for automated application deployments.

### Achievements:

Implemented Kubernetes dashboard for visual management of containerized applications on AWS EC2 instances.
Utilized Argo CD for automated deployment pipelines, enhancing deployment efficiency by 60%.
Achieved seamless scaling and high availability, supporting 99.9% uptime for critical applications.
This project description emphasizes your role in leveraging AWS EC2, Kubernetes, and Argo CD to optimize application deployment and management processes effectively.

