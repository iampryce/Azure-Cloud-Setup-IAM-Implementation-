<p align="center">
  <img src="https://swimburger.net/media/ppnn3pcl/azure.png" width="150">
</p>

<h1 align="center">Azure Cloud Setup & IAM Implementation
</h1>

<p align="center">

</p>



## Overview
This project documents the setup and configuration of a **Microsoft Azure environment** for a company, including domain integration, identity and access management (IAM), security configuration, and organizational hierarchy.  
The documentation provides a step-by-step guide to replicate the environment and understand best practices for Azure governance.

---

## Table of Contents
- [Overview](#overview)  
- [Step-by-Step Implementation](#step-by-step-implementation)  
- [Architecture Diagrams](#architecture-diagrams)  
- [Setup Instructions](#setup-instructions)  
- [Contributing](#contributing)  
- [License](#license)

---

## Step-by-Step Implementation

### **Step 1 – Register Domain Name**
- **What was done:** Registered a company domain for Azure services.  
- **Purpose / Outcome:** Establishes a unique namespace for email, Azure resources, and identity management.  
- **Notes:** Ensure the domain registrar supports DNS management for Azure integration.

---

### **Step 2 – Create Azure Account**
- **What was done:** Created an Azure account to manage all cloud resources and services.  
- **Purpose / Outcome:** Provides access to Azure Portal, subscriptions, and administrative control.  
- **Notes:** Use a company email to maintain organizational control and billing.

---

### **Step 3 – Integrate Domain Name with Azure**
- **What was done:** Verified and added the registered domain to Azure tenant.  
- **Purpose / Outcome:** Enables company emails for Azure Active Directory (AAD) login and authentication.  
- **Notes:** Verification requires adding DNS TXT records.

---

### **Step 4 – Company Branding in Azure Tenant**
- **What was done:** Configured tenant branding, including logo, colors, and sign-in page customizations.  
- **Purpose / Outcome:** Improves company identity and enhances user experience.  
- **Notes:** Branding reinforces trust and security for internal users.

---

### **Step 5 – Azure Entra ID IAM (Single & Bulk User Creation)**
- **What was done:** Added users to Azure Entra ID individually and via bulk CSV import.  
- **Purpose / Outcome:** Centralized identity management for employees.  
- **Notes:** Use strong passwords and consistent naming conventions for easier administration.

---

### **Step 6 – Group Creation, Roles & Permissions**
- **What was done:** Created groups, assigned roles, and configured permissions using role-based access control (RBAC).  
- **Purpose / Outcome:** Streamlines access management and enforces least privilege.  
- **Notes:** Assign permissions carefully to reduce risk of overprivileged users.

---

### **Step 7 – IAM Security & Password Protection**
- **What was done:** Configured password policies, multi-factor authentication (MFA), and security defaults.  
- **Purpose / Outcome:** Protects accounts and reduces risk of compromise.  
- **Notes:** MFA is strongly recommended for all administrative accounts.

---

### **Step 8 – Azure Cloud Organization Hierarchy**
- **What was done:** Designed Azure hierarchy with management groups, subscriptions, and resource groups.  
- **Purpose / Outcome:** Ensures proper governance, cost management, and access control.  
- **Notes:** Structure resources by department, environment (Dev/Test/Prod), or business unit.

---

## Architecture Diagrams
> Add diagrams in the `/images` folder and reference here.

- **Domain Integration Diagram:** `images/domain-integration.png`  
- **Azure Tenant Structure:** `images/azure-tenant-structure.png`  
- **IAM Roles & Group Hierarchy:** `images/iam-hierarchy.png`

---

## Setup Instructions
1. Register a domain and create Azure account.  
2. Add and verify the domain in Azure tenant.  
3. Configure company branding.  
4. Create users (single/bulk) in Azure Entra ID.  
5. Create groups, assign roles, and configure RBAC.  
6. Implement security policies including MFA and password requirements.  
7. Design cloud hierarchy with management groups and subscriptions.  
8. Document architecture diagrams for reference.

---

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.  
2. Create a feature branch (`git checkout -b feature-name`).  
3. Commit your changes (`git commit -m 'Add feature'`).  
4. Push to branch (`git push origin feature-name`).  
5. Open a Pull Request.

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
