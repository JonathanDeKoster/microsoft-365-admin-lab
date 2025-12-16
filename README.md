# Microsoft 365 Admin Lab – Luminous Solutions

This project documents a hands-on Microsoft 365 admin lab using a fictional company, **Luminous Solutions, Inc.** The lab demonstrates user management, license assignment, team and group creation, mailbox configuration, and basic security in a Microsoft 365 environment.

---

## Project Overview

- **Company Name:** Luminous Solutions, Inc.  
- **Tenant Type:** Microsoft 365 Business Basic  
- **Number of Users:** 5  
- **Admin Account:** Jonathan DeKoster (Global Admin)  
- **Purpose:** Practice and document core Microsoft 365 admin tasks, including Teams collaboration, licensing, mailbox management, and security settings.

- Microsoft 365 Admin Center
- <img width="1600" height="862" alt="Admin Center Home" src="https://github.com/user-attachments/assets/82c44749-0c7e-47db-9500-8c1660ce19c7" />

- Global Admin "Jonathan DeKoster"
- <img width="1599" height="770" alt="Jonathan DeKoster  Global Admin" src="https://github.com/user-attachments/assets/90e8c8f2-5b98-4462-9349-77c54612564f" />

**Lab Phases:**  
1. Users & license management  
2. Teams & channels setup  
3. Exchange Online: Distribution Lists, Microsoft 365 Groups, and Shared Mailboxes  

---

## Phase 1: Users & Roles

| Name | Role | License | Notes | Screenshots |
|------|------|--------|-------|------------|
| Greg Richards | SharePoint Admin | Business Basic | License toggled off/on; SharePoint admin role assigned | `NewUserSuccessful`, `Greg Richards Licensed`, `Greg Richards SharePoint Admin` |
| Samantha McCarthy | User | Business Basic | Standard access | |
| Jeff Page | User | Business Basic | Standard access | [Insert screenshots] |
| Jimmy Andrews | User | Business Basic | MFA enabled | [Insert screenshots] |
| Linda Sullivan | User | Business Basic | Standard access | [Insert screenshots] |

**Notes:** Demonstrates user creation, license assignment, role management, and MFA setup.

**Screenshots**

Add User Samantha McCarthy
<img width="1599" height="779" alt="Add New Users - Samantha McCarthy" src="https://github.com/user-attachments/assets/921ca530-323f-4b43-a838-ac31a6835384" />

<img width="1599" height="779" alt="Add New User Successful" src="https://github.com/user-attachments/assets/89cdad0d-c9a3-44c5-9e9d-0c244a8ba75c" />

Greg Richards Licensing and Role Assigned
<img width="986" height="325" alt="Greg Richards Unlicensed" src="https://github.com/user-attachments/assets/9ebe2ec1-f06c-4c71-a49b-03977cee5822" />

<img width="1315" height="719" alt="Greg Richards Licensed" src="https://github.com/user-attachments/assets/ebaff2ef-c5b4-4fc2-acea-23b344787de6" />

<img width="1594" height="773" alt="Greg Richards SharePoint Admin" src="https://github.com/user-attachments/assets/ca2c1708-0e9c-4b6c-9f3c-aa0ac438b765" />
<img width="1600" height="777" alt="Greg Richards SharePoint Admin 2" src="https://github.com/user-attachments/assets/5b22fb1f-44e2-45f7-9d96-c3bf2259f273" />

---

## Phase 2: Entra ID & Authentication

- **Setup MFA / authentication methods** for selected users.  
- Example for Samantha McCarthy: email authentication method configured.

**Screenshots:**  

Entra ID Admin Center
<img width="1597" height="773" alt="Microsoft Entra Admin Center" src="https://github.com/user-attachments/assets/21cb8c14-3d89-4d0e-a2db-d82ef522d8a5" />


Samantha McCarthy MFA Enabled
<img width="1600" height="776" alt="Entra Samantha add authentication method" src="https://github.com/user-attachments/assets/a5696895-aebf-4dca-a0be-b8ecc69e9c2b" />

<img width="1596" height="777" alt="Samantha Entra ID MFA Enabled" src="https://github.com/user-attachments/assets/f9885532-09b7-4310-836b-b3a551ff05d1" />

> Demonstrates knowledge of user identity management and multi-factor authentication in Microsoft 365.
---

## Phase 3: Teams & Channels

**Team Name:** Marketing Project  
**Purpose:** Coordinate marketing campaigns, share project files, and communicate updates among the marketing team.  
**Privacy:** Private (only invited members have access)  
**Email Address:** marketingproject@luminous.com

**Team Configuration:**  
- **Owners:** Greg Richards, Jimmy Andrews  
- **Members:** Samantha McCarthy, Jeff Page, Linda Sullivan  
- **Channels:** General, Announcements, Campaigns

**Screenshots:**  
- Creating the team
- <img width="1600" height="775" alt="New Team - Marketing Project" src="https://github.com/user-attachments/assets/a0f2ed26-fd05-484b-98b5-a2a00fcb65a3" />
 
- Member permissions review
- <img width="1600" height="774" alt="Teams MArketing Project toggle allow member permissions" src="https://github.com/user-attachments/assets/83e6f8a7-d379-4f44-8179-4e199d5eb91c" />

