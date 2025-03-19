# osTicket: Tickets and Ticket Lifecycle

## Overview
This guide walks through the **ticket lifecycle process** in **osTicket**, from ticket creation to resolution. We will cover:
- Creating tickets as end-users
- Observing and managing ticket properties as help desk agents
- Assigning priorities, SLAs, and departments
- Working tickets to completion
- Understanding real-world ticket intake workflows

## 🔗 Access Links
- **Admin/Analyst Login Page:** [http://localhost/osTicket/scp/login.php](http://localhost/osTicket/scp/login.php)
- **End Users osTicket URL:** [http://localhost/osTicket](http://localhost/osTicket)

## 🎯 Key Steps

### 1️⃣ Modify Departments

- **Delete** the `Maintenance` department (do not archive).

![Screenshot 2025-03-18 163400](https://github.com/user-attachments/assets/ec67b265-ec63-4663-980b-4fc6a69773d9)
![Screenshot 2025-03-18 163429](https://github.com/user-attachments/assets/08d5de99-9958-46df-86ba-e959c03723d1)

### 2️⃣ Create and Manage Tickets
#### **Ticket 1: Online Banking System Down**
- **End-User Action:** Submit a ticket titled: `Entire mobile/online banking system is down`.

![Screenshot 2025-03-18 164726](https://github.com/user-attachments/assets/5c35c627-6408-47e5-9843-e817505b0db7)

- **Help Desk Agent (John) Action:** Observe ticket properties:
  - `Priority`
  - `Department`
  - `SLA`
  - `Assigned To`

![Screenshot 2025-03-18 220456](https://github.com/user-attachments/assets/b0382fef-19c6-4b0d-bc53-f9f2180ea5f5)

- **Set Ticket Properties:**
  - `Sev-A (1 hour, 24/7)`
![Screenshot 2025-03-18 221253](https://github.com/user-attachments/assets/8fcd94f8-fd06-4201-8bc1-ccf042eb76eb)

![Screenshot 2025-03-18 221451](https://github.com/user-attachments/assets/bfb29af2-b000-454f-b40d-0b08558aa18d)

   - `Online Banking Department`
![Screenshot 2025-03-18 221930](https://github.com/user-attachments/assets/28c1f84d-716d-4c67-af2a-b6edfed6c362)


- **Check Visibility:** Can John still view/change the ticket?

![Screenshot 2025-03-18 222022](https://github.com/user-attachments/assets/53820a9a-4965-43eb-bdb9-973d56815225)
John does not have the same level of access as the Online Banking team, so the ticket is no longer viewable.

- **Work Ticket to Completion as Jane**
 ![image](https://github.com/user-attachments/assets/afced6e8-47d5-42f0-adbd-8f74cbe32097)



#### **Ticket 2: Adobe Upgrade Issue**
- **End-User Action:** Submit a ticket titled: `Accounting department needs Adobe upgrade, broken`.
- **Help Desk Agent (John) Action:** Observe ticket properties:
  - `Priority`
  - `Department`
  - `SLA`
  - `Assigned To`
- **Set Ticket Properties:**
  - `Sev-B (4 hours, 24/7)`
  - `Support Department`
- **Work Ticket to Completion as John**

#### **Ticket 3: CFO Laptop Issue**
- **End-User Action:** Submit a ticket titled: `CFO’s laptop will no longer turn on`.
- **Help Desk Agent (John) Action:** Observe ticket properties:
  - `Priority`
  - `Department`
  - `SLA`
  - `Assigned To`
- **Set Ticket Properties:**
  - `Sev-B (4 hours, 24/7)`
  - `Support Department`
- **Work Ticket to Completion as John**

### 3️⃣ Escalation and Access Control
- **Set properties for all tickets**, ensuring **SEV-A (SysAdmins) is last**.
- Observe that the ticket becomes **inaccessible**.
- **Admin Panel:** Assign yourself **View-access** to `SysAdmins`.
- **Switch to Agent Panel:** Observe the escalated ticket.
- Notice that you can no longer make changes to it.

### 4️⃣ Solve All Tickets
- Work all tickets to completion.
- Understand that **osTicket (and most ticketing systems) includes an email feature** to notify users of updates.

### 5️⃣ Understanding Real-World Ticket Intake
- Tickets can be created via:
  - **Phone**
  - **Chat app**
  - **Email**
  - **Web form**
  - **In-person requests**
- **Best practice:** Always create tickets for work done, even for on-the-spot fixes. This helps with tracking and metrics.

### 6️⃣ Additional Practice
- Explore **osTicket's email feature**.
- Repeat this lab multiple times to gain confidence.
- Build intuition by following this **simple checklist**.
- Understand that **technical skill development requires repetition**.

## ✅ Conclusion
By following this guide, you now understand how to:
- **Create, manage, and escalate tickets** in osTicket.
- **Set appropriate SLAs and departments** for tickets.
- **Manage user and agent access to escalated tickets**.
- **Apply ticketing best practices in real-world help desk scenarios**.
