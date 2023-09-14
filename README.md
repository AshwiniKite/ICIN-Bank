# ICIN-Bank
Create a dynamic and responsive Java online banking web application to deposit, withdraw, and transfer the money between the accounts. ICIN is one of the top banking firms that accepts deposits from the public for the purpose of lending loans to the public. It also invests an amount in securities.

Guide to Execute the projects :

1.ICIN Bank - Backend 
  Open Spring tool Suite 
  Browse to the folder that contains the project. 
  Configure the application.properties file to the database that you wish to use. 
  Run the project as a spring boot app
___________________________________________________
2.User Portal - Frontend 
  Open Visual Studio Code  
  In the terminal type Navigate to the project folder (cd userportal-angular) 
  In the terminal type: npm install  
  Once done type: ng s --o to execute
________________________________________________
3.Admin Portal - Frontend 
  Open Visual Studio Code (adminportal-angular) 
  In the terminal type Navigate to the project folder (cd userportal-angular) 
  In the terminal type: npm install  
  Once done type: ng s --o to execute 

Note: Please make sure that you configure all the ports  
  User backend:8080 
  Admin Backend:8084 
  User frontend: 4200 
  Admin Front End: 4201 
__________________________________________________
4. Backend Testing
STEPS FOR TESTING OF BOTH THE PORTALS. 
STEP 1: Open the project in Eclipse 
STEP 2: Go to src/test/java 
STEP 3: There will be two packages:1)Authentication 2)User Actions 
STEP 4: In the file, in System.setProperty("webdriver.gecko.driver", "(Give the path where the driver is stored)"); 
STEP 5: Under Authentication, There will be Login.java 
STEP 6: Run the file as TestNG test 
STEP 7: Similarly under UserActions,there are files named 
CheckBookRequests.java,EditProfile.java etc 
STEP 8: Open them one by one . Make the changes mentioned in STEP 4 and do Step 6.
