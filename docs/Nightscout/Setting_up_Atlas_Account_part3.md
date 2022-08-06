<!-- this is on github live server !
docs made by D.Galloway 2019- 2021-->

# Welcome to The Diabetic way
For full Website content visit [The Diabetic Way](https://www.thediabeticway.co.uk/index.php/en/).
<br>
<br>



<img width="auto" height="auto" border="0" align="center"  src="../../img/Atlas/Robot face_ Atlas account_860x462.jpg" Setting up Atlas Part 3"/><br><br>
## **Part 3 Setting up a Atlas Account for Nightscout**<br><br>





###1. **Now Open another tab**  to make a Mongodb Atlas** Account: <a href="https://www.mongodb.com/cloud/atlas" target="_blank" title="Click Try Free">See Here</a> 
  and **click** <span style="background-color: #FFFF00">**Start Free**</span><br>
  <img width="auto" height="auto" border="0" align="center"  src="../../img/Atlas/free Atlas Account.jpg" title="Sign up a Atlas Account"/></a>	
###2. Enter your Account Details like I have and then click <span style="background-color: #FFFF00">**get started free**</span> 
  <img width="auto" height="auto" border="0" align="center"  src="../../img/Atlas/setting up a free  Atlas Account.jpg"Fill in your details"/><br><br>
###3. Atlas will send you an email, if you don't receive it check your Spam folder.<br>
###4. Now verify your email<br>
<img width="auto" height="auto" border="0" align="center"  src="../../img/Atlas/verify your email.jpg"Verify your email"/><br>
###5. Enter some information like I have below and then Finish <br>
  <img width="auto" height="auto" border="0" align="center"  src="../../img/Atlas/welcome to Atlas.jpg" Welcome to Atlas"/>
###6. Select Create a cluster in <span style="background-color: #FFFF00">**Shared Clusters (FREE)**</span><br>
  <img width="auto" height="auto" border="0" align="center"  src="../../img/Atlas/deploy a could database free.jpg" title="Shared Clusters (FREE)"/>
###7. Leave all default values and click <span style="background-color: #FFFF00">**Create Cluster**</span><br>
  <img width="auto" height="auto" border="0" align="center"  src="../../img/Atlas/create shared clusters.jpg" title="Create Cluster"/><br>
  Atlas will create your default cluster, wait until it is complete... (can take more than 3 minutes) If not sure after a while click on the leaf icon in the top left!<br><br>
###8.  Click on <span style="background-color: #FFFF00">**CONNECT**</span><br>
    <img width="auto" height="auto" border="0" align="center"  src="../../img/Atlas/click on connect.jpg" title="click connect"/><br>
###9. Click on <span style="background-color: #FFFF00">**Allow Access from Anywhere**</span><br>
   <img width="auto" height="auto" border="0" align="center"  src="../../img/Atlas/Allow Access from Anywhere.jpg" title="Allow Access from Anywhere"/><br>
   <table width="1166" Height="185 border="1" style="border-color: #000000; background-color: #ffffff;" cellpadding="1" cellspacing="1" height="98">
<tbody>
<tr style="height: 16px;">
<td style="width: 1158px; border-color: #000000; background-color: #db4e12;" fff=""><span style="font-size: 14pt;"><strong><span style="color: #ffffff;">Note!</span></strong></span></td>
</tr>
<tr style="height: 56.4063px;">
<td style="width: 1158px; border-color: #000000;"><span style="font-family: tahoma, arial, helvetica, sans-serif; font-size: 14pt;">If you don't allow access from anywhere (IP 0.0.0.0/0) Nightscout will not be able to access your database.!<br></span></td>
</tr>
</tbody>
</table><br>
###10. Click on <span style="background-color: #FFFF00">**Add IP Address**</span><br>
   <img width="auto" height="auto" border="0" align="center"  src="../../img/Atlas/Add IP Address.jpg" title=" Click on Add IP Address"/><br>
<table width="1166" Height="185 border="1" style="border-color: #000000; background-color: #ffffff;" cellpadding="1" cellspacing="1" height="98">
<tbody>
<tr style="height: 16px;">
<td style="width: 1158px; border-color: #000000; background-color: #db4e12;" fff=""><span style="font-size: 14pt;"><strong><span style="color: #ffffff;">Note!</span></strong></span></td>
</tr>
<tr style="height: 56.4063px;">
<td style="width: 1158px; border-color: #000000;"><span style="font-family: tahoma, arial, helvetica, sans-serif; font-size: 14pt;">Database Details: Make sure to not use your Atlas account Account details. <br>Do not use special characters: only letters and numbers. No spaces.<br>
 </span></td>
</tr>
</tbody>
</table><br> 
###11. Add a database username (for example <span style="background-color: #FFFF00">**nightkai**</span>) and a database user password (in the my examples below <span style="background-color: #FFFF00">** Madeuppassword7**</span>) but please change it later, see both images below!!
    <img width="auto" height="auto" border="0" align="center"  src="../../img/Atlas/database username and a database password.jpg" title=" Add a database username and a database password, see both images below!"/><br>
###12. Then click <span style="background-color: #FFFF00">**Create Database User**</span>.<br>
   <img width="auto" height="auto" border="0" align="center"  src="../../img/Atlas/create database user.jpg" title=" Create Database User"/><br>
   <table width="1166" Height="185 border="1" style="border-color: #000000; background-color: #ffffff;" cellpadding="1" cellspacing="1" height="98">
<tbody>
<tr style="height: 16px;">
<td style="width: 1158px; border-color: #000000; background-color: #db4e12;" fff=""><span style="font-size: 14pt;"><strong><span style="color: #ffffff;">Note!</span></strong></span></td>
</tr>
<tr style="height: 56.4063px;">
<td style="width: 1158px; border-color: #000000;"><span style="font-family: tahoma, arial, helvetica, sans-serif; font-size: 14pt;">Make sure you write these details down in a safe place, you are going to need them later in the boxes below to make your Connection String!<br> <span style="background-color: #FFFF00">db user</span> and <span style="background-color: #FFFF00">db user password!</span></span></td>
</tr>
</tbody>
</table><br>
###13. Click on  <span style="background-color: #FFFF00">**Choose a Connection Method**</span><br>
   <img width="auto" height="auto" border="0" align="center"  src="../../img/Atlas/connection method.jpg" title=" connection method"/><br>
###14.  Now Select <span style="background-color: #FFFF00">**Connect your application**</span><br>
  <img width="auto" height="auto" border="0" align="center"  src="../../img/Atlas/Connect your application.jpg" title=" Connect your application"/><br>
###15. Copy the <span style="background-color: #FFFF00">**Connection string:**</span> click Copy icon and paste it somewhere to edit it later(like Notepad).
<img width="auto" height="auto" border="0" align="center"  src="../../img/Atlas/connection string.jpg" title=" connection string"/><br>
<table width="1166" Height="185 border="1" style="border-color: #000000; background-color: #ffffff;" cellpadding="1" cellspacing="1" height="98">
<tbody>
<tr style="height: 16px;">
<td style="width: 1158px; border-color: #000000; background-color: #db4e12;" fff=""><span style="font-size: 14pt;"><strong><span style="color: #ffffff;">Note! It should be similar to this - cluster0 (xxxxx) will be different):</span></strong></span></td>
</tr>
<tr style="height: 56.4063px;">
<td style="width: 1158px; border-color: #000000;"><span style="font-family: tahoma, arial, helvetica, sans-serif; font-size: 14pt;">mongodb+srv://nightkai:password@cluster0.xxxxx.mongodb.net/myFirstDatabase?retryWrites=true&w=majority<br>
 </span></td>
