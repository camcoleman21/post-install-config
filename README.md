<p align="center">
<img width="700" height="208" alt="image" src="https://github.com/user-attachments/assets/5590c10a-8ff3-48f4-924f-0808b23671c5" />
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>Post-Install Configuration Objectives</h2>

- Configuration of Roles, Departments, and Teams
- Setup of Agents (workers) and Users (customers)
- SLA Configurations
- Setup of Help Topics

<h2>Configuration Steps</h2>

<p>
<img width="2878" height="1706" alt="image" src="https://github.com/user-attachments/assets/27d1f48c-9c13-4717-add0-da9787bdc51e" />
</p>
<p>
Log back into the Azure osTicket VM. Note that these are the separate login pages: Admin/Analyst Login Page: http://localhost/osTicket/scp/login.php and End Users' osTicket URL:
http://localhost/osTicket. Notice the differences between each page (end user is on the left, admin is on the right)
</p>
<br />

<p>
<img width="2876" height="1710" alt="image" src="https://github.com/user-attachments/assets/a9f83c07-dbb0-43e3-8c82-24b46159eedd" />
</p>
<p>
Log in to the Admin page. Once logged in, navigate to the Admin Panel -> Agents -> Roles, and select 'Add New Role'
</p>
<br />

<p>
<img width="2874" height="1714" alt="image" src="https://github.com/user-attachments/assets/11f37b43-6a7f-4071-a098-21b92b4f833d" />
</p>
<p>
Give the new role a name (ex. Supreme Admin) and set of permissions on the next tabs for Tickets, Tabs, and Knowledge Base. Save Changes.
</p>
<br />

<p>
<img width="2880" height="1710" alt="image" src="https://github.com/user-attachments/assets/dbf34732-1340-425e-b8b9-11772023a646" />
</p>
<p>
Next, we will configure departments. Go to the Admin Panel -> Agents -> Departments. Add a new department and configure the settings below. Click Create Dept at the bottom. </p>
<br />

<p>
<img width="2880" height="1664" alt="image" src="https://github.com/user-attachments/assets/b1b384fd-0a33-4db5-b302-e4d4bf1adf95" />
</p>
<p>
To configure Teams, go to the Admin Panel -> Agents -> Teams. Click 'Add a New Team' and input a name and any agents for that team.</p>
<br />

<p>
<img width="2834" height="1566" alt="image" src="https://github.com/user-attachments/assets/ac7a3c81-0323-476f-ab70-90504c32b103" />
</p>
<p>
This next setting will allow anyone to create tickets without an account requirement. Admin Panel -> Settings -> User Settings (UNCHECK: Registered users can create tickets) </p>
<br />

<p>
<img width="2832" height="1566" alt="image" src="https://github.com/user-attachments/assets/ebb15f0a-2109-4a1e-8864-40d56822439d" />
</p>
<p>
Next, Configure Agents (workers) Admin Panel -> Agents -> Add New. Create an agent named Jane (Dept: SysAdmins) and one named John (Dept: Support)
</p>
<br />

<p>
<img width="2842" height="1560" alt="image" src="https://github.com/user-attachments/assets/4f7fcd65-ecc2-40af-a53b-4a818a29a08b" />
</p>
<p>
Next, configure Users (customers) by navigating to Agent Panel -> Users -> Add New. Create a user named Karen. </p>
<br />

<p>
<img width="2852" height="1570" alt="image" src="https://github.com/user-attachments/assets/87d2c3b5-e441-49a2-9372-fd56386d9a8a" />
</p>
<p>
Next, we will configure the SLA by navigating to the Admin Panel -> Manage -> SLA. Add a new SLA plan and set the following: Sev-A (Grace Period: 1 hour, Schedule: 24/7). Sev-B (Grace Period: 4 hours, Schedule: 24/7). Sev-C (Grace Period: 8 hours, Business Hours). </p>
<br />

<p>
<img width="2844" height="1556" alt="image" src="https://github.com/user-attachments/assets/4be4ee20-8063-4bce-9076-5daf30a63371" />
</p>
<p>
Finally, we'll want to configure Help Topics for when users create a ticket. Admin Panel -> Manage -> Help Topics -> Add New Help Topic. Create the following: Business Critical Outage (PT: Report a Problem), Personal Computer Issues (PT: Report a Problem), Equipment Request (PT: General Inquiry), Password Reset (PT: Report a Problem), Other (PT: General Inquiry)
 </p>
<br />
