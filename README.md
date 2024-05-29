<div align="center"><b><h1>Society Management</h1></b></div>

Welcome to the Society Management System (SMS) - an innovative and comprehensive solution designed to revolutionize the way housing societies are managed. In today's fast-paced world, managing the intricate details of a housing society can be a daunting task. SMS bridges the gap between society members and management by providing a seamless interface that enhances communication, efficiency, and transparency.
Our system is meticulously crafted to handle the diverse needs of society management. Whether it's maintaining records of flat owners, calculating maintenance and electricity bills, or managing visitor logs, SMS automates these processes to save time and reduce errors. By leveraging modern technologies like PHP and MySQL, we ensure a robust and user-friendly experience for both administrators and society members.
Key features of the Society Management System include:
<li><strong><ins>User-Friendly Interface:</ins></strong> A simple and intuitive design that facilitates easy navigation for all users.</li>
<li><strong><ins>Automated Billing:</ins></strong> Effortlessly generates monthly maintenance and electricity bills, reducing manual workload and errors.</li>
<li><strong><ins>Complaint Management:</ins></strong> Allows residents to lodge complaints online, ensuring swift resolutions and better service.</li>
<li><strong><ins>Visitor Tracking:</ins></strong> Maintains detailed records of all visitors, enhancing security within the society.</li>
<br />
SMS is a testament to how technology can simplify and streamline the management of housing societies, making life easier for both residents and administrators. Dive into the details of our project to discover how SMS can transform your society's management, bringing efficiency, reliability, and convenience to your doorstep.

<h2>Table of Contents</h2>
<ul>
  <li><a href="#purpose">Purpose</a></li>
  <li><a href="#key-features">Key Features</a></li>
  <li><a href="#technologies-used">Technologies used</a></li>
  <li><a href="#getting-started">Getting Started</a></li>
  <li><a href="#usage">Usage</a></li>
  <li><a href="#screenshots">Screenshots</a></li>
  <li><a href="#Contributing">Contributing</a></li>
</ul>

<h2 id="purpose">Purpose</h2>
<p>The primary purpose of the Society Management System (SMS) project is to streamline and enhance the management of housing societies through a comprehensive and automated platform. Designed to address the common challenges faced by both society members and administrators, SMS aims to bring efficiency, transparency, and convenience to the forefront of society management.</p>

### Key Objectives:
<ul>
<li><strong><ins>Automate Administrative Tasks:</ins></strong> Simplify and automate tasks such as bill generation, complaint resolution, and visitor tracking, reducing manual workload and minimizing errors.</li>
<li><strong><ins>Enhance Communication:</ins></strong> Provide a seamless interface for society members to interact with the management, lodge complaints, and receive updates, ensuring better communication and faster response times.</li>
<li><strong><ins>Improve Security:</ins></strong> Maintain detailed visitor logs and monitor access to the society, enhancing the overall security for residents.</li>
<li><strong><ins>Data Management:</ins></strong> Efficiently manage and store data related to flat owners, their families, and society resources, ensuring easy retrieval and accurate record-keeping.</li>
<li><strong><ins>Increase Transparency:</ins></strong> Ensure that all transactions and activities are transparent, fostering trust and accountability within the society.</li>
</ul>
<br />
By integrating modern web technologies like PHP, MySQL, and JavaScript, SMS not only provides a robust solution to current management issues but also sets the foundation for future enhancements and scalability. This project exemplifies how technology can be leveraged to improve day-to-day operations, making it an ideal addition to any housing society looking to upgrade their management practices.
<br /><br />
The Society Management System is a testament to innovative problem-solving and practical application of programming skills, showcasing my ability to deliver impactful and efficient software solutions. This project highlights my expertise in web development, database management, and user interface design, making it a perfect showcase for potential recruiters.

<h2 id="key-features">Key Features</h2>

