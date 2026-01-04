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
<img width="2874" height="1714" alt="image" src="https://github.com/user-attachments/assets/11f37b43-6a7f-4071-a098-21b92b4f833d" />
</p>
<p>
Give the new role a name and set of permissions on the next tabs for Tickets, Tabs, and Knowledge Base.
</p>
<br />

<p>
<img width="2874" height="1714" alt="image" src="https://github.com/user-attachments/assets/11f37b43-6a7f-4071-a098-21b92b4f833d" />
</p>
<p>
Give the new role a name and set of permissions on the next tabs for Tickets, Tabs, and Knowledge Base.
</p>
<br />

<p>
<img width="2874" height="1714" alt="image" src="https://github.com/user-attachments/assets/11f37b43-6a7f-4071-a098-21b92b4f833d" />
</p>
<p>
Give the new role a name and set of permissions on the next tabs for Tickets, Tabs, and Knowledge Base.
</p>
<br />
