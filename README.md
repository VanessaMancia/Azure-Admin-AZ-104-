# Lab 01 - Manage Microsoft Entra ID Identities 

## Create a new user
### Select Users, then in the New user drop-down select Create new user.

### Create a new user with the following settings (leave others with their defaults). On the Properties tab notice all the different types of information that can be included in the user account.

| Setting                  | Value
| ------------------------ | -----
| User principal name      | az104-user1
| Display name             | az104-user1
| Auto-generate password   | checked
| Account Enabled          | checked
| Job title (Properties tab)| IT Lab Administrator 
| Department (Properties tab)| IT 
| Usage Location (Properties tab) | United States

---

![image](https://github.com/VanessaMancia/Azure-Admin-AZ-104-/assets/112146207/b7cfa204-aaee-4f27-a0fc-9be482ce74c9)


---
### Once you have finished reviewing, select Review + create and then Create.

### Refresh the page and confirm your new user was created.

---

## Invite an external user 

### In the New user drop-down select Invite an external user.

| Setting                  | Value
| ------------------------ | -----
| Email                    | your email address
| Display name             | your name
| Send Invite Message      | check the box
| Message                  | Welcome to Azure and our group project

### Move to the Properties tab. Complete the basic information, including these fields.

| Setting                  | Value
| ------------------------ | -----
| Job Title                | IT Lab Administrator 
| Department               | IT
| Usage Location (Properties Tab)  | United States

---

![image](https://github.com/VanessaMancia/Azure-Admin-AZ-104-/assets/112146207/af5d2000-0b1b-407d-9ee7-0e6a25c55b7e)

---
### Select Review + invite, and then Invite.

### Refresh the page and confirm the invited user was created. You should receive the invitation email shortly.

---

## Task 2: Create groups and add members 

### There are 2 ways members are assigned to groups: Statically and Dynamically. Static groups require admins to add and remove members manually whereas dynamic groups update automatically based on the properties of the user account/device. 

### In the Azure portal, search for and select Groups.

### In the All groups blade, select + New group and create a new group.

| Setting                  | Value
| ------------------------ | -----
| Group Type               |Security 
| Group Name              | IT Lab Administrators
| Group Description(Properties Tab)  | Administrators that manage the IT Lab 
| Membership type | Assigned 

### Add members to the group and select create to deploy the group

### Review the member and owner information 

---

![image](https://github.com/VanessaMancia/Azure-Admin-AZ-104-/assets/112146207/411392e5-08fc-4c0e-a089-c918d745a3af)

