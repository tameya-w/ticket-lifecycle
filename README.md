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

### 1 Modify Departments

- **Delete** the `Maintenance` department (do not archive).

![Screenshot 2025-03-18 163400](https://github.com/user-attachments/assets/ec67b265-ec63-4663-980b-4fc6a69773d9)
![Screenshot 2025-03-18 163429](https://github.com/user-attachments/assets/08d5de99-9958-46df-86ba-e959c03723d1)

### 2 Create and Manage Tickets
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

**Work Ticket to Completion as Jane**

  Ticket 1: Online Banking System Down

  🔹 Initial Diagnosis:

   - Review the ticket details (priority, department, SLA, assigned agent).
   - Check if multiple users are experiencing the issue.
   - Attempt to reproduce the problem by accessing the banking system.

  🔹 Troubleshooting & Resolution:

  - If hardware-related, test with another charger or battery.
  - Perform a hard reset (holding power button for 10-15 seconds).
   - Boot into Safe Mode to rule out software issues.
   - If it’s a major hardware failure, escalate to the SysAdmins or IT procurement team.
  
  🔹 Closure:

- If resolved, close the ticket and document the fix.
- If unresolved, escalate to the proper team with diagnostic details.
- Ensure the user receives email confirmation of the resolution.

![image](https://github.com/user-attachments/assets/afced6e8-47d5-42f0-adbd-8f74cbe32097)

![Screenshot 2025-03-19 090651](https://github.com/user-attachments/assets/af1c8975-cdb0-45e8-bb2a-6d6174e0185c)

![Screenshot 2025-03-19 091600](https://github.com/user-attachments/assets/b9193b80-0319-4ef2-a4c7-e79a59e5bea0)



#### **Ticket 2: Adobe Upgrade Issue**

- **End-User Action:** Submit a ticket titled: `Accounting department needs Adobe upgrade, broken`.

![Screenshot 2025-03-19 093107](https://github.com/user-attachments/assets/ca756477-5a89-4e2d-b34e-24f4435c307c)


- **Help Desk Agent (John) Action:** Observe ticket properties:
  - `Priority`
  - `Department`
  - `SLA`
  - `Assigned To`

![Screenshot 2025-03-19 093720](https://github.com/user-attachments/assets/37e525b6-0dba-4895-a0fa-96c8acebf020)

- **Set Ticket Properties:**
  - `Sev-C (4 hours, 24/7)`
  - `Support Department`

![Screenshot 2025-03-19 094608](https://github.com/user-attachments/assets/903e611c-c8a2-43cc-8f04-8a080981e3ee)

![Screenshot 2025-03-19 094457](https://github.com/user-attachments/assets/4db02ca8-7c32-40a1-97f1-0d442091bef9)

- **Work Ticket to Completion as John**

Ticket 2: Accounting Department Needs Adobe Upgrade

🔹 Initial Diagnosis:

  - Review license availability and system compatibility.
  - Check if the user has admin rights to install software.

🔹 Troubleshooting & Resolution:

  - Remote into the user’s machine to verify Adobe’s version/status.
  - Install/update Adobe software from the official repository.
  - Verify installation and test functionality with the user.

🔹 Closure:

  - Update the ticket with installation steps and verification results.
  - Confirm with the user that the issue is resolved before closing.
  - If further escalation is needed (e.g., purchasing a new license), assign the ticket accordingly.


![Screenshot 2025-03-19 095539](https://github.com/user-attachments/assets/5faacc2a-d96c-4585-955e-3f5f917e5577)

![Screenshot 2025-03-19 095739](https://github.com/user-attachments/assets/bc9f0ba4-876d-4279-bfd1-5582935dce1b)


![Screenshot 2025-03-19 095753](https://github.com/user-attachments/assets/41cc15e5-7fec-4dfe-8e04-7d43fe0b8c8f)




#### **Ticket 3: CFO Laptop Issue**


- **End-User Action:** Submit a ticket titled: `CFO’s laptop will no longer turn on`.

![Screenshot 2025-03-19 112048](https://github.com/user-attachments/assets/06256668-cb0e-443c-a6e3-33545ad100ba)


- **Help Desk Agent (John) Action:** Observe ticket properties:
  - `Priority`
  - `Department`
  - `SLA`
  - `Assigned To`

![Screenshot 2025-03-19 112838](https://github.com/user-attachments/assets/e108d34b-adc5-4e8d-8dbd-c07d12e9a31a)

- **Set Ticket Properties:**
  - `Sev-B (4 hours, 24/7)`
  - `Support Department`

![image](https://github.com/user-attachments/assets/14123b88-48e5-4431-88be-48176a588e35)


- **Work Ticket to Completion as John**

Ticket 3: CFO’s Laptop Won’t Turn On

🔹 Initial Diagnosis:

  - Verify if the laptop is receiving power (battery, charger, power cord).
  - Ask if any recent changes or updates were made.

🔹 Troubleshooting & Resolution:

  - If hardware-related, test with another charger or battery.
  - Perform a hard reset (holding power button for 10-15 seconds).
  - Boot into Safe Mode to rule out software issues.
  - If it’s a major hardware failure, escalate to the SysAdmins or IT procurement team.

🔹 Closure:

  - Document all troubleshooting steps in the ticket.
  - If the laptop is repaired or replaced, confirm with the CFO.
  - Close the ticket once resolved and notify the user.

![Screenshot 2025-03-19 113411](https://github.com/user-attachments/assets/20826851-7328-400f-afa6-591e00dd2ae6)

![Screenshot 2025-03-19 113813](https://github.com/user-attachments/assets/b5f3c51c-78b2-4943-a542-c55b792e6e46)

![Screenshot 2025-03-19 113829](https://github.com/user-attachments/assets/991c7738-a744-4ac3-be66-d255f7ef0f3b)


### 3 Solve All Tickets
- Work all tickets to completion.
- Understand that **osTicket (and most ticketing systems) includes an email feature** to notify users of updates.

### 4 Understanding Real-World Ticket Intake
- Tickets can be created via:
  - **Phone**
  - **Chat app**
  - **Email**
  - **Web form**
  - **In-person requests**
- **Best practice:** Always create tickets for work done, even for on-the-spot fixes. This helps with tracking and metrics.


## ✅ Conclusion
By following this guide, you now understand how to:
- **Create, manage, and escalate tickets** in osTicket.
- **Set appropriate SLAs and departments** for tickets.
- **Manage user and agent access to escalated tickets**.
- **Apply ticketing best practices in real-world help desk scenarios**.