</tr>
</tbody>
</table><br><br>
###16. Makeup a name for your database, this is not a important information (example kdatabase ), note that default is <span style="background-color: #FFFF00">**myFirstDatabase**</span>. Only letters and numbers, no spaces.<br><br>
###17. I will try to give you an example about the way to do it below:


<br>
  ** A.** In the boxes below 1st is your Atlas Account you gave yourself a <span style="background-color: #FFFF00">**User Name**</span> add it to the box below User Name on the left side!
 <br>
   **B.** Then you also made a <span style="background-color: #FFFF00">**Database user Password add your Password** </span>you  created for your database add this too into the box on the left side.
<br>
   **C.** For the Cluster0 xxxxx where everyones will be unique when making a cluster when it is made so yours needs to be added into the Connection string part after it says Cluster0<br>
   **D.** And lastly you made up a <span style="background-color: #FFFF00">**Database Name** </span>, also add this to the last box on the left and click the <span style="background-color: #FFFF00">**Generate button**</span>  which will generate your <span style="background-color: #FFFF00">**connection string code**</span> that you will  need to add to your Heroku API
<br>
    <br>
####	**I have given you my examples below on the right side of the  boxes so just ignore them they are my examples to show you how the connection string is made up! **<br> You need to had your details into the left side Boxes making sure to remove (click here, delete and put your own!)first, and click on Generate.

