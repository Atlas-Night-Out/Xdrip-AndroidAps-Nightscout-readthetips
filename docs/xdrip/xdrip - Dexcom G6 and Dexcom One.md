<!-- this is not on github server its local only and run my mkdocs server!
docs made by D.Galloway 2019- 2021-->
<img width="860" height="615" border="0" align="center"  src="../../img/xdrip/Hardware Data Source_header.jpg" title="Dexcom G6 and Dexcom One"/></a><br>

## [xdrip± Back to Data Source](../xdrip/xdrip%20-%20hardwaredatasource.md#xdrip-data-source) <br>
<img width="500" height="auto" border="0" align="center"  src="../../img/xdrip/choose data source.png" title="choose data source"/></a><br><br>

## Adding Dexcom G6 and Dexcom One Data Source
<table width="1166" height="148" border="1" style="border-color: #000000; background-color: #ffffff;" cellpadding="1" cellspacing="1" height="98">
<tbody>
<tr style="height: 16px;">
<td style="width: 1158px; border-color: #000000; background-color: #FF0000;" fff=""><span style="font-size: 14pt;"><strong><span style="color: #ffffff;">Warning! Do not use your mobiles bluetooth connection </span></strong></span></td>
</tr>
<tr style="height: 56.4063px;">
<td style="width: 1158px; "350 border-color: #000000;><span style="font-family: tahoma, arial, helvetica, sans-serif; font-size: 14pt;">

Do not use your mobiles auto Bluetooth connection to pair your Transmitter! If it does unpair it, before you begin. xdrip+ will ask you to do it!  <a href="https://clarity.dexcom.com/" target="_blank" title="Dexcom USA Account">See Here</a> <a href="https://clarity.dexcom.eu/" target="_blank" title="Bluetooth connection"> </a> 
</span></td>
</tr>
</tbody>
</table>
Go to Hamburger/ <br>

<img width="500" height="auto" border="0" align="center"  src="../../img/xdrip/left Hamburger bar.jpg" title="Hamburger Menu"/></a><br><br>

Settings/

<img width="300" height="auto" border="0" align="center"  src="../../img/xdrip/Main Settings (2).jpg" title="Main Settings"/></a><br>

Hardware Data Source<br>

<img width="500" height="auto" border="0" align="center"  src="../../img/xdrip/Hardware Data Source.jpg" title="Hardware Data Source"/></a><br>

Enter the Correct Data Source, from the list (In this case it will be G5/G6 Transmitter) label on the box and  confirm it.<br>

<img width="300" height="auto" border="0" align="center"  src="../../img/xdrip/Hardware Datasource G5_G6 Transmitter.jpg" title="Data Source G5/G6 Transmitter"/></a><br>

