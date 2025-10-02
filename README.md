<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo" />
</p>

# osTicket - Ticket Lifecycle: Intake Through Resolution

This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.

---

## Environments and Technologies Used

- Microsoft Azure (Virtual Machines/Compute)  
- Remote Desktop  
- Internet Information Services (IIS)  

## Operating Systems Used

- Windows 10 (21H2)  

## Ticket Lifecycle Stages

- Intake  
- Assignment and Communication  
- Working the Issue  
- Resolution  

---

## 🔐 Portal Login Links

- **End-User Ticket Portal:** [http://localhost/osTicket](http://localhost/osTicket)  
- **Admin/Agent Panel:** [http://localhost/osTicket/scp/login.php](http://localhost/osTicket/scp/login.php)
 


---

# 🎓 Example: Entire Mobile/Online Banking System is Down

## Step 1: Create a Ticket as Karen (End-User) — [http://localhost/osTicket](http://localhost/osTicket)

<p align="center">
  <img width="700" height="700" alt="End-User Portal" src="https://github.com/user-attachments/assets/2a92135c-f8ae-476d-89a9-350eaade0418" />
</p>

- Log into the **End-User Portal**
- Select **Open a New Ticket**

<p align="center">
  <img width="700" height="700" alt="End-User Submission" src="https://github.com/user-attachments/assets/33b0345b-46d7-4836-995c-794bea2ab4f7" />
</p>

- Enter Karen's contact info  
- Help Topic: **Report a Problem**

> 💡 Entered from Karen’s point of view, so not all technical info may be included.

<p align="center">
  <img width="700" height="700" alt="Ticket Details- OBS" src="https://github.com/user-attachments/assets/f5bfe3b4-52cc-4870-bb95-490c3e680fc5" />
</p>

- Click **Create Ticket**

---

## Step 2: Agent John Logs In — [http://localhost/osTicket/scp/login.php](http://localhost/osTicket/scp/login.php)

<p align="center">
  <img width="700" height="700" alt="Agent Jane" src="https://github.com/user-attachments/assets/95fe35ea-69f9-4a5c-93a9-0903a9977375" />
</p>

- Log in to the **Agent Panel**
- View and open the new ticket

<p align="center">
  <img width="700" height="700" alt="Agent logged in" src="https://github.com/user-attachments/assets/c2661662-cc89-48b0-8d84-9066b67cd245" />
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/58e4e593-185e-4703-9a60-8228934a4b4d" alt="Ticket Properties" />
</p>

- Review properties: priority, SLA, help topic, assignment

---

## Step 3: Update SLA and Help Topic

<p align="center">
  <img src="https://github.com/user-attachments/assets/40a2a866-c548-42d7-afc0-154470bb9827" alt="Update SLA" />
</p>

- Set SLA Plan to **Sev-A**

<p align="center">
  <img src="https://github.com/user-attachments/assets/62f40770-7892-4d04-9035-af1bcc368f2d" alt="Update Help Topic" />
</p>

- Change Help Topic to **Report a Problem / Business Critical Outage**

<p align="center">
  <img src="https://github.com/user-attachments/assets/1e9f7f7f-6897-418f-8d60-094552c1d56c" alt="Priority Level" />
</p>

- Update Priority to **Emergency**

---

## Step 4: View Ticket Updates

<p align="center">
  <img src="https://github.com/user-attachments/assets/95ff98d1-f500-4b87-84a1-bb19641f3c00" alt="Ticket Thread" />
</p>

- Refresh the ticket thread to see updates

---

## Step 5: Assign Ticket to Online Banking Team

<p align="center">
  <img src="https://github.com/user-attachments/assets/a54b3da6-bace-4b04-8acb-a284eede6a2e" alt="Assign to Team" />
</p>

- Assign to: **Online Banking Team**  
- Log out of John’s account

---

## Step 6: Jane Takes Over the Ticket

<p align="center">
  <img src="https://github.com/user-attachments/assets/3c616d21-0220-460b-a135-8a7b3e0ada84" alt="Jane Login" />
</p>

- Log in as **Jane**  
- Open and claim the ticket

<p align="center">
  <img src="https://github.com/user-attachments/assets/2ab23d5b-c327-4209-8857-6c4decfb1635" alt="Jane Takes Ticket" />
</p>

- Assign ticket to **Jane** specifically

<p align="center">
  <img src="https://github.com/user-attachments/assets/86a449ee-f895-4d7f-9ea1-9964984cee8a" alt="Update Assignee" />
  <br/>
  <img src="https://github.com/user-attachments/assets/ac135ffb-1683-42ce-83d9-2dd2ed2fa2fb" alt="Assigned to Jane" />
</p>

---

## Step 7: Update the Client on Status

<p align="center">
  <img src="https://github.com/user-attachments/assets/765f5c41-d89f-467b-ae74-e3758acb1088" alt="Client Update" />
</p>

- Use **Post Reply** to notify the client of progress

<p align="center">
  <img src="https://github.com/user-attachments/assets/b0e463c8-94c0-4968-bffc-4ed2b1d49270" alt="Reply Posted" />
</p>

---

## Step 8: Review Ticket Trail and Close It

<p align="center">
  <img src="https://github.com/user-attachments/assets/16b779b1-998f-4a00-8031-0315d2d4eadb" alt="Work Trail" />
</p>

- Review the full work log

<p align="center">
  <img src="https://github.com/user-attachments/assets/3de6b423-76e1-43fd-abc2-9dd2c25b87b3" alt="Resolved" />
</p>

- Set status to **Resolved**  
- Click **Close Ticket**

---

# ✅ Congratulations!

You've successfully walked through a complete osTicket lifecycle: from end-user intake to technician resolution.

---
