<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

# osTicket - Prerequisites and Installation

This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system **osTicket**.

## Table of Contents
- [Environments and Technologies Used](#environments-and-technologies-used)
- [Operating Systems Used](#operating-systems-used)
- [List of Prerequisites](#list-of-prerequisites)
- [Installation Steps](#installation-steps)
  - [1. Installing and Enabling IIS](#1-installing-and-enabling-iis)
  - [2. Installing PHP and the Rewrite Module](#2-installing-php-and-the-rewrite-module)
  - [3. Installing Visual C++ Redistributable](#3-installing-visual-c-redistributable)
  - [4. Installing MySQL](#4-installing-mysql)
  - [5. Installing osTicket](#5-installing-osticket)
- [Conclusion](#conclusion)

---

## Environments and Technologies Used
- **Microsoft Azure** (Virtual Machines/Compute)
- **Remote Desktop**
- **Internet Information Services (IIS)**

---

## Operating Systems Used
- **Windows 10**

---

## List of Prerequisites
Before proceeding with the installation, the following components need to be installed and configured:
- ✅ Enable **IIS (Internet Information Services) with CGI** in Windows
- ✅ Install **Web Platform Installer**
- ✅ Install **C++ Redistributable**
- ✅ Install **MySQL** and set up username/password
- ✅ Install **osTicket**

---

## Installation Steps

### 1. Installing and Enabling IIS
For the first part of the lab, I installed and enabled **Internet Information Services (IIS)** with **CGI** on Windows. This step is crucial because osTicket requires a web server to execute dynamic, server-side scripts (written in PHP) to manage ticket creation, updates, and overall support workflows.

![Installing IIS](https://github.com/user-attachments/assets/3eace168-4fd7-4c72-8e7c-feda2a971d65)
![Enabling CGI](https://github.com/user-attachments/assets/e80ad8e2-ddd1-4820-a2d9-26d08881d3f2)
![IIS Installed](https://github.com/user-attachments/assets/4f777b0a-bcf6-470f-88d9-db60434c9052)

---

### 2. Installing PHP and the Rewrite Module
For the next step, I installed **PHP** and the **Rewrite Module**.

#### Why Download PHP?
osTicket is built with PHP, which allows it to function dynamically. PHP handles user input, interacts with the MySQL database, and generates web pages. Without PHP, osTicket wouldn’t function properly.

#### Why Install a Rewrite Module?
A rewrite module (like the **URL Rewrite Module for IIS**) cleans up web addresses, turning long, messy URLs into shorter, user-friendly ones. This improves usability and ensures osTicket’s links and navigation work properly on IIS.

![Installing PHP](https://github.com/user-attachments/assets/edd95b12-a711-4fb6-a902-b3143254ce1e)
![PHP Installed](https://github.com/user-attachments/assets/b13c6948-46a4-4269-bfdd-56b2ae066009)
![Installing Rewrite Module](https://github.com/user-attachments/assets/c637f156-29e1-4f80-81e6-3efcf1794ac2)
![Rewrite Module Installed](https://github.com/user-attachments/assets/1a50d436-0f9a-429b-be8c-09cad5dfc385)

---

### 3. Installing Visual C++ Redistributable
Installing the **Visual C++ Redistributable** is crucial because many components of osTicket, such as PHP, rely on Microsoft’s C++ libraries to function properly. Without these libraries, you may encounter errors or crashes.

![Installing C++ Redistributable](https://github.com/user-attachments/assets/eb3606d9-40d7-4bd2-a1eb-83ed9275f087)

---

### 4. Installing MySQL
I installed **MySQL Database** and configured the username and password.

#### Why Install MySQL?
MySQL acts as the **central storage system** for osTicket’s data. It stores all **support tickets, customer details, and system settings**. Without MySQL, osTicket wouldn’t have a place to save or retrieve this information.

![Installing MySQL](https://github.com/user-attachments/assets/abde783a-0218-4572-b92c-fd10d3134ee2)

---

### 5. Installing osTicket
The final step was installing **osTicket**, which organizes and tracks customer support requests, making it easier for teams to manage and resolve issues.

![osTicket Installation - Step 1](https://github.com/user-attachments/assets/d9564311-dd4c-4c21-be05-ea719440fca8)
![osTicket Installation - Step 2](https://github.com/user-attachments/assets/4639290f-e771-4a79-87c2-e4218d6b2816)
![osTicket Installation - Step 3](https://github.com/user-attachments/assets/51d8ec25-b3ef-494c-95ba-9eb6206d66f3)
![osTicket Installation - Step 4](https://github.com/user-attachments/assets/bd41655b-ce8a-4120-962c-7514829a8bb3)
![osTicket Installation - Completed](https://github.com/user-attachments/assets/e6e19e2d-77ba-44b8-b43a-19d0c6df61c3)

---

## Conclusion
This tutorial documented the **prerequisites and installation** of **osTicket**, a powerful **open-source help desk ticketing system**. By following these steps, you can successfully set up osTicket on **Windows 10 with IIS and MySQL**.


---
