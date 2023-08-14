<p align="center">
<img src= "https://i.ibb.co/yNrB5Np/osticket.jpg" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- MySQL
<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Configuration Steps</h2>
</p>
<br />
The first step is logging into osTicket using the username/password we used while creating it 
</p>
<br />
<img src="https://i.ibb.co/dQHBQjp/step1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Once you're in, click the "Admin" panel and it should bring you into the admin options page
</p>
<br />
<img src="https://i.ibb.co/X5rpTtj/step1-2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Click on "Agents" and select the "Departments" option
</p>
<br />
<img src="https://i.ibb.co/Tb01DDW/step1-3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Select the "Roles" option and click "Add New Role" too create a new role
</p>
<br />
<img src="https://i.ibb.co/4NdBgs1/step1-4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.ibb.co/0ttZ5xV/step1-5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Create a role called "Supreme Admin" this will serve as the role too control everything on osTicket 
</p>
<br />
<img src="https://i.ibb.co/d5mSR4G/step1-6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Check mark all the boxes for "Tickets/Tasks/Knowledge Base" too grant permission. Press "Add role" afterwards too complete the setup
</p>
<br />
<img src="https://i.ibb.co/LJzdHB8/step1-7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.ibb.co/rw1J7XJ/step1-8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.ibb.co/ZBDdH9r/step1-9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Congratualations! You have successfully configured a "Supreme Admin" role 
</p>
<br />
<img src="https://i.ibb.co/5k6VkRr/step2-0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Next we will want too setup a new department. Click on the "Department" option
</p>
<br />
<img src="https://i.ibb.co/jwjW9mg/step2-1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Select "Add New Department"
</p>
<br />
<img src="https://i.ibb.co/6HGhcmx/step2-2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Name the new department "System Adminstrators" and leave all of it on default. Click the "Create Dept" button too complete 
</p>
<br />
<img src="https://i.ibb.co/0jX7zYw/step2-3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
We have now created the new department for System Adminstrators 
</p>
<br />
<img src="https://i.ibb.co/QjKSbFw/step2-4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Next we are going too create a new team, under the Agent's tab; select "Teams" then click on the "Add New Team" button
</p>
<br />
<img src="https://i.ibb.co/wYwZZ9q/step2-5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Name the new team "Level II Support" and keep the rest on default
</p>
<br />
<img src="https://i.ibb.co/gyf1V8k/step2-6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Select yourself as the agent (You can add as many agents as you like on the team) and press "Create Team"
</p>
<br />
<img src="https://i.ibb.co/jw8cdxf/step2-7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Next we will want too make sure that anyone is allowed too create tickets. Too check this, go "Settings" tab and click "Users". Make sure the "Require registration and login too create tickets" box is unchecked, and "Public- Anyone can register" box is selected 
</p>
<br />
<img src="https://i.ibb.co/cC6sNV5/step2-8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Next we will want too create new agents and setup their accounts. Start by clicking the "Agents" tab and selecting the "Add New Agent" option 
</p>
<br />
<img src="https://i.ibb.co/1fWH0m5/step2-9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
It should take you too the account creation page, fill in the blank space and set a password. For this example we are going with "Jane Doe" as the new agent
</p>
<br />
<img src="https://i.ibb.co/hKQf8zL/step3-0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.ibb.co/ftBtKV5/step3-1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Click on the "Access" tab, make sure the agent is under "System Administrators" and "Supreme Admin" options for Primary Department* 
</p>
<br />
<img src="https://i.ibb.co/84SqqZN/step3-2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Next click on "Teams", select "Level II Support" group and press "Add" too put them into the group. Select the "Create" button afterwards
</p>
<br />
<img src="https://i.ibb.co/Mg407dH/step3-3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.ibb.co/JRFHWS5/step3-4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Create another agent replicating the same steps, for this agent we will name him "John Doe" 
</p>
<br />
<img src="https://i.ibb.co/CsjNbSk/step3-5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Once we configured the agents, we will move onto creating the "Users" for osTicket. Start this by selecting the "Agent Panel" option too switch pages
</p>
<br />
<img src="https://i.ibb.co/rk9MRbZ/step3-6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Once you switch pages, select the "Users" tab and click "Add User"
</p>
<br />
<img src="https://i.ibb.co/0jVT8DJ/step3-7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Give the user a name and email, select "Add User" after to finish creating. For this example we went with Karen/karen@gmail.com 
</p>
<br />
<img src="https://i.ibb.co/M9z4rWv/step3-8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Create another user, this time we went with Ken/ken@gmail.com. Congratulations now you know how too create two users for osTicket!
</p>
<br />
<img src="https://i.ibb.co/ryhFB3p/step3-9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Next we will configure "SLA" (Service Level Agreements), this will help determine the ticket level severity. Too begin, go back too the "Admin Panel" page, click "Manage" tab and "SLA". Once your under the "SLA" tab, click "Add New SLA Plan"
</p>
<br />
<img src="https://i.ibb.co/XxdQgPg/step4-0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
We will start with SEV-A (SEV for severity) category. Grace period is 1 and schedule is 24/7. This means that once the ticket is created , it must be DONE in 1 hour when its created. 24/7 schedule means that the ticket must be resolved at anytime of the day regardless if its the weekend. 
</p>
<br />
<img src="https://i.ibb.co/7bffyD9/step4-1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
The next SLA will be SEV-B. Grace period is 4 hours and schedule is 24/7. Tickets in this catergory must be done within 4 hours once the ticket is created. 
</p>
<br />
<img src="https://i.ibb.co/wCc4smX/step4-2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Last SLA we will create is SEV-C. Grace period is 8 hours, the schedule will be from Mon-Fri 8am-5pm with U.S Holidays. This means that whenever the ticket is created is must be done within 8 hours during Mon-Fri. For example, if you get a ticket on Friday at 4pm, it must be done at 3pm on Monday. 
</p>
<br />
<img src="https://i.ibb.co/x8qnTTs/step4-3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Congratulations! You have now created 3 SLA plans, you can observe these plans under the "SLA" tab
</p>
<br />
<img src="https://i.ibb.co/j835gsR/step4-4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Next we are going too configure new help topics. In the Admin panel go to the "Manage" tab and select "Help Topics"
</p>
<br />
<img src="https://i.ibb.co/c6q57bQ/step4-5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
Next we are going too create 4 help topics (Buisness Critical Outage, Personal Computer Issues, Equipment Reset, and Password Reset) Type them in and select "Add Topic" too finalize them
<img src="https://i.ibb.co/Gp6K2wy/step4-6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.ibb.co/rMyhnjm/step4-7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.ibb.co/f1w5jq8/step4-8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.ibb.co/ynCrD8N/step4-9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br/ >
Once thats done, you can now observe them on the help topics section 
</p>
<br />
<img src="https://i.ibb.co/T4H1nHw/step5-0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
</p>
<br />
Congratulations! You have now successfully configured your osTicket post-installation! 







