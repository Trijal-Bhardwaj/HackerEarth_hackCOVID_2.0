# CoviCure Real-Time Chat Application

### [Site is Live](https://60df10a4c5f3c1dcbcb16a8a--covicure-chat-application.netlify.app/)

* Name of the Team : Team Galactus

* Number of Members in the Team : 2

* College : Maharaja Agrasen Institute of Technology (MAIT), Rohini

* Theme of the Project : HealthCare

* Video Link of Project Working :<br/> 
        # https://www.youtube.com/watch?v=s9hB2Dh1RQU<br/> 

* Power Point Presentation Link Of Project Idea :<br/> 
https://docs.google.com/presentation/d/1d3MucTDWLTPeOp9L25mnyVE_nBvDekIjZvipGuIv4ek/edit?usp=sharing 

* Detailed Explaination of Our Project Idea:  
                1. Our idea is about creating a supply chain optimisation as well as a resource management system using a full-fledged web application to address the demand of Covid resources.<br/> 
                2. It will serve for urgent medical essentials and services such as availability of hospital beds, oxygen cylinders, blood & plasma donors, medicines, etc.  
                3. Using our Chat Application, we aim to create a helping community in these harsh times.<br/> 

* The problem it Solves / Solutions Provided : 
        In these hard times of the pandemic, many people have lost their loving ones. There are many people, who after their Covid Recovery, are ready to donate Covid Resources. Our idea revolves around solving this problem. Our community will bridge the gap between the people who are in dire need of help and the ones who are willing to donate.<br/> 
        The major problems/challenges our project addresses are :<br/> 
        1. There are many people who are in dire need of urgent medical resources, especially during this pandemic situation. But it becomes quite difficult for them to find those people who are willing to donate these resources. So, our main objective is to bridge the gap between the willing donor and the needy by creating a community where they can connect and help each other.<br/> 
        2. We will also be ensuring to facilitate the exchange between them, by providing on-time delivery and transportation of these resources.<br/> 
        3. Our application will also provide real time availability of oxygen refill centres and nearby hospital beds for emergency requirements.<br/> 

* How it Works? :<br/> 
                1. Web Scraping is used to collect data of both the willing donors and the people in need.  
                2. Using Automation, an automated message is sent to all the users, containing the link of our Chat Application. <br/> 
                3. Using our Chat application, people can communicate with each other in real-time. Their essential data is also stored securely. <br/> 
                4. Finally, our CoviCure Website displays the data of all the donors. It also addresses Supply Chain Optimisation and Resource Management Services such as Nearby Oxygen Refill Centres and Hospital Beds availability. <br/>  

* Real-Time Usage of Project : <br/> 
        Fully-Fledged and Completely Independent Application that can be used by any Individual or ant Organisation for the Betterment of the Society<br/> 

