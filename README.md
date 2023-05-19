<h1 align="center">osTicket: Ticket Lifecycle</h1>

<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png"/>
</p>

<h1>Introduction</h1>
In this section we will play around in osTicket and show the ticketing process. This part is more of a self-experimentation for you to explore the ticket process than a tutorial<br />

<h2>Walkthrough</h2>

<h3>Step 1: Creating a ticket as users</h3>

http://localhost/osTicket/ 

Using the link above, create a ticket, log in as one of the users you create in the previous tutorial, select one of the help topics you've made in the previous tutorial, fill in the blanks at your own discretion and hit "Create Ticket." You can then create another ticket as the other user by clicking on "Open a New Ticket" up top.

 <p align="center">
<img src="https://github.com/Mwajiduddin/Mwajiduddin/blob/main/images/g1.png" />
</p>

 <p align="center">
<img src="https://github.com/Mwajiduddin/Mwajiduddin/blob/main/images/g2.png" />
</p>

 <p align="center">
<img src="https://github.com/Mwajiduddin/Mwajiduddin/blob/main/images/g3.png" />
</p>

 <p align="center">
<img src="https://github.com/Mwajiduddin/Mwajiduddin/blob/main/images/g4.png" />
</p>

<h3>Step 2: Modify and resolving a ticket as an agent</h3>

Now copy and paste the link at the bottom and log back in as the agent that you made in the previous tutorial and you'll see the tickets that you've made are populated in the front page.

http://localhost/osTicket/scp/login.php

 <p align="center">
<img src="https://github.com/Mwajiduddin/Mwajiduddin/blob/main/images/g5.png" />
</p>

 <p align="center">
<img src="https://github.com/Mwajiduddin/Mwajiduddin/blob/main/images/g6.png" />
</p>


Click on one of the ticket you created and you'll see that you can modify its configuration such as its status, priority, department, specifiy on who you want to assign it, change the SLA, and ticket status. 

Remember: the reason why you can change so much of the ticket's paramaters is because in the previous tutorial we assigned our agent, Jane Doe, the role as a Supreme Admin and the Supreme Admin has all the permissions enabled.

 <p align="center">
<img src="https://github.com/Mwajiduddin/Mwajiduddin/blob/main/images/g7.png" />
</p>

You can resolve tickets by selecting "Resolved" from the drop-down menu next to "Ticket Status" and clicking on "Post Reply" then it will be in the "Closed" section and it will specify who closed the ticket. 


<p align="center">
<img src="https://github.com/Mwajiduddin/Mwajiduddin/blob/main/images/g8.png" />
</p>

 <p align="center">
<img src="https://github.com/Mwajiduddin/Mwajiduddin/blob/main/images/g9.png" />
</p>

Remember to delete you virtual machine in Azure once you're done playing around in osTicket.


























