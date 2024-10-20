---
title: "Mastering Microsoft Excel: A Step-by-Step Guide on Leveraging the YEAR Function"
date: 2024-10-19T18:28:45.665Z
updated: 2024-10-20T18:31:12.308Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/0ca2747bace885998e167d601fb15c3166c8be683eacac54f4c7c14302087724.jpg
---

## Mastering Microsoft Excel: A Step-by-Step Guide on Leveraging the YEAR Function

If you need to quickly extract the year from a date in Microsoft Excel, you can use the YEAR function. This will give you the year value in a separate cell, allowing you to use it in a separate formula.

 The YEAR function can be especially useful if you've [converted text to date values in Excel,](https://screen-mirror.techidaily.com/how-to-screen-mirroring-samsung-galaxy-xcover-7-drfone-by-drfone-android/) and you want to extract the year values from your data.

Related: [How to Convert Text to Date Values in Microsoft Excel](https://screen-mirror.techidaily.com/how-to-screen-mirroring-samsung-galaxy-xcover-7-drfone-by-drfone-android/) 

 To use the YEAR function, you'll need to open your Excel spreadsheet and have cells containing dates (in any format) set as an appropriate "Date" number value.

 It's best to set these cell values as "Long Date" or "Short Date" numbers value using the Home > Number drop-down menu. You can also use cells with custom date formats.

![Ensure cells with dates in Excel are set to an appropriate &quot;Date&quot; number value using the Home &gt; Number drop-down menu.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/09/Excel-Set-Number-as-Date.png) 

 If you have a date converted to a number, you can also extract the year from a 5-digit Excel "serial" number, which counts the number of days from the 1st January 1900\. You can see this value by changing any date value to a standard number value using the Home > Number menu.

 Because of this particular limit, you can only use YEAR to extract the year from dates starting from the 1st January 1900 onwards. The function won't work with dates earlier than that.

 To extract the year from a cell containing a date, type 

        `=YEAR(CELL)`
    
 , replacing 

        `CELL`
    
 with a cell reference. For instance, 

        `=YEAR(A2)`
    
 will take the date value from cell A2 and extract the year from it.

![Examples of the YEAR function used in Microsoft Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/09/Excel-YEAR-Function.png) 

 The example above shows various styles of date values in column A. Regardless of the format, the YEAR function used in column B is able to read these and extract the year value.

 If you prefer, you could also use a 5-digit Excel "serial" number, rather than a cell reference.

![Examples of the YEAR function used in Microsoft Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/09/Excel-YEAR-Function.png) 

 The example above shows this using the formula 

        `=YEAR(43478)`
    
 , with a serial number (43478) matching the date (13th January 2019), which the YEAR function is able to understand. From this serial number, the year (2019) is returned.

 The value returned by a formula containing the YEAR function can then be used by other formula. For instance, you could combine it with a DATE formula (eg. 

        `=DATE(YEAR(A2),1,11`
    
) to create a valid date value.

![An example DATE formula value, created using the value created by a YEAR formula in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/09/Excel-DATE-Function-Example.png) 

 If you want to repeat it for multiple date values, you can [use the fill handle](https://visual-screen-recording.techidaily.com/new-in-2024-top-5-best-hdmi-21-gaming-monitors-ps5-compatible/) to copy the YEAR formula into additional cells.

Related: [How to Automatically Fill Sequential Data into Excel with the Fill Handle](https://visual-screen-recording.techidaily.com/new-in-2024-top-5-best-hdmi-21-gaming-monitors-ps5-compatible/)

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
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-from-live-action-to-digital-footage-gadget-guidebook/"><u>[New] 2024 Approved From Live Action to Digital Footage Gadget Guidebook</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-androids-lightroom-app-decoded-a-complete-analysis-for-2024/"><u>[New] Android's Lightroom App Decoded A Complete Analysis for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/n-2024-streaming-success-enter-the-500-sub-club-for-profit/"><u>[New] In 2024, Streaming Success Enter the 500-Sub Club for Profit</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-in-2024-accessing-facebook-videos-via-apple-tv-essential-tips/"><u>[Updated] In 2024, Accessing Facebook Videos via Apple TV Essential Tips</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-pinnacle-platforms-transforming-online-interaction-for-2024/"><u>[Updated] Pinnacle Platforms Transforming Online Interaction for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/brand-pixels-customizing-gaming-banners-with-style-for-2024/"><u>Brand Pixels Customizing Gaming Banners with Style for 2024</u></a></li>
<li><a href="https://win-dash.techidaily.com/effortlessly-fix-your-bcm2045a0-driver-problems-a-step-by-step-guide/"><u>Effortlessly Fix Your BCM2045A0 Driver Problems: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-dash.techidaily.com/enhance-gaming-with-newest-geforce-rtx-3080-driver-optimized-for-windows-11-8-and-7/"><u>Enhance Gaming with Newest GeForce RTX 3080 Driver - Optimized for Windows 11, 8 & 7</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/from-recordings-to-live-an-obs-guide-to-youtube-and-twitch-streaming/"><u>From Recordings to Live An OBS Guide to YouTube and Twitch Streaming</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-your-hp-laserjet-pro-mfp-m1n27fn-device-drivers-here-for-windows-and-mac/"><u>Get Your HP LaserJet Pro MFP M1n27Fn Device Drivers Here for Windows and Mac</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-your-zexmt-usb-bluetooth-dongle-updated-drivers-for-windows-pcs-7-8-and-11/"><u>Get Your ZexMT USB Bluetooth Dongle Updated Drivers for Windows PCs (7, 8, & 11)</u></a></li>
<li><a href="https://win-dash.techidaily.com/installing-printer-drivers-made-simple-epson-wf-2750-software-free/"><u>Installing Printer Drivers Made Simple - Epson WF-2750 Software FREE!</u></a></li>
<li><a href="https://win-dash.techidaily.com/instant-access-to-wacom-drivers-fast-and-easy-download-process/"><u>Instant Access to Wacom Drivers - Fast and Easy Download Process</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722976479355-mrs-analyzes-the-biochemical-makeup-of-brain-tissue-and-can-help-differentiate-between-types-of-brain-lesions/"><u>MRS Analyzes the Biochemical Makeup of Brain Tissue and Can Help Differentiate Between Types of Brain Lesions</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-2024-approved-replace-sony-vegas-with-these-powerful-windows-video-editing-tools/"><u>New 2024 Approved Replace Sony Vegas with These Powerful Windows Video Editing Tools</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-get-rid-of-tiktok-logos-best-online-watermark-removers-for-2024/"><u>New Get Rid of TikTok Logos Best Online Watermark Removers for 2024</u></a></li>
<li><a href="https://win-dash.techidaily.com/seamlessly-upload-your-wacom-intuos-pro-driver-to-windows-11/"><u>Seamlessly Upload Your Wacom Intuos Pro Driver to Windows 11</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049387/7443" target="_top" id="2049387">
  <img src="//a.impactradius-go.com/display-ad/7443-2049387" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049387/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

