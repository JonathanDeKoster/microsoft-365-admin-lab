# Microsoft 365 Admin Lab – Luminous Solutions

This project documents a hands-on Microsoft 365 admin lab using a fictional company, **Luminous Solutions, Inc.** The lab demonstrates user management, license assignment, team and group creation, mailbox configuration, and basic security in a Microsoft 365 environment.

---

## Project Overview

- **Company Name:** Luminous Solutions, Inc.  
- **Tenant Type:** Microsoft 365 Business Basic  
- **Number of Users:** 5  
- **Admin Account:** Jonathan DeCoster (Global Admin)  
- **Purpose:** Practice and document core Microsoft 365 admin tasks, including Teams collaboration, licensing, mailbox management, and security settings.

**Lab Phases:**  
1. Users & license management  
2. Teams & channels setup  
3. Exchange Online: Distribution Lists, Microsoft 365 Groups, and Shared Mailboxes  

---

## Phase 1: Users & Roles

| Name | Role | License | Notes | Screenshots |
|------|------|--------|-------|------------|
| Greg Richards | SharePoint Admin | Business Basic | License toggled off/on; SharePoint admin role assigned | `NewUserSuccessful`, `Greg Richards Licensed`, `Greg Richards SharePoint Admin` |
| Samantha McCarthy | User | Business Basic | Standard access | `NewUserSamanthaMcCarthy`, `Samantha McCarthy` |
| Jeff Page | User | Business Basic | Standard access | [Insert screenshots] |
| Jimmy Andrews | User | Business Basic | MFA enabled | [Insert screenshots] |
| Linda Sullivan | User | Business Basic | Standard access | [Insert screenshots] |

**Notes:** Demonstrates user creation, license assignment, role management, and MFA setup.

---

## Phase 2: Entra ID & Authentication

- **Setup MFA / authentication methods** for selected users.  
- Example for Samantha McCarthy: email authentication method configured.

**Screenshots:**  
- `Microsoft Entra Admin Center`  
- `EntraID Samantha Rolls`  
- `EntraID Samantha Add Authentication Method`  
- `EntraID Samantha Email Authentication`  
- `EntraID MFA Enabled`

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
- `NewTeamMarketingProject` – Creating the team  
- `Team's Marketing Project Toggle Allow Member Permissions` – Member permissions review  
- `Team's Page Including New Marketing Project` – Full team page with members and channels  
- `AnnouncementsNewChannelReview`, `NewChannelCampaignsReview` – Channel creation review

> Demonstrates creating teams, adding owners/members, configuring channels, and setting privacy.

---

## Phase 4: Distribution List

**Distribution List:** Marketing Announcements

- Name: Marketing Announcements  
- Owners & Members assigned  
- Email address configured

**Screenshots:**  
- `add a DistributionListBasics`  
- `add a DistributionListMembers`  
- `add a DistributionListOwners`  
- `add a DistributionListReview`  
- `add a DistributionListSettingEmailAddress`

> Demonstrates creating a distribution list for targeted communications.

---

## Phase 5: Microsoft 365 Group & Mailbox

**Group Name:** Marketing Operations

- Owners & members assigned  
- Mailbox configured and verified via test email  
- Optional alias added: Sam

**Screenshots:**  
- `NewGroupMarketingOperations`  
- `NewGroupMarketingMembers`  
- `NewGroupMarketingOperationsOwner`  
- `NewGroupMarketingOperationReview`  
- `ConfigureUserMailbox`  
- `add Alias Sam`  
- `Test Email for Marketing Operations Group`  
- `Outlook Marketing Operations Test Email Success`

> Demonstrates creating a Microsoft 365 Group with mailbox, assigning members, and verifying mail flow.

---

## Phase 6: Shared Mailbox (Optional)

**Shared Mailbox:** Marketing Support

- Members assigned: Greg Richards, Samantha McCarthy, Jeff Page  
- Purpose: Centralized mailbox for marketing team support

**Screenshots:**  
- `NewSharedMailbox` – Creating the shared mailbox  
- `MarketingSupportMembers` – Members added  
- `MarketingSupportSummary` – Confirmation of mailbox setup

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
