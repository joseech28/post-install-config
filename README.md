<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>


<h2>Configuration Steps</h2>

<p>
<img src="https://imgur.com/6Uhcr4z.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
1. In order to ensure proper access control, we assign roles to agents based on their respective departments. Each role is assigned a set of permissions that can be customized by agents based on their access 
to specific departments. If an agent has access to multiple departments, they can be assigned multiple roles to manage different responsibilities across those departments. This system ensures that agents have 
the right level of access to perform their duties while maintaining security and compliance.  
</p>
<br />

<p>
<img src="https://imgur.com/G6xCRD4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
2. To configure departments within the Admin Panel, navigate to the Agents tab and select Departments. This option is only available to System Administrators. From there, you can add, edit, or delete departments as needed.  
</p>
<br />

<p>
<img src="https://imgur.com/iW1hwOC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
3. The system already has a couple of built-in roles, but I'll create another one so I can understand what this is all about, and I'll call it Supreme-Admin.
</p>
<br />

<p>
<img src="https://imgur.com/HjJwICH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
4. This supreme admin can be like anything right now I'm just going to name it and then add permissions these are like all the the 
different areas I can add access to it. 

</p>
<br />
<p>
<img src="https://imgur.com/B4KJ2Da.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
5.  To configure agents (workers), within the Admin Panel, navigate to the Agents tab and select Add New. From there, you can add new agents such as Jane and   to your system. Once added, you can John assign them to teams, departments, and roles as needed to ensure they have the appropriate access and permissions to complete their tasks.   


</p>
<br />
<p>
<img src="https://imgur.com/GUAYepM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
6. So, now I'm going to do this in the admin panel, then agents departments (I'm already here), and then we'll go to departments, so it appears that there's a maintenance department and a support department by default.
</p>
<br />
<p>
<img src="https://imgur.com/A4tewuf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
7. Next, it's simply on the admin panel agents team, so I'm already on that, and then teams so we can say Level I support or Level II support. I can just build a new one named a team or something similar, and I'll call it level II support.
</p>
<br />
<p>

</p>
<br />
<p>
<img src="https://imgur.com/Mi7d4lF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
8. So, to create agents go to admin panel agents add new so I'm in the admin panel
agents and then I'll add a couple of new agents Jane and John Doe.

</p>
<br />
<p>
<img src="https://imgur.com/u6ufc2a.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
9. Next, I can assign a department to a specific person so that they can be added to system administrators, and then I can see the 
role that I created earlier that allows me to see and literally do everything, so I can make Jane Doe a supreme admin with extended 
access, or I can add more access based on the departments.



</p>
<br />
<p>
<img src="https://imgur.com/y0hGNm4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
10. Nine! I created credentials for Jane and John Doe a supreme admin and extended access.
</p>
<br />
<p>
<img src="https://imgur.com/BfjSRWH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

  11. Next, I'll going to add the users switch to the agent panel and then I'll create and add
users then with their full names Karen Karen and and Ken Ken.

<img src="https://imgur.com/rlgU3Rx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
12. Ok! I created credentials the users Karen and and Ken Ken.Next we're going to configure SLAS.

</p>
<br />
<p>
<img src="https://imgur.com/lE5dHBo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
13. Next go to admin panel here go to manage my SLA is and then SLA
I'll create three slas this is something you kind of might see this in
the real world something like Sev-A, Sev-B and Sev-C so,
Sav-A let's set the schedule for 24 7 basically means if something
happens on the weekend it doesn't matter that it's on the weekend it kind of it
still applies so we can say like one hour for instance so if it happens if a
Sav a comes through on like Sunday night at 10 pm it needs to be resolved by
Sunday night at 11 PM. 

</p>
<br />
<p>
<img src="https://imgur.com/abcJfja.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
14. Sev-A, Sev-B and Sev-C all set up now and ready to go.
</p>
<br />
<p>
<img src="https://imgur.com/UtLG94g.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
15. Next for creating tickets we're going
to do is configure help topics Business Critical Outage.
</p>
<br />
<p>
<img src="https://imgur.com/4SM5HHN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 16. Next help topics Personal Computer Issues

</p>
<br />
<p>
<img src="https://imgur.com/g0WIYMj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
17. Next help topics Equipment Request.

</p>
<br />
<p>
<img src="https://imgur.com/V3ZebPg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
18. Next help topics Password Reset.
</p>
<br />
<p>


