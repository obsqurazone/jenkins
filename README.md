# Jenkins Installation-Windows

Step1:Download and Install
Download windows version (LTS) from https://www.jenkins.io/download/

Proceed and complete the installation

Step2:Disable auto start of service

Go to sevices--> 
Right click Jenkins service--> 
Click on properties-->
Change the startup type to manual-->
Click ok and close the window


Step3:Run jenkinS from batch file

Copy the .bat file in the repository and double click to run it-->
Open http://localhost:8080/ in chrome-->
Copy initial password displayed from the command line and paste it in UI when asked-->
Proceed with default plugins when asked in the UI-->
Wait for the plugin instaaltion to complete-->
Proceed by creating an admin user

