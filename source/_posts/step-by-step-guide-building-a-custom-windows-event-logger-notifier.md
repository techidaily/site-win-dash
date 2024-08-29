---
title: "Step-by-Step Guide: Building a Custom Windows Event Logger Notifier"
date: 2024-08-28T01:33:44.988Z
updated: 2024-08-29T01:33:44.988Z
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

##  How It Works

 Our solution works by using a freeware utility, MyEventViewer, by Nirsoft which allows you to easily export Windows Event Logs to a comma separated file. Based on this output, we have developed an easy to configure batch script which filters these results and then can email and/or save the filtered results file. Because the results are a comma separated file, it can be opened in Excel (or your favorite CSV program) and further sorted and filtered.

<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1896607/21553" target="_top" id="1896607"><img src="//a.impactradius-go.com/display-ad/21553-1896607" border="0" alt="" width="750" height="422"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1896607/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Configuration

 The configuration settings and options are documented as inline comments in the script, however we will cover a few of them in a bit of detail here.

**Event Log Name** 

 When specifying the Event Logs you want to capture the events from, you must use the system full name of the log. This is not necessarily what you see in the Event Viewer list of logs.

 For example, if you wanted to capture events from the "Microsoft Office Alerts" log, go to the Properties dialog of the log.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2011/08/image1.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4621764&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.x-mirage.com/x-mirage/img/page-home.jpg" border="0"></a>
<!-- affiliate ads end -->
 Note the value in the Full Name value, in this case "OAlerts". This would be the value you would need to enter into the script's configuration.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2011/08/image2.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4530091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/cit_win/banScrn.jpg" border="0">CollageIt Pro</a>
<!-- affiliate ads end -->
**Event Types** 

 The values for the Event Types is simply the text you see in the "Level" column when you are viewing Event Logs. Typically these are either Information, Warning or Error but various logs may have different values.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2011/08/image3.png) 

<!-- affiliate ads begin -->
<a href="https://turtlebeachus.sjv.io/c/5597632/1988416/23719" target="_top" id="1988416"><img src="//a.impactradius-go.com/display-ad/23719-1988416" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1988416/23719" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**Scheduled Task Setup** 

 The typical usage of this script is most likely in an automated process. So to make sure there is no overlap between your capture interval and when the process runs, you should set up a Windows Scheduled Task to complement the capture time.

 Quite simply, if your configuration is set to capture events for the last day, you should have a scheduled task that runs once per day. If your configuration is set to capture for the last hour, your scheduled task should be set to run once every hour. Etc.

 As an additional note, in order to make sure the MyEventViewer application can get to the information it needs, the respective scheduled task should be run with administrator rights on the machine.

