<p align="center">
  <img src="https://swimburger.net/media/ppnn3pcl/azure.png" width="150">
</p>

<h1 align="center">Azure Cloud Setup & IAM Implementation
</h1>

<p align="center">

</p>



## Project Overview

This project documents the setup and configuration of a Microsoft Azure environment for a company, including domain integration, identity and access management (IAM), security configuration, and organizational hierarchy.  
The documentation provides a step-by-step guide to replicate the environment and understand best practices for Azure governance.

---


### 🧿 Step 1 – Register Domain Name
- **What was done:** Registered a company domain for Azure services.
- 📌 **Purpose:** Establishes a unique namespace for email, Azure resources, and identity management.  
- **Notes:** Ensure the domain registrar supports DNS management for Azure integration.

_✔ Registered a domain name for the company Rivetrecords.online_

  <img width="1344" height="620" alt="image" src="https://github.com/user-attachments/assets/18a67e4f-7998-4835-83d5-b64543267316" />


---




### 🧿  Step 2 – Create Azure Account

- **What was done:** Created an Azure account to manage all cloud resources and services.  
- 📌 **Purpose**: Provides access to Azure Portal, subscriptions, and administrative control.  
- **Notes:** Use a company email to maintain organizational control and billing. I will use microsoft outlook email for the company
- Enable Multi-Factor Authentication (MFA) immediately after account creation.

  
_✔ Created an Azure Acount for the company_
<br/>

<img width="1312" height="673" alt="image" src="https://github.com/user-attachments/assets/b0c70ec2-0909-4648-abb1-591be283d718" />

---



### 🧿  **Step 3 – Integrate Domain Name with Azure (Microsoft Entra ID)**

- **What was done:** Verified and added the registered domain to Azure tenant.  
- 📌 **Purpose:** Enables company emails for Azure Active Directory (AAD) login and authentication.  
- **Notes:** Verification requires adding DNS TXT records.

<img width="1347" height="648" alt="image" src="https://github.com/user-attachments/assets/729c055f-b2b7-4cd0-b3b0-954e8df0fce2" />


<img width="1331" height="571" alt="image" src="https://github.com/user-attachments/assets/a9d3aa2e-25e7-4d74-a217-5cb1ee1a31ba" />


✔ _Copy out Destination or points to address_ (TXT Record)

<img width="1074" height="617" alt="image" src="https://github.com/user-attachments/assets/8e3d124e-584e-4e82-82d1-8928ba2e7bf4" />

✔ _Filled in the detail in the advance DNS setup of the purchased domain name pannel_

<img width="1295" height="644" alt="image" src="https://github.com/user-attachments/assets/412b4925-2901-4f47-836f-252da9596790" />

✔ _Verified domain name_

<img width="1341" height="632" alt="image" src="https://github.com/user-attachments/assets/937a2fb4-698b-43e6-b2fd-961b7c7b3736" />

<img width="1032" height="516" alt="image" src="https://github.com/user-attachments/assets/06aa0532-209f-4b74-97ac-eff7da878a42" />

✔ _Domain name integrated and set as primary_

<img width="887" height="564" alt="image" src="https://github.com/user-attachments/assets/c08e0fe7-38a7-436e-9281-04fa9bf50248" />

---


### 🧿   Step 4 – Company Branding in Azure Tenant

- **What was done:** Configured tenant branding, including logo, colors, and sign-in page customizations.  
- 📌 **Purpose:** Improves company identity and enhances user experience.  
- **Notes:** Branding reinforces trust and security for internal users.
  
✔ _The company Sign-in page is customized and branded_

<img width="1331" height="659" alt="image" src="https://github.com/user-attachments/assets/eae8e8b9-b508-45ad-b2d0-db9a3396b7d6" />

---


### 🧿  Step 5 – Azure Entra ID IAM (Single & Bulk User Creation)
- **What was done:** Added users to Azure Entra ID individually and via bulk CSV import.  
- 📌 **Purpose:** Centralized identity management for employees.  
- **Notes:** Use strong passwords and consistent naming conventions for easier administration.
  

✔ _Created single user_

https://github.com/user-attachments/assets/d23c9456-ef04-413f-a3ee-652c417fde43


✔ _Created bulk user_

https://github.com/user-attachments/assets/89343130-26a6-4067-8034-c139afa51a99

<img width="1346" height="645" alt="image" src="https://github.com/user-attachments/assets/8d7ade4f-09f8-440f-b0e2-1603194882d4" />

---

### 🧿 **Step 6 – Group Creation, Roles & Permissions**
- **What was done:** Created groups, assigned roles, and configured permissions using role-based access control (RBAC).  
- 📌 **Purpose:** Streamlines access management and enforces least privilege.  
- **Notes:** Assign permissions carefully to reduce risk of overprivileged users.

✔ _Created a Group, added owner and user based on job description_

https://github.com/user-attachments/assets/64c71ef7-7304-4ad2-b998-e390b3dcf915

<img width="1098" height="609" alt="image" src="https://github.com/user-attachments/assets/42a0811d-d827-48e7-9ebf-4e990e9a2e8c" />



---

### 🧿 **Step 7 – IAM Security & Password Protection**
- **What was done:** Configured password policies, multi-factor authentication (MFA), and security defaults.  
- 📌 **Purpose:** Protects accounts and reduces risk of compromise.  
- **Notes:** MFA is strongly recommended for all administrative accounts.

### Password Policies & MFA

Notes
Some advanced security features and detailed policy customization require Microsoft Entra ID Premium licensing. Due to licensing limitations, full configuration screenshots and advanced policy documentation were not included.

 - Strong password enforcement enabled ✔ 

- MFA applied through security defaults ✔ 

- Improved account protection against unauthorized access ✔ 

---


  


---