### Admin :-
<ul>
<li><strong><ins> Dashboard:</ins></strong> Provides a comprehensive overview including Total Flats, Total Bills, Total Allotments, Total Visitors, Unresolved Complaints, In-progress Complaints, Resolved Complaints, and Total Complaints.</li>
<li><strong><ins> Flats Management:</ins></strong> Allows admins to add and update flat details.</li>
<li><strong><ins> Allotment Management:</ins></strong> Enables the admin to manage the allotment of flats (Add/Update).</li>
<li><strong><ins> Bills Management:</ins></strong> Facilitates the management of bills (Add/Update).</li>
<li><strong><ins> Complaint Handling:</ins></strong> Admins can view, respond to, and update the status of complaints lodged by society members.</li>
<li><strong><ins> Visitor Management:</ins></strong> Manages the details of visitors (Add/Update) including incoming and outgoing details.</li>
<li><strong><ins> Search Functionality:</ins></strong> Allows admins to search for flat allotments and visitors using flat numbers, names, or mobile numbers.</li>
<li><strong><ins> Reports Generation:</ins></strong> Admins can generate reports to view allotments and visitor logs over specific periods.</li>
</ul>

![Admin2](https://github.com/Manishn18/Society-Management/assets/87479740/b964e122-63dd-49f9-be65-419afe45adc4)

### User :-
<ul>
<li><strong><ins> Dashboard:</ins></strong> It is welcome page for society members.</li>
<li><strong><ins> View Bill:</ins></strong> In this section, user can view his/her own society charges which will generated by admin per month.</li>
<li><strong><ins> Visitor:</ins></strong> In this section, user can view detail of visitor who visited in his/her own flat.</li>
<li><strong><ins> Complain:</ins></strong> In this section, user can raise the complain and view the complain status which is provided by society admin.</li>
<li><strong><ins> Search:</ins></strong> In this section, user can search visitor who visited in his/her flats.</li>
<li><strong><ins> Reports:</ins></strong> In this section, user can view how many visitor visit in a flats in particular periods.</li>
</ul>

![User2](https://github.com/Manishn18/Society-Management/assets/87479740/e5f3908c-5be8-4636-a00c-a83baf501c9e)

### Entity-Relationship diagram :- 
Entity-Relationship Diagram: An E-R (Entity-Relationship) Diagram is used to represent the relationships between entities within the tables.

![Screenshot 2024-05-30 030246](https://github.com/Manishn18/Society-Management/assets/87479740/334d3194-123e-4ac2-b766-22e4c8acade4)

### Database design :-
To effectively manage and retrieve data within the system, we meticulously designed the database as part of our overall system architecture. During the analysis phase, we identified essential data elements and structures, which we then organized into a cohesive data storage and retrieval system.
<br></br>
A well-designed database is a collection of interrelated data stored with minimal redundancy, serving multiple users quickly and efficiently. Our primary goal is to ensure that database access is seamless, fast, cost-effective, and flexible for users. By establishing clear relationships between data items and eliminating unnecessary data, we achieved an optimal design.
<br></br>
We implemented normalization to maintain internal data consistency, minimize redundancy, and maximize stability. This approach reduces the required data storage, minimizes the risk of data inconsistencies, and optimizes update operations. For this project, we selected MS Access as the database platform, leveraging its robust features to develop the necessary databases efficiently.
<br />
Society Management System (SMS) contains <ins>7 MySQL tables</ins> :-

1.) <strong><ins>tbladmin table Structure</ins> :</strong> This table store the admin login and personal Details.

![Screenshot 2024-05-30 030358](https://github.com/Manishn18/Society-Management/assets/87479740/c0f899e5-54d1-4dc8-8dfb-b2241572602e)

2.) <strong><ins>tblallotment table Structure</ins> :</strong> This table store the allotment detail of flats.

![Screenshot 2024-05-30 030407](https://github.com/Manishn18/Society-Management/assets/87479740/de684987-883b-4b4c-aacd-e958825a6b4c)

3.) <strong><ins>tblbill table Structure</ins> :</strong> This table store the bill detail of flats.

![Screenshot 2024-05-30 030415](https://github.com/Manishn18/Society-Management/assets/87479740/c76416f6-c2f3-4336-bd0e-5431f54a6644)

4.) <strong><ins>tblblocks table Structure</ins> :</strong>  This table store the blocks of society.

![Screenshot 2024-05-30 030421](https://github.com/Manishn18/Society-Management/assets/87479740/6702d3e1-3873-46f0-84c1-f055c19e5889)

5.) <strong><ins>tblflat table Structure</ins>  :</strong>  This table store the flats details of society.

![Screenshot 2024-05-30 030429](https://github.com/Manishn18/Society-Management/assets/87479740/e52b5c9e-b555-4ff6-a3f1-73c765ea2fa2)

6.) <strong><ins>tblvisitor table Structure</ins> :</strong>  This table store the details of visitors who visit in flats.

![Screenshot 2024-05-30 030434](https://github.com/Manishn18/Society-Management/assets/87479740/3367e026-ec5a-4c6a-a012-d2172835c7ed)

7.) <strong><ins>tblcomplain table Structure :</ins></strong>  This table store the details of complains.

![Screenshot 2024-05-30 030439](https://github.com/Manishn18/Society-Management/assets/87479740/826ce03b-3b50-41c4-a554-e1afd0fc7509)

#### Class Diagram

![Screenshot 2024-05-30 030454](https://github.com/Manishn18/Society-Management/assets/87479740/24f62161-aea4-4f35-bcef-15973635c37c)

<h2 id="technologies-used">Technologies used</h2>
<ul>
<li><strong><ins>PHP</ins>:</strong> Used as the primary server-side scripting language to handle backend logic, manage server-side operations, and interact with the database.</li>
<li><strong><ins>MySQL</ins>:</strong> Employed for database management, enabling efficient storage, retrieval, and manipulation of data.</li>
<li><strong><ins>HTML5</ins>:</strong> Provides the structure and layout of the web pages, ensuring a consistent and responsive user interface.</li>
<li><strong><ins>CSS3</ins>:</strong> Utilized for styling and designing the web pages, enhancing the visual appeal and user experience.</li>
<li><strong><ins>JavaScript</ins>:</strong> Implements client-side scripting to enable dynamic interactions and enhance the functionality of web pages.</li>
<li><strong><ins>Bootstrap</ins>:</strong> A front-end framework used to create responsive and mobile-first web designs, ensuring the application is accessible across various devices and screen sizes.</li>
<li><strong><ins>jQuery</ins>:</strong> Simplifies HTML document traversal, event handling, and animation, making the web pages more interactive and user-friendly.</li>
<li><strong><ins>Ajax</ins>:</strong> Facilitates asynchronous data loading, improving the responsiveness and performance of the application by enabling dynamic content updates without page reloads.</li>
<li><strong><ins>MS Access</ins>:</strong> Chosen for database development due to its powerful features and ease of use, ensuring efficient data management and retrieval.</li>
</ul>

<h2 id="getting-started">Getting Started</h2>
To get started with the Society Management System (SMS) project, follow these steps to set up the development environment and run the application locally.
### Prerequisites
Ensure you have the following software installed on your system:
<li><strong><ins>XAMPP or WAMP</ins> :</strong> To create a local server environment.</li>
<li><strong><ins>Web Browser</ins> :</strong> Any modern web browser (e.g., Chrome, Firefox).</li>
<li><strong><ins>Text Editor or IDE</ins> :</strong> For editing the source code (e.g., Visual Studio Code, Sublime Text)</li>

### Installation

#### Step 1: Clone the Repository
Clone the repository to your local machine using the following command:

```
git clone https://github.com/yourusername/Society-Management-System.git
```

#### Step 2: Set Up the Local Server
<li><strong><ins>Open phpMyAdmin</ins>:</strong> Access phpMyAdmin by navigating to http://localhost/phpmyadmin in your web browser.</li>
<li><strong><ins>Create a New Database:</strong> Create a new database named sms.</li>
<li><strong><ins>Import SQL File:</strong> Import the sms.sql file located in the database folder of the project into the newly created sms database.</li>

#### Step 3: Import the Database
<li><strong><ins>Open phpMyAdmin</ins>:</strong>Access phpMyAdmin by navigating to http://localhost/phpmyadmin in your web browser.
<li><strong><ins>Create a New Database</ins>:</strong> Create a new database named sms.
<li><strong><ins>Import SQL File</ins>:</strong> Import the sms.sql file located in the database folder of the project into the newly created sms database.

#### Step 4: Configure the Database Connection
<li><strong><ins>Open Configuration File</ins>:</strong>  Open the config.php file located in the project's root directory.</li>
<li><strong><ins>Update Database Credentials</ins>:</strong> Ensure the database connection settings match your local server configuration:</li>
<br />


define('DB_SERVER', 'localhost');
define('DB_USERNAME', 'root');
define('DB_PASSWORD', '');
define('DB_DATABASE', 'sms');

#### Step 5: Run the Application
<li><strong><ins>Start the Local Server</ins>:</strong> Ensure that Apache and MySQL services are running in XAMPP/WAMP.</li>
<li><strong><ins>Access the Application</ins>:</strong> Open your web browser and navigate to http://localhost/Society-Management-System.</li>

<h2 id = "usage">Usage</h2>

#### Step 1: Clone the Repository
Clone the repository to your local machine using the following command:

```
git clone https://github.com/yourusername/Society-Management-System.git
```

#### Step 2: Set Up the Local Server

<ul>
<li><strong><ins>Install XAMPP/WAMP</ins>:</strong> Download and install XAMPP or WAMP.</li>
<li><strong><ins>Start Services</ins>:</strong> Launch XAMPP or WAMP and start the Apache and MySQL services.</li>
<li><strong><ins>Move Project Files</ins>:</strong> Copy the cloned project directory to the htdocs directory in XAMPP (typically C:\xampp\htdocs) or the www directory in WAMP (typically C:\wamp\www).</li>
</ul>

#### Step 3: Import the Database

<ul>
<li><strong><ins>Access phpMyAdmin</ins>:</strong> Open your web browser and go to http://localhost/phpmyadmin.</li>
<li><strong><ins>Create Database</ins>:</strong> Create a new database named sms.</li>
<li><strong><ins>Import SQL File</ins>:</strong> Select the sms database, click on the 'Import' tab, choose the sms.sql file from the database folder in the project directory, and click 'Go' to import the database schema and data.</li>
</ul>


#### Step 4: Configure the Database Connection

<ul>
<li><strong><ins>Open Configuration File</ins>:</strong> Use a text editor or IDE to open the config.php file located in the project's root directory.</li>
<li><strong><ins>Update Database Credentials</ins>:</strong> Ensure the database connection settings are correct:</li>
</ul>

```
define('DB_SERVER', 'localhost');
define('DB_USERNAME', 'root');
define('DB_PASSWORD', '');
define('DB_DATABASE', 'sms');
```

### Running the Application

#### Step 1: Start the Local Server
<li><strong><ins>Launch XAMPP/WAMP Control Panel</ins>:</strong> Ensure Apache and MySQL services are running.</li>

#### Step 2: Access the Application
<li><strong><ins>Open Web Browser</ins>:</strong> Open your preferred web browser. Navigate to the application by going to <code>http://localhost/Society-Management-System</code></li>

#### Step 3:  Log In</ins></strong><br/>
<li><strong><ins>Admin Login</ins>:</strong> Use the default admin credentials to log in and start exploring the application features.</li>
</ul>

<h2 id = "screenshots">Screenshots</h2>

#### Homepage

![Screenshot 2024-05-30 031326](https://github.com/Manishn18/Society-Management/assets/87479740/5cab86cf-0094-4efd-99c6-612999491e43)

#### Admin Login

![Screenshot 2024-05-30 031514](https://github.com/Manishn18/Society-Management/assets/87479740/1322dcee-490f-447f-816a-9531c2222f0b)

#### Forgot Password

![Screenshot 2024-05-30 031607](https://github.com/Manishn18/Society-Management/assets/87479740/9fea5d56-1ddf-4e85-975d-bce4a4cf885d)

#### Dashboard

![Screenshot 2024-05-30 031700](https://github.com/Manishn18/Society-Management/assets/87479740/d5cc5435-b55c-4a21-9baf-1556b287656e)

#### Admin Profile

![Screenshot 2024-05-30 031959](https://github.com/Manishn18/Society-Management/assets/87479740/fbdaf0e6-c876-4594-86e3-bed8989668c9)

### Change Passwords

![Screenshot 2024-05-30 032046](https://github.com/Manishn18/Society-Management/assets/87479740/59bee288-8f78-4f40-95f3-206cfaf4981e)

### Add Flats

![Screenshot 2024-05-30 032119](https://github.com/Manishn18/Society-Management/assets/87479740/bf3c07d3-b323-438b-aacf-36da132b330e)

