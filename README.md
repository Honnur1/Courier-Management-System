# Courier-Management-System

Project: Courier Management System using PHP/MySQLi

About
The Courier Management System is a simple PHP/MySQLi project that helps a courier company or businesses manage their customers parcel details. The system stores all the branches or the company that can be also use when setting a destination where can recipient pickup their packages or parcels. The system has tracking feature where can help to monitor the movement of the customer's parcel. The system has 2 types of user which is the Admin user and the Branch Staff user. The Admin user can manage all the data in the system including managing the branches and branches staff user. The Branch user can only track a parcel and manage the list of parcels where the origin or the destination of a parcel under the logged in staff branch. The couriered items has multiple statuses which are the "Item Accepted by Courier", "Collected", "Shipped", "In-Transit","Arrived At Destination", "Out for Delivery", "Ready to Pickup", "Delivered", "Picked-up", and "Unsuccessfull Delivery Attempt". This statuses will help to determin the parcels movement. The system also generates a report between two dates and selected status. The couriered items of the clients can be set into "Deliver" and "Pickup". The parcels that marked as deliver are the items to be deliver directly to the recipient while the pickup will be delivered to the branch of the company near to the recipient address. The system admin or staff user can store or adds a multiple items at the same time but these items will be stored in the database seperately because each packagre has a different reference number or different tracking number. For example, Client 1 has 3 boxes of package to be couriered in a same recipient, the system user can submit the parcel registration to the system at once but will be stored seperately so that the system will generate a different unique reference number in each item so that they can track easily each items.

Features
Admin Side
Login Page
The page where the admin user submits their system credentials to access the admin side of the system.
Home Page
The page where the admin user is being redirected by default after logging into the system. This page displays a summary of the data of the system.
New Branch Page
The page where the admin submits the information of the new branch of the courier company.
List of Braches Page
The page where all the branches of the courier company are listed and managed.
New Branch Staff Page
The page where the system admin creates a new user for the specific branch of the company.
Branch Staff List Page 
The page where all of the staff user of the system in all branches are listed and managed.

Both User
New Parcel Page
The page where can system users submit the information of the parcels such as the sender and recipient details.
Parcel List Page
The where the parcels are listed and managed. 
Track Parcel Page
The page that displays the movement of the client's packages or parcels.
Report Page
The page where the printable list of transaction of the courier company with the clients are listed.


The Courier Management System was developed using HTML, PHP/MySQLi, CSS, JavaScript (jQuery/Ajax), and Bootstrap for the design. The source code is fully functional and easy to modify or enhance. Follow the instruction below to have an actual experience using this simple project.

How to Run
Download the source code and extract the zip file.
Download or set up any local web server that runs PHP script.
Open the web-server database and create a new database name it cms_db.
Import the SQL file located in the database folder of the source code.
Copy and paste the source code to the location where your local web server accessing your local projects. Example for XAMPP('C:\xampp\htdocs')
Open a web browser and browse the project. E.g [http://localhost/courier-management-system]
​​​​​​​Default Admin Access
Username: 
Password: 

I hope this simple Courier Management System will help you with what you are looking for, feel free to download and modify the source code.

Explore more on this website for more source codes and tutorials.

Enjoy!
