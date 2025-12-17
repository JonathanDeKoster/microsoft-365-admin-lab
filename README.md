# Microsoft 365 Admin Lab – Luminous Solutions, Inc.

This project documents a hands-on Microsoft 365 admin lab for a fictional company, **Luminous Solutions, Inc.** The lab demonstrates practical skills in **user and license management, Teams and channels setup, Exchange Online configuration, and basic security** in a Microsoft 365 environment.

**Lab Objective:** Build and document exposure to Microsoft 365 admin tasks relevant for entry-level IT/help desk roles.  

**Environment:**  
- Tenant Type: Microsoft 365 Business Basic  
- Users: 5  
- Admin Account: Jonathan DeKoster (Global Admin)  

---

## Phase 1: Users & License Management

**Objective:** Demonstrate creating users, assigning licenses, configuring roles, and enabling MFA.

| Name | Role | License | Notes |
|------|------|--------|-------|
| Greg Richards | SharePoint Admin | Business Basic | License toggled off/on; SharePoint admin role assigned |
| Samantha McCarthy | Standard User | Business Basic | Standard access |
| Jeff Page | Standard User | Business Basic | Standard access |
| Jimmy Andrews | Standard User | Business Basic | MFA enabled |
| Linda Sullivan | Standard User | Business Basic | Standard access |

**Screenshots:**