</font>
<br><p>
<span style="background-color: #FFFF00">**username:**</span> <input type="text" id="username" value="click here, delete and put your own! " size="32">  Eg: username: <input type="text" id="egusername" value="nightkai" size="32"><br>

<span style="background-color: #FFFF00">**Database password:**</span> <input type="text" id="dbpassword" value="click here,delete and put your own!" size="31">Eg: Database password: <input type="text" id="egdbpassword" value="   Madeuppassword7" size="20"><br>
<br>
<span style="background-color: #FFFF00">**@cluster0:xxxxx**</span> <input type="text" id="@cluster" value="click here, delete and put your own! " size="32"> E.g: cluster0.xxxxx <input type="text" id="egdbname" value=" j2iil " size="20><br>output: <input type="text" id="output" value="click here, delete and put your own " size="32">

<br>
<span style="background-color: #FFFF00">**Database Name:**</span> <input type="text" id="dbname" value="click here, delete and put your own! " size="32"> E.g: Database Name: <input type="text" id="egdbname" value=" kdatabase " size="20><br>output: <input type="text" id="output" value="click here, delete and put your own " size="32"><br>

<br>
<p></p>

<button onclick="myFunction()">Generate</button><br><br><br><br>
<span style="background-color: #FFFF00">**mongodb+srv://**</span> <input type="text" id="field3"value="User Name">
: <input type="text" id="field4"value="Database Password">
@cluster0.<input type="text" id="field6"value="cluster0.xxxxx ">.mongodb.net/ <input type="text" id="field5"value="Database Name">?retryWrites=true&w=majority<br><br>

**E.** After you have generated it, yours should be looking somthing similar to the one below. Mine might be a little different to what yours should be so do check it carefully, and make sure to copy and paste it into notepad like I will show you in the video below<br>

### **My Connection String results**
<font size="+0"> **mongodb+srv://nightkai:Madeuppassword7@cluster0.j2iil.mongodb.net/kdatabase?retryWrites=true&w=majority**</font><br>

<img width="auto" height="auto" border="0" align="center"  src="../../img/Atlas/how to make connection string.jpg" title="My Connection String results"/>
<table width="1266" Height="120 border="1" style="border-color: #000000; background-color: #ffffff;" cellpadding="1" cellspacing="1" height="98">
<tbody>
<tr style="height: 16px;">
<td style="width: 1158px; border-color: #000000; background-color: #FF0000;" fff=""><span style="font-size: 14pt;"><strong><span style="color: #ffffff;">Warning!</span></strong></span></td>
</tr>
<tr style="height: 56.4063px;">
<td style="width: 1158px; border-color: #000000;"><span style="font-family: tahoma, arial, helvetica, sans-serif; font-size: 14pt;"> Keep this string safely aside, it is called your MONGODB_URI<br/>  </span></td>
</tr>
</tbody>
</table><br>



