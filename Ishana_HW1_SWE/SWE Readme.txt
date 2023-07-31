README HW1    
NAME : ISHANA


INSTALLATION:


1) JDK installation:


- download and install jdk17.0.2 environment where tomcat will run
- Set up the JAVA_HOME environment variable that points to the path of your JDK installation.


2) Tomcat Installation:
- on the internet, search " Download Tomcat"
- Download the zip file for the latest version of Tomcat and extract it.
- To check if Tomcat is up and running, go to http://localhost:8080 and you will be able to see the homepage


3) Eclipse Installation:
- Download the latest Enterprise Edition of Eclipse IDE from http://www.eclipse.org.
- Once downloaded, start the installation.
- Open the IDE and create a Dynamic Web Project and configure Tomcat in Eclipse:
- File --> New --> Dynamic Web Project
- On the pop-up window, Change the path of Target runtime to the installed Tomcat directory and click on finish.
- A new Dynamic Web Project will be created.
- Right click on the servers tab and select new to define new server. Select Tomcat. You should be able to see the Tomcat server in the servers tab
- To check if the server is working, right click and click on start. Access the homepage at localhost:8080 on the browser


- Troubleshooting Steps
- If you don’t see the Server tab in the bottom portion of the Eclipse IDE, do the following:
– Window-> Show View -> Other - > Servers
- Once the server is started, go to localhost:8080.
- If you get page not found error do the following:
1) Right click on the Tomcat Server --> Properties --> Switch Location to Servers/ Tomcat...
2) Double click on Tomcat Server and select "Use Tomcat Installation"
3)Save changes. Restart the Server






PART 1: 


For part 1 of the assignment, I have created a portfolio website for myself. To run this code, you need to download the following files for it to execute the code without any errors. The index.html file contains About, Experience, Education, Projects and Publications, Interests and Accomplishments. It includes the relevant information that was required as part of the assignment.


Files for Part 1:
* index.html
* js folder with scripts.js
* css folder with styles.css
* assets folder -> img folder -> favicon.ico, profile.jpg, profile1.jpeg
* error.html
* error.css
* 404error1.jpeg


All the files mentioned are uploaded on the S3 AWS console to host the static webpage. Using the link you are directed to the portfolio page else you are directed to the error page if the portfolio page link doesn't work.


Link for Part 1: 
http://ishana-portfolio.s3-website-us-east-1.amazonaws.com


PART 2: 


Note : In the portfolio website under SWE Assignments you will find the link to the student survey page created.


The second part of this assignment was to create a dynamic web project. For this I used Eclipse Enterprise Edition to create a dynamic web page. I added Apache Tomcat 10.0 as the server on eclipse ide. The web page is a student survey form that includes text boxes, radio buttons, dropdown menu, checkboxes, raffle entry box, as well as submit buttons. The war file for this project was created through eclipse ide and later deployed on the Bitnami Tomcat server in the webapps folder. After deploying this file on the EC2 instance we use the Public IPv4 DNS address link to successfully run the survey form.


Link for Part 2:
https://ec2-54-159-30-104.compute-1.amazonaws.com/Ishana_SWE_HW1/Form.html