Now select <span style="background-color: #FFFF00">**Dexcom Transmitter Id**</span> below it and enter your Code. <img width="500" height="auto" border="0" align="center"  src="../../img/xdrip/Dexcom Transmitter ID code.jpg" title="Dexcom SN"/></a><br>(You can find this code on your box as a SN which you need to Enter the code, and confirm it.<br>
<br>
<img width="500" height="auto" border="0" align="center"  src="../../img/xdrip/Dexcom SN Code.jpg" title="Dexcom SN"/></a><br>

I normally Take a picture of the transmitter code as well as keeping the box. In case I lose it or if I’m out and need to re-enter it for any reasons. But also keep a record Date has it has a 3-month limit on the Transmitter from when it stops working on you. 90 Days from day you start your first sensor with it.<br>

## G5/G6 Debug Settings

Now move down and select your Debug settings. <img width="500" height="auto" border="0" align="center"  src="../../img/xdrip/G5_G6 Debug Settings.jpg" title="G5_G6 Debug Settings"/></a><br>

This section can be very frustrating and can cause issues with you not having the correct settings for your particular Setup.<br>
Do NOT enable restart sensor. Not at all sure why as I had no issues having this enabled!<br>

<img width="400" height="auto" border="0" align="center"  src="../../img/xdrip/G5_G6 Debug Settings_P1.jpg" title="G5_G6 Debug Settings"/></a><br>

With Android versions below 10 unselect  Avoid Scanning.
With Android versions 10 and above, if you experience stoppages you can try to disable first <span style="background-color: #FFFF00">**avoid Scanning**</span> and also <span style="background-color: #FFFF00">**Minimize Scanning**</span>. I had no issues on Android Version 11 or v12 with these selected on a Samsung Mobile.<br>

<img width="400" height="auto" border="0" align="center"  src="../../img/xdrip/G5_G6 Debug Settings_P2.jpg" title="G5_G6 Debug Settings"/></a><br>

If you use a Samsung phone with Android 11 and above, you should <span style="background-color: #FFFF00">**enable Special Pairing Workaround**</span>. <br> Again, on my Samsung device I did not have this selected and had no issues.<br><br>

## Less Common Settings <br>
Go to

Go to Hamburger/<br>

<img width="500" height="auto" border="0" align="center"  src="../../img/xdrip/left Hamburger bar.jpg" title="Hamburger Menu"/></a><br>

Settings/<br>

<img width="300" height="auto" border="0" align="center"  src="../../img/xdrip/Main Settings (2).jpg" title="Main Settings"/></a><br>


Less Common Settings<br>

<img width="500" height="auto" border="0" align="center"  src="../../img/xdrip/Less Common settings.jpg" title="Less Common settings"/></a><br>

Then Go to Advance Calibration / Bluetooth Settings<br>

<img width="500" height="auto" border="0" align="center"  src="../../img/xdrip/Bluetooth Settings.jpg" title="Bluetooth Settings"/></a><br>

<img width="400" height="auto" border="0" align="center"  src="../../img/xdrip/Bluetooth full Settings.jpg" title="Bluetooth Full Settings"/></a><br>

<span style="background-color: #FFFF00">**Trust Auto-Connect**</span> needs to be (disable for Samsung mobiles)<br>
If you are having issues with your mobile type also disable this option!<br>

!!!info  
    The <span style="background-color: #FFFF00">**Bluetooth Watchdog**</span> and <span style="background-color: #FFFF00">**G5 Bluetooth Watchdog**</span> will turn off then on your phone Bluetooth, this will lead to a temporary Bluetooth disconnection on all connected devices. You might want to disable this feature if you use AAPS and your bridge/pump doesn't recover automatically Bluetooth connection.<br>

For Android version 8 and above you can enable <span style="background-color: #FFFF00">**Use Background Scans**</span>. If you lose connection, leave it disabled.

## Advanced Calibration

<img width="500" height="auto" border="0" align="center"  src="../../img/xdrip/Advanced Calibration.jpg" title="Advanced Calibration"/></a><br>

Disable Automatic Calibration 
go to     Settings / Less common settings / Advanced Calibration / Automatic Calibration<br>

<img width="400" height="auto" border="0" align="center"  src="../../img/xdrip/Automatic Calibration.jpg" title="Advanced Calibration"/></a><br>

<span style="background-color: #FFFF00">**Restart your Mobile**</span> to make sure all constraints are being taken into account.<br>

## Now Check connection

## Insertion-Video
Now Insert the transmitter in your sensor. If you do not know how to do this see 
[Dexcom insertion-video](../Dexcom/Userguide.md#dexcom-insertion-video)<br>

You will not be able to <span style="background-color: #FFFF00">**connect xDrip+ if the transmitter**</span> is not inserted in the sensor.<br>

## System Status
Now go to [system status](../xdrip/xdrip%20-%20System%20Status.md#g5g6-system-status-page) and make sure the transmitter is connected (paired). Come back to here: when you have connected or if you know already continue below:<br>

<img width="308" height="auto" border="0" align="center"  src="../../img/xdrip/system status wait until paired.jpg" title="System Status Wait until paired"/></a>-<img width="300" height="auto" border="0" align="center"  src="../../img/xdrip/system status connected.jpg" title="System Status Now Connected"/></a><br>

Do not continue until paired information is showing in the System Status page.<br>

<img width="300" height="auto" border="0" align="center"  src="../../img/xdrip/Bluetooth pairing request.jpg" title="Bluetooth pairing request"/></a><br>


And Showing on the <span style="background-color: #FFFF00">**Classic Status Page**</span> Connection Status.<br>

<img width="500" height="auto" border="0" align="center"  src="../../img/xdrip/Classic Status Page_Connection Status paired.jpg" title="Classic Status Page - Connection Status paired"/></a><br>


If not paired after a while do a <span style="background-color: #FFFF00">**Forget Device**</span> and then a <span style="background-color: #FFFF00">**Restart Collector**</span> on the <span style="background-color: #FFFF00">**Classic Status Page**</span> and wait in G5/G6 Status again for connection to pair. <br>

Can take a while but I would give it around 10 to 15 minutes until I try again.<br>

## Once connection is confirmed proceed to [Start Sensor](../xdrip/xdrip%20-%20Start%20Sensor.md#start-new-sensor) <br>.


<table width="1166" height="148" border="1" style="border-color: #000000; background-color: #ffffff;" cellpadding="1" cellspacing="1" height="98">
<tbody>
<tr style="height: 16px;">
<td style="width: 1158px; border-color: #000000; background-color: #FF0000;" fff=""><span style="font-size: 14pt;"><strong><span style="color: #ffffff;">Warning! Do not use your mobiles bluetooth connection </span></strong></span></td>
</tr>
<tr style="height: 56.4063px;">
<td style="width: 1158px; "350 border-color: #000000;><span style="font-family: tahoma, arial, helvetica, sans-serif; font-size: 14pt;">

Do not use your mobiles auto Bluetooth connection to pair your Transmitter! If it does unpair it, before you begin. xdrip+ will ask you to do it!  <a href="https://clarity.dexcom.com/" target="_blank" title="Dexcom USA Account">See Here</a> <a href="https://clarity.dexcom.eu/" target="_blank" title="Bluetooth connection"> </a> 
</span></td>
</tr>
</tbody>
</table><br>




  

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

