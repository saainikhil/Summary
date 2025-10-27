

### **Tasks**

**Task 1: Docker Installation**
In this task, I learned how to install Docker on a Linux system and verify its successful setup. I practiced essential Docker commands such as `docker ps`, `docker images`, and `docker run`. This helped me understand containerization and how Docker simplifies application deployment in isolated environments.

**Task 2: Linux Practice (Using Alice, Bob & Charlie)**
In this task, I explored fundamental Linux user management concepts by creating and managing users named Alice, Bob, and Charlie. I learned how to set permissions, create groups, and navigate the file system using commands like `cat`, `sudo su`, `head`, `tail`, and `touch`. This improved my understanding of Linux file structures, process management, and access permissions for read, write, and execute operations.

**Task 3: Simple Dockerfile Project (Image Creation)**
Here, I created a simple Flask API and wrote a Dockerfile to build a custom Docker image from a base image. I learned how to use Dockerfile instructions such as `FROM`, `COPY`, and `RUN` to build images locally. This task gave me hands-on experience in image creation and helped me understand how to build reusable environments for API-based applications.

**Task 4: Dockerize Your Own Application**
In this task, I dockerized my own web application by creating a Dockerfile that defined all dependencies, built the image, and ran it as a container on Docker Desktop. I learned how to expose ports, configure environment variables, and manage containerized applications efficiently. This strengthened my understanding of deploying real-world applications using Docker.

**Task 5: Shell Scripting — Health Check Script**
I developed a shell script named `healthcheck.sh` to monitor system performance. The script displayed details like current date and time, system uptime, CPU and memory usage, disk utilization, and top processes consuming resources. It also checked the status of services like Nginx and SSH and logged all outputs with timestamps in `healthlog.txt`. This task enhanced my skills in automation, system monitoring, and log management using shell scripting.

**Task 6: Bash Scripting — Backup Tool**
In this task, I created an automated backup script to copy important directories and compress them into archive files. I used commands like `chown`, `chmod`, `grep`, and `awk` for managing permissions and filtering data. The script handled error checking, logged backup details, and ensured secure data management. Through this, I learned how to automate file management tasks and schedule regular backups effectively.

---

### **Projects**

**Project 1: Network Protocol — Mail Server Setup**
I configured a local mail server using Postfix (SMTP) and Dovecot (IMAP) to understand real-world email communication protocols. The setup enabled sending and receiving emails between local users, Alice and Bob. I explored how email delivery and retrieval work internally, practiced manual SMTP sessions using Telnet, verified encryption with OpenSSL, and captured network packets using `tcpdump`. This project deepened my understanding of mail server configuration, encryption, and communication protocols like SMTP, IMAP, and TLS.

**Project 2: CI/CD Pipeline with GitHub Actions**
In this project, I built an automated CI/CD pipeline using GitHub Actions to streamline code testing, building, and deployment on every new commit. I learned how to write YAML workflow files, configure runners, set build triggers, and manage artifact storage. This project gave me strong practical knowledge of continuous integration and deployment automation.

**Project 3: Microservices Project**
Here, I created multiple FastAPI-based microservices such as user-service, task-service, and gateway-service. Each service was containerized using individual Dockerfiles and connected via Docker Compose, with Nginx acting as a reverse proxy. This project helped me understand microservice architecture, container orchestration, and inter-service communication in a scalable environment.

**Project 4: Messaging System with RabbitMQ, Celery, Nginx, and Python**
In this project, I built a messaging system demonstrating asynchronous task processing using RabbitMQ as a message broker and Celery for background task management. The backend was developed using Flask and served through Nginx as a reverse proxy. The system enabled sending emails asynchronously and retrieving server time via endpoints, tested publicly through Ngrok. This project improved my understanding of distributed task queues, asynchronous processing, and reverse proxy configuration.

**Project 5: Linux User Creation Automation Script**
This project involved writing a bash script named `create_users.sh` to automate user and group creation. The script read data from a text file, generated random passwords, logged all actions to `/var/log/user_management.log`, and securely stored passwords in `/var/secure/user_passwords.txt`. I also documented the technical process in detail. This enhanced my scripting skills and understanding of automated user management in production environments.

**Project 6: devopsfetch — Server Monitoring Tool**
I developed a command-line tool named **devopsfetch** to retrieve and display system information such as active ports, running services, Docker containers, Nginx configurations, and user login history. I also implemented a systemd service for continuous monitoring and logging. This project gave me valuable insights into system monitoring, logging mechanisms, and CLI tool development.

**Project 7: Jenkins — Automated CI Pipeline for a Web Application**
In this project, I created a Jenkins-based CI pipeline to automate testing and building of a Flask web application. The pipeline included stages such as code checkout, dependency installation, testing, building, packaging, and post-build actions. This helped me understand Jenkins integration with GitHub, pipeline automation, and the role of CI in maintaining code quality and streamlining software delivery.

---

### **Overall Learning**

Through all these tasks and projects, I gained extensive hands-on experience in **DevOps tools and practices** including Docker, Jenkins, Bash scripting, YAML, Linux, GitHub Actions, and Python. These experiences helped me build a strong foundation in automation, continuous integration, deployment, system monitoring, and real-world project implementation—preparing me to work effectively in modern DevOps environments focused on performance, reliability, and scalability.

---

