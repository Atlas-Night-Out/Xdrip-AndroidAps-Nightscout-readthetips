<!-- this is not on github server its local only and run my mkdocs server!
docs made by D.Galloway 2019- 2021-->

## G5/G6 System Status Page <br>
Go to Settings top left menu bar / System Status<br>

<img width="400" height="auto" border="0" align="center"  src="../../img/xdrip/Burger menu.jpg" title="Burger menu"/></a><br>

<img width="400" height="auto" border="0" align="center"  src="../../img/xdrip/settings_system_status.jpg" title="Settings System Status"/></a><br>
 
 
You can Swipe left or right on your screen to access different status pages.
Each status page has a specific heading. (Classic Status Page, <span style="background-color: #FFFF00">**G5/G6 Status,**</span> Followers, Uploaders)<br>

<iframe id="video7" width="260" height="440" src="https://www.youtube.com/embed/NK2td93ufdY" title="System Status" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

If you are using xDrip as the collector from Dexcom G5, G6 or Dexcom One, go to the G5/G6 status page with the “G5/G6 Status” heading.<br>

<img width="400" height="auto" border="0" align="center"  src="../../img/xdrip/System Status.jpg" title="System Status"/></a><br>
 
The transmitter ID shown on this page is unique to your transmitter and can be used to interfere with your system. 

Be careful with whom you share it. Best you blackout the transmitter ID before posting a screenshot  on a forum as no one needs to see it in order to help you.<br>

## Classic Status Page

This page shows information about currently installed version, and in the past installed version.
For a new installation the <span style="background-color: #FFFF00">**down gradable version**</span> will show as 1603091400 by default.<br>


<img width="400" height="auto" border="0" align="center"  src="../../img/xdrip/classic status page.jpg" title="Classic Status Page"/></a><br>

<span style="background-color: #FFFF00">**Version information**</span>
 allows you to quickly <a href=" https://github.com/NightscoutFoundation/xDrip/releases" target="_blank" title="download xdrip">download xdrip</a> versions you are after. You will see the version date and the build version so that you can update or downgrade if you have any issues.<br>

Any <span style="background-color: #FFFF00">**Version information**</span> name that shows further information, like debug, dev, a smartwatch name, care link, will be  a [forked version release](../xdrip/xdrip%20-%20Download.md#forked-versions) of xDrip+ and might not contain all the latest functions of xdrip+ released app.<br>

<img width="500" height="auto" border="0" align="center"  src="../../img/xdrip/data source sensor start connection status.jpg" title="Data Source - Bluetooth Device - Connection Status - Sensor Start"/></a><br>

Also, on this page you will find the <span style="background-color: #FFFF00">**Data Source: **</span> Type (one you selected to receive your BG values in my case a Dexcom G6) <br>
After the data source type, you'll see the name of the actual <span style="background-color: #FFFF00">**Bluetooth Device:**</span>  Serial number connected to xDrip+<br>
<span style="background-color: #FFFF00">**Connection Status:**</span> is where you will see if you are connected to your transmitter.<br>
And the <span style="background-color: #FFFF00">**Sensor Start Date:**</span> (as entered as sensor start date and time, or automatically detected, depending on the sensor type).<br>

This page doesn't update automatically, you will need to touch the rounded arrows at the bottom to refresh it.<br>

<img width="200" height="auto" border="0" align="center"  src="../../img/xdrip/rounded arrows.jpg" title="Rounded Arrows"/></a><br>

## Restart collector - Forget Device

<img width="500" height="auto" border="0" align="center"  src="../../img/xdrip/Restart collector - Forget Device.jpg" title="Restart collector - Forget Device - Rounded Arrows"/></a><br>

<span style="background-color: #FFFF00">**Restart collector:**</span> will restart xDrip+ Core collector mechanism. The effect depends on the data source.<br>
<span style="background-color: #FFFF00">**Forget device:**</span> will only have effect when xDrip+ is connected through Bluetooth to a device.
The device will be disconnected, and you will need to wait to pair a Bluetooth connection again. Best to slide to the G5/G6 Status page and wait to pair!<br>

## System Status
Wait for your transmitter to be connected<br>

<img width="308" height="auto" border="0" align="center"  src="../../img/xdrip/system status wait until paired.jpg" title="System Status Wait until paired"/></a>-<img width="300" height="auto" border="0" align="center"  src="../../img/xdrip/system status connected.jpg" title="System Status Now Connected"/></a><br>

Do not continue until paired information is showing in the System Status page and battery showing.<br>

<img width="300" height="auto" border="0" align="center"  src="../../img/xdrip/Bluetooth pairing request.jpg" title="Bluetooth pairing request"/></a><br>


Pair your transmitter <span style="background-color: #FFFF00">**wait until it pops up**</span> Bluetooth pairing request.<br>

<img width="500" height="auto" border="0" align="center"  src="../../img/xdrip/Classic Status Page_Connection Status paired.jpg" title="Classic Status Page - Connection Status paired"/></a><br>


If not paired after a while do a <span style="background-color: #FFFF00">**Forget Device**</span> and then a <span style="background-color: #FFFF00">**Restart Collector**</span> on the <span style="background-color: #FFFF00">**Classic Status Page**</span> and wait in G5/G6 Status again for connection to pair. <br>

Can take a while but I would give it around 10 to 15 minutes until you try again.<br>

## Once connection is confirmed proceed to [Start Sensor](../xdrip/xdrip%20-%20Start%20Sensor.md#start-new-sensor) <br>.


## xDrip+ Sync Follower
[xDrip+ follower](../xdrip/Xdrip%20Follower%20Setup.md#xdrip-follower-setup) is a really handy tool to have and use, not only for others to follow you but also for yourself to share to other mobiles or Tablets within your household to see your BG levels. See Follower to setup, see link above.<br>

<img width="500" height="auto" border="0" align="center"  src="../../img/xdrip/xdrip status follower.jpg" title="status follower"/></a><br>
Followers will <span style="background-color: #FFFF00">**add-up**</span> in the list when recognized, if you remove a follower it might take some time before it's actually removed from the list.

 Issues with follower, is most likely a network connection or <a href=" https://support.google.com/googleplay/answer/9037938?hl=en" target="_blank" title="Google Play services">Google Play services</a> issues, has these are required to use this feature. Make sure they are present, enabled and not subject to battery optimization. <br>

Also having a [Nightscout](../Nightscout/Setting_up_Github_Account_part1.md#part-1-setting-up-the-github-for-nightscout) setup available as a backup follower solution is another suggested way when troubleshooting or following a child or adult. <br>

Nightscout is also good to use with Google <a href=" https://github.com/nielsmaerten/gluco-check" target="_blank" title="Gluco Check">Gluco Check</a> to Use <a href=" https://www.youtube.com/watch?v=xfVby1EjmRM&ab_channel=NielsMaerten" target="_blank" title="Routines">Routines</a> to turn "Hey Google, ask Gluco Check my blood sugar" into
 in my case "Hey Google, Nightscout Status".<br>

## Gluco Check 
<center>
<iframe id="video10" width="auto" height="500" src="https://www.youtube.com/embed/2E0WwGHz9Xo" title="Gluco Check" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></center><br>




## To Be continued!

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


************************************************************************

!!!info  
    The Bluetooth watchdog and G5 Bluetooth watchdog with turn off then on your phone Bluetooth, this will lead to a temporary Bluetooth disconnection on all connected devices. You might want to disable this feature if you use AAPS and your bridge/pump doesn't recover automatically Bluetooth connection.

    ********************************************************************

<a>
  <img width="auto" height="auto" border="0" align="center"  src="/img/Nightscout/Time to Update Nightscout.png" title="Update Tool"/></a>	


link
<a href=" https://github.com/" target="_blank" title="First create a user account by going to">Click Here</a>

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