<script>
function myFunction() {
  document.getElementById("field3").value = document.getElementById("username").value;
  document.getElementById("field4").value = document.getElementById("dbpassword").value;
  document.getElementById("field5").value = document.getElementById("dbname").value;
  document.getElementById("field6").value = document.getElementById("@cluster").value;
  
}
</script><br><br>


<table width="1166" Height="485 border="1" style="border-color: #000000; background-color: #ffffff;" cellpadding="1" cellspacing="1" height="98">
<tbody>
<tr style="height: 16px;">
<td style="width: 1158px; border-color: #000000; background-color: #5B9BD5;" fff="" ><span style="font-size: 14pt;"><span style="color: #ffffff; ">video demo of getting connection string,</span></span></td>
</tr>
<tr style="height: 56.4063px;">
<td style="width: 1158px; border-color: #000000;"><span style="font-family: tahoma, arial, helvetica, sans-serif; font-size: 14pt;">
 <iframe id="video3" width="860" height="615" src="https://www.youtube.com/embed/iYnNddVSbzY?start=19" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</tr>
</tbody>
</table><br>











****************************************************************************************
   
   a) If you want to do it manually: replace <password> with your database password as noted previously (in the example below **Madeuppassword7** ) and <dbname> by any text you want to add as your **database name**, say kdatabase in my example. The result will be like this:<br>
 <img width="auto" height="auto" border="0" align="center"  src="../../img/Atlas/how to make connection string.jpg" title="My Connection String results"/>


### ** Another example for you below!** 
<img width="auto" height="auto" border="0" align="center"  src="../../img/Fork and Deploy cgm remote monitory Part 4/connecting_to_cluster.jpg" title="connecting_to_cluster"/>
<table width="1166" Height="185 border="1" style="border-color: #000000; background-color: #ffffff;" cellpadding="1" cellspacing="1" height="98">
<tbody>
<tr style="height: 16px;">
<td style="width: 1158px; border-color: #000000; background-color: #5B9BD5;" fff=""><span style="font-size: 14pt;"><strong><span style="color: #ffffff;">Note!</span></strong></span></td>
</tr>
<tr style="height: 56.4063px;">
<td style="width: 1158px; border-color: #000000;"><span style="font-family: tahoma, arial, helvetica, sans-serif; font-size: 14pt;" " target="_blank" title="First create a user account by going to">There are no < and > characters in the final string, neither for password nor for database name.</span></span></td>
</tr>
</tbody>
</table><br>
## <center>Now we need to do <br></center>
<br>
# <center>Part 4: <a href="https://atlas-night-out.github.io/my-project/user-guide/Fork_and_Deploy_cgm_remote_monitory_part4/" target="_blank" title="Fork and Deploy cgm remote monitory Part 4">Fork and Deploy cgm remote monitory</a> </center>
<br><br>
<a href="https://www.diabetes.org.uk/" target="_blank">
  <img width="auto" height="auto" border="0" align="center"  src="/my-project/img/Diabetesuk/pngarea.com_rutgers-logo-png-8467605.png" title="Diabetes UK"/>