- Full team page with members and channels
- <img width="1600" height="772" alt="Teams page including new marketing project" src="https://github.com/user-attachments/assets/6a308970-a9ac-4b2e-9cc7-9acea8b0a420" />

-Channel creation review
- <img width="1596" height="776" alt="Announcements new channel review" src="https://github.com/user-attachments/assets/6a614659-ab29-49bb-8f51-0392866eff36" />
- <img width="1600" height="774" alt="New Channel campaigns review" src="https://github.com/user-attachments/assets/8a654237-5a12-4266-b966-8cb5c33c97fd" />



> Demonstrates creating teams, adding owners/members, configuring channels, and setting privacy.

---

## Phase 4: Distribution List

**Distribution List:** Marketing Announcements

- Name: Marketing Announcements  
- Owners & Members assigned  
- Email address configured

**Screenshots:**  

-  <img width="1598" height="772" alt="Add a distribution list basics" src="https://github.com/user-attachments/assets/8b58e33b-4660-4f8b-93be-d4698b55811c" />

-  <img width="1600" height="774" alt="Add a distribution list members" src="https://github.com/user-attachments/assets/f4c9f1db-c6cd-47b7-b201-b845c87471fb" />

-  <img width="1599" height="779" alt="Add a distribution list owners" src="https://github.com/user-attachments/assets/cb4b5a85-d369-43b1-a5a4-a8290fbda71c" />

-  <img width="1600" height="779" alt="Add a distribution list review" src="https://github.com/user-attachments/assets/2d99d400-6819-4a57-8804-e7c04f1be78c" />

-  <img width="1600" height="775" alt="Add a distribution list setting email address" src="https://github.com/user-attachments/assets/11321531-d92d-4051-b309-7f2bbbdd9245" />


> Demonstrates creating a distribution list for targeted communications.

---

## Phase 5: Microsoft 365 Group & Mailbox

**Group Name:** Marketing Operations

- Owners & members assigned  
- Mailbox configured and verified via test email  
- Optional alias added: Sam

**Screenshots:**  
- <img width="1600" height="775" alt="New Group Marketing Operations" src="https://github.com/user-attachments/assets/ea90191b-03aa-4346-9be0-b205cfc53ccb" />
  
- <img width="1599" height="776" alt="New Group Marketing Members" src="https://github.com/user-attachments/assets/60ba0022-c275-4332-a9f9-44f442df71e2" />
  
- <img width="1599" height="771" alt="New Group Marketing Operation Owner" src="https://github.com/user-attachments/assets/657e5184-643a-48fd-b9a7-f5a8ce39b6c5" />
  
- <img width="1598" height="772" alt="New Group Marketing Operation Review" src="https://github.com/user-attachments/assets/3b0b5f66-d8a3-4e24-89bd-4ef2ef53c8bb" />
  
- <img width="1596" height="775" alt="Configure User Mailbox add alias sam@lumsol" src="https://github.com/user-attachments/assets/78f86f4d-27ed-40ff-a821-b854bdd35102" />
    
- <img width="1600" height="769" alt="Test Email for Marketing Operations Group" src="https://github.com/user-attachments/assets/6688c54d-112b-4380-bdfe-6cac89c11ecb" />
  
- <img width="1600" height="821" alt="Logged in as Loraine Sunrise Outlook Marketing Operations test email success" src="https://github.com/user-attachments/assets/ae0e011a-8204-445c-8f8a-edc3c93f3e7d" />


> Demonstrates creating a Microsoft 365 Group with mailbox, assigning members, and verifying mail flow.

---

## Phase 6: Shared Mailbox (Optional)

**Shared Mailbox:** Marketing Support

- Members assigned: Greg Richards, Samantha McCarthy, Jeff Page  
- Purpose: Centralized mailbox for marketing team support

**Screenshots:**  
- Creating the shared mailbox
-  <img width="1600" height="778" alt="New Shared Mailbox Marketing Support" src="https://github.com/user-attachments/assets/675dcfa5-4bce-404b-9479-3027256cd422" />

- Members added
- <img width="1599" height="777" alt="New Shared Mailbox Marketing Support members" src="https://github.com/user-attachments/assets/cb48c6e2-22ab-4d82-8cf5-1084488db536" />
  
- Confirmation of mailbox setup
- <img width="1600" height="774" alt="New Shared Mailbox Marketing Support summary" src="https://github.com/user-attachments/assets/1dd2d308-e1f1-4b10-9d8d-315eaf5c9b5a" />


> Demonstrates shared mailbox creation and collaborative email management.

---

## Licensing & Services

- Business Basic licenses assigned to all users (temporary toggle-off used for demonstration).  
- Services included: Teams, Exchange Online, OneDrive, SharePoint, Web Office Apps.  
- Demonstrates license assignment and awareness of included services.

---

## Security & Admin Highlights

- MFA enabled for select users  
- Admin roles assigned appropriately (Global Admin, SharePoint Admin)  
- Demonstrates understanding of access control and basic security configuration

---

## Summary / Takeaways

This lab demonstrates the core skills necessary for Microsoft 365 administration:

- Creating and managing users and licenses  
- Configuring Teams, channels, and team collaboration  
- Setting up Distribution Lists, Microsoft 365 Groups, and shared mailboxes  
- Applying basic security configurations such as MFA and admin roles

The environment simulates a small company setup, providing a **portfolio-ready example** of practical Microsoft 365 admin capabilities.

---

## Screenshots
