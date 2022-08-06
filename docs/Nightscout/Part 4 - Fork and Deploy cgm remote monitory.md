<!-- this is not on github server its local only and run my mkdocs server!
docs made by D.Galloway 2019- 2021-->
# Welcome to The Diabetic way
For full Website content visit [The Diabetic Way](https://www.thediabeticway.co.uk/index.php/en/).
<br>
<br>
<br>
<img width="auto" height="auto" border="0" align="center"  src="../../img/Fork and Deploy cgm remote monitory Part 4/Fork_and_Deploy_cgm_remote_monitory_Part_4t_860x462.jpg" Setting up Atlas Part 3"/>

## **Part 4 - Fork and Deploy cgm remote monitory  **<br><br>
## If you would like to follow these instructions with video then see below other wise continue step by step below<br>
<br>

<table width="1166" height="560" border="1" style="border-color: #000000; background-color: #ffffff;" cellpadding="1" cellspacing="1" height="98">
<tbody>
<tr style="height: 16px;">
<td style="width: 1158px; border-color: #000000; background-color: #5B9BD5;" fff=""><span style="font-size: 14pt;"><span style="color: #ffffff;">video Instructions,</span></span></td>
</tr>
<tr style="height: 56.4063px;">
<td style="width: 1158px; border-color: #000000;"><span style="font-family: tahoma, arial, helvetica, sans-serif; font-size: 14pt;">
 <iframe id="video3" width="860" height="615" src="https://www.youtube.com/embed/mEilmCDz1pc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> </span></td>
</tr>
</tbody>
</table><br>

<table width="1166" height="180" border="1" style="border-color: #000000; background-color: #ffffff;" cellpadding="1" cellspacing="1" height="98">
<tbody>
<tr style="height: 16px;">
<td style="width: 1158px; border-color: #000000; background-color: #db4e12;" fff=""><span style="font-size: 14pt;"><strong><span style="color: #ffffff;">Note!</span></strong></span></td>
</tr>
<tr style="height: 56.4063px;">
<td style="width: 1158px; border-color: #000000;"><span style="font-family: tahoma, arial, helvetica, sans-serif; font-size: 14pt;">If you have already forked your  cgm-remote-monitor, before reaching this stage, you should delete the existing cgm-remote-monitor repository before proceeding.<br>
Delete your current cgm-remote-monitor fork using (<a href="  https://atlas-night-out.github.io/my-project/user-guide/Deleting-your-cgm-remote-monitor/" target="_blank" title="Video showing you how to delete your cgm-remote-monitor">Video STEP</a>!).</span></td><br>
</tr>
</tbody>
</table>
 
<br>  
<font size="4"> 
###1. Hopfully you should now have 3 pages opened in your browser: <span style="background-color: #FFFF00">**Heroku, Atlas, and Github,**</span> Make sure you are logged-in on each one (<span style="background-color: #FFFF00">**i.e. important**</span>) before you continue.

###2.  <a href="https://github.com/nightscout/cgm-remote-monitor" target="_blank" title="Nightscout Release Versions">Click Here</a> or goto https://github.com/nightscout/cgm-remote-monitor, to open a new GitHub page. Click the on <span style="background-color: #FFFF00">**Fork**</span> icon in the top right
   <img width="auto" height="auto" border="0" align="center"  src="../../img/Fork and Deploy cgm remote monitory Part 4/1_fork.jpg"/>

###3. Wait for a moment
  <img width="auto" height="auto" border="0" align="center"  src="../../img/Fork and Deploy cgm remote monitory Part 4/forking.jpg" title="WAIT until compleate"/>
</a>
   
###3.1. Scroll down the page and click <span style="background-color: #FFFF00">**Deploy to Heroku**</span> 
   <img width="auto" height="auto" border="0" align="center"  src="../../img/Fork and Deploy cgm remote monitory Part 4/Deploy_to_Heroku.jpg"title="This deploys to Heroku Account"/>
   
###4. Enter in your Heroku account a site name: invent a name you would like to use or see your BG in on the internet. Confirm that the name is available.
 <img width="auto" height="auto" border="0" align="center"  src="../../img/Fork and Deploy cgm remote monitory Part 4/site_name.jpg"title="Give yourself a App name"/>
 
###5.  Don’t change the region.

###6. <span style="background-color: #FFFF00">**Scroll down**</span> and setup the following variables: You can come back to these later later by going to settings and config Vars Enable in Heroku!
<img width="auto" height="auto" height="215" border="0" align="center"  src="../../img/Fork and Deploy cgm remote monitory Part 4/API_SECRET_Required2.jpg"title="Give yourself a API Secret Passwod"/>
     <iframe width="800" height="415" src="https://www.youtube.com/embed/65KI5-3E_XM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
	 

<table width="1166" height="215" border="1" style="border-color: #000000; background-color: #ffffff;" cellpadding="1" cellspacing="1" height="98">
<tbody>
<tr style="height: 16px;">
<td style="width: 1158px; border-color: #000000; background-color: #db4e12;" fff=""><span style="font-size: 14pt;"><strong><span style="color: #ffffff;">Note!</span></strong></span></td>
</tr>
<tr style="height: 56.4063px;">
<td style="width: 1158px; border-color: #000000;"><span style="font-family: tahoma, arial, helvetica, sans-serif; font-size: 14pt;">The API_SECRET is the main password allowing full access to your Nightscout site. Make sure its secure (mix upper and lowercase letters, plus digits) and do no not share it publicly. If you think you exposed it by mistake, it is recommended that you change it. </span></td><br>
</tr>
</tbody>
</table>

###7. <span style="background-color: #FFFF00">**API_SECRET**</span> will be your Nightscout site password, it needs to be at least 12 characters long and <span style="background-color: #FFFF00">**you should NOT use spaces if you use @ or ! symbol you should NOT use spaces if you use @ or ! symbols**</span> remember you will probably need to express them using Percent encoding in your uploader and downloader apps. If you're not sure on how to do this, it is recommended to <span style="background-color: #FFFF00">**use only letters (uppercase + lowercase) and digits**</span>.
<img width="auto" height="auto" border="0" align="center"  src="../../img/Fork and Deploy cgm remote monitory Part 4/API_SECRET_Required1.jpg"title="Give yourself a API Secret Passwod"/><br>
###8. If you <span style="background-color: #FFFF00">**want to link your Dexcom Share account**</span> as a data source, complete the following 3 lines:
<img width="auto" height="auto" border="0" align="center"  src="../../img/Fork and Deploy cgm remote monitory Part 4/bridge_for_Dexcom_share.jpg"title=" Link your Dexcom Share Account "/><br>
<table width="1166" height="390" border="1" style="border-color: #000000; background-color: #ffffff;" cellpadding="1" cellspacing="1" height="98">
<tbody>
<tr style="height: 16px;">
<td style="width: 1158px; border-color: #000000; background-color: #FF0000;" fff=""><span style="font-size: 14pt;"><strong><span style="color: #ffffff;">Warning!  Common Errors</span></strong></span></td>
</tr>
<tr style="height: 56.4063px;">
<td style="width: 1158px; "350 border-color: #000000;><span style="font-family: tahoma, arial, helvetica, sans-serif; font-size: 14pt;">MOST COMMON ERRORS

The BRIDGE_PASSWORD and BRIDGE_USER_NAME are NOT visible from within your Dexcom app or online account. These values are what you entered into your Dexcom mobile app when you logged into that app for the VERY FIRST time. The BRIDGE_USER_NAME is not an email address. The most common error on initial Nightscout setups is that people incorrectly use an old account or an old password. To test your username and password, go to Dexcom's Clarity page (check here <a href="https://clarity.dexcom.com/" target="_blank" title="Dexcom USA Account">See Here</a> for USA accounts and <a href="https://clarity.dexcom.eu/" target="_blank" title="Dexcom EU Account"> Here</a> here for the others) and try logging in to your Dexcom account. If your account info isn't valid, or you don't see any data in your Clarity account... you need to figure out your actual credentials before moving ahead.
</span></td>
</tr>
</tbody>
</table><br>
###9. If you want to link your <span style="background-color: #FFFF00">**Care Link account**</span> as a data source (currently not functional with Heroku), complete the following lines:<br>
<img width="auto" height="auto" border="0" align="center"  src="../../img/Fork and Deploy cgm remote monitory Part 4/mmconnect.jpg"title="Care Link Account"/><br>
###10. Select the units you’re using in <span style="background-color: #FFFF00">**DISPLAY_UNITS**</span> the acceptable choices are <span style="background-color: #FFFF00">**mg/dl or mmol/L**</span> (or just <span style="background-color: #FFFF00">**mmol**</span> when entering it).
<img width="auto" height="auto" border="0" align="center"  src="../../img/Fork and Deploy cgm remote monitory Part 4/display_units.jpg"title="Display Units"/><br>
In <span style="background-color: #FFFF00">**my case I used mmol**</span> <img width="auto" height="auto" border="0" align="center"  src="../../img/Fork and Deploy cgm remote monitory Part 4/display_unit_EU.jpg"title="Display Units"/><br>
## Plugins <br>

###11.    In <span style="background-color: #FFFF00">**ENABLE,**</span> copy and paste the following Plugins below <span style="background-color: #FFFF00">**(separated by a space)**</span> so that won't have to think about which you want now and learn the rest later!<br><br>
**Plugins I added to config var Enable**<br>
<img width="auto" height="auto" border="0" align="center"  src="../../img/Fork and Deploy cgm remote monitory Part 4/enable.jpg"title="Plugins you can add to enable"/><br>
 **Plugins I added**<br>
careportal basal dbsize rawbg iob maker cob bwp cage iage sage boluscalc pushover treatmentnotify loop pump profile food openaps bage alexa override speech cors<br>
<table width="1166" padding="0.35rem" border="1" style="border-color: #000000; background-color: #ffffff;" cellpadding="0" cellspacing="0" height="0">
<tbody>
<tr style="height: 0px;">
<td style="width: 1158px; border-color: #000000; background-color: #5B9BD5;" fff=""><span style="font-size: 14pt;"><strong><span style="color: #ffffff;">Enable Words</span></strong></span></td>
</tr>
<tr style="height: 0px;">
<td style="width: 1158px; border-color: #000000;"><span style="font-family: tahoma, arial, helvetica, sans-serif; font-size: 14pt;">You will find more information about the ENABLE on the: Nightscout Plugin Page <a href="http://127.0.0.1:8000/user-guide/Nightscout_Plugins/" target="_blank" title="Nightscout Plugin link">Here</a> </span></td>
</tr>
</tbody>
</table><br>
<table width="1166" height="210" border="1" style="border-color: #000000; background-color: #ffffff;" cellpadding="1" cellspacing="1" height="98">
<tbody>
<tr style="height: 16px;">
<td style="width: 1158px; border-color: #000000; background-color: #db4e12;" fff=""><span style="font-size: 14pt;"><strong><span style="color: #ffffff;">Note!</span></strong></span></td>
</tr>
<tr style="height: 56.4063px;">
<td style="width: 1158px; border-color: #000000;"><span style="font-family: tahoma, arial, helvetica, sans-serif; font-size: 14pt;">If you are using your Dexcom share account as a data source add a bridge at the end of your plugins, after a space like this: careportal basal dbsize rawbg iob maker cob bwp cage iage sage boluscalc pushover treatmentnotify loop pump profile food openaps bage alexa override speech cors bridge
<span style="background-color: #FFFF00">bridge</span><br></span></td>
</tr>
</tbody>
</table><br>
###12. Now you need the <span style="background-color: #FFFF00">**connection string**</span> you defined during the <span style="background-color: #FFFF00">**Atlas cluster creation - Part 3**</span> (as the example below, but not the string below). Copy and paste your! results into the MONGODB_URI variable field in Heroku vars.<br><br>
 <img width="auto" height="auto" border="0" align="center"  src="../../img/Fork and Deploy cgm remote monitory Part 4/mongo_uri.jpg" title="Mongo_URI"/></a>	
###13. I will try to give you an example about the way to do it again below, you can also see my video if you get stuck!


<br>
  ** A.** In the boxes below 1st is your Atlas Account you gave yourself a <span style="background-color: #FFFF00">**User Name**</span> add it to the box below User Name on the left side!
 <br>
   **B.** Then you also made a <span style="background-color: #FFFF00">**Database user Password add your Password** </span>you  created for your database add this too into the box on the left side.
<br>
   **C.** And lastly you made up a <span style="background-color: #FFFF00">**Database Name** </span>, also add this to the last box on the left and click the <span style="background-color: #FFFF00">**Generate button**</span>  which will generate your <span style="background-color: #FFFF00">**connection string code**</span> that you will  need to add to your Heroku API
<br>
    <br>
####	**I have given you my examples below on the right side of the  boxes so just ignore them they are my examples to show you how the connection string is made up! **

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
<br />
**D.** After you have generated it, yours should look similar to the one below mine might be a little different to what yours should be so do check it carefully, and make sure to copy and paste it into notepad like I show you in the video below<br>
 
<span style="background-color: #FFFF00">**mongodb+srv://**</span> <input type="text" id="field3"value="User Name">
: <input type="text" id="field4"value="Database Password">
@cluster0.<input type="text" id="field6"value="cluster0.xxxxx ">.mongodb.net/ <input type="text" id="field5"value="Database Name">?retryWrites=true&w=majority<br><br>

### **My Connection String results**
<font size="+0"> **mongodb+srv://nightkai:Madeuppassword7@cluster0.j2iil.mongodb.net/kdatabase?retryWrites=true&w=majority**</font><br>

<img width="auto" height="auto" border="0" align="center"  src="../../img/Atlas/how to make connection string.jpg" title="Update Tool"/><br>
<table width="1266" height="120"border="1" style="border-color: #000000; background-color: #ffffff;" cellpadding="1" cellspacing="1" height="98">
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


<table width="1166" height="560" border="1" style="border-color: #000000; background-color: #ffffff;" cellpadding="1" cellspacing="1" height="98">
<tbody>
<tr style="height: 16px;">
<td style="width: 1158px; border-color: #000000; background-color: #5B9BD5;" fff="" ><span style="font-size: 14pt;"><span style="color: #ffffff; ">video demo of getting connection string,</span></span></td>
</tr>
<tr style="height: 56.4063px;">
<td style="width: 1158px; border-color: #000000;"><span style="font-family: tahoma, arial, helvetica, sans-serif; font-size: 14pt;">
 <iframe id="video3" width="860" height="615" src="https://www.youtube.com/embed/iYnNddVSbzY?start=19" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>  </span></td>
</tr>
</tbody>
</table><br>
###14. Once you have added your Connection string into the MongoDB_Uri. Scroll down to the bottom of the Config var list and click the <span style="background-color: #FFFF00">**Deploy APP**</span><br>
You will WAIT until a while for them completion. Do not stop  the process until it's complete.
<img width="auto" height="auto" border="0" align="center"  src="../../img/Fork and Deploy cgm remote monitory Part 4/select deploy app.jpg" title="Select the Deploy Button"/></a>	<br>
###15.  click the  <span style="background-color: #FFFF00">**View button**</span> and it should come up (if not, then click the Manage App -> Open App, in the top right corner)<br>
<img width="auto" height="auto" border="0" align="center"  src="../../img/Fork and Deploy cgm remote monitory Part 4/click view.jpg" title="click the view button"/></a>	<br>
###16. Your Nightscout site  should open and direct you to fill in profile editor for Nightscout.<br>
<img width="auto" height="auto" border="0" align="center"  src="../../img/Fork and Deploy cgm remote monitory Part 4/profile editor.jpg" title="Nightscout profile editor"/></a>	<br>
###17. All you need to fill in at this moment in time is your <span style="background-color: #FFFF00">**Time zone**</span> and eventually all the other fields e.g. Insulin to carbs. Make sure to not leave any fields empty. If you don't understand which value to use, just use the <span style="background-color: #FFFF00">**default value**</span>.<br>
**a.** You can come back and change these values later at any time by going to your  Nightscout URL selecting the <span style="background-color: #FFFF00">**Hamberger icon**</span> on the right and selecting <span style="background-color: #FFFF00">**profile editor**</span>.<br>
<img width="auto" height="auto" border="0" align="center"  src="../../img/Fork and Deploy cgm remote monitory Part 4/getting to nightscout profile editor.jpg" title="Getting to your Nightscout profile editor"/></a>	<br>
###18. You will then need to go down to <span style="background-color: #FFFF00">**Authentication Status**</span> on the left and click Authentication.  And enter your <span style="background-color: #FFFF00">**Heroku API secret**</span> you made earlier. Then click <span style="background-color: #FFFF00">**Authenticate button**</span>, Then <span style="background-color: #FFFF00">**save**</span>.
<img width="auto" height="auto" border="0" align="center"  src="../../img/Fork and Deploy cgm remote monitory Part 4/Authentication.jpg" title="Authentication"/><img width="auto" height="auto" border="0" align="center"  src="/my-project/img/Fork and Deploy cgm remote monitory Part 4/Api secret image.jpg" title="Look in Heroku - Settings -  Reveal config Vars for API_SECRET"/><img width="auto" height="auto" border="0" align="center"  src="/my-project/img/Fork and Deploy cgm remote monitory Part 4/save.jpg" title="Save it image"/></a>	<br>
<table width="auto" Height="185 border="1" style="border-color: #000000; background-color: #ffffff;" cellpadding="1" cellspacing="1" height="98">
<tbody>
<tr style="height: 16px;">
<td style="width: 1158px; border-color: #000000; background-color: #db4e12;" fff=""><span style="font-size: 14pt;"><strong><span style="color: #ffffff;">Your Privacy warning!</span></strong></span></td>
</tr>
<tr style="height: 56.4063px;">
<td style="width: 1158px; border-color: #000000;"><span style="font-family: tahoma, arial, helvetica, sans-serif; font-size: 14pt;">Anyone with your URL of your Nightscout site, can view your values and run reports of your data. It is recommended that you enable <a href="http://127.0.0.1:8000/user-guide/Nightscout%20Safety%20Check/" target="_blank" title="Best to set security to your nightscout">security</a> to your site once you're done this setup.<br></span></td>
</tr>
</tbody>
</table><br>
###19. Dexcom Share and CareLink users should see data working after a few minutes. <br>Other uploaders like <span style="background-color: #FFFF00">**xDrip+**</span>, <span style="background-color: #FFFF00">**Spike**</span>, xDrip4iOS, Gimp,Tomato etc will need to be setup with a Nightscout address and API secret in each Apps settings (<a href=" https://github.com/" target="_blank" title="see uploaders">See Uploaders</a>).<br><br><br>
## Nightscout Address for your Uploader Apps<br>
<img width="auto" height="auto" border="0" align="center"  src="../../img/Fork and Deploy cgm remote monitory Part 4/Nightscout Address.jpg" title="Nightscout Address for your Uploader Apps"/></a><br>
## PAPERTRAIL<br>
**a.** Lastly, you might want to change the PAPERTRAIL_API_TOKEN line. Heroku gives you a free, tiny amount of Papertrail service (this is like a logging service for how the site is running), but this generates a lot of confusion to most people later on.<br> when they get a message that their "Free Papertrail Service has run out of room". Papertrail is not needed at all, edit the line with the pensil icon and add <span style="background-color: #FFFF00">** DISABLED**</span> at the end, so that you can recover the function if you need it later.<br><br>
<img width="auto" height="auto" border="0" align="center"  src="../../img/Fork and Deploy cgm remote monitory Part 4/PAPERTRAIL_DISABLED.jpg" title="PAPERTRAIL has been Disabled"/><br>
<br><br>
<img width="auto" height="auto" border="0" align="center"  src="../../img/Fork and Deploy cgm remote monitory Part 4/Nightscout.jpg" title="Nightscout All setup and working"/><br><br>

<font size="6"> <center>**Congratulations Nightscout is now setup!**</center><br><br></font><br><br>

## **Enable Auto Deploys in Heroku**<br><br>
Automatic deploys will allow you to update routinely your Heroku apps when you renew the GitHub repository.
You will then not need to login into Heroku and execute Manual Deploy, as soon as do a new version of the repo be merged into GitHub an automatic deploy will trigger in all enabled Heroku apps.

a)	To allow automatic deploy, log in Heroku and select your app, in my case diabeticway and then selecting the <span style="background-color: #FFFF00">**Deploy section**</span>.<br>
b)	 Select <span style="background-color: #FFFF00">**Connect to Github**</span><br>
<img width="auto" height="auto" border="0" align="center"  src="../../img/Fork and Deploy cgm remote monitory Part 4/Deploy heroku.jpg" title="Go to Deploy Section"/></a>	<br>
c) Authenticate GitHub and your cgm-remote-monitor app are now connected.
<img width="auto" height="auto" border="0" align="center"  src="../../img/Fork and Deploy cgm remote monitory Part 4/connect to github.jpg" title="Authenticate GitHub"/></a>	<br>
d) Click on <span style="background-color: #FFFF00">**search**</span> and add your repo name, it will then connect to Github<br>
<img width="auto" height="auto" border="0" align="center"  src="../../img/Fork and Deploy cgm remote monitory Part 4/search.jpg" title="search"/></a><br>
<img width="auto" height="auto" border="0" align="center"  src="../../img/Fork and Deploy cgm remote monitory Part 4/repo name.jpg" title="your repo name"/></a><br>
e) Verify the master branch is selected and click <span style="background-color: #FFFF00">**Enable Automatic Deploys**</span>.
<img width="auto" height="auto" border="0" align="center"  src="../../img/Fork and Deploy cgm remote monitory Part 4/Verify the master branch.jpg" title="Enable Automatic Deploys"/></a>	<br>
f) Your site will <span style="background-color: #FFFF00">**update automatically**</span> every time you update the GitHub repository now.<br><br>
<img width="auto" height="auto" border="0" align="center"  src="../../img/Fork and Deploy cgm remote monitory Part 4/Verify the master branch_2.jpg" title="Verify the master branch"/></a>	<br>

