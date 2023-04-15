#Section 1: Purpose of the PHP Crude CRUD Application#
The PHP Crude CRUD Application is a web-based application that allows users to perform CRUD (Create, Read, Update, Delete) operations on a MySQL database. In addition, it provides an easy-to-use graphical user interface for managing database records without extensive knowledge of SQL.
**Section 2: Overview of Application Deployment**
To deploy the PHP Crude CRUD application, the following steps are required:
Provision a virtual machine with sufficient resources, including 2048MB RAM, 1 or 2 vCPUs, and a 40GB HDD.
Install the Ubuntu 20.04 operating system on the virtual machine.
Install and configure Apache 2 and PHP on the virtual machine.
Install and configure MySQL on the virtual machine.
Configure the connection and credentials for PHP to connect to the MySQL database.
Deploy the PHP Crude CRUD application on the virtual machine.
**Section 3: Suggested Virtual Machine Configuration**
To run the PHP Crude CRUD application, we suggest a virtual machine with the following configuration:
Disk: At least 40 GB of available storage
CPU: 2 vCPUs
RAM: 4 GB
**Section 4: Creating a VirtualBox Virtual Machine**
To create a VirtualBox virtual machine, follow these steps:
Download and install VirtualBox from https://www.virtualbox.org/wiki/Downloads
Open VirtualBox and click on "New" to create a new virtual machine.
Choose a name and location for the virtual machine.
Select "Linux" as the type and "Ubuntu (64-bit)" as the version.
Choose the amount of memory and number of processors to allocate to the virtual machine.
Create a new virtual hard disk or use an existing one.
Follow the prompts to complete the virtual machine creation process.
**Section 5: Installing Ubuntu 20.04 Operating System**
To install the Ubuntu 20.04 operating system, follow these steps:
Download the Ubuntu 20.04 LTS ISO image from https://releases.ubuntu.com/20.04/
Start the VirtualBox virtual machine and select the Ubuntu ISO as the bootable image.
Follow the prompts to complete the Ubuntu installation process.
Section 6: Installing Apache 2 and PHP
To install Apache 2 and PHP, follow these steps:
Open a terminal window in Ubuntu.
Run the following command to install Apache: sudo apt-get install apache2
Run the following command to install PHP and required dependencies: sudo apt-get install php libapache2-mod-php php-mysql
Restart Apache: sudo systemctl restart apache2
**Section 7: Installing MySQL
To install MySQL, follow these steps:
Open a terminal window in Ubuntu
Run the following command to install MySQL: sudo apt-get install mysql-server
During the installation process, set the root password for the MySQL server when prompted
**Section 8: Configuring Database Connection and Credentials
To configure the connection and credentials for PHP to connect to the MySQL database, follow these steps:
Open a terminal window in Ubuntu
Edit the index.html file located in the PHP Crude CRUD application directory.
Update the database connection information with the appropriate host, database name, username, and password.
Update the credentials.php file with the appropriate user name and password..
Save and close the config.php file.
**Section 9:Deploying the PHP Crude CRUD Application
To deploy the PHP Crude CRUD application, follow these steps:
Copy the PHP Crude CRUD application files to the Apache web root directory (/var/www/html/)

