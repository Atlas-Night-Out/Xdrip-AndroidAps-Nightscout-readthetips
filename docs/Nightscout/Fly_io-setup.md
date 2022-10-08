<!-- this is  on github live server!
docs made by D.Galloway 2019- 2021-->

For full Website content visit [The Diabetic Way](https://www.thediabeticway.co.uk/index.php/en/).


###  **Fly_io for Nightscout**<br>


Credit too:Big thanks to Robby,  for the idea, links putting it together, implementing the installer, and testing everything with myself for the docs, and Robby for the tips.<br>

## Upcoming changes made:
Process:old heroku accout to a new Turbo Fly_io Account. <br><br>

<center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Fly_io/Turbocharge your heroku app with fly.jpg" title="Turbocharge your Heroku App with Fly"/></a>	</center><br>

### **So with all that, let’s set up a free Turbo Account on Fly_io <br>**
You will need to keep to the free Tier for this setup to be free, in you having a nightscout site again totaly free. This could change and we are not fully knowing for how long it will be free, all we know is as long as you stick to the free tire Requirements it should be free. Lets hope for life.<br>

## [Fly_io Account ±]() <br>

#### 1.	Setup Fly_io Account: By going to https://fly.io/launch/heroku or <a href=" https://fly.io/launch/heroku" target="_blank" title="Account">Fly_io Account</a>
<a href="https://www.noip.com/" target="_blank">
  <center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Fly_io/my-heroku-app.jpg" title="sign up to Google cloud"/></center>
</a><br>


### 2. Fill in your organization name, pick a App name you would like (I have just done an example in the image above for these instruction!) and choose your Heroku app you used on Heroku<br>
You will then be asked to fill in your payment details
Fill in your payment details, don't worry,you will not be charged if you keep to a free tier as outlined.
<br>
<center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Fly_io/fly payment.jpg" title="Your hostname"/></a>	</center><br>

### 3. After filling in and setting up your payment details go back to the page you just come from before you filled in the payment details, and carry on the Deploying process  from the Heroku site. This can take a while to do..<br>

<center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Fly_io/Deploying.jpg" title="Deploying"/></a>	</center>

### 4.  Sit back have another cuppa. <br>

### 5.  Fly_io Dashboard <br>
You should now be able to see or be at your Fly_io Dashboard and be presented with your Hostname<br><br>

**Host Name**<center><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Fly_io/new heroku installation is ready url.jpg" title="Installation is Ready"/>	</center><br>

**Dashboard**<br>

</a><img width="auto" height="auto" border="0" align="center"  src="../../img/Nightscout/Fly_io/Dashboard_Hostname.jpg" title="Dashboard Host Name"/></a>


##  **We now need to setup Xdrip**

We need to use Xdrip to upload are CGM readings to Nightscout and it will need you to enter the correct URL in it's setting for Nightscout to start receiving readings from your CGM!<br> You may use other software other than Xdrip+ but for this tutorial I will be using xdrip+ you will have to excuse me if I just put xdrip as I keep forgetiing to put the + 

### 6. **Set up xDrip to upload to your Nightscout** <br>
Also see here if you like other wise carry on below!S<br>
 [Base URL - Set up xDrip to upload to your Nightscout ±](../xdrip/xdrip%20-%20Base.md#1-set-up-xdrip-to-upload-to-your-nightscout) <br>

This is what you need to do in xDrip on your master (Main) Mobile.<br>
#### a. Go to xDrip Settings −> Cloud Upload −> Nightscout Sync (REST-API)<br>
<center><img width="250" height="Auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/xdrip settings.jpg" title=" xdrip settings"/></a><img width="250" height="Auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/xdrip cloud upload.jpg" title=" Cloud Upload"/></a><img width="250" height="Auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/xdrip Nightscout Sync (REST-API).jpg" title=" Nightscout Sync (REST-API)"/></a></center><br>
#### b. Select Enable at the top, if not already enabled.<br>
<img width="400" height="Auto" border="0" align="center"  src="../../img/Nightscout/Fly_io/Nightscout sync (REST-API).jpg" title=" Enable Nightscout Sync (REST-API)"/></a>
#### c. Tap on Base URL. Enter the following Url. Remeber yours will be different than what I show you here. You will need to add your Secret-API and your Host to the set out code!
https://<span style="background-color: #FFFF00">**ThisIsyourSecret-API**</span>@<span style="background-color: #26AF06">**thisisyourHostName**</span>/api/v1/<br>
If you  forgot or lose your secret-API it can be located at Heroku/ Settings/Config Vars and look down the list for API_SECRET<br>
This will now be located in a differrent place now within Fly_io<br>

Your Host name is located in your Fly_io Dashboard.
<center><img width="Auto" height="Auto" border="0" align="center"  src="../../img/Nightscout/Fly_io/example Base URL.jpg" title="Adding Your Base"/></a></center><br>

#### d. (Reminder)Tap on Base URL. Enter the following. https://API-Secret@hostname/api/v1/  <br>

That’s it. Your xDrip readings should now upload to your Nightscout web site.<br>
If you do not see levels after 5 mins, triple check the way you have added your Base URL correctly, it is very case sensitive!with no spaces<br>

### 7. **Set up xDrip uploader to go to your AndroidAPS** <br>
#### Basic settings for Most CGM 
This is the same has above except your Url will be your web address for Fly_io Host address, not like xdrip's where it has Both Secret and Fly_io host on one line with the added api/v1 at the end of it<br>
On AASP it is done seperatly, you add your Nightscout Web URL and then add your Secret in NS API secret below.There is no api/v1 in it<br>
<center><img width="350" height="Auto" border="0" align="center"  src="../../img/Nightscout/Fly_io/AAPS_Base URL.jpg" title="AAPS Base"/></a></center><br>

#### a. Set your Nightscout URL e.g. https://yoursitesname.fly.dev/<br>

#### b. You will also need to Disable <span style="background-color: #FFFF00">**Upload treatments**</span> and <span style="background-color: #FFFF00">**Back-fill data**</span> from xDrip+, or else treatments can be doubled in AAPS leading to false COB and IOB.<br>

#### c. <span style="background-color: #FFFF00">**Alert on failures**</span> should also be deactivated.<br>

These are in your settings/Cloud Upload/Nightscout Sync (REST-API) / Extra Options.<br>

<center><img width="300" height="Auto" border="0" align="center"  src="../../img/xdrip/Disable Upload treatments.jpg" title="Disable Upload treatments,Alert on failures,Back-fill data"/></a></center><br>

#### d. Also Disable <span style="background-color: #FFFF00">**Automatic Calibration**</span> you can enable it for the first time but then after that it will need to be Disabled.<br> you can do this by selecting the Download treatments  to switch Automatic calibration (on/Off)

You can do this at: Settings/Cloud Upload/Nightscout Sync (REST-API) /<br>

<center><img width="300" height="Auto" border="0" align="center"  src="../../img/xdrip/Disable Automatic Calibration.jpg" title="Disable Automatic Calibration"/></a></center><br>




### 8. **Setting up xDrip as a (follower) like for your dad from the example from above**

This will be on your <span style="background-color: #FFFF00">**followers mobile phone,**</span> not your own.
#### 1. In the xDrip Settings / Hardware Data Source, choose “Nightscout Follower” as the hardware data source. See  [xdrip - Base URL](../xdrip/xdrip%20-%20Base.md#1-setting-up-xdrip-as-a-follower-for-your-dad) for more information<br>
<center><img width="250" height="Auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/xdrip settings.jpg" title=" xdrip settings"/><img width="250" height="Auto" border="0" align="center"  src="../..//img/Nightscout/Google Cloud/Hardware Data Source1.jpg" title=" Select Hardware Data Source"/></a><img width="250" height="Auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/Hardware Data Source.jpg" title=" Nightscout Follow"/></a></center><br>


##  **Issues or Concerns** 

If you have any issues or concerns please post your questions in the  <a href="https://www.facebook.com/groups/5390196001057776" target="_blank">
  <img width="50" height="auto" border="0" align="center"  src="/img/facebook/facebook-logo-png-11.png" title="Facebook group xdrip uk"/></a> <a href=" https://www.facebook.com/groups/5390196001057776" target="_blank" title="Facebook xDrip - UK"> Facebook Group</a> or you can go to the <span style="background-color: #FFFF00">**Discussions**</span> on <a href=" https://github.com/NightscoutFoundation/xDrip/discussions" target="_blank" title="Discussions"> Github</a><a href="https://www.facebook.com/groups/5390196001057776" target="_blank">
  <img width="50" height="auto" border="0" align="center"  src="../../img/github/github-logo-icon-16155.png" title="Github"/></a><br>

  ## To Be continued!

	

<br><br>
<center><a href="https://www.diabetes.org.uk/" target="_blank">
  <img width="auto" height="auto" border="0" align="center"  src="../../img/Diabetesuk/pngarea.com_rutgers-logo-png-8467605.png" title="Diabetes UK"/>
</a>Why Not take visit [UK Wide Cycle Ride - Diabetes.uk](https://cycle.diabetes.org.uk/) or  [Swim22 - Diabetes.uk](https://swim22.diabetes.org.uk/) for your Diabetes Needs!</center><br><br>







</font>

 <!--

<table width="1166" border="1" style="border-color: #000000; background-color: #ffffff;" cellpadding="1" cellspacing="1" height="98">
<tbody>
<tr style="height: 16px;">
<td style="width: 1158px; border-color: #000000; background-color: #5B9BD5;" fff=""><span style="font-size: 14pt;"><span style="color: #ffffff;">Note!  If you prefer video, see below</span></span></td>
</tr>
<tr style="height: 56.4063px;">
<td style="width: 1158px; border-color: #000000;"><span style="font-family: tahoma, arial, helvetica, sans-serif; font-size: 14pt;">
<iframe width="850" height="415" src="https://www.youtube.com/embed/gUEqZAfPEZ4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>  </span></td>
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
external link with image 
<a href="https://www.facebook.com/groups/5390196001057776" target="_blank">
  <img width="50" height="auto" border="0" align="center"  src="/img/github/github-logo-icon-16155.png" title="Github"/></a>

		
<a href="http://nightscout.github.io/pages/update-fork/" target="_blank">
  <img width="auto" height="auto" border="0" align="center"  src="/img/Nightscout/Time to Update Nightscout.png" title="Update Tool"/></a>		
		
		
adding 	Yellow Hightligher!!!!!!!!	with bold too
<span style="background-color: #FFFF00">**Marked text**</span>

adding 	Green Hightligher!!!!!!!!	with bold too
<span style="background-color: #26AF06">**Marked text**</span>

<a>
  <img width="auto" height="auto" border="0" align="center"  src="/img/Nightscout/Time to Update Nightscout.png" title="Update Tool"/></a>	




Adding a image with link
<a href="https://www.youtube.com/watch?v=MFsbm45b6YY" target="_blank">
  <img width="auto" height="auto" border="0" align="center"  src="/img/Part 1 Setting up Github 2021/Github account details.jpg" title="github account details"/>
</a><br>

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