![image](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2011/08/image4.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BScreen%2BRecorder%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/f026b149-fc7c-fd54-5f3e-1460bbb19b6b.jpg" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://instagram-clips.techidaily.com/new-direct-to-your-library-simple-windows-and-mac-techniques-for-downloading-igtv/"><u>[New] Direct to Your Library  Simple Windows & Mac Techniques for Downloading IGTV</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-in-2024-parrots-in-flight-a-deep-dive-into-bebops-essence/"><u>[New] In 2024, Parrots in Flight  A Deep Dive Into Bebop's Essence</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-parallel-audio-stream-mapping/"><u>[New] Parallel Audio Stream Mapping</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-step-by-step-manual-implementing-speech-to-text-with-google-docs-for-2024/"><u>[New] Step-by-Step Manual  Implementing Speech to Text with Google Docs for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-from-fan-to-earner-understanding-view-requirements/"><u>[Updated] 2024 Approved  From Fan to Earner  Understanding View Requirements</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-sunshine-strategies-to-lighten-up-android-videos/"><u>[Updated] 2024 Approved  Sunshine Strategies to Lighten up Android Videos</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-elevate-viewer-connection-mastering-the-art-of-square-footage-in-videos/"><u>[Updated] Elevate Viewer Connection  Mastering the Art of Square Footage in Videos</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-efficiency-in-conversion-a-compact-list-of-the-top-10-video-transformers/"><u>[Updated] In 2024, Efficiency in Conversion  A Compact List of the Top 10 Video Transformers</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-ranking-the-top-10-secret-stories-observers/"><u>[Updated] In 2024, Ranking the Top 10 Secret Stories Observers</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-straightforward-storyline-outline/"><u>[Updated] Straightforward Storyline Outline</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-youtube-cpm-rates-how-much-do-youtubers-make-for-2024/"><u>[Updated] YouTube CPM Rates  How Much Do YouTubers Make for 2024</u></a></li>
<li><a href="https://win-dash.techidaily.com/amd-radeon-rx-amo-easy-download-and-update-of-drivers/"><u>AMD Radeon RX Amo - Easy Download and Update of Drivers</u></a></li>
<li><a href="https://win-dash.techidaily.com/compatible-logitech-brio-webcam-driver-downloads-for-windows-1087-users/"><u>Compatible Logitech BRIO Webcam Driver Downloads for Windows 10/8/7 Users</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/conquered-recurring-monitor-blanks-now-stable/"><u>Conquered Recurring Monitor Blanks, Now Stable</u></a></li>
<li><a href="https://tech-revival.techidaily.com/creating-a-customized-chatbot-with-gpt-ai-from-concept-to-creation/"><u>Creating a Customized Chatbot with GPT AI: From Concept to Creation</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/cutting-edge-techniques-for-live-videos-from-your-smartphone-for-2024/"><u>Cutting-Edge Techniques for Live Videos From Your Smartphone for 2024</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-and-install-latest-driver-updates-for-nvidia-rtx-2070-super-on-windows-11/"><u>Download and Install Latest Driver Updates for Nvidia RTX 2070 Super on Windows 11</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-and-install-your-logitech-webcam-drivers-on-windows-1011-c623/"><u>Download and Install Your Logitech Webcam Drivers on Windows 10/11 (C623)</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-hp-officejet-pro-8600-printer-drivers-on-windows-step-by-step-guide/"><u>Download HP Officejet Pro 8600 Printer Drivers on Windows: Step-by-Step Guide</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-intels-official-usb-30-drivers-for-seamless-integration-with-windows-11/"><u>Download Intel's Official USB 3.0 Drivers for Seamless Integration with Windows 11</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-intelligent-thunderbolt-drivers-fast-simple-steps-inside/"><u>Download Intelligent Thunderbolt Drivers Fast: Simple Steps Inside</u></a></li>
<li><a href="https://win-dash.techidaily.com/easy-instructions-for-integrating-beats-audio-into-your-system/"><u>Easy Instructions for Integrating Beats Audio Into Your System</u></a></li>
<li><a href="https://win-dash.techidaily.com/epson-l3150-printer-drivers-download-and-installation-guide-for-windows-1187/"><u>Epson L3150 Printer Drivers: Download & Installation Guide for Windows 11/8/7</u></a></li>
<li><a href="https://win-dash.techidaily.com/free-epson-wf-2630-driver-download-updated-software-for-windows-os-versions/"><u>Free Epson WF 2630 Driver Download: Updated Software for Windows OS Versions</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722963012436-get-the-latest-canon-drivers-fast-free-downloads-and-guides-for-windows-users/"><u>Get the Latest Canon Drivers Fast - Free Downloads & Guides for Windows Users</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-new-driver-for-your-lenovo-camera-compatible-with-windows-n-7-systems/"><u>Get the New Driver for Your Lenovo Camera: Compatible with Windows N 7 Systems</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-new-geforce-rtx-3080-ti-windows-support-package-win-1087/"><u>Get the New GeForce RTX 3080 Ti Windows Support Package (Win 10/8/7)</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-newest-drivers-for-your-epson-xp-310-free-download-available-now/"><u>Get the Newest Drivers for Your Epson XP-310 - Free Download Available Now</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-your-realtek-rtl8188cu-wireless-network-adapter-driver-for-win-107-today/"><u>Get Your Realtek RTL8188CU Wireless Network Adapter Driver for Win 10/7 Today!</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/guide-to-identifying-recent-instagram-leavers/"><u>Guide to Identifying Recent Instagram Leavers</u></a></li>
<li><a href="https://win-dash.techidaily.com/guide-how-to-get-the-newest-version-of-sas-for-your-pc-windows/"><u>Guide: How To Get The Newest Version Of SAS for Your PC (Windows)</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-get-your-hands-on-free-nvidia-3d-vision-drivers-for-windows-without-hassle/"><u>How to Get Your Hands on Free Nvidia 3D Vision Drivers for Windows Without Hassle</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-hidefake-snapchat-location-on-your-meizu-21-pro-drfone-by-drfone-virtual-android/"><u>How to Hide/Fake Snapchat Location on Your Meizu 21 Pro | Dr.fone</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-install-the-newest-canon-mg2n-software-on-your-inkjet-printer/"><u>How to Install the Newest Canon MG2n Software on Your Inkjet Printer</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-keep-your-microsoft-surface-book-2-running-smoothly-with-driver-updates/"><u>How to Keep Your Microsoft Surface Book 2 Running Smoothly with Driver Updates</u></a></li>
<li><a href="https://techidaily.com/how-to-perform-hard-reset-on-vivo-v29e-drfone-by-drfone-reset-android-reset-android/"><u>How to Perform Hard Reset on Vivo V29e? | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-bypass-icloud-by-checkra1n-even-from-apple-iphone-6-plus-if-youve-tried-everything-by-drfone-ios/"><u>In 2024, How To Bypass iCloud By Checkra1n Even From Apple iPhone 6 Plus If Youve Tried Everything</u></a></li>
<li><a href="https://article-files.techidaily.com/in-2024-the-essential-guide-to-downloading-and-editing-whatsapp-alerts/"><u>In 2024, The Essential Guide to Downloading & Editing WhatsApp Alerts</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-5-tracking-apps-to-track-vivo-y100a-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, Top 5 Tracking Apps to Track Vivo Y100A without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://win-dash.techidaily.com/install-latest-intel-hd-graphics-drivers-compatible-with-windows-1011-free-downloads/"><u>Install Latest Intel HD Graphics Drivers Compatible with Windows 10/11 - Free Downloads</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-2024-approved-proven-7-audio-processors-to-peacefully-remove-populated-sounds-from-media/"><u>New 2024 Approved Proven 7 Audio Processors to Peacefully Remove Populated Sounds From Media</u></a></li>
<li><a href="https://win-dash.techidaily.com/official-guide-to-obtain-and-install-samsung-mobile-device-adb-drivers/"><u>Official Guide to Obtain and Install Samsung Mobile Device Adb Drivers</u></a></li>
<li><a href="https://windows11.techidaily.com/preventing-issues-with-the-epic-games-launcher-for-win-users/"><u>Preventing Issues with the Epic Games Launcher for Win Users</u></a></li>
<li><a href="https://win-dash.techidaily.com/quick-fix-with-validity-fingerprint-sensor-driver-download-today/"><u>Quick Fix with Validity Fingerprint Sensor Driver - Download Today</u></a></li>
<li><a href="https://win-dash.techidaily.com/quick-guide-updating-dell-inspiron-g7-drivers-with-speed-and-simplicity/"><u>Quick Guide: Updating Dell Inspiron G7 Drivers with Speed and Simplicity</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/resolving-dota-2-game-crashes-effective-solutions-and-tips/"><u>Resolving Dota 2 Game Crashes: Effective Solutions and Tips</u></a></li>
<li><a href="https://win-dash.techidaily.com/resolving-problems-with-the-realtek-rtl8723be-network-adapter-drivers/"><u>Resolving Problems with the Realtek RTL8723BE Network Adapter Drivers</u></a></li>
<li><a href="https://win-dash.techidaily.com/seamless-download-and-update-how-to-get-the-newest-drivers-for-your-amd-rx-580/"><u>Seamless Download and Update: How to Get the Newest Drivers for Your AMD RX 580</u></a></li>
<li><a href="https://win-dash.techidaily.com/step-by-step-process-to-fresh-update-of-epson-printing-drivers-in-windows-10/"><u>Step-by-Step Process to Fresh Update of Epson Printing Drivers in Windows 10</u></a></li>
<li><a href="https://win11.techidaily.com/step-by-step-to-delete-onedrive-icon-in-windows-explore/"><u>Step-by-Step to Delete OneDrive Icon in Windows Explore</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/switching-from-snippet-to-live-play-in-yt-for-2024/"><u>Switching From Snippet to Live Play in YT for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/tutorial-to-change-motorola-edge-2023-imei-without-root-a-comprehensive-guide-by-drfone-android/"><u>Tutorial to Change Motorola Edge 2023 IMEI without Root A Comprehensive Guide</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/unleashing-potential-profile-video-elevation/"><u>Unleashing Potential  Profile Video Elevation</u></a></li>
<li><a href="https://win-dash.techidaily.com/up-to-date-konica-minolta-printer-drivers-available-here-tailored-to-work-on-windows-11-down-to-v7/"><u>Up-to-Date Konica Minolta Printer Drivers Available Here: Tailored to Work on Windows 11 Down to V7</u></a></li>
<li><a href="https://win-dash.techidaily.com/update-your-dell-thunderbolt-tb17-adapter-free-driver-download-and-installation-guide/"><u>Update Your Dell Thunderbolt TB17 Adapter - Free Driver Download & Installation Guide</u></a></li>
<li><a href="https://win-dash.techidaily.com/update-your-epson-wf-3720-printer-software-for-optimal-performance/"><u>Update Your Epson WF-3720 Printer Software for Optimal Performance</u></a></li>
</ul></div>
