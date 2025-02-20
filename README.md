<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Install / Enable IIS (Internet Information Services) with CGI in Windows
- Install web platform installer
- Install C++ redistributable
- Install MySQL and set up the username/password
- Install osTicket
  
<h2>Installation Steps</h2>

<h3>Step 1:</h3>

<p>
For the first part of the lab, I installed and enabled Internet Information Services (IIS) with CGI on Windows. This step is crucial because osTicket—a robust, open-source help desk ticketing system—requires a web server that can execute dynamic, server-side scripts (typically written in PHP) to manage ticket creation, updates, and overall support workflows.
</p>



![image](https://github.com/user-attachments/assets/3eace168-4fd7-4c72-8e7c-feda2a971d65)

![image](https://github.com/user-attachments/assets/e80ad8e2-ddd1-4820-a2d9-26d08881d3f2)

![image](https://github.com/user-attachments/assets/4f777b0a-bcf6-470f-88d9-db60434c9052)

<br />

<h3>Step 2:</h3>

<p>
For the second part of the lab, I installed PHP and the Rewrite Module. 

Why Download PHP?

osTicket is built with PHP, which lets the system work dynamically. PHP handles user input, talks to the MySQL database, and builds web pages. Without it, osTicket wouldn’t function properly. Installing the right version of PHP makes sure all osTicket features run smoothly.

Why Install a Rewrite Module?

A rewrite module (like the URL Rewrite Module for IIS) cleans up web addresses. It turns long, messy URLs into short, easy-to-read ones that are better for users and search engines. This helps osTicket’s links and navigation work correctly on IIS.
</p>


![image](https://github.com/user-attachments/assets/edd95b12-a711-4fb6-a902-b3143254ce1e)

![image](https://github.com/user-attachments/assets/b13c6948-46a4-4269-bfdd-56b2ae066009)

![image](https://github.com/user-attachments/assets/c637f156-29e1-4f80-81e6-3efcf1794ac2)

![image](https://github.com/user-attachments/assets/1a50d436-0f9a-429b-be8c-09cad5dfc385)


<br />

<h3>Step 3:</h3>

<p>
Installing the Visual C++ Redistributable is important because many parts of osTicket, like PHP, are built with Microsoft’s C++ tools. These components need specific C++ libraries to run properly. Without them, you might get errors or crashes. In simple terms, installing C++ helps everything work smoothly on your server.
</p>


![image](https://github.com/user-attachments/assets/eb3606d9-40d7-4bd2-a1eb-83ed9275f087)



<br />

<h3>Step 4:</h3>

<p>

I installed MySQL Database and set up the username and password. 

Installing MySQL is crucial because it acts as the central storage system for osTicket’s data. Imagine it as a digital filing cabinet where all support tickets, customer details, and settings are organized. Without MySQL, osTicket wouldn’t have a place to store or retrieve this important information when needed.
</p>

![image](https://github.com/user-attachments/assets/abde783a-0218-4572-b92c-fd10d3134ee2)


<h3>Step 5:</h3>

<p>

Next, I installed osTicket to organize and track customer support requests, making it easier for teams to manage and resolve issues.

</p>

<img width="1109" alt="Screenshot 2025-02-20 at 1 04 16 PM" src="https://github.com/user-attachments/assets/d9564311-dd4c-4c21-be05-ea719440fca8" />

<img width="1128" alt="Screenshot 2025-02-20 at 1 07 32 PM" src="https://github.com/user-attachments/assets/4639290f-e771-4a79-87c2-e4218d6b2816" />

<img width="1130" alt="Screenshot 2025-02-20 at 1 49 13 PM" src="https://github.com/user-attachments/assets/51d8ec25-b3ef-494c-95ba-9eb6206d66f3" />

<img width="1067" alt="Screenshot 2025-02-20 at 1 52 35 PM" src="https://github.com/user-attachments/assets/bd41655b-ce8a-4120-962c-7514829a8bb3" />

<img width="1435" alt="Screenshot 2025-02-20 at 1 53 58 PM" src="https://github.com/user-attachments/assets/e6e19e2d-77ba-44b8-b43a-19d0c6df61c3" />



