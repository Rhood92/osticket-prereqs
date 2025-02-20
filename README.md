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
- Configure permissions and install osTicket
  
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
