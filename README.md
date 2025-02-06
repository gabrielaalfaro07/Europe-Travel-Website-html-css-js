# EuroTrip Planner Website


## Scope

This project demonstrates the deployment of a static teaser website on Google Cloud Platform (GCP). The site, featuring European travel destinations, is containerized and orchestrated using Kubernetes and Google Kubernetes Engine (GKE), with a load balancer ensuring high availability and efficient traffic management.


## Original Repository

[https://github.com/GNiruthian/Europe-Travel-Website-html-css-js](https://github.com/GNiruthian/Europe-Travel-Website-html-css-js)


## Deployment Steps

--Clone the Website Repository and Prepare for Docker Deployment--

-Clone the repository locally.
Create a Dockerfile and build a Docker image of the website.
Push the Docker Image to Google Container Registry

-Authenticate with GCP.
Push the built Docker image to GCR.
This step ensures the image is stored securely in the cloud and is ready for GKE deployment.
Set Up Kubernetes Deployment and Service Locally

-Write Kubernetes YAML manifests (e.g., deployment.yaml, service.yaml) for deploying the website and exposing it via a LoadBalancer.
Deploy the Website on Google Kubernetes Engine (GKE)

-Create a GKE cluster in Google Cloud.
Apply the Kubernetes manifests (kubectl apply -f deployment.yaml) to deploy the website.
This will create pods, a deployment, and a LoadBalancer to expose the service.
Ensure the Website is Publicly Accessible

-Verify that the Load Balancer works correctly and the service is publicly accessible.
Test the website using the external IP or domain name assigned to the Load Balancer.


## Authors

[Code-Runners]
