# Mini Project - Working with Docker Images

## Project Overview
This project explores Docker images, including pulling from Docker Hub, creating a custom Nginx image with a Dockerfile, running containers, pushing to Docker Hub, and dockerizing a static web page, executed on Ubuntu 20.04 LTS with VS Code.

## Setup
- Initiated on Jul 04, 2025, 01:35 PM WAT.
- Used Ubuntu terminal (WSL) with VS Code, documented in /mnt/c/Users/User/Documents/Workspace/Shell_AWS_Mini_Project.

## Execution Steps
1. **Pull Images from Docker Hub**:
   - Searched and pulled `ubuntu` image, verified with `docker images`.
   
2. **Create Dockerfile for Nginx**:
   - Built `darey-nginx` image with `index.html` ("Welcome to Darey.io").
   -
3. **Run Container**:
   - Ran container on port 8080, updated EC2 security group.
   
4. **Push to Docker Hub**:
   - Tagged and pushed `darey-nginx-repo` to Docker Hub.
   
5. **Side Hustle - Dockerize Static Page**:
   - Built and ran `my-static-site` with custom HTML.
   

## Learning Summary
This project deepened my understanding of Docker images as portable, self-contained packages that form the basis of containers. I learned to pull images like `ubuntu` from Docker Hub using `docker pull`, and created a custom Nginx image with a Dockerfile, defining steps to copy `index.html` and expose port 80. Running the container and securing port 8080 on EC2 showcased practical deployment, while pushing to Docker Hub demonstrated image sharing. The side hustle task of dockerizing a static web page reinforced Dockerfile customization and container management, highlighting Docker’s role in ensuring consistency and scalability across environments.

## Tools Used
- **Ubuntu Terminal (WSL)**: For Docker commands and instance management.
- **VS Code**: For editing `Dockerfile` and `README.md`.
- **Git Bash**: For version control and GitHub push.
- **AWS EC2**: For hosting the Ubuntu instance.
- **Docker Hub**: For image repository.

## Project Deliverables
- **Documentation**: This `README.md` with steps and learning summary.

- **Script Link**: [GitHub Repository](https://github.com/westgrin/Shell_AWS_Mini_Project)

## Conclusion
This project successfully explored Docker images, from pulling and building to running and sharing, with a practical static web page dockerization, documented for future reference, enhancing my containerization skills.