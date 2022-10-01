<!-- this is not on github server its local only and run my mkdocs server!
docs made by D.Galloway 2019- 2021-->
<img width="860" height="615" border="0" align="center"  src="../../img/xdrip/xdrip+ original logo.jpg" title="Xdrip+"/></a><br>

# **BASE_URL** <br>
### xdrip+ Base_URL 
### 1. **Set up xDrip to upload to your Nightscout** <br>
This is what you need to do in xDrip on your master (Main)  phone.<br>
#### a. Go to xDrip Settings −> Cloud Upload −> Nightscout Sync (REST-API)<br>
<center><img width="250" height="Auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/xdrip settings.jpg" title=" xdrip settings"/></a><img width="250" height="Auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/xdrip cloud upload.jpg" title=" Cloud Upload"/></a><img width="250" height="Auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/xdrip Nightscout Sync (REST-API).jpg" title=" Nightscout Sync (REST-API)"/></a></center><br>
#### b. Select Enable at the top, if not already enabled.<br>
<img width="400" height="Auto" border="0" align="center"  src="../../img/Nightscout/Fly_io/Nightscout sync (REST-API).jpg" title=" Enable Nightscout Sync (REST-API)"/></a>
#### c. Tap on Base URL. Enter the following Url. Remeber yours will be different than what I show you here. You will need to add your Secret-API and your Host to the set out code!
https://<span style="background-color: #FFFF00">**ThisIsyourSecret-API**</span>@<span style="background-color: #26AF06">**thisisyourHostName**</span>/api/v1/<br>
If you  forgot or lose your secret-API it can be located at Heroku/ Settings/Config Vars and look down the list for API_SECRET<br>
This will now be located in a differrent place now within Fly_io<br>

Your Host name is located if <span style="background-color: #FFFF00">**using Heroku**</span> at Heroku/Settings/ and scroll down to the bottom.<br>
<center><img width="Auto" height="Auto" border="0" align="center"  src="../../img/Heroku/Heroku App name.jpg" title="Heroku App URL "/></a></center><br>
Or you can click on the Open app in your Heroku acount at the top of your screen and copy the url from the browser.<br>
<center><img width="Auto" height="Auto" border="0" align="center"  src="../../img/Heroku/open heroku app.jpg" title="Heroku Open App "/></a></center><br>
<center><img width="Auto" height="Auto" border="0" align="center"  src="../../img/Heroku/rightclick url nightscout.jpg" title="Heroku Open App "/></a></center><br>
<br>
Your Host name is located if <span style="background-color: #FFFF00">**using Fly_io**</span> its in your Fly_io Dashboard.
<center><img width="Auto" height="Auto" border="0" align="center"  src="../../img/Nightscout/Fly_io/example Base URL.jpg" title="Adding Your Base"/></a></center><br>

#### d. (Reminder)Tap on Base URL. Enter the following. https://API-Secret@hostname/api/v1/  <br>

That’s it. Your xDrip readings should now upload to your Nightscout web site.<br>
If you do not see levels after 5 mins, triple check the way you have added your Base URL correctly, it is very case sensitive!with no spaces<br>
### AndroidAPS Base_URL
### 1. **Set up AndroidAPS to go to your Fly_io or Heroku ** <br>
This is the same has above except your Url will be your web address for Fly_io Host address, not like xdrip's where it has Both Secret and Fly_io host on one line with the added api/v1 at the end of it<br>
On AASP it is done seperatly, you add your Nightscout Web URL and then add your Secret in NS API secret below.There is no api/v1 in it<br>
                                  
<center>Fly_io<img width="300" height="Auto" border="0" align="center"  src="../../img/Nightscout/Fly_io/AAPS_Base URL.jpg" title="Fly_io Base"/></a>Heroku<img width="300" height="Auto" border="0" align="center"  src="../../img/Heroku/AAPS Heroku URL (2).jpg" title="AAPS Heroku Base"/></a></center><br>

### Adding a Follower
### 1. **Setting up xDrip as a (follower) for your dad**
This will be on your <span style="background-color: #FFFF00">**followers mobile phone,**</span> not your own.
#### a. In the xDrip Settings / Hardware Data Source, choose “Nightscout Follower” as the hardware data source.
<center><img width="250" height="Auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/xdrip settings.jpg" title=" xdrip settings"/><img width="250" height="Auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/Hardware Data Source1.jpg" title=" Select Hardware Data Source"/></a><img width="250" height="Auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/Hardware Data Source.jpg" title=" Nightscout Follow"/></a></center><br>

Under “Nightscout Follow URL”, <br>
<center><img width="250" height="auto" border="0" align="center"  src="../../img/Nightscout/Google Cloud/nightscout follow url.jpg" title=" follow url"/><br>Fly_io<img width="250" height="auto" border="0" align="center"  src="../../img/xdrip/fly nightscout followers url.jpg" title=" fly nightscout followers url"/>Heroku<img width="250" height="auto" border="0" align="center"  src="../../img/xdrip/heroku nightscout followers url.jpg" title=" Heroku nightscout followers url"/></center><br>

Add your Fly_io Host address into it or your Heroku Name URL depending on which one you are using.<br>
This will only be setting a follower up giving them the full URL Address but with no Secret Password for it like yourself would have.<br>
There are a few other ways to add followers and will be needing for you to setup a Token in Nightscout admin section. <br>

You can also add a Token and email it to some one to follow you.<br>




##  **Issues or Concerns** 

If you have any issues or concerns please post your questions in the  <a href="https://www.facebook.com/groups/5390196001057776" target="_blank">
  <img width="50" height="auto" border="0" align="center"  src="/img/facebook/facebook-logo-png-11.png" title="Facebook group xdrip uk"/></a> <a href=" https://www.facebook.com/groups/5390196001057776" target="_blank" title="Facebook xDrip - UK"> Facebook Group</a> or you can go to the <span style="background-color: #FFFF00">**Discussions**</span> on <a href=" https://github.com/NightscoutFoundation/xDrip/discussions" target="_blank" title="Discussions"> Github</a><a href="https://www.facebook.com/groups/5390196001057776" target="_blank">
  <img width="50" height="auto" border="0" align="center"  src="../../img/github/github-logo-icon-16155.png" title="Github"/></a><br>




<br>
<a href="https://www.diabetes.org.uk/" target="_blank">
 <center> <img width="auto" height="auto" border="0" align="center"  src="../../img/Diabetesuk/pngarea.com_rutgers-logo-png-8467605.png" title="Diabetes UK"/>
</a>               Why Not take visit [UK Wide Cycle Ride - Diabetes.uk](https://cycle.diabetes.org.uk/) <span style="background-color: #FFFF00">**or**</span>  [Swim22 - Diabetes.uk](https://swim22.diabetes.org.uk/) <span style="background-color: #FFFF00">**or**</span> [Month of Miles - Diabetes.uk](https://monthofmiles.diabetes.org.uk/?gclid=CjwKCAjwz5iMBhAEEiwAMEAwGO2_OoOGRQdN3BDD3NUQ8WoYAsJsxd1YUJN8dSVJowD1E4AjJ1RdVxoC9bgQAvD_BwE) for all of your Diabetes Needs!
</center>


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

