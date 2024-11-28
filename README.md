<h1>Launch a server in AWS</h1>


<h2>Description</h2>
Create a Linux server on AWS with Lightsail,
Connect to the server,
Run some Linux commands, 
Delete the server.

<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Diskpart</b>

<h2>Environments Used </h2>

- <b>Linux Distribution/Amazon Linux 2</b> 

<h2>Program walk-through:</h2>

<p align="center">
Create a Linux server: <br/>
  <h2>First, login to your AWS free tier, make sure you use the correct credentials (your email and your password)
After login in, you will land on the Console Home page, click on Services to get the list of services offered by AWS</h2>
<img src="https://res.cloudinary.com/dk3bkl3ji/image/upload/v1732770333/Screenshot_2024-11-27_214012_rbj5wh.png"/>
<br />
<br />
After clicking on Services, click on Compute in the drop down menu, Select Lightsail in the list of compute services
This will open a new tab in the browser
  <br/>
<img src="https://res.cloudinary.com/dk3bkl3ji/image/upload/v1732771483/Screenshot_2024-11-27_215132_xfmail.png"/>
<br />
<br />
You will land on the Lightsail home page
Click on the Create instance button (instance = server)
 <br/>
<img src="https://res.cloudinary.com/dk3bkl3ji/image/upload/v1732772173/Screenshot_2024-11-27_215316_bc6bwg.png"/>
<br />
<br />
You will then have the possibility to give the characteristics of your instance
Allow the default instance Location,
Allow Linux/Unix as your instance image,
Select OS Only as the blueprint  <br/>
<img src="https://res.cloudinary.com/dk3bkl3ji/image/upload/v1732772270/Screenshot_2024-11-27_215446_xm9wat.png"/>
<br />
<br />
Scroll down and select CentOS (equivalent to CentOS 9) as shown on the image
Scroll down again to choose the instance plan
Select Dual-stack as network type
Allow it to $5 per month (This is free for the first 3 months)
  <br/>
<img src="https://res.cloudinary.com/dk3bkl3ji/image/upload/v1732772894/Screenshot_2024-11-27_215559_cmivps.png"/>
<br />
<br />
Now, scroll down and click on the button Create instance
It might take few minutes for your instance to be fully up. 
  <br/>
<img src="https://res.cloudinary.com/dk3bkl3ji/image/upload/v1732772949/Screenshot_2024-11-27_215630_ojrbr8.png"/>
<br />
<br />
After some time, it will go from the status Pending to Running
The server is successfully launched <br/>
<img src="https://res.cloudinary.com/dk3bkl3ji/image/upload/v1732773008/Screenshot_2024-11-27_220320_eau6ug.png"/>
  <br/>
<img src="https://res.cloudinary.com/dk3bkl3ji/image/upload/v1732773066/Screenshot_2024-11-27_220503_yuk3yl.png"/>
Connect to the server, once the server is up and running, let’s connect to it
Click on the button indicated on the following image and wait few seconds for the Terminal to open

<br />
<br />
Delete the server, First, close the Terminal window you are working on
the,click on the button indicated in the below image then choose Delete

<br />
<br />
 A pop up will open for you to confirm that you want to delete the instance
Click on Yes, delete <br/>
<img src="https://res.cloudinary.com/dk3bkl3ji/image/upload/v1732773185/Screenshot_2024-11-27_234449_hfzgle.png"/>

--!>
