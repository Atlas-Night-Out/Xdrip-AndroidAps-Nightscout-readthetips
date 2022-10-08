<!-- this is  on github live server!
docs made by D.Galloway 2019- 2021-->

For full Website content visit [The Diabetic Way](https://www.thediabeticway.co.uk/index.php/en/).


###  **Nightscout on Google Cloud**<br>

<img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/Google Cloude_setup_.jpg" title="Google Cloude_setup"/></a>	

Credit too:Big thanks go to jamorham, the current xDrip head developer, for the idea, putting it together, implementing the installer, and testing everything with myself and Navid doing the documents with me David!.<br>

I have not fully tested this so please let us all know how you go on with it! Thank you!

Upcoming changes made:
Added Terminal Process:old heroku accout to it. 

### **So with all that, let’s set up a free account on Google Cloud <br>**


## **1. <a href=" https://www.noip.com/" target="_blank" title="Noip Account">Noip Account</a>**

### a.	First Sign up Noip: By going to https://www.noip.com/ or <a href=" https://www.noip.com/" target="_blank" title="Sign up Noip">Noip</a>
<a href="https://www.noip.com/" target="_blank">
  <img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/noipsignin.jpg" title="sign up to Google cloud"/>
</a><br>


### b. You need to enter your email address, choose a password, and choose a hostname. Make a note of all of it.test<br>
<center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/hostname2.jpg" title="Your hostname"/></a>	</center><Br>


### c.  Select the “Free Sign Up” not the  “Get Enhanced”.<br>
<center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/free signup.jpg" title="Free sign up"/></a>	</center><br>

### d.  Sit back have a cuppa and enjoy video waiting for your email to “Confirm Account” before you advance to the next section. <br>
<center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/confirm your account.jpg" title="wait for your email"/></a><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/confirm your account_email.jpg" title="Confirm email"/></a>		</center><br>

### e. Host Name
You will be given a Hostname, that you will use to go to your nightscout site later and also add it to your settings and other things like when you setup a Follower. I will show you an example Host below.<br>
<center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/noip_examplehost.jpg" title="Example Host"/></a>	</center><br>

## 2. **<a href=" https://support.google.com/accounts/answer/27441?hl=en" target="_blank" title="Google Account">Google Account</a>**

### a. You need a Google account to proceed. If you do not have one go to https://support.google.com/accounts/answer/27441?hl=en and sign up or <a href=" https://support.google.com/accounts/answer/27441?hl=en" target="_blank" title="Sign up">Google Account</a>
<a href="https://support.google.com/accounts/answer/27441?hl=en" target="_blank">
  <img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/create a google account.jpg" title="sign up for a Google Account"/><br><br>
  
  **Once you have created a Google account** <br><br>

Go to

## 3. <a href=" https://console.cloud.google.com" target="_blank" title="Log into Google Cloud">Google Cloud</a> <br>

Google Cloud console, and sign in with your Google Account<br>

<a href= https://console.cloud.google.com" target="_blank">
  <img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/google cloud.jpg" title=" Google cloud Console"/>
</a><br>

### a. Make a new project<br>
<center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/new project.jpg" title="New Project"/></a><br>	
Give it a name and click create.</center><br>

### b. Select your new project.<br>
<center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/select project.jpg" title="Select your project you have just created"/></a><br>	
</center><br>

### c. Select the dashboard.<br>
<center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/Dashboard.jpg" title="Dashboard"/></a><br>	
</center><br>

### d. Select the Compute Engine.<br>
<center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/conpute engine.jpg" title="Compute Engine"/></a><br>	
</center><br>

This next section is where we need to go through settings to get a free Tier from Google. You can view the specifications we will be needing to fulfil are Task.<br>

### e. Select  Enable which you wil have to do billing process twice!<br>
<center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/conpute engine enable.jpg" title="Enable"/></a><br>	
</center><br>

### f. Select  Enable Billing which will take a while! <br>
<center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/billing required.jpg" title="Enable Billing"/></a><br>	
</center><br>

### g. Go to <a href=" https://console.cloud.google.com/" target="_blank" title="Enable Billing by going to">Google Cloud </a> or https://console.cloud.google.com/ Enable the engine again. It will ask you to enable billing again. But, this time, select the billing account you just created.
Enable billing for your new project. <br>
<center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/set billing account.jpg" title="Enable Billing again"/></a><br>	
</center><br>

### h. **Free Tier virtual machine Spesifications you need to pick** <a href=" https://cloud.google.com/free/docs/free-cloud-features#free-tier" target="_blank" title="Specifications you need to pick"> Free Tier Specifications </a> to see the Specifications: Or go to  https://cloud.google.com/free/docs/free-cloud-features#free-tier I will give you the settings below is what I picked from the specifications list. For you to select in the next process you need to do. see Section **14.** below now.<br>

<center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/1 GB network.jpg" title="1 GB Network"/></a><br>	
</center><br>
<center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/1 non-preemptible e2-micro VM instance.jpg" title="e2-micro VM instance"/></a><br>	
</center><br>
<span style="background-color: #FFFF00">**The above three regions are the regions your virtual machine can be located, not where you have to be in living. In other words if you live in the U.K you still need to pick one of the three above. Oregon. Lowa, or South Carlolina** to get a free Tier</span><br>

<center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/Machine Type.jpg" title="Machine Type"/></a><br>	
</center><br>

<center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/Boot Disk Specs.jpg" title="Boot Disk Specs"/></a><br>	
</center><br>



### i. **Process you need to do now **  Go to the dashboard. Select **“Compute Engine”**. Select the **“VM instances”** tab in the left pane if it’s not already selected.
Select “Create Instance”.<br>
<center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/Creat instance.jpg" title="Creat Instance"/></a><br>	
</center><br>

### j.  **Settings you need to fill in Now:**
#### 1. Set name to “nightscout”.
#### 2. Set machine type to “e2-micro 1GB”.
#### 3. Select a region that qualifies for <a href=" https://cloud.google.com/free/docs/free-cloud-features#free-tier" target="_blank" title="Free Tier">free tier</a>.  <br>
<center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/Machine Configuration.jpg" title="Machine Configuration"/></a><br>	
</center><br>

### k.  **Go Down to Boot Disk Section :**
Edit it by clicking on change “Boot Disk” and modify as shown below. Click on “Select”.
<center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/boot disk change.jpg" title="Boot Disk Change"/></a><br>	
</center><br>
#### 1. **Ubunta**.<br>
#### 2. **Ubunta 20.04 LTS Minimal**.<br>
x86/64, amd64 focal minimal image built on 2022-09-10, supports Shielded VM features<br>
#### 3. **Standard Persistance Disk**<br>
#### 4. **30GB**  <br>
<center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/Boot Disk Specs.jpg" title="Boot Disk Specs"/></a><br>	
</center><br>
 <span style="background-color: #FFFF00">**Click on “Select”.**</span> <br>

### l.  **Under the firewall Section, **
#### a. enable both **http and https**.<br>
<center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/firwall.jpg" title="Firewall Section"/></a><br>	
</center><br>

### m. Click on “Create” to start creating the virtual machine. Google will now bring up your virtual machine after its finished which will take a while, so sit back and relax.<br>
<center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/VM Instance.jpg" title="VM instances"/></a><br></center>	

 

### n. After the external IP address column is finished, click on <span style="background-color: #FFFF00">**“SSH”**</span> on the right side of the IP address. A terminal will appear shortly.<br>
<center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/SSH.jpg" title="SSH"/></a><br></center>
This should bring up your browser, if it dosn't like it did not with me in firefox browser I had to allow popups for it to work!<br>

### o. **Copy and paste the following line into the terminal** window that has just come up. Be very cautious not to copy it into any other machine as it will overwrite the contents of the machine. Copy the code below into teh teminal.
 <span style="background-color: #FFFF00">**curl https://raw.githubusercontent.com/jamorham/nightscout-vps/vps-1/bootstrap.sh | bash**</span> <br><br>

<center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/Add code to terminal.jpg" title="Add the code"/></a><br></center><br>

You might get a pop up preventing you from opening the terminal window. If you do, select the options and allow the popups window. Then select the SSH again to open it.<br>
<center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/allow popup.jpg" title="Allow Popup"/></a><br></center><br>


## 4. **Now Wrap up Linux installation ** <br>

### a. If you get an error message that says <span style="background-color: #FFFF00">**(EINTEGRITY) ending with (0 bytes)**</span> and it hangs, just press CTRL and C keys at the same time to interrupt. Then, re-run the curl bootstrap command above that you have just entered into it again. You can use the up arrow on the terminal to go back to the previous command entries.<br>

### b. **After the installation is finalized, you will be asked to login.** To log into the virtual machine, use the email address and password you used to register from when you did your <span style="background-color: #FFFF00">**<a href=" https://www.noip.com/" target="_blank" title="Noip Account">Noip Account</a>**</span><br>
<center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/no ip email and password.jpg" title="Add email and password from noip"/></a></center><br>

### c. Terminal Process:<br>
####  Now Leave the update interval at 30.
<center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/Leave the update interval at 30.jpg" title="Leave the update interval at 30"/></a><br></center>

####  Select N for running command during update<br>
<center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/select N for running command during update.jpg" title="select N for running command during update"/></a><br></center><br>

####  Enter email address “used for urgent renewal<br>
<center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/Enter email address “used for urgent renewal.jpg" title="Enter email address “used for urgent renewal"/></a><br></center><br>

####  Press A to accept the terms of service.<br>
<center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/Press A to accept the terms of service2.jpg" title="Press A to accept the terms of service."/></a><br></center><br>

####  Press N to decline sharing email address.<br>
<center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/Press N to decline sharing email address.jpg" title="Press N to decline sharing email address"/></a><br></center><br>

####  Select 2 to redirect to secure https.<br>
<center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/Select 2 to redirect to secure https.jpg" title="Select 2 to redirect to secure https"/></a><br></center><br>

####  If you want to copy your old nightscout site, please state the name here ( Example: https://site.herokuapp.com) To skip just press enter.<br>
I added my old Herroku account here.<br>
<center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/add old nightscout site.jpg" title="Add Old Nightscout Site"/></a><br></center><br>

###  **API secret:** <br>You will be asked to replace the API secret. This is the password you will login to Nightscout with later.
Enter a password and take note of it and keep safe.<br>
It needs to be more than 12 characters long<br>
I would also not use symbols characters within making your password, I don't think xdrip likes it.

<center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/change the API secret.jpg" title="Change the API secret"/></a></center><br>

###  **Installation is Complete:** <br> When you see the following, the installation is complete and you can close the terminal by clicking on X at the top right corner of the terminal window.<br>
<center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/Installation is Complete.jpg" title="Installation is Complete"/></a></center><br>

##  5. **Now We need to Set up Nightscout:** <br> 
###  **Set up Nightscout:**<br>
#### a. Use a web browser and copy your hostname from noip. <br>
<center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/noip hostname.jpg" title="noip hostname"/></a></center><br>And Paste it into your browser.
<center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/add host to browser.jpg" title="add host to browser"/></a></center><br>
(from when you registered at noip.com). <br>
 <center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/noip hostname.jpg" title="noip hostname"/></a></center><br>
#### b. This will bring up your Nightscout. It will ask you for a password. Enter your API-Secret you did earlier in the Google Cloud terminal.<br>
Check “Remember this device” checkbox to avoid having to re-enter it.<br>

<center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/Enter your API-Secret.jpg" title="Enter your API-Secret"/></a></center><br>
#### c. On first time, Nightscout will ask you to set up a profile for sensitivity etc. Either enter real values or just click save and then use close button on top right of the screen. You may need to do this twice<br>

<center><img width="300" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/nightscout profile editor1.jpg" title="Nightscout Profile Editor"/></a><img width="300" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/nightscout profile editor2.jpg" title="Nightscout Profile Editor close"/></a></center><br>

## 6.  **Set up xDrip to upload to your Nightscout** <br>
This is what you need to do in xDrip on your master (Main)  phone.<br>
#### a. Go to xDrip Settings −> Cloud Upload −> Nightscout Sync (REST-API).<br>
<center><img width="250" height="Auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/xdrip settings.jpg" title=" xdrip settings"/></a><img width="250" height="Auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/xdrip cloud upload.jpg" title=" Cloud Upload"/></a><img width="250" height="Auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/xdrip Nightscout Sync (REST-API).jpg" title=" Nightscout Sync (REST-API)"/></a></center><br>
#### b. Select Enable at the top.<br>
<img width="250" height="Auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/xdrip enable Rest-API.jpg" title=" Enable Nightscout Sync (REST-API)"/></a>
#### c. Let’s say the hostname you chose when you signed up for noip.com was hostname. And let’s say you set the API secret, while finalizing the installation as explained in the previous section, to API-Secret.<br>
<center><img width="Auto" height="Auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/xdrip Adding Your Base.jpg" title="Adding Your Base"/></a></center><br>
#### d. Tap on Base URL. Enter the following. https://API-Secret@hostname/api/v1/  <br>

That’s it. Your xDrip readings should now upload to your Nightscout on Google Cloud.<br>
If not triple check the way you have added your Base URL correctly, it is very case sensitive!<br>
## 7.  **Set up xDrip uploader to go to your AndroidAPS** <br>

#### Basic settings for Most CGM <br>


<table width="1166" height="150" border="1" style="border-color: #000000; background-color: #ffffff;" cellpadding="1" cellspacing="1" height="98">
<tbody>
<tr style="height: 16px;">
<td style="width: 1158px; border-color: #000000; background-color: #FF0000;" fff=""><span style="font-size: 14pt;"><strong><span style="color: #ffffff;">Warning!</span></strong></span></td>
</tr>
<tr style="height: 56.4063px;">
<td style="width: 1158px; border-color: #000000;"><span style="font-family: tahoma, arial, helvetica, sans-serif; font-size: 14pt;">(I have not tested this bit on AndroidAPS so please report any issues if you have any. Links are at the bottom of the page!)
</span></td>
</tr>
</tbody>
</table>


This is the same has above except your Url will be your web address noip Host address, not like xdrip's where it has Both Secret and Noip host on one line, with the added api/v1 at the end of it.<br>
In AASP it is done separately, you add your Nightscout Web URL and then add your Secret in NS API secret below. There is no api/v1 in it at all.
<br>
<center><img width="350" height="Auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/AAPS_Base URL googlecloud.jpg" title="AAPS Base URL"/></a></center><br>

### a. Set your Nightscout URL e.g. https://yoursitesname.ddns.net<br>

### b. You will also need to Disable <span style="background-color: #FFFF00">**Upload treatments**</span> and <span style="background-color: #FFFF00">**Back-fill data**</span> from xDrip+, or else treatments can be doubled in AAPS leading to false COB and IOB.<br>

### c. <span style="background-color: #FFFF00">**Alert on failures**</span> should also be deactivated.<br>

These are in your settings/Cloud Upload/Nightscout Sync (REST-API) / Extra Options.<br>

<center><img width="300" height="Auto" border="0" align="center"  src="../../img/xdrip/Disable Upload treatments.jpg" title="Disable Upload treatments,Alert on failures,Back-fill data"/></a></center><br>

### d. Also Disable <span style="background-color: #FFFF00">**Automatic Calibration**</span> you can enable it for the first time but then after that it will need to be Disabled.<br> you can do this by selecting the Download treatments  to switch Automatic calibration (on/Off)

You can do this at: Settings/Cloud Upload/Nightscout Sync (REST-API) /<br>

<center><img width="300" height="Auto" border="0" align="center"  src="../../img/xdrip/Disable Automatic Calibration.jpg" title="Disable Automatic Calibration"/></a></center><br>

## 8. How to Configure DDNS (Dynamic DNS) in a Router 
### a. Is another issue some of you may face if you do not have a static Ip address. There is software available for you to download from noip called a <a href=" https://my.noip.com/dynamic-dns/duc" target="_blank" title="Dynamic update client">Dynamic update client</a>. <br>
<iframe width="860" height="615" src="https://www.youtube.com/embed/gNWuYJs3suY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br>

Which can be ok during the day while your computer is running but not so good at night if you wish to be saving power and turning your computer off, has this can and will stop your nightscout from running if your ip changes while your computer is off, making it an unsafe process for nightscout at night. <br>

### b. The next video  method is good for them that are able to use these router's but again some of us cannot use these methods and these kinds of router with a DHCP some are on routers that only have a DHCU<br>

### c. This I found very frustrating to have to go through all of this due to some Service providers preventing you having a static Ip address. And this process I hope will help resolve a lot of them for you. But again, a cost in having to buy a second router! <br>

I did this setup running on a Hub 3.0 VMDG505/TG2492LG-VM
<center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/virgin hub 3.0.jpg" title="virgin hub 3.0"/></a></center><br>

## 9. Create Acess Tokens and Roll
###  **Set up Nightscout tokens for your followers and AndroidAPS** <br>
### a. Go to your Web site Nightscout and verify again and verify API-Secret again if needed. See "Now We need to Set up Nightscout" above. And click on the top right menu button.<br>
<center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/nightscout burger menu.jpg" title=" Burger Menu"/></a></center><br>

### b. Click on "Admin Tools"<br>
<center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/nightscout admins tool.jpg" title=" Admins Tool"/></a></center><br>


### c. You will see seven predefined roles:<br>
<center><img width="auto" height="auto" border="0" align="center"  src="/img/Nightscout/Google Cloud/nightscout predefined roles.jpg" title=" predefined roles"/></a></center><br>

**Roles**

- admin: full Access

- Readable: read-only access; no ability to make CarePortal/treatment entries. This user can view reports and profile information.

- Careportal: can view the site and make CarePortal/treatment entries
  - Denied: no access (this role only works if the AUTH_DEFAULT_ROLES setting is also denied. You can’t have a site that is readable to everyone and create a “denied” token for a specific user.)

- Devicestatus-upload: used by devices.<br>

### d. **Make a Token**<br>
Click the 'Add New Subject' 

<center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/nightscout Add New Subject.jpg" title=" Add New Subject"/></a></center><br>

### e. In the form that opens, enter a name. Then under “Roles”, copy a role from the table. For example, for your dad that is only supposed to see your readings and nothing else and not be able to enter any other details or do anything else, then enter 'readable' in the roles section. <br><br>
<center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/rolls blank edit subject.jpg" title=" edit subject"/></center><br>
You can enter a combination of different roles by separating them with “,”<br>
You can also add an optional comment if you like, and then click the save button.<br>

### f. The token will be displayed. You can use it in two various ways:<br>
<center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/access token for role.jpg" title=" Access Token for Role Dad"/></center><br>

Now make sure to take a note of the access token, that you are given<br>

You can create multiple tokens with specific permissions for each.<br>

<table width="1166" Height="185 border="1" style="border-color: #000000; background-color: #ffffff;" cellpadding="1" cellspacing="1" height="98">
<tbody>
<tr style="height: 16px;">
<td style="width: 1158px; border-color: #000000; background-color: #db4e12;" fff=""><span style="font-size: 14pt;"><strong><span style="color: #ffffff;">Note!</span></strong></span></td>
</tr>
<tr style="height: 56.4063px;">
<td style="width: 1158px; border-color: #000000;"><span style="font-family: tahoma, arial, helvetica, sans-serif; font-size: 14pt;">Now make sure to take a note of the access token, that you are given.<br><br>

You can create multiple tokens with specific permissions for each.<br></span></td>
</tr>
</tbody>
</table><br>

## 10.  **Setting up xDrip as a (follower) like your dad, from the example above**

### a. In the xDrip Data Source Settings, choose “Nightscout Follower” as the hardware data source. See [xdrip - Base URL](../xdrip/xdrip%20-%20Base.md#1-setting-up-xdrip-as-a-follower-for-your-dad) for more information<br>
<center><img width="250" height="Auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/xdrip settings.jpg" title=" xdrip settings"/><img width="250" height="Auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/Hardware Data Source1.jpg" title=" Select Hardware Data Source"/></a><img width="250" height="Auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/Hardware Data Source.jpg" title=" Nightscout Follow"/></a></center><br>



If you have any issues or concerns please post your questions in the  <a href="https://www.facebook.com/groups/5390196001057776" target="_blank">
  <img width="50" height="auto" border="0" align="center"  src="../../img/facebook/facebook-logo-png-11.png" title="Facebook group xdrip uk"/></a> <a href=" https://www.facebook.com/groups/5390196001057776" target="_blank" title="Facebook xDrip - UK"> Facebook Group</a> or you can go to the <span style="background-color: #FFFF00">**Discussions**</span> on <a href=" https://github.com/NightscoutFoundation/xDrip/discussions" target="_blank" title="Discussions"> Github</a><a href="https://www.facebook.com/groups/5390196001057776" target="_blank">
  <img width="50" height="auto" border="0" align="center"  src="../../img/Github/github-logo-icon-16155.png" title="Github"/></a>






<br><br>
<center><a href="https://www.diabetes.org.uk/" target="_blank">
  <img width="auto" height="auto" border="0" align="center"  src="../../img/Diabetesuk/pngarea.com_rutgers-logo-png-8467605.png" title="Diabetes UK"/>
</a>Why Not take visit [UK Wide Cycle Ride - Diabetes.uk](https://cycle.diabetes.org.uk/) or  [Swim22 - Diabetes.uk](https://swim22.diabetes.org.uk/) for your Diabetes Needs!</center><br><br>







</font>

 <!--

<table width="1166" height="150" border="1" style="border-color: #000000; background-color: #ffffff;" cellpadding="1" cellspacing="1" height="98">
<tbody>
<tr style="height: 16px;">
<td style="width: 1158px; border-color: #000000; background-color: #FF0000;" fff=""><span style="font-size: 14pt;"><strong><span style="color: #ffffff;">Warning!</span></strong></span></td>
</tr>
<tr style="height: 56.4063px;">
<td style="width: 1158px; border-color: #000000;"><span style="font-family: tahoma, arial, helvetica, sans-serif; font-size: 14pt;">(I have not tested this bit on AndroidAPS so please report any issues if you have any. Links are at the bottom of the page!)
</span></td>
</tr>
</tbody>
</table>


-->


<!--  
  ******************************************************************************************************************
  mkdocs.yml    # The configuration file.
    docs/
    index.md  # The documentation homepage.
       ...       # Other markdown pages, images and other files.
		
		*************************************************************************
		center text**
		## <center>Now Do  </center><br>
		
		*************************************************************
		
********************************************
    Adding exernal link to other a web sites
**********************************************
# <center>Part 2: <a href=" https://atlas-night-out.github.io/my-project/user-guide/Setting_up_Heroku_Account_part2/" target="_blank" title="Setting up Heroku Account">Setting up Heroku Account</a> </center>
<br>
**********************************************

		
<a href="http://nightscout.github.io/pages/update-fork/" target="_blank">
  <img width="auto" height="auto" border="0" align="center"  src="/img/Nightscout/Time to Update Nightscout.png" title="Update Tool"/></a>		
		
		
adding 	Yellow Hightligher!!!!!!!!	with bold too
<span style="background-color: #FFFF00">**Marked text**</span>


<a>
  <img width="auto" height="auto" border="0" align="center"  src="/img/Nightscout/Time to Update Nightscout.png" title="Update Tool"/></a>	




Adding a image with link
<a href="https://www.youtube.com/watch?v=MFsbm45b6YY" target="_blank">
  <img width="auto" height="auto" border="0" align="center"  src="/img/Part 1 Setting up Github 2021/Github account details.jpg" title="github account details"/>
</a><br>

link
<a href=" https://github.com/" target="_blank" title="First create a user account by going to">Click Here</a>

just an image!
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

