#  Ansible-Based Configuration Management & Web Server Deployment

This project demonstrates **Configuration Management Automation** using **Ansible** to deploy a static website across remote servers. It installs and configures the **Apache HTTP Web Server (httpd)** and copies an `index.html` web page to the server's hosting directory.

---

##  Project Objectives

- Automate installation of Apache web server using Ansible
- Ensure consistent server configuration across multiple hosts
- Deploy static HTML content automatically
- Demonstrate idempotent Infrastructure as Code (IaC) approach

---

##  Scope

This project includes:

✔ Installing Apache (`apache2`)  
✔ Updating system package cache  
✔ Copying `index.html` to `/var/www/html/`  
✔ Managing multiple machines via inventory  

> **Note:**  
> This project doesn't include HTTPS configuration, domain management, load balancing, templating, or containerization — but can be improved to include these later.

---

##  Tech Stack

| Component     | Description                    |
|---------------|--------------------------------|
| OS            | Ubuntu Linux                   |
| Automation    | Ansible                        |
| Web Server    | Apache (`apache2`)             |
| File Hosted   | Static `index.html`            |
| Protocol      | HTTP                           |

---



