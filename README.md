# **Open Source CRM with Drupal in Docker**

This project demonstrates the deployment of an open-source CRM system using Drupal, hosted via Docker. Drupal is a powerful open-source content management framework widely used for web applications and CRM solutions. This setup provides a containerized environment, ensuring quick deployment and scalability.


## **Table of Contents**

**1.)** About the Project

**2.)** Technologies Used

**3.)** Prerequisites

**4.)** Installation

**5.)** Usage


## **About the Project**

This project deploys a Drupal instance using Docker containers, leveraging the official Drupal Docker image from Docker Hub. The system enables users to set up and experiment with an open-source CRM in an isolated and lightweight environment.

## **Technologies Used**

**[Drupal](https://hub.docker.com/_/drupal/):** Open-source content management system (CMS).

![Screenshot 2024-12-07 202130](https://github.com/user-attachments/assets/7b31faa4-69e6-4eaf-afac-857ae57d4d46)

![Screenshot 2024-12-07 202146](https://github.com/user-attachments/assets/74fc3871-9667-4e55-b6e7-7d316a992c35)


**Docker:** Containerization platform.

![Screenshot 2024-12-07 203930](https://github.com/user-attachments/assets/77bd2f01-5841-40aa-a15e-65826a067d58)

![Screenshot 2024-12-07 204204](https://github.com/user-attachments/assets/703ee1c1-f4d8-473d-8b56-ff76d079c7e9)

**Docker Hub:** Source for the official Drupal image.

## **Prerequisites**

Ensure the following software is installed on your machine:

[Docker](https://www.docker.com/products/docker-desktop/) (version 20.10 or later recommended)

![Screenshot 2024-12-07 202808](https://github.com/user-attachments/assets/192179b2-9261-4fd6-9f2d-f85a9f7e6f92)

## **Installation**

### **1.)** **Clone the Repository**

**Clone this repository to your local machine:**

git clone https://github.com/nihaal2707/CRM-with-Drupal-Docker.git  
cd repo-name  

### **2.) Pull the Drupal Docker Image**

The required image is pulled automatically when the container is created.

### **3.) Run the Docker Container**

Use the following commands to set up and run the Drupal container:

**Option 1:**

**Create a default Drupal container:**

docker run --name some-drupal -d drupal  

**Option 2:**

**Bind the container to a specific port (e.g., 8080):**

docker run --name drupal -p 8080:80 -d drupal  

### **4.) Access Drupal**

**Open a web browser and go to:**

http://localhost:8080  

Follow the setup instructions to configure the Drupal instance.

## **Usage**

**1.)** Navigate to the Drupal interface via your browser.

**2.)** Customize the system for your CRM needs.

**3.)** Add modules, themes, or configurations as required.

## **Troubleshooting**

**1.)** Port Conflict: Ensure port 8080 is not in use by another application.

**2.)** Stopping the Container: Use the command:

docker stop drupal  

**3.)** Removing the Container: Use the command:

docker rm drupal  



