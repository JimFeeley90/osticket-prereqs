# osTicket-prereqs
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

- Install osTicket installation zip file.
- Install / Enable IIS in Windows with CGI.
- Install PHP manager for IIS from osTicket installation zip file.
- Install MySQL 5.5.62
- Install HeidiSQL and create an "osTicket" database.

<h2>Installation Steps</h2>

<p>
<img src=https://i.imgur.com/rxqw7nq.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<h2> Install osTicket installation zip file: To install the osTicket application from the provided ZIP file, first download the ZIP archive to your computer. Once downloaded, extract the contents of the ZIP file to a folder on your server or local machine. Ensure your server meets the system requirements, such as PHP and MySQL. After extraction, upload the contents to your web server’s root directory or a subfolder where you want osTicket to be installed. Next, open your browser and navigate to the directory where you uploaded the files. Follow the on-screen installation instructions to complete the setup, which will involve configuring your database settings and admin details.



</h2>
<p>

</p>
<br />

<p>
<img src=https://i.imgur.com/wiU4tMy.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src=https://i.imgur.com/t08vTXe.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 
<h2>Install / Enable IIS in Windows WITH CGI: To install or enable IIS (Internet Information Services) with CGI support on Windows, first, open the "Control Panel" and go to "Programs" > "Turn Windows features on or off." In the "Windows Features" window, find and expand the "Internet Information Services" section. Check the box for "Web Management Tools" and "World Wide Web Services," then expand the "Application Development Features" and enable "CGI" by checking the corresponding box. Click "OK" to begin the installation. Once completed, IIS will be installed with CGI support enabled, allowing you to run CGI scripts on your web server. You can verify this by opening the IIS Manager and checking the features available under your server settings.



</h2>

<br />

<p>
<img src=https://i.imgur.com/npbiUnW.png height="80%" width="80%" alt="Disk Sanitization Steps"/>" 

</p>

<h2>Install PHP manager from the osTicket installation file: To install the PHP Manager for IIS from the osTicket installation ZIP file, first extract the contents of the osTicket ZIP file to a folder on your computer. Inside the extracted folder, locate the "PHP Manager" folder. Copy the PHP Manager installer (usually named something like phpmanager_installer.exe) to your server. Run the installer, and follow the on-screen instructions to complete the installation. After installation, open the IIS Manager, and you should see the "PHP Manager" option under the server's features. This tool allows you to manage PHP settings for IIS, ensuring that PHP is properly configured for use with osTicket.



</h2>
<p>
<img src=https://i.imgur.com/2dKgJOb.png height="80%" width="80%" alt="Disk Sanitization Steps"/>" 

</p>
<h2>Install MySQL 5.5.62: To install MySQL 5.5.62, begin by downloading the MySQL 5.5.62 installer from the official MySQL website or a trusted source. Once the installer is downloaded, run the setup file and follow the on-screen prompts. During installation, choose the appropriate setup type (e.g., Typical or Custom) based on your needs. When prompted, configure your MySQL root password and set up any additional options as required. After installation is complete, launch the MySQL Server instance from the Start menu or the MySQL Workbench. Verify the installation by opening a command prompt and typing mysql -u root -p to access the MySQL command line, then entering your root password.</h2>
<br />

<p>
 
 <img src=https://i.imgur.com/rRUJWAy.png height="80%" width="80%" alt="Disk Sanitization Steps"/>" 
</p>
<p>
<h2> Install HeidiSQL and create an "osTicket" database: To install HeidiSQL and create an "osTicket" database, first, download the HeidiSQL installer from the official website and run the setup file. Follow the installation prompts to complete the process. Once installed, open HeidiSQL and connect to your MySQL server by entering the connection details (e.g., hostname, username, and password). After connecting, right-click on the "Databases" section in the left panel and select "Create new database." Name the new database "osTicket" and choose the appropriate collation (usually "utf8_general_ci"). Click "OK" to create the database, which is now ready to be used during the osTicket installation.



</h2>
</p>

<p>
 <img src=https://i.imgur.com/UAIx4bx.png height="80%" width="80%" alt="Disk Sanitization Steps"/>" 
 <img src=https://i.imgur.com/HWLHZ5H.png height="80%" width="80%" alt="Disk Sanitization Steps"/>" 
</p>

<p>
<h2> osTicket has been installed!</h2>
</p>
