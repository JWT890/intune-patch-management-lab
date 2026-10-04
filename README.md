# intune-patch-management-lab

Patch management is an important part within the lifecyle of a system since it shows compliance with standards, updates with the latest security features, and ensures against threats from attackers that might exploit previous vulnerabilites


# Setup
Windows 11 Enterprise LTSC 2024 Download: https://www.microsoft.com/en-us/evalcenter/download-windows-11-iot-enterprise-ltsc-eval   
Intune set up link: https://learn.microsoft.com/en-us/intune/fundamentals/free-trial-sign-up. Then go this link and set up the Intune environment do both P1 and P2:  
![Signup](./pictures/signup.png)    
Then after setting up the trial you will get to the Microsoft 365 Admin Center here:    
![365](./pictures/365.png)  
Then click on show all to show all the admin centers and click on Microsoft Intune to get to the Intune center: 
![Intune](./pictures/intune.png)    
Then create a user for patch management by going to users tab and click on new user and create the user and after creating the user, go to users in 365 and assign the Intune trial licenses to the test user after creation.   
Then go to Devices -> Enrollment to see this:   
![Enroll]   
Set MDM User scope to all and hit save
