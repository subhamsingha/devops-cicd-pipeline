#devops-cicd-pipeline

Project: CI/CD pipeline setup to deploy a standalone web application.
Environment: AWS, Jenkins, GitHub, Docker, Maven, Ansible, Tomcat
Here, Jenkins has been used to build, test and Deploy docker image to deploy web application.

Steps: 
•	Pull the source code for a web application 
•	Compile (build) the code using Maven to generate the WAR file using Jenkins 
•	Create a Docker image using the jar. 
•	Run Test cases & ensure they pass 
•	Push the Docker image to the Docker Hub  
•	Pull the image from Docker hub with the help to Ansible and deploy to Docker host and Tomcat server.

Please refer DevOps Tool Installation Guide.docx to install the DevOps tools.