_Adding a new user (Samantha McCarthy)_  
![Add New Users - Samantha McCarthy](https://github.com/user-attachments/assets/921ca530-323f-4b43-a838-ac31a6835384)

_User creation confirmation_  
![Add New User Successful](https://github.com/user-attachments/assets/89cdad0d-c9a3-44c5-9e9d-0c244a8ba75c)

_Greg Richards: License assignment & SharePoint Admin role_  
![Greg Richards Licensed](https://github.com/user-attachments/assets/ebaff2ef-c5b4-4fc2-acea-23b344787de6)  
![Greg Richards SharePoint Admin](https://github.com/user-attachments/assets/ca2c1708-0e9c-4b6c-9f3c-aa0ac438b765)

---

## Phase 2: Entra ID & Authentication

**Objective:** Configure authentication methods and MFA for selected users.

**Screenshots:**

_Entra Admin Center_  
![Microsoft Entra Admin Center](https://github.com/user-attachments/assets/21cb8c14-3d89-4d0e-a2db-d82ef522d8a5)

_Adding authentication method for Samantha McCarthy_  
![Entra Samantha add authentication method](https://github.com/user-attachments/assets/a5696895-aebf-4dca-a0be-b8ecc69e9c2b)

_Email authentication/MFA enabled_  
![Samantha Entra ID MFA Enabled](https://github.com/user-attachments/assets/f9885532-09b7-4310-836b-b3a551ff05d1)

> Demonstrates user identity management and enabling MFA.

---

## Phase 3: Teams & Channels

**Team:** Marketing Project  
**Purpose:** Coordinate marketing campaigns, share files, communicate updates.  
**Privacy:** Private  
**Email Address:** marketingproject@luminous.com  

**Configuration:**  
- **Owners:** Greg Richards, Jimmy Andrews  
- **Members:** Samantha McCarthy, Jeff Page, Linda Sullivan  
- **Channels:** General, Announcements, Campaigns  

**Screenshots:**  

_Creating the team_  
![New Team - Marketing Project](https://github.com/user-attachments/assets/a0f2ed26-fd05-484b-98b5-a2a00fcb65a3)

_Member permissions toggle_  
![Teams Marketing Project toggle allow member permissions](https://github.com/user-attachments/assets/83e6f8a7-d379-4f44-8179-4e199d5eb91c)

_Full team page with members  
<img width="1600" height="774" alt="Marketing Project Post Creation Members" src="https://github.com/user-attachments/assets/e852eb95-6a91-41d8-9d84-5050b1447c92" />



_Channel creation review_  
![Announcements new channel review](https://github.com/user-attachments/assets/6a614659-ab29-49bb-8f51-0392866eff36)  
![New Channel campaigns review](https://github.com/user-attachments/assets/8a654237-5a12-4266-b966-8cb5c33c97fd)

_Full team page with channels
<img width="1600" height="777" alt="Marketing Project Post Creation Channels" src="https://github.com/user-attachments/assets/90087fca-698e-49d2-bc68-d01a58579959" />

> Demonstrates creating teams, adding owners/members, configuring channels, and setting privacy.

---

## Phase 4: Distribution List

**Distribution List:** Marketing Announcements  

**Configuration:**  
- Name: Marketing Announcements  
- Owners & Members assigned  
- Email address configured  

**Screenshots:**  

_Basics_  
![Add a distribution list basics](https://github.com/user-attachments/assets/8b58e33b-4660-4f8b-93be-d4698b55811c)  

_Members_  
![Add a distribution list members](https://github.com/user-attachments/assets/f4c9f1db-c6cd-47b7-b201-b845c87471fb)  

_Owners & Review_  
![Add a distribution list owners](https://github.com/user-attachments/assets/cb4b5a85-d369-43b1-a5a4-a8290fbda71c)  
![Add a distribution list review](https://github.com/user-attachments/assets/2d99d400-6819-4a57-8804-e7c04f1be78c)

_Email address configured_  
![Add a distribution list setting email address](https://github.com/user-attachments/assets/11321531-d92d-4051-b309-7f2bbbdd9245)

---

## Phase 5: Microsoft 365 Group & Mailbox

**Group:** Marketing Operations  

**Configuration:**  
- Owners & Members assigned  
- Mailbox configured  
- Test email sent and verified  
- Alias added for Samantha McCarthy: Sam  

**Screenshots:**  

_Group & Members_  
![New Group Marketing Operations](https://github.com/user-attachments/assets/ea90191b-03aa-4346-9be0-b205cfc53ccb)  
![New Group Marketing Members](https://github.com/user-attachments/assets/60ba0022-c275-4332-a9f9-44f442df71e2)  

_Owners & Review_  
![New Group Marketing Operation Owner](https://github.com/user-attachments/assets/657e5184-643a-48fd-b9a7-f5a8ce39b6c5)  
![New Group Marketing Operation Review](https://github.com/user-attachments/assets/3b0b5f66-d8a3-4e24-89bd-4ef2ef53c8bb)  

_Mailbox Configuration & Test_  
![Configure User Mailbox add alias sam@lumsol](https://github.com/user-attachments/assets/78f86f4d-27ed-40ff-a821-b854bdd35102)  
![Test Email for Marketing Operations Group](https://github.com/user-attachments/assets/6688c54d-112b-4380-bdfe-6cac89c11ecb)  
![Logged in as Lorraine Sunrise Outlook Marketing Operations test email success](https://github.com/user-attachments/assets/ae0e011a-8204-445c-8f8a-edc3c93f3e7d)

---

## Phase 6: Shared Mailbox (Optional)

**Shared Mailbox:** Marketing Support  
- Members: Greg Richards, Samantha McCarthy, Jeff Page  
- Purpose: Centralized support mailbox for marketing team  

**Screenshots:**  

_Creation_  
![New Shared Mailbox Marketing Support](https://github.com/user-attachments/assets/675dcfa5-4bce-404b-9479-3027256cd422)  

_Members added_  
![New Shared Mailbox Marketing Support members](https://github.com/user-attachments/assets/cb48c6e2-22ab-4d82-8cf5-1084488db536)  

_Summary_  
![New Shared Mailbox Marketing Support summary](https://github.com/user-attachments/assets/1dd2d308-e1f1-4b10-9d8d-315eaf5c9b5a)

---

## Licensing & Services
- Business Basic licenses assigned to all users  
- Services included: Teams, Exchange Online, OneDrive, SharePoint, Web Office Apps  

---

## Security & Admin Highlights
- MFA enabled for selected users  
- Admin roles assigned appropriately (Global Admin, SharePoint Admin)  

---

## Summary / Takeaways
This lab demonstrates **core Microsoft 365 administration skills**:

- User and license management  
- Team and channel setup  
- Distribution Lists, Microsoft 365 Groups, and shared mailbox configuration  
- Basic security configuration (MFA, admin roles)  

This environment simulates a small company, providing a **portfolio-ready example** of practical Microsoft 365 admin experience.

