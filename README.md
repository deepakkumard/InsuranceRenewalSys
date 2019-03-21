# Team Member

AJAY KUMAR S 15CSA04 (711715104004) 

DEEPAK KUMAR D 15CSA13 (711715104013)

GUNA S 15CSA82 (711715104303)

# Agent Insurance renewal app
Agent Insurance Renewal app helps to reduce the work of the client and to keep them updated about the date of expiry and also the status of their policy. The agent can search any client with their respective Policy number or the Vehicle number registered with the policy. Having an insurance policy reduces the financial burden in the case of loss or damages arising from an accident caused to or by your insured vehicle. The renewal date of your insurance policy is based on the date your policy grabbed. Using this app, the agents can notify the clients through. E-mail or SMS regarding the unpaid (pending) amount and acknowledge for the renewal process. The agent can enter the type of vehicle for proceeding with the renewal process. The payment will be done to the insurance company by the client with the help of the agent. If the client forgets about renewing the policy, an alert will be sent by the application for the second time in order to notify the client again. The insurance can also be renewed by the client through this app.

# Module splitup

Firebase authentication and fetch Realtime database (ajaykumar and Guna)

Provide an Email /SMS alert feature for agent (deepak kumar)

Generate a renewal notice based on Taxes, agent commission (Guna)

Inclusion of payments

# Minimum Requirment

Android studio 3.3.2
Kotlin 1.2
Firebase
Operating system  :	Windows 7/8/10

# Advantages

The system is to be built with KOTLIN, and Firebase for database. It calculates the renewal amount with respect to Government updates. Provide SMS and Email notification based on the expiry of the renewal date. Generate a renewal notice with Included taxes, no claim bonus and other commissions. Payment will be done to the Insurance company with the help of the agent.


# Project Status

Completed (80%)

# Module Descrpition

    Firebase database (Guna)
 
 The Firebase Realtime Database is a cloud-hosted database. Data is stored as JSON and synchronized in realtime to every connected client. When you build cross-platform apps with our iOS, Android, and JavaScript SDKs, all of your clients share one Realtime Database instance and automatically receive updates with the newest data. The Realtime database which includes the details such as

•	Policy number

•	Name of insurer

•	Sum insured

•	Mail

•	Vehicle make, Model, Year

•	Vehicle number

•	Issued date, Expiry date

•	Ex coverage amount, premium

•	Tax id, amount, percent


     Email and SMS notification (Deepak kumar)
  
  Based on the expiry date refered from client database , it alerts the client through SMS/Email 30 days in advance.In the alert message the insurance amount along with current Gst to be paid.
  
   In mainfest to send a SMS message  first we need to get SMS permission and similarly to send a mail we need to get Internet permission.There is format to send SMS message called "SMS SEND ACTION".If we use this format it automatically sends message to that particular person ,this details are retrived from FireBase.If we click OK button the message will be send automatically.Inoder to send a mail we will set a mail ID in URI the same SEND ACTION is used to send a mail.Two intent is passed one is e-mail to whom we send and another one is subject and Body of the Content what we display.If we use START ACTIVITY the SMS and e-mail is send to the client.
 
  

    
    
 
    




