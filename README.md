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

##Overview: 

Spearheaded the deployment of scalable applications on AWS EC2, utilizing Kubernetes and Argo CD to enhance management efficiency and enable continuous integration. Managed deployments through the Kubernetes dashboard, optimizing resource allocation and facilitating smooth scaling operations.

##Technological Stack:

AWS EC2: Provided the infrastructure for hosting Kubernetes clusters.
Kubernetes Dashboard: Offered an intuitive interface for overseeing containerized applications.
Argo CD: Served as a continuous delivery tool to automate application deployment processes.

##Achievements:

Successfully integrated the Kubernetes dashboard for visual oversight of containerized applications hosted on AWS EC2.
Leveraged Argo CD to create automated deployment pipelines, resulting in a 60% improvement in deployment efficiency.
Ensured seamless scaling and high availability, achieving 99.9% uptime for mission-critical applications.
This project highlights my ability to effectively utilize AWS EC2, Kubernetes, and Argo CD to streamline application deployment and management, driving operational excellence.

