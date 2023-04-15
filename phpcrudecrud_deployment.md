# Section 1: Purpose of the PHP Crude CRUD Application

The PHP Crude CRUD Application is a web-based application that allows users to perform CRUD (Create, Read, Update, Delete) operations on a MySQL database. In addition, it provides an easy-to-use graphical user interface for managing database records without extensive knowledge of SQL.

# Section 2: High-Level Overview of Application Deployment

To deploy the PHP Crude CRUD application, the following general steps are required:

- Provision a virtual machine with sufficient resources, including 2048MB RAM, 1 or 2 vCPUs, and a 40GB HDD.
- Install the Ubuntu 20.04 operating system on the virtual machine.
- Install and configure Apache 2 and PHP on the virtual machine.
- Install and configure MySQL on the virtual machine.
- Configure the connection and credentials for PHP to connect to the MySQL database.
- Deploy the PHP Crude CRUD application on the virtual machine.

# Section 3: Suggested Virtual Machine Configuration

To run the PHP Crude CRUD application, we suggest a virtual machine with the following configuration:

- Disk: At least 40 GB of available storage
- CPU: 2 vCPUs
- RAM: 4 GB

# Section 4: Creating a VirtualBox Virtual Machine

To create a VirtualBox virtual machine, follow these steps:

1. Download and install VirtualBox from https://www.virtualbox.org/wiki/Downloads
2. Open VirtualBox and click on "New" to create a new virtual machine.
3. Choose a name and location for the virtual machine.
4. Select "Linux" as the type and "Ubuntu (64-bit)" as the version.
5. Choose the amount of memory and number of processors to allocate to the virtual machine.
6. Create a new virtual hard disk or use an existing one.
7. Follow the prompts to complete the virtual machine creation process.

# Section 5: Installing Ubuntu 20.04 Operating System

To install the Ubuntu 20.04 operating system, follow these steps:

1. Download the Ubuntu 20.04 LTS ISO image from https://releases.ubuntu.com/20.04/
2. Start the VirtualBox virtual machine and select the Ubuntu ISO as the bootable image.
3. Follow the prompts to complete the Ubuntu installation process.

# Section 6: Installing Apache 2 and PHP

To install Apache 2 and PHP, follow these steps:

1. Open a terminal window in Ubuntu.
2. Run the following command to install Apache: `sudo apt-get install apache2`
3. Run the following command to install PHP and required dependencies: `sudo apt-get install php libapache2-mod-php php-mysql`
4. Restart Apache: `sudo systemctl restart apache2`

# Section 7: Installing MySQL

To install MySQL, follow these steps:

1. Open a terminal window in Ubuntu
2. Run the following command to install MySQL: `sudo apt-get install mysql-server`
3. During the installation process, set the root password for the MySQL server when prompted.

# Section 8: Configuring Database Connection and Credentials

To configure the connection and credentials for PHP to connect to the MySQL database, follow these steps:

1. Open a terminal window in Ubuntu
2. Edit the `index.html` file located in the PHP Crude CRUD application directory.
3. Update the database connection information with the appropriate host, database name, username, and password.
4. Update the `credentials.php` file with the appropriate user name and password.
5. Save and close the `config.php` file.

# Section 9: Deploying the PHP Crude CRUD Application

To deploy the PHP Crude CRUD application, follow these steps:

1. Copy the PHP Crude CRUD application files to the Apache web root directory (`/var/www/html/`).
2. Restart Apache: `sudo systemctl restart apache`

# Section 10: System Tests

To ensure that the PHP Crude CRUD application is working properly, we recommend running the following system tests:

1. Test all the CRUD operations and make sure they work correctly. Verify that records can be created, read, updated, and deleted.
2. Test the application's interaction with the database management system (DBMS), including inserting, deleting, updating, and retrieving records.

