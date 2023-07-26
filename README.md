<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Configuration


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)
- Remote Desktop
- osTicket

<h2>Operating Systems Used </h2>

- Windows 10</b>

<h2>List of Prerequisites</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents
- Configure Users
- Configure Service Level Agreements(SLA)
- Creating Help Topics

<h2>Installation Steps</h2>

osTicket was installed on a virtual machine through Azure, the installation instructions are outlined at https://github.com/josiahshiel/osticket-prereqs

STEP 1 – LOGGING INTO OSTICKET
<p>
Log onto osTicket at https://localhost/osTicket/ 
  
Go to "Settings" and you should see what is shown in EXAMPLE 1A.
<p>
EXAMPLE 1A
<p>
<img width="716" alt="1st" src="https://github.com/JosiahShiel/osticket-post-install/assets/139602019/78e51b04-7cf1-43a3-840c-740744bf190d">

</p>
<p>
Under admin Panel we will go to Agents -> Roles and add Supreme Admin
</p>
EXAMPLE 1B
<p>
<img width="716" alt="2" src="https://github.com/JosiahShiel/osticket-post-install/assets/139602019/fcab1e8d-9cbf-42ef-a1e0-933b88c2b8de">
</p>
STEP 2 – CONFIGURE DEPARTMENTS
<p>
<br />
We can configure departments by selecting the “Departments” button while still in the “Agents” tab. We can then “Add New Department”, see EXAMPLE 2A and EXAMPLE 2B.
</p>
<br />
EXAMPLE 2A
<p>
<img width="716" alt="3" src="https://github.com/JosiahShiel/osticket-post-install/assets/139602019/c24e0b3f-2276-43ee-a993-857fc5d00b46">
</p>
<p>
EXAMPLE 2B
<p>
<img width="715" alt="4" src="https://github.com/JosiahShiel/osticket-post-install/assets/139602019/4e9ed2a5-7cb9-4b65-b81d-43363b29564d">
</p>
<p>
STEP 3 - SETTING UP USERS AND AGENTS
</p>
<br />
In the users tab a few agents have been created to populate this project. In EXAMPLE 3A John Doe has been created along with his employee information, access, permissions, and teams. 
</p>
<br />
EXAMPLE 3A
<p>
<img width="716" alt="5" src="https://github.com/JosiahShiel/osticket-post-install/assets/139602019/ee9e4576-c4c5-4649-ab2a-3208bdb4a374">
</p>
<p>
Additionally by going to Admin Panel>Settings>User Settings we can allow anyone to create tickets by having the item unchecked named “Require registration and login to create tickets”. 
To add users (non-IT employees) go to the “Agent Panel” by selecting the icon on the top right of the screen. Here we can enter employees into the system. 
</p>
<br />
<p>
</p>
<p>
<br />
STEP 4 – SETTING UP TEAMS
</p>
<br />
We can set up team by continuing to be in the admin panel>Agents>Teams as seen in EXAMPLE 4A. We can select “Add New Team” button to add a new team. 
</p>
<br />
EXAMPLE 4A
<p>
<img width="717" alt="6" src="https://github.com/JosiahShiel/osticket-post-install/assets/139602019/7553cd30-5064-4c48-9d8f-a8dfaa26adda">
</p>
<p>
<br />
STEP 5 – SETTING UP SLA
</p>
<br />
Go to the “Admin Panel” at the top right of the page then select the tab Manage>SLA.
</p>
<br />
EXAMPLE 5A
<img width="716" alt="7" src="https://github.com/JosiahShiel/osticket-post-install/assets/139602019/dabf0a0b-21dc-4736-94d8-ee1e6da9a5f8">
</p>
<p>
In EXAMPLE 5B we have created different SLA’s for the tickets depending on their severity. 
</p>
<br />
EXAMPLE 5B
<img width="716" alt="8" src="https://github.com/JosiahShiel/osticket-post-install/assets/139602019/564a9c8c-87ff-436b-b35a-142fbbb91e98">
</p>
<p>
STEP 6 – CREATING HELP TOPICS
</p>
<br />
Going to the tab “Manager” we see “Help Topics” display. We can add help topics to be unique to the business we are supporting, see EXAMPLE 6A.
</p>
<br />
EXAMPLE 6A
<img width="715" alt="10" src="https://github.com/JosiahShiel/osticket-post-install/assets/139602019/6bb62d5c-39f5-4a90-b204-ce55b378a95b">
</p>
<p>
Below we see several additional Help Topics have been added to the list such as Business Critical Outage, Personal Computer Issues, Equipment Request, and Password Reset in EXAMPLE 6B.
</p>
<br />
EXAMPLE 6B
<img width="715" alt="9" src="https://github.com/JosiahShiel/osticket-post-install/assets/139602019/b8926bf8-f3b8-4bfe-b52b-1c72bc1beb3f">
</p>
<p>
This concludes this project in setting up the osTicketing system which will allow for a good starting framework.
</p>
<br />
END OF TUTORIAL
