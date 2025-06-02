# Complete CI/CD Pipeline with EKS and DockerHub

## **Project Overview**
Project Purpose: Deploy a complete Jenkins CI/CD pipeline with stages to automatically increment a Java application version, use Apache Maven to build a Java artifact, build and push a Docker image to a private AWS ECR Docker repository, and commit the updated Java application version to GitLab using Git.
This project provides a comprehensive walkthrough of writing a Jenkinsfile and accounts for the necessary prerequisites prior to additional Groovy code being written. A complete Jenkins CI/CD pipeline is successfully executed at the project’s conclusion.

---
  
## **Feature**

### **Complete CI/CD Pipeline with DockerHub**

- Created Deployment and Service for App deployment
- Adjust Jenkinsfile to set environment variables with envsubst
- Installed “gettext-base” tool inside Jenkins Container on DigitalOcean Server to have envsubst available
- Created Secret for DockerHub Registry in EKS cluster (connect to EKS cluster if not already) and added reference to Deployment file
- Executed Jenkins Pipeline

### **Diagrammatic Presentation**
- Connected to the cluster

  ![image](https://github.com/user-attachments/assets/02cf7397-d6af-483d-8dd7-42ec272d289a)



- Created Deployment and Service for App deployment
- Adjust Jenkinsfile to set environment variables with envsubst

  ![image](https://github.com/user-attachments/assets/922a3233-5f4a-4dcd-b12c-78480adf62da)

- Installed “gettext-base” tool inside Jenkins Container on DigitalOcean Server to have envsubst available
- Created Secret for DockerHub Registry in EKS cluster (connect to EKS cluster if not already) and added reference to Deployment file
  
  ![image](https://github.com/user-attachments/assets/c86f5e65-6365-423b-aaed-530543719e5f)

- Executed Jenkins Pipeline

  ![image](https://github.com/user-attachments/assets/aa2fbc0c-2e49-4e17-9469-d2a36363e9cd)


  ![image](https://github.com/user-attachments/assets/5d836f5f-888d-4b11-9ee9-23ebd7e92ba0)


  ![image](https://github.com/user-attachments/assets/5e5033f1-c469-4e68-ae34-4c0a83dec31f)


  ![image](https://github.com/user-attachments/assets/27c06d21-57aa-4eae-9fca-c0b51e942248)


  ![image](https://github.com/user-attachments/assets/f39d2367-957c-47d7-960d-80c4bb882460)



  ![image](https://github.com/user-attachments/assets/e9921053-34e0-40c6-9659-49505c07e624)


  ![image](https://github.com/user-attachments/assets/8dfb506d-44b0-4f7a-9922-d63471b0cd5a)







