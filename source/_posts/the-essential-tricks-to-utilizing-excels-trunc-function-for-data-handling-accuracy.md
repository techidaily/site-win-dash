---
title: The Essential Tricks to Utilizing Excel's TRUNC Function for Data Handling Accuracy
date: 2024-10-16T18:43:59.904Z
updated: 2024-10-20T16:49:23.744Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/07/stock-lede-microsoft-office_excel-1.png
---

## The Essential Tricks to Utilizing Excel's TRUNC Function for Data Handling Accuracy

### Quick Links

* [What Is the TRUNC Function?](https://extra-resources.techidaily.com/systematic-upgrade-procedures-for-macos-sierra-users/)
* [How to Use the TRUNC Function](https://data-wizards.techidaily.com/immediate-fix-to-freezing-problem-in-vlc/)
* [Remove the Time from a Date-Time Stamp](https://fox-direct.techidaily.com/exploring-interconnected-digital-universes-meta-and-omni-for-2024/)
* [Use TRUNC to Shorten Numbers](https://fox-info.techidaily.com/updated-the-ultimate-strategy-for-posting-srt-content-socially/)

 There are a variety of ways in Excel to remove decimal points and shortening number values. In this article, we explain how to use the TRUNC function and what makes it different from other techniques.

##  What Is the TRUNC Function?

 The TRUNC function truncates a number to a specified number of decimal places. The key factor that makes TRUNC different from other functions that remove decimal places is that the TRUNC function does not round values. If you use TRUNC to remove all the decimals from the value 4.68, the result is 4.

 The TRUNC function requires two pieces of information:

=TRUNC(number, [digits])

 The number is the value you want to truncate. Digits are the number of numerals you want to truncate the value to. The digits portion is optional, and if not answered, TRUNC will remove all decimal places.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136618/26400" target="_top" id="2136618">
  <img src="//a.impactradius-go.com/display-ad/26400-2136618" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136618/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  How to Use the TRUNC Function

 Let's look at examples of the TRUNC function with some sample data. The below example uses the following TRUNC function.

=TRUNC(A2)

 If you do not specify how many digits to truncate, all decimal places will be removed.

![First TRUNC function example](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/03/first-example.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1934183/19272" target="_top" id="1934183">
  <img src="//a.impactradius-go.com/display-ad/19272-1934183" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934183/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can see with the value in cell A2 that the TRUNC function does not apply any rounding. It simply truncates the number to 411.

 Let's see another example. This time we will reduce the values to two decimal places.

=TRUNC(A2,2)

![TRUNC function to two decimal places](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/03/two-decimal-places.png) 

 The TRUNC function will not display extra decimals if you ask it to show more than you have.

 Take the following example, and let's truncate it to two decimal places.

=TRUNC(A2,2)

![No extra decimals shown by TRUNC](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/03/no-extra-decimals.png) 

 The value in cell A4 is reduced to two decimal places, but the values in A2 and A3 stay as they are because they have less than two decimal places already.

 If you want to display the two decimals, the cells will need to be formatted to be forced to show them.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484939/16446" target="_top" id="1484939">
  <img src="//a.impactradius-go.com/display-ad/16446-1484939" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484939/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Remove the Time from a Date-Time Stamp

 A useful example of TRUNC is to remove the time from a date and time stamp in Excel.

 Imagine having the following date and time stamps, but we just want the date in a column for analysis.

![Date and time sample data](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/03/date-and-time-data.png) 

 The following formula will work to remove the time.

=TRUNC(A2)

![Time removed from a date in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/03/time-removed.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043639/7443" target="_top" id="2043639">
  <img src="//a.impactradius-go.com/display-ad/7443-2043639" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043639/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Although the time is removed, the resulting cells will still need to be formatted as a date only.

##  Use TRUNC to Shorten Numbers

 This is a rare technique, but it is worth knowing that the TRUNC function will also accept negative numbers for the digits argument. When you use a negative number, the formula truncates the numbers to the left of the decimal point. However, it does not change the number of digits. It will replace them with zeroes.

 Let's look at the following example.

=TRUNC(A2,-1)

![Entering minus digits for the second argument](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/03/minus-digits.png) 

 You can see in each example that zero was used to replace the number that was removed from the left of the decimal point.

---

 There are multiple ways in Excel to remove decimal places, however, most of these will apply a rounding of some nature. The strength of the TRUNC function is that it does not round values and simply shortens them to the specified decimal place amount.

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
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-navigating-the-path-of-adobe-presenter-video-creation/"><u>[New] 2024 Approved Navigating the Path of Adobe Presenter Video Creation</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-advanced-screenshot-options-for-windows-users/"><u>[New] In 2024, Advanced Screenshot Options for Windows Users</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-2024-approved-the-insider-guide-to-listening-to-podcasts-on-your-iphone/"><u>[Updated] 2024 Approved The Insider Guide to Listening to Podcasts on Your iPhone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/blueprint-for-buzz-elevating-your-profile-on-fb/"><u>Blueprint for Buzz Elevating Your Profile on FB</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-and-update-mpow-bluetooth-drivers-for-windows-1187-easy-guide/"><u>Download and Update MPOW Bluetooth Drivers for Windows 11/8/7: Easy Guide</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-and-update-the-ultimate-creative-webcam-driver-guide-for-windows-users/"><u>Download and Update: The Ultimate Creative Webcam Driver Guide for Windows Users</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-windows-8-radeon-hd-graphics-drivers-for-free-amd/"><u>Download Windows 8 Radeon HD Graphics Drivers For Free - AMD</u></a></li>
<li><a href="https://win-dash.techidaily.com/easy-setup-guide-downloading-and-installing-brother-mfc-9130cw-drivers/"><u>Easy Setup Guide: Downloading and Installing Brother MFC-9130CW Drivers</u></a></li>
<li><a href="https://win-dash.techidaily.com/free-hp-network-adapter-drivers-for-windows-10-7-and-8-download-now/"><u>Free HP Network Adapter Drivers for Windows 10, 7 & 8 - Download Now!</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722962075455-get-your-canon-mf7e3cdw-drivers-on-windows-free-and-instant-access/"><u>Get Your Canon MF7e3CDW Drivers on Windows - Free and Instant Access</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722975187452-grab-your-gigabyte-audio-drivers-for-free/"><u>Grab Your Gigabyte AUDIO Drivers for FREE</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-ensure-seamless-operation-with-updated-zebra-printer-drivers-on-windows/"><u>How to Ensure Seamless Operation with Updated Zebra Printer Drivers on Windows</u></a></li>
<li><a href="https://tech-hub.techidaily.com/how-to-safely-change-proton-vpn-account-info-plus-unveiling-the-truth-behind-chatgpt-windows-applications/"><u>How to Safely Change Proton VPN Account Info + Unveiling the Truth Behind ChatGPT Windows Applications</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-safely-get-and-install-zebra-technologies-zp450-printer-drivers-a-comprehensive-tutorial/"><u>How to Safely Get and Install Zebra Technologies ZP450 Printer Drivers - A Comprehensive Tutorial</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-lightning-leap-into-facebook-id-sleuthing/"><u>In 2024, Lightning Leap Into Facebook ID Sleuthing</u></a></li>
<li><a href="https://review-topics.techidaily.com/lava-bypass-tools-to-bypass-lock-screen-lava-blaze-2-by-drfone-android-unlock-android-unlock/"><u>Lava Bypass Tools to Bypass Lock Screen(Lava Blaze 2)</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/perfect-your-posts-instagram-video-edits-with-borders/"><u>Perfect Your Posts Instagram Video Edits with Borders</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-inner-workings-of-an-ai-prompt-injection-assault-on-tech-systems/"><u>The Inner Workings of an AI Prompt Injection Assault on Tech Systems</u></a></li>
<li><a href="https://fox-ssl.techidaily.com/transforming-office-documents-into-interactive-ebooks-with-tables-of-contents-using-flipbuilder/"><u>Transforming Office Documents Into Interactive Ebooks With Tables of Contents Using FlipBuilder</u></a></li>
</ul></div>