</a>               Why Not take visit [UK Wide Cycle Ride - Diabetes.uk](https://cycle.diabetes.org.uk/) <span style="background-color: #FFFF00">**or**</span>  [Swim22 - Diabetes.uk](https://swim22.diabetes.org.uk/) <span style="background-color: #FFFF00">**or**</span> [Month of Miles - Diabetes.uk](https://monthofmiles.diabetes.org.uk/?gclid=CjwKCAjwz5iMBhAEEiwAMEAwGO2_OoOGRQdN3BDD3NUQ8WoYAsJsxd1YUJN8dSVJowD1E4AjJ1RdVxoC9bgQAvD_BwE) for all of your Diabetes Needs!<br><br>





 


  <!--  
  ****************************************************************************************************************
  remove this after you finish it!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
  
  ##Step 4: Fork and deploy cgm-remote-monitor
   
<br>   
   1.  You should now have 3 pages opened in your browser: Heroku, Atlas, and Github, Make sure you are logged-in on each one (i.e. not asking you to login) before you continue.
   
   2.  Click this link https://github.com/nightscout/cgm-remote-monitor, a new GitHub page will open. Click on Fork
   
   3. d) Scroll down and click Deploy to Heroku
   
   
   4. Enter your CGM in the Cloud site name: invent a name you will use to see your BG in the cloud. Confirm that the name is available.
   
   5.  Don’t change the region.
   
   6. Scroll down and setup the following variables:
   
   7. API_SECRET will be your Nightscout site password, it needs to be at least 12 characters long and you should NOT use spaces if you use @ or ! symbols remember you will probably need to express them using Percent encoding in your uploader and downloader apps. If you're not sure on how to do this, it is recommended to use only letters (uppercase + lowercase) and digits.
   
   8. If you want to link your Dexcom Share account as a data source, complete the following lines:
   
   9. If you want to link your CareLink account as a data source (currently not functional with Heroku), complete the following lines:
   
   10. Select the units you’re using in DISPLAY_UNITS acceptable choices are mg/dl or mmol/L (or just mmol).


11. In ENABLE, copy and paste the following words (separated by a space) so that won't have to think about which you want now:
12. Now you need the connection string you defined during the Atlas cluster creation (as the example below, but not the string below). Copy and paste it in the MONGODB_URI variable field.

If you compiled all the fields and successfully generated the string this is what you should copy in MONGODB_URI:

Sorry... something is missing for me to make it automatically...

13. If you preferred to make it yourself, make sure it looks like this:
mongodb+srv://nightscout:soo5ecret@cluster0.xxxxx.mongodb.net/mycgmic?retryWrites=true&w=majority


14. Scroll down to the end of the list and click Deploy app

15.  WAIT until completion (will take some time). Do not interrupt the process until it's complete.

16. Then click View (if nothing happens, click Manage App -> Open App, in upper right corner)

17. Your Nightscout site should open and direct you to a new profile creation.

18. Setup your Time zone and eventually all other fields. Do not leave any fields empty. If you don't know which value to use, just use the default value. You can change these values later at any time.

19. Browse down to Authentication status and click Authenticate. Enter your API secret. Click Update.


20. Click Save.

21.  If the following pop-up shows up click OK, and check status (upper right of the window).

22. If you need to modify your profile after this, authenticate with the lock icon (top right of the page): enter your API secret. Then click on the hamburger menu and select Profile Editor.

23. Dexcom Share and CareLink users should see data flowing in after some minutes. Other uploaders like xDrip+, Spike, xDrip4iOS, etc will need to be setup with the Nightscout address and API secret in the app.
   
   
   
   
</font>
 

Check what version you are upto on your Nightscout site. In my example I'm on version  14.06 (Liquorice)

<table width="1166" border="1" style="border-color: #000000; background-color: #ffffff;" cellpadding="1" cellspacing="1" height="98">
<tbody>
<tr style="height: 16px;">
<td style="width: 1158px; border-color: #000000; background-color: #5B9BD5;" fff=""><span style="font-size: 14pt;"><span style="color: #ffffff;">Note! video, see below</span></span></td>
</tr>
<tr style="height: 56.4063px;">
<td style="width: 1158px; border-color: #000000;"><span style="font-family: tahoma, arial, helvetica, sans-serif; font-size: 14pt;">
<iframe width="850" height="415" src="https://www.youtube.com/embed/MFsbm45b6YY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>  </span></td>
</tr>
</tbody>
</table>



