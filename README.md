Charity Donation Website
This Charity Donation Website allows users to donate to various causes using PHP. Below are the steps to set up the project using XAMPP on both local and web servers.

Local Server Setup (Using XAMPP)
Step 1: Install XAMPP
Download and install XAMPP for your operating system.
Start the Apache and MySQL services from the XAMPP Control Panel.
Step 2: Clone the Project
Clone the project repository into the htdocs directory of your XAMPP installation:
bash
Copy code
Step 3: Database Configuration
Open phpMyAdmin by visiting http://localhost/phpmyadmin in your web browser.
Create a new database named charity_donation.
Import the provided SQL file (database.sql) into the newly created database.
Step 4: Run the Application
Open your web browser and navigate to http://localhost/charity-donation.
You should now be able to access and use the Charity Donation Website.
Web Server Setup
Follow similar steps to those outlined above for setting up the project on a web server. Ensure that your web server supports PHP and MySQL databases. Adjust configuration settings accordingly.

Requirements
XAMPP (or any other local server solution)
PHP version 7.x or higher
MySQL database
Git (optional, for cloning the project repository)

Usage
Register for an account on the Charity Donation Website.
Browse through the list of causes and select one to donate to.
Enter the donation amount and proceed to make the payment.
Upon successful donation, you will receive a confirmation message.
