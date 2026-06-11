# AWS EC2 Instance Setup & Linux Administration

## 📌 Project Overview

This project demonstrates the deployment and management of an Amazon EC2 instance on AWS. The objective was to gain hands-on experience with cloud infrastructure, Linux administration, networking, user management, security groups, SSH connectivity, and shell scripting.

---

## 🚀 Technologies Used

* Amazon Web Services (AWS)
* Amazon EC2
* Ubuntu Linux
* SSH
* Linux Commands
* Shell Scripting (Bash)
* Git & GitHub

---

## 📋 Project Tasks Performed

### 1. EC2 Instance Launch

* Created an AWS account and accessed the AWS Management Console.
* Launched an Ubuntu EC2 instance.
* Selected appropriate instance type.
* Created and downloaded a key pair (.pem file).

### 2. Security Configuration

* Configured Security Groups.
* Opened required inbound ports:

  * SSH (22)
  * HTTP (80)
  * HTTPS (443)

### 3. SSH Connectivity

Connected securely to the EC2 instance using:

```bash
ssh -i key.pem ubuntu@public-ip
```

### 4. Linux Administration

Performed basic Linux administration tasks:

```bash
pwd
ls
cd
mkdir
touch
rm
cp
mv
cat
```

### 5. User Management

Created and managed Linux users:

```bash
sudo useradd -m username
sudo passwd username
sudo userdel username
```

### 6. Group Management

```bash
sudo groupadd MIDC
sudo usermod -aG MIDC username
```

### 7. File Permissions

```bash
chmod 755 file.sh
chown ubuntu:ubuntu file.sh
```

### 8. Shell Scripting

Implemented scripts using:

* Variables
* User Input
* Conditional Statements
* Comparison Operators
* Functions
* For Loops
* While Loops

Example:

```bash
#!/bin/bash

for((i=1;i<=5;i++))
do
    echo "Welcome $i"
done
```

### 9. Git & GitHub Integration

Configured Git:

```bash
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
```

Repository Operations:

```bash
git init
git add .
git commit -m "Initial Commit"
git branch -M main
git push origin main
```

---

## 🎯 Learning Outcomes

Through this project, I learned:

* Cloud Computing Fundamentals
* AWS EC2 Deployment
* Linux Administration
* User & Group Management
* Linux Permissions
* Shell Scripting
* SSH Connectivity
* Git & GitHub Version Control
* Basic Cloud Security Concepts

---

## 📸 Screenshots

Add screenshots of:

* EC2 Dashboard
* Security Group Configuration
* SSH Connection
* Linux Commands Execution
* User Creation
* Shell Script Output
* GitHub Repository

---

## 👩‍💻 Author

**Shravni Bhadale**

Cloud Application Development Learner | AWS | Linux | Git & GitHub | DevOps Enthusiast

GitHub: https://github.com/shravnibhadale