Updating your website to the latest version
 <a href="https://github.com/nightscout/cgm-remote-monitor/releases" target="_blank" title="Nightscout Release Versions">See Here</a> for the 
 current released version at moment) is easy with the update tool linked below. 
  
  
  
  
  
  
  
  
  
  ********************************************************************************************************************************
  mkdocs.yml    # The configuration file.
    docs/
    index.md  # The documentation homepage.
       ...       # Other markdown pages, images and other files.
		
		
	**************************
  Links
  ******************************	
<a href="http://nightscout.github.io/pages/update-fork/" target="_blank">
  <img width="auto" height="auto" border="0" align="center"  src="/img/Nightscout/Time to Update Nightscout.png" title="Update Tool"/></a>		
		

*******************		
external link
******************

# <center>Part 4: <a href="https://atlas-night-out.github.io/my-project/user-guide/Fork_and_Deploy_cgm_remote_monitory_part4/" target="_blank" title="Fork and Deploy cgm remote monitory Part 4">Fork and Deploy cgm remote monitory</a> </center>




adding 	Yellow Hightligher!!!!!!!!	
<span style="background-color: #FFFF00">**Marked text**</span>


***********************
adding an image
***********************

  <a><img width="auto" height="auto" border="0" align="center"  src="/img/Nightscout/Time to Update Nightscout.png" title="Update Tool"/></a>	




<a href="https://www.youtube.com/watch?v=MFsbm45b6YY" target="_blank">
  <img width="auto" height="auto" border="0" align="center"  src="/img/Nightscout/nightscout version_14.06.jpg" title="Version of Nightscout Video"/>
</a>

*******************************************************************************
Adding Video

<iframe width="850" height="415" src="https://www.youtube.com/embed/MFsbm45b6YY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Note
**Note:** a note is something that needs to be mentioned but is apart from the context.


List
This is a regular paragraph.

Paragraph:

1. **Now Open another tab**  to make a Mongodb Atlas** Account: <a href="https://www.mongodb.com/cloud/atlas" target="_blank" title="Click Start Free">See Here</a> 
  and **click** Start Free
 <img width="auto" height="auto" border="0" align="center"  src="/img/Atlas/MongoDB Atlas start free.jpg"Click Start"/>
   2. Sub item two
   3. Sub item three
2. Item two



font size
<font size="4">

</font>

*******************************
orange table

<table width="1166" border="1" style="border-color: #000000; background-color: #ffffff;" cellpadding="1" cellspacing="1" height="98">
<tbody>
<tr style="height: 16px;">
<td style="width: 1158px; border-color: #000000; background-color: #db4e12;" fff=""><span style="font-size: 14pt;"><strong><span style="color: #ffffff;">Note!</span></strong></span></td>
</tr>
<tr style="height: 56.4063px;">
<td style="width: 1158px; border-color: #000000;"><span style="font-family: tahoma, arial, helvetica, sans-serif; font-size: 14pt;">If you’re on Heroku and have Automatic Deploys enabled, you’re done!<br>
 If you don’t have Automatic Deploys on yet, or aren’t sure, run through these steps below!</span></td>
</tr>
</tbody>
</table>
***************************************
red warning table
***************************
<table width="1266" border="1" style="border-color: #000000; background-color: #ffffff;" cellpadding="1" cellspacing="1" height="98">
<tbody>
<tr style="height: 16px;">
<td style="width: 1158px; border-color: #000000; background-color: #FF0000;" fff=""><span style="font-size: 14pt;"><strong><span style="color: #ffffff;">Warning!</span></strong></span></td>
</tr>
<tr style="height: 56.4063px;">
<td style="width: 1158px; border-color: #000000;"><span style="font-family: tahoma, arial, helvetica, sans-serif; font-size: 14pt;"> 1: Some new features, updates, or bug fixes may require that you clear your browser cache before you will see the changes taken effect<br/> 2: If you get no errors and no readings after a while see about doing a <a href="http://127.0.0.1:8000/user-guide/Redeploying%20your%20repository/" target="_blank" title="Redeploying your repository link">Redeploying your repository</a> </span></td>
</tr>
</tbody>
</table>




*******************************
Table
| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |


-->

