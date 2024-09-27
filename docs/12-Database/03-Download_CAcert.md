--- 
title: "CA Certificate"
---
 
 ### What is CA Certificate 
  <span className="smallFont">
    A CA (Certificate Authority) certificate in the context of databases is a digital certificate issued by a trusted Certificate Authority that verifies the identity of a server or client. It plays a crucial role in establishing secure communications between clients and database servers through SSL/TLS encryption.
  </span>

 ### Why CA Certificate 
  <span className="smallFont">
    CA (Certificate Authority) certificates are used in databases like PostgreSQL and Redis to establish secure connections through SSL/TLS encryption. Here’s why they are important:
    1. Authentication
    2. Encryption
    3. Data integrity
    4. Compliance
  </span>

 ### Learn how to use CA certificate
   
   <span className="smallFont">
   **Step 01 :**  Create the database [(Refer To create database)](http://localhost:3000/docs/Database/Create_database).
   
   **Step 02 :** When the database changes from "In Progress" to "Success," click on the specific database and scroll down to find the "Download CA Certificate" button. Click this button to download the CA certificate. 

       ![create_app](/assets/Database/CA_crt.png)

   **Step 03 :** Use this CA certificate while connecting to your database.
   
        
:::info
  The CA certificate is available only for PostgreSQL and Redis.
:::
</span>
