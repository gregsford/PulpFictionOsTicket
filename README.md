<div align="center">
  <img src="pf.jpg">
  
  <h1>Pulp Fiction osTicket</h1>
  <h2><i>Marcellus Wallace has a new way of handling his business... <br>Help Desk tickets!</i></h2>
  <br>
  <p>For this demonstration I decided to base an open source ticket system and applied it to the movie Pulp Fiction.  
I will walkthrough the process of setting up OsTicket through virtual machines in a cloud environment using Microsoft Azure.</p>

<h3>Environments and Technologies Used:</h3>
Microsoft Azure<br>
osTicket software<br>
Remote Desktop<br>
HeidiSQL

<h3>Operating Systems Used:</h3>
Windows 10

<h4>Step 1 - Setting up an environment in Microsoft Azure.</h4>
<p>In the initial step I set up a Resource Group and created a virtual machine. After setting up a Microsoft 10 operating system and creating a user and password, I copied the public IP address and used a remote desktop connection to log in. Inside the virtual machine is where I will set up my environment for osTicket.</p> 

<img src="1.png">

<h4>Step 2 - Setting up IIS.</h4>
<p>Here I set up all the correct configurations for IIS to run.  This is to ensure that we can get osTicket up and running.</p>

<img src="2.png">
<img src="3.png">

<h4>Step 2 - Setting up osTicket.</h4>
<p>With help from the Information Technology course on CourseCareers, I have a supply of files to download in order to get osTicket running.  Some of these include the osTicket ticket software, PHP software, and a HeidiSQL database.</p>

<img src="4.png">
<img src="5.png">

<h4>Step 2 - Profile information.</h4>
<p>Pretty self explanatory, in this section I filled in all the information that was asked in order to set up. Notice on the bottom about the database required fields.  This was set up with the database that we created in HeieSQL.</p>

<img src="6.png">

<h4>Step 2 - Logging into osTicket</h4>
<p>After setting up my profile and database, I then logged in to osTicket to verify that it works.  As you can see here, it works and brings us to the main screen to see what tickets may be awaiting us.</p>

<img src="7.png">
<img src="8.png">

<h4>Step 3 - Adding Roles, Admins, SLA Plans, Help Topics, and Users</h4>
<p>Now that we are all set up, the gangsters need to start putting in requests to Marsellus Wallace for their needs. 
So I set up some roles and Admins, and created an SLA Plan <i>(normally there will be various types of SLA, but in the gangster realm only 1 or 2 should suffice).</i> Then I created some Help Topics and then some Users, so Jules and Vincent can log in when something occurs. Like when they needed the aid of The Wolf to clean up a messy situation.</p>

<img src="9.png">
<img src="10.png">
<img src="11.png">
<img src="12.png">
<img src="13.png">
<img src="15.png">

<h4>Step 2 - Creating a Help Desk Ticket</h4>
<p>Now that everything is set up, it's time for the Users to start submitting requests.  Once a ticket is submitted, they will be assigned to the appropriate agent or admin with the correct SLA and have any comments noted in alignmnent with the issue of the ticket.</p>

<img src="14.png">

<h4>Step 2 - Logging off the Remote Desktop</h4>
<p>Now that the project has been set up, tested, and practiced on, it's now time to dismantle our project.  This start of this is simply ending the remote session by either logging out of the virtual machine or clicking on X.</p>

<img src="16.png">


<h4>Final Step: Deleting our project</h4>
<p>With Microsoft Azure, you will have to pay for what you use unless you have credits when you initially sign up.
However when you keep your environment running it'll cost you. 
So essentially here we go back into the Azure and delete our virtual machines and resource group.
Make sure you delete it all.</p>  
<img src="17.png">
<img src="18.png"><br>
<br>
<p>The last thing you want to do is make a mistake and have Jules Winnfield knocking on your door at 7am and begin to recite 
<i>"The path of the righteous man is beset on all sides by the inequities of the selfish and the tyranny of evil men. 
Blessed is he who, in the name of charity and good will, shepherds the weak through the valley of the darkness, 
for he is truly his brother's keeper and the finder of lost children. 
And I will strike down upon thee with great vengeance and furious anger those who attempt to poison and destroy My brothers. 
And you will know I am the Lord when I lay My vengeance upon you."</i><br>
It's just not a good idea.</p>
</div>


