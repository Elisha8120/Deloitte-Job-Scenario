



# Responding to a Breach as a Cybersecurity Specialist. 

<img width="440" height="327" alt="image" src="https://github.com/user-attachments/assets/de710e33-a3be-404b-8199-314bdd85d531" />









# Overview

In this project I will be working on a real on the job scenario that Deloitte has provided to simulate being apart of their Cyber Security Team. While gaining real life experience we will putting our cyber security expertise to the test and applying what we've learned to real life scenarios. The tools I will be using to complete this job assignment will be Sublime Text, and Ubuntu Linux which I more familiar with. 


# Task from my Employers  
<img width="907" height="164" alt="image" src="https://github.com/user-attachments/assets/86e9dd69-0743-4de0-965a-3544ee682fed" />



# Job Completion Steps 


Using Sublime Text I open the incident file where I can expand the file and use keywords to narrow down my search. In this case I used the search feature in Sublime text to look for key words like machine=*.  Also looking for stuff like "api/factory/machine/status" where there are repeated requests to the systems. Still using Sublime I was able to look at the timstamps more closely and look for automated patterns that show any abnormalities. 


<img width="1901" height="1048" alt="image" src="https://github.com/user-attachments/assets/c1e97373-4a0e-47b1-a261-1a90780daff8" />


 
 
 
 # Attackers Identifying Features (Answers) 

 In the photo below we see different identifying characteristics. Where we are able to answer our employers questions and complete the tasks at hand. 
 
 (Numbers are in reference to the numbers and arrows in the screenshot) 

 

 
 1. We are able to see the suspicious activites source IP address. (We are able to notice that the IP Address is a private network IP that shows that it is froma private network.) So turns out is an internal private network IP address, letting us know that it is possibly malicious insider, or a compromised internal machine. 

 2. Here we see the time stamps which show identifying characteristics of an automated polling pattern. Time Stamp: (2021-06-25T16:14:00.000Z)
 
 3. I can also from the same data set see the UserID which is, "mdB7yD2dp1BFZPontHBQ1Z"
 
 4. Here we can easily see a pattern of consecutive requests, which showws automated and scripted charcterisitcs.

 5. Another identifying characterisitc that shows the common requests made by these automated or scripted attacks indicating a possible botnet based attack.  


<img width="1865" height="470" alt="Screenshot 2025-08-30 150414" src="https://github.com/user-attachments/assets/a00d1c38-6cef-4a9d-a51d-851cf7cc3513" />

















# Conclusion 


This investigation into the alleged system breach provided a hands-on simulation of a critical cybersecurity incident response scenario. By systematically analyzing the "web_activity.log file", I was able to transition from a broad alert to a precise understanding of the attack's origin, method, and scope.

My analysis conclusively determined that the suspicious activity was not an external attack but an internal security incident. The attack originated from the private IP address "192.168.0.101", leveraging the compromised credentials of user "mdB7yD2dp1BFZPontHBQ1Z" to execute an automated, scripted data exfiltration attack. The script methodically polled the "/api/factory/machine/status" API endpoint for all factories and machines, a clear signature of malicious intent rather than legitimate user activity.


















# Incident report, and guidline
https://cdn.theforage.com/vinternships/companyassets/9PBTqmSxAf6zZTseP/how-to-read-the-logs.pdf

https://github.com/Elisha8120/Deloitte-Job-Scenario/blob/main/web_activity.log



# Tools 
<img width="32" height="32" alt="image" src="https://github.com/user-attachments/assets/b7438925-1643-482b-b34a-3e292302a80f" />
https://www.sublimetext.com/








<img width="76" height="94" alt="image" src="https://github.com/user-attachments/assets/24e048a1-e08e-4036-b493-1b54fc43bf1d" />
https://ubuntu.com/



# Source: 
https://www.theforage.com/virtual-experience/E9pA6qsdbeyEkp3ti/deloitte-australia/cyber-c1e3/cyber-security






<img width="894" height="227" alt="image" src="https://github.com/user-attachments/assets/0ccf94ae-76e9-4cb4-976b-de1f30cdcb8e" />