<a href="https://www.diabetes.org.uk/" target="_blank">
 <img width="auto" height="auto" border="0" align="center"  src="../../img/Diabetesuk/pngarea.com_rutgers-logo-png-8467605.png" title="Diabetes UK"/>
</a>               Why Not take visit [UK Wide Cycle Ride - Diabetes.uk](https://cycle.diabetes.org.uk/) <span style="background-color: #FFFF00">**or**</span>  [Swim22 - Diabetes.uk](https://swim22.diabetes.org.uk/) <span style="background-color: #FFFF00">**or**</span> [Month of Miles - Diabetes.uk](https://monthofmiles.diabetes.org.uk/?gclid=CjwKCAjwz5iMBhAEEiwAMEAwGO2_OoOGRQdN3BDD3NUQ8WoYAsJsxd1YUJN8dSVJowD1E4AjJ1RdVxoC9bgQAvD_BwE) for all of your Diabetes Needs!



   
   
</font>
 








  <!--  
  ******************************************************************************************************************
  mkdocs.yml    # The configuration file.
    docs/
    index.md  # The documentation homepage.
       ...       # Other markdown pages, images and other files.
		
		
		
<a href="http://nightscout.github.io/pages/update-fork/" target="_blank">
  <img width="auto" height="auto" border="0" align="center"  src="/img/Nightscout/Time to Update Nightscout.png" title="Update Tool"/></a>		
		
		
adding 	Yellow Hightligher!!!!!!!!	with bold too
<span style="background-color: #FFFF00">**Marked text**</span>


link
<a href=" https://github.com/" target="_blank" title="First create a user account by going to">Click Here</a>

  <img width="auto" height="auto" border="0" align="center"  src="/img/Fork and Deploy cgm remote monitory Part 4/warning_sign.png" title="Update Tool"/></a>	

<img width="30" height="30" src="/img/Fork and Deploy cgm remote monitory Part 4/clipart2068155.png">

Adding a image with link
<a href="https://www.youtube.com/watch?v=MFsbm45b6YY" target="_blank">
  <img width="auto" height="auto" border="0" align="center"  src="/img/Part 1 Setting up Github 2021/Github account details.jpg" title="github account details"/>
</a><br>


Adding Video

<iframe width="850" height="415" src="https://www.youtube.com/embed/MFsbm45b6YY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


Adding an embeded video
<iframe id="video3" width="560" height="315" src="https://www.youtube.com/embed/o7-T2IrDJ_A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


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

link
<a href=" https://github.com/" target="_blank" title="First create a user account by going to">Click Here</a>

*******************************************************************************************************************************
*******************************
orange table

<table width="auto" border="1" style="border-color: #000000; background-color: #ffffff;" cellpadding="1" cellspacing="1" height="98">
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




Table
| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |


Video in a box border!

<table width="1166" border="1" style="border-color: #000000; background-color: #ffffff;" cellpadding="1" cellspacing="1" height="98">
<tbody>
<tr style="height: 16px;">
<td style="width: 1158px; border-color: #000000; background-color: #5B9BD5;" fff=""><span style="font-size: 14pt;"><span style="color: #ffffff;">video Instructions,</span></span></td>
</tr>
<tr style="height: 56.4063px;">
<td style="width: 1158px; border-color: #000000;"><span style="font-family: tahoma, arial, helvetica, sans-serif; font-size: 14pt;">
 <iframe id="video3" width="860" height="515" src="https://www.youtube.com/embed/6o3AdkQBVog" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>  </span></td>
</tr>
</tbody>
</table>
*****************************************************
Warning Note<table width="1266" border="1" style="border-color: #000000; background-color: #ffffff;" cellpadding="1" cellspacing="1" height="98">
<tbody>
<tr style="height: 16px;">
<td style="width: 1158px; border-color: #000000; background-color: #FF0000;" fff=""><span style="font-size: 14pt;"><strong><span style="color: #ffffff;">Warning!</span></strong></span></td>
</tr>
<tr style="height: 56.4063px;">
<td style="width: 1158px; border-color: #000000;"><span style="font-family: tahoma, arial, helvetica, sans-serif; font-size: 14pt;"> 1: Some new features, updates, or bug fixes may require that you clear your browser cache before you will see the changes taken effect<br/> 2: If you get no errors and no readings after a while see about doing a <a href="http://127.0.0.1:8000/user-guide/Redeploying%20your%20repository/" target="_blank" title="Redeploying your repository link">Redeploying your repository</a> </span></td>
</tr>
</tbody>
</table>

-->

