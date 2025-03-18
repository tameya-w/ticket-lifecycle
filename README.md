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


- **Set Ticket Properties:**
  - `Sev-A (1 hour, 24/7)`
  - `Online Banking Department`
- **Check Visibility:** Can John still view/change the ticket?
- **Work Ticket to Completion as Jane**

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
