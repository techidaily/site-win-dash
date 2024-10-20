---
title: "Step-by-Step Guide: Building a Custom Windows Event Logger Notifier"
date: 2024-10-15T18:02:03.009Z
updated: 2024-10-20T16:21:38.040Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/ff8e499dfacbb3f8c53c52b2127d34f19a999ba4d08ba1beb7fd17db0047dd1a.jpg
---

## Step-by-Step Guide: Building a Custom Windows Event Logger Notifier

### Quick Links

* [How It Works](https://common-error.techidaily.com/the-laptop-headset-harmony-breakthrough-solution/)
* [Configuration](https://some-guidance.techidaily.com/enhance-your-website-with-cookiebot-technology-smart-data-driven-solutions/)
* [Examples](https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-tecno-camon-30-pro-5g-to-other-android-devices-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/)

 The Windows Event Logs are a tremendous resource as they can not only help you troubleshoot current system issues, but can also provide you with warning signs of potential future problems. So keeping on top of the events your system records can be key to keeping your system running as it should. Unfortunately, sifting through the Event Logs or creating custom views can be a cumbersome manual process.

 Thankfully, we have a solution which will easily allow you to export and filter Windows Event Log entries and then have them emailed and/or saved to a text file. When this process is configured as part of a scheduled task you can have, for example, warning and error messages emailed to you automatically.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144289/7443" target="_top" id="2144289">
  <img src="//a.impactradius-go.com/display-ad/7443-2144289" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144289/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  How It Works

 Our solution works by using a freeware utility, MyEventViewer, by Nirsoft which allows you to easily export Windows Event Logs to a comma separated file. Based on this output, we have developed an easy to configure batch script which filters these results and then can email and/or save the filtered results file. Because the results are a comma separated file, it can be opened in Excel (or your favorite CSV program) and further sorted and filtered.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997630/19272" target="_top" id="1997630">
  <img src="//a.impactradius-go.com/display-ad/19272-1997630" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997630/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Configuration

 The configuration settings and options are documented as inline comments in the script, however we will cover a few of them in a bit of detail here.

**Event Log Name** 

 When specifying the Event Logs you want to capture the events from, you must use the system full name of the log. This is not necessarily what you see in the Event Viewer list of logs.

 For example, if you wanted to capture events from the "Microsoft Office Alerts" log, go to the Properties dialog of the log.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2011/08/image1.png) 

<!-- affiliate ads begin -->
<span id="1484963">
					<video width="864" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1484963.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1484963">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1484963.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1484963%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1484963/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Note the value in the Full Name value, in this case "OAlerts". This would be the value you would need to enter into the script's configuration.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2011/08/image2.png) 

**Event Types** 

 The values for the Event Types is simply the text you see in the "Level" column when you are viewing Event Logs. Typically these are either Information, Warning or Error but various logs may have different values.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2011/08/image3.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006946/19272" target="_top" id="2006946">
  <img src="//a.impactradius-go.com/display-ad/19272-2006946" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006946/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**Scheduled Task Setup** 

 The typical usage of this script is most likely in an automated process. So to make sure there is no overlap between your capture interval and when the process runs, you should set up a Windows Scheduled Task to complement the capture time.

 Quite simply, if your configuration is set to capture events for the last day, you should have a scheduled task that runs once per day. If your configuration is set to capture for the last hour, your scheduled task should be set to run once every hour. Etc.

 As an additional note, in order to make sure the MyEventViewer application can get to the information it needs, the respective scheduled task should be run with administrator rights on the machine.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2011/08/image4.png) 

##  Examples

 This configuration would email Errors and Warnings from the System and Application Event Logs recorded in the past day (24 hours) to my@email.com as well as save the output to the C:\\EventNotices folder:

* EmailResults=1
* EmailTo=my@email.com
* SaveResults=1
* SaveTo=C:\\EventNotices
* TimeInterval=3
* TimeValue=1
* Logs=System,Application
* Types=Error,Warning
* Scheduled Task should run every day.

 This configuration would only email Errors from the System Event Log recorded in the past hour to my@email.com:

* EmailResults=1
* EmailTo=my@email.com
* SaveResults=0
* TimeInterval=2
* TimeValue=1
* Logs=System
* Types=Error
* Scheduled Task should run every hour.

 This configuration would only save Errors and Warnings from the Application Event Log in the past week to the desktop of user JFaulkner (Windows 7) C:\\Users\\jfaulkner\\Desktop:

   * EmailResults=0
   * SaveResults=1
   * SaveTo=C:\\Users\\jfaulkner\\Desktop
   * TimeInterval=3
   * TimeValue=7
   * Logs=Application
   * Types=Error,Warning
   * Scheduled Task should run every week.

[Download Event Log Notifier Script from How-To Geek](https://printer-issues.techidaily.com/revived-post-windows-update-printer-workflow/) 

[Download MyEventViewer from Nirsoft](http://www.nirsoft.net/utils/my%5Fevent%5Fviewer.html) 

[Download Blat from Sourceforge](http://sourceforge.net/projects/blat/files/)

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-building-successful-youtube-collaborations-step-by-step/"><u>[New] 2024 Approved Building Successful YouTube Collaborations Step by Step</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/024-approved-top-10-no-cost-digital-video-editors-the-2023-guide/"><u>[New] 2024 Approved Top 10 No-Cost Digital Video Editors The 2023 Guide</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-pro-fishing-visionaries-discovering-our-5-best-cameras/"><u>[Updated] Pro-Fishing Visionaries Discovering Our 5 Best Cameras</u></a></li>
<li><a href="https://win-dash.techidaily.com/easy-guide-installing-broadcom-bluetooth-drivers-on-your-windows-1087-device/"><u>Easy Guide: Installing Broadcom Bluetooth Drivers on Your Windows 10/8/7 Device</u></a></li>
<li><a href="https://fox-that.techidaily.com/faster-safari-browsing-top-4-tips-for-speeding-up-ios/"><u>Faster Safari Browsing: Top 4 Tips for Speeding Up iOS</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-updating-facebook-video-coverage-with-ease/"><u>In 2024, Updating Facebook Video Coverage with Ease</u></a></li>
<li><a href="https://win-dash.techidaily.com/intel-wireless-network-adapter-driver-download-and-update-for-wi-fi-6-ax200-on-windows-1110/"><u>Intel Wireless Network Adapter Driver Download and Update for Wi-Fi 6 AX200 on Windows 11/10</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722976682305-kodak-printer-drivers-download-and-update-easily/"><u>KODAK Printer Drivers Download & Update Easily!</u></a></li>
<li><a href="https://games-able.techidaily.com/leading-list-of-11-excellent-cost-free-words-games/"><u>Leading List of 11 Excellent, Cost-Free Words Games</u></a></li>
<li><a href="https://win-dash.techidaily.com/quick-guide-downloading-intels-thunderbolt-chip-drivers-with-ease/"><u>Quick Guide: Downloading Intel's Thunderbolt Chip Drivers with Ease</u></a></li>
<li><a href="https://win-dash.techidaily.com/speedy-setup-your-guide-to-downloading-elgato-drivers-today/"><u>Speedy Setup: Your Guide to Downloading Elgato Drivers Today</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/the-ultimate-guide-to-earning-top-dollar-from-your-old-dvd-collection-on-a-local-and-global-scale/"><u>The Ultimate Guide to Earning Top Dollar From Your Old DVD Collection on a Local and Global Scale</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/ultimate-collection-of-netflixs-3d-movies-201/"><u>Ultimate Collection of Netflix's 3D Movies (201</u></a></li>
</ul></div>

