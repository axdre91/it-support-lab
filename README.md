## 🎥 Demo Videos

- [Loom Video 1: Ticket creation + VM Setup + Active Directory](https://loom.com/share/46c417b867e94d9cba36b4fe9e71f469)
- [Loom Video 2: Reset user passwprd](https://loom.com/share/77f46e081a414d9895251d11b7ac2dac)
# it-support-lab
Basic IT Support Lab: ServiceNow, AWS, EC2, Active Directory
# IT Support / Help Desk Lab

This project documents the steps I followed to complete a basic Help Desk / IT Support lab. The goal was to simulate real-world technical support tasks using tools like ServiceNow, AWS EC2, and Windows Server with Active Directory.

---

## 🧰 Tools Used

- **ServiceNow** – for ticket management
- **Amazon Web Services (AWS)** – for provisioning a virtual machine (EC2)
- **Windows Server** – for Active Directory configuration
- **Remote Desktop** – to connect to EC2 instance
- ## 🖼️ Architecture Diagram

![IT Lab Architecture](IT_Lab_Architecture.drawio%20(1).png)

---

## 🧪 Lab Overview

### 1. 📩 ServiceNow Ticket Creation

- Logged into ServiceNow.
- Created a new incident ticket.
- Entered details such as issue description, category, and priority.
- Saved and documented the ticket number.

---

### 2. ☁️ AWS EC2 Virtual Machine Setup

- Logged into AWS Management Console.
- Launched a new EC2 instance using the Windows Server 2019 AMI.
- Configured:
  - Instance type: `t2.micro`
  - Key pair for RDP access
  - Security group to allow RDP (port 3389)
- Launched and waited for the instance to be ready.
- Retrieved the password and connected via RDP.

---

### 3. 🧱 Active Directory Configuration

Once connected to the Windows Server EC2 instance:

#### a. Installed Active Directory Domain Services (AD DS)

- Used Server Manager to add the AD DS role.
- Promoted the server to a Domain Controller with a new forest.

#### b. Created Users

- Opened Active Directory Users and Computers (ADUC).
- Created several new users with appropriate names and usernames.

#### c. Created Groups

- Created Security Groups (e.g., "IT", "HR", "Sales").
- Assigned users to relevant groups.

#### d. Reset Passwords

- Simulated support tasks:
  - Located users in ADUC.
  - Right-clicked and reset passwords.

---

## ✅ Summary

This lab provided hands-on experience with core IT support tasks:
- Ticket creation and documentation in ServiceNow
- Cloud-based VM provisioning in AWS
- Basic Active Directory administration

---

## 📁 Files

- No additional scripts or files included in this lab.

---

## 📌 Notes

- All tasks were performed in a test environment.
- This documentation serves as a personal knowledge base and portfolio piece.