* ![CoviCure Chat App UI](https://github.com/Trijal-Bhardwaj/covicure_chat_application/blob/master/CoviCureUI.png)

## Tech Stack Used:<br/> 
*Web Scraping & Automation: Node.js & Puppeteer*<br/> 
*Front-End: Reactjs, HTML, CSS, JS*<br/> 
*Back-End: Node.js, Express, Socket.io*<br/> 

## Demo Video:
![Demo Video](https://github.com/Trijal-Bhardwaj/covicure_chat_application/blob/master/CoviCureProjectDemo.gif)

* Project is Live At:<br/> 
https://60df10a4c5f3c1dcbcb16a8a--covicure-chat-application.netlify.app/<br/> 

* Step-By-Step Procedure to Run this Project on Your Local Machine :<br/> 
            Step 1 : Fork this repository or else use git clone, to clone the repository on your local machine<br/> 
            Step 2 : Install node and some NPM Libraries such as puppeteer, request and require modules for Web Scraping and Automation. To Run the Real-Time Chat Application, Install React NPM Libraries such as react-router-dom, react-scrollable-feed, react-emoji, socket.io-client, query-string, etc.<br/> 
            Step 3 : Open Any Code Editor :<br/> 
            Step 4 : Run the code in Following Manner :<br/> 
            # For Running Web-Scraping & Automation Part-<br/> 
                    Run dataWebScrappingDonor.js File. It will scrap, collect and store data of Donor people in a donor.json File.<br/> 
                    Run dataWebScrappingNeedy.js File. It will scrap, collect and store data o Needy people in a needy.json File.<br/> 
                    Run automation.js File. It will Automate Twitter and will Tweet an Automated Message from Our Personal Twitter Account to Evey Donor and Needy Person, containing the Hosted Link of our CoviCure Real-Time Chat Application.<br/> 
                    Run htmlUpdate.js File. It will Display a List of All the Donor and Needy People Twitter UserIDs. It will also show the Tweet Delivery Status for Each Person.<br/> Through our Real-Time Chat Application Link, the user can join and connect with each other from our Real-Time Chat Application, where there is a Helping Community to assist you regarding any emergency requirements related to Covid Resources.<br/> 
            # For Running CoviCure Real-Time Chat Application-<br/> 
                    Open the CoviCure ChatApp Folder, run npm i && npm start for both client and server Folders to Start the Development Server<br/>

# Hospital Management
---
## Screenshots
### Homepage
![Homepage Snap](https://github.com/Trijal-Bhardwaj/Amity-University-Technothon1.0/blob/master/covi-cure-hospitalmanagement-website/static/screenshots/homepage.png)
### Admin Dashboard
![Dashboard Snap](https://github.com/Trijal-Bhardwaj/Amity-University-Technothon1.0/blob/master/covi-cure-hospitalmanagement-website/static/screenshots/admin_dashboard.png)
### Invoice Receipt
![Invoice Snap](https://github.com/Trijal-Bhardwaj/Amity-University-Technothon1.0/blob/master/covi-cure-hospitalmanagement-website/static/screenshots/invoice.png)
### Doctors List
![Doctor Snap](https://github.com/Trijal-Bhardwaj/Amity-University-Technothon1.0/blob/master/covi-cure-hospitalmanagement-website/static/screenshots/admin_doctor.png)
---
## Functions
### Admin
- Can Signup with Their Account. Then Login (No Approval Required).
- Can Register/View/Approve/Reject/Delete Doctors (Approve those Doctors who have Applied for Job in their Hospital).
- Can Admit/View/Approve/Reject/Discharge Patients (Discharge Patients When the Treatment is Done).
- Can Generate/Download Invoice as PDF (Generate Invoice According to the Medicine Costs, Room Charges, Doctor Charges and Other Charges).
- Can View/Book/Approve Appointment (Approve those Appointments which are Requested By the Patients).

### Doctor
- Apply for Job in Hospital. Then Login (Approval Required by Hospital Admin, then only Doctor can Login).
- Can Only View their Patient Details (Symptoms, Name, Mobile) Assigned to that Doctor By the Admin.
- Can View their Discharged (By Admin) Patient List.
- Can View their Appointment, Booked By Admin.
- Can Delete their Appointment, When Doctor Attended their Appointment.

### Patient
- Create Account for Admit in Hospital. Then Login (Approval Required by Hospital Admin, Then only Patient can Login).
- Can View assigned doctor's details like (Specialization, Mobile, Address).
- Can View their Booked Appointment Status (Pending/Confirmed by Admin).
- Can book appointments.(Approval Required By Admin)
- Can View/Download Invoice as PDF (Only When that Patient is Discharged By Admin).

---

## HOW TO RUN THIS PROJECT
- Install Python(3.7.6) (Dont Forget to Tick Add to Path while Installing Python)
- Open Terminal and Execute Following Commands :
```
pip install django==3.0.5
pip install django-widget-tweaks
pip install xhtml2pdf
```
- Download This Project Zip Folder and Extract it
- Move to Project Folder in Terminal. Then Run Following Commands :
```
py manage.py makemigrations
py manage.py migrate
py manage.py runserver
```
- Now Enter Following URL in Your Browser Installed On Your PC
```
http://127.0.0.1:8000/
```

## CHANGES REQUIRED FOR CONTACT US PAGE
- In settings.py file, You have to Give Your Email and Password
```
EMAIL_HOST_USER = 'youremail@gmail.com'
EMAIL_HOST_PASSWORD = 'your email password'
EMAIL_RECEIVING_USER = 'youremail@gmail.com'
```
- Login to Gmail through Host Email ID in Your Browser and Open Following Link and Turn It ON
```
https://myaccount.google.com/lesssecureapps
```
## Drawbacks/LoopHoles
- Any One can be Admin. There is No Approval Required for an Admin Account. So you can Disable Admin Sign Process and Use Any Logic like Creating Superser.
- There should be At Least One Doctor in Hospital Before Admitting a Patient. So First Add Doctor.
- On Update Page of Doctor/Patient You Must have to Update Password.

## Disclaimer
This Project is Developed for Demo Purposes and It's Not Supposed to be Used in Real Application.
