---
title: The Essential Tricks to Utilizing Excel's TRUNC Function for Data Handling Accuracy
date: 2024-08-28T01:34:53.080Z
updated: 2024-08-29T01:34:53.080Z
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
##  How to Use the TRUNC Function

 Let's look at examples of the TRUNC function with some sample data. The below example uses the following TRUNC function.

=TRUNC(A2)

 If you do not specify how many digits to truncate, all decimal places will be removed.

![First TRUNC function example](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/03/first-example.png) 

 You can see with the value in cell A2 that the TRUNC function does not apply any rounding. It simply truncates the number to 411.

 Let's see another example. This time we will reduce the values to two decimal places.

=TRUNC(A2,2)

![TRUNC function to two decimal places](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/03/two-decimal-places.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
<!-- affiliate ads end -->
 The TRUNC function will not display extra decimals if you ask it to show more than you have.

 Take the following example, and let's truncate it to two decimal places.

=TRUNC(A2,2)

![No extra decimals shown by TRUNC](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/03/no-extra-decimals.png) 

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793233/19578" target="_top" id="1793233"><img src="//a.impactradius-go.com/display-ad/19578-1793233" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793233/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 The value in cell A4 is reduced to two decimal places, but the values in A2 and A3 stay as they are because they have less than two decimal places already.

 If you want to display the two decimals, the cells will need to be formatted to be forced to show them.

##  Remove the Time from a Date-Time Stamp

 A useful example of TRUNC is to remove the time from a date and time stamp in Excel.

 Imagine having the following date and time stamps, but we just want the date in a column for analysis.

![Date and time sample data](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/03/date-and-time-data.png) 

<!-- affiliate ads begin -->
<span id="1993650">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 The following formula will work to remove the time.

=TRUNC(A2)

![Time removed from a date in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/03/time-removed.png) 

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->
 Although the time is removed, the resulting cells will still need to be formatted as a date only.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
<!-- affiliate ads end -->
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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-foremost-news-channels-on-youtube-to-watch-daily/"><u>[New] 2024 Approved  Foremost News Channels on YouTube to Watch Daily</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-exclusive-guide-turning-fb-videos-into-mp4-and-hd/"><u>[New] Exclusive Guide  Turning FB Videos Into MP4 & HD</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-brain-mechanisms-guiding-high-stakes-business-conclusions/"><u>[New] In 2024, Brain Mechanisms Guiding High-Stakes Business Conclusions</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-enhance-video-purity-optimal-watermark-eliminators/"><u>[New] In 2024, Enhance Video Purity  Optimal Watermark Eliminators</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-the-ultimate-chrome-selection-5-pioneers-in-fb-video-download-for-2024/"><u>[Updated] The Ultimate Chrome Selection  5 Pioneers in FB Video Download for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-accurate-age-reflection-in-just-a-minute/"><u>2024 Approved  Accurate Age Reflection in Just a Minute</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-ultimate-guide-to-the-best-10-cost-free-photo-hosters/"><u>2024 Approved  Ultimate Guide to the Best 10 Cost-Free Photo Hosters</u></a></li>
<li><a href="https://win-dash.techidaily.com/complete-guide-downloading-the-hp-universal-print-driver-compatible-with-windows/"><u>Complete Guide: Downloading the HP Universal Print Driver Compatible with Windows</u></a></li>
<li><a href="https://win-dash.techidaily.com/direct-link-to-download-hp-photosmart-7520-printers-essential-software/"><u>Direct Link to Download HP Photosmart 7520 Printer's Essential Software</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-amd-radeon-rx-6800-drivers-on-windows-11-10-8-and-7-step-by-step-guide/"><u>Download AMD Radeon RX 6800 Drivers on Windows 11, 10, 8 & 7 – Step by Step Guide</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-the-latest-lenovo-thunderbolt-3-docking-station-drivers/"><u>Download the Latest Lenovo Thunderbolt 3 Docking Station Drivers</u></a></li>
<li><a href="https://win-dash.techidaily.com/easy-installation-lenovo-x1-carbon-drivers-for-windows-11-and-7-systems/"><u>Easy Installation: Lenovo X1 Carbon Drivers for Windows 11 and 7 Systems</u></a></li>
<li><a href="https://win-dash.techidaily.com/effortless-fixes-resolving-compatibility-issues-between-i2c-and-hid-device-drivers/"><u>Effortless Fixes: Resolving Compatibility Issues Between I2C and HID Device Drivers</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722957164463-effortless-installation-of-scansnap-drivers-on-windows-get-your-latest-updates-now/"><u>Effortless Installation of ScanSnap Drivers on Windows – Get Your Latest Updates Now</u></a></li>
<li><a href="https://driver-error.techidaily.com/fix-built-in-wifi-and-bluetooth-on-my-laptop-refuse-to-shut-down-in-windows/"><u>Fix: Built-In Wifi and Bluetooth on My Laptop Refuse to Shut Down in Windows</u></a></li>
<li><a href="https://win-dash.techidaily.com/free-download-quick-and-simple-guide-to-installing-easycap-driver/"><u>Free Download: Quick & Simple Guide to Installing EasyCap Driver</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-most-recent-nvidia-quadro-graphics-driver-updates-for-windows-11-systems/"><u>Get the Most Recent NVIDIA Quadro Graphics Driver Updates for Windows 11 Systems</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-get-the-newest-logitech-mk710-driver-version-online/"><u>How to Get the Newest Logitech MK710 Driver Version Online</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-obtain-and-upgrade-sas-software-on-your-pc-windows-10-8-or-7/"><u>How to Obtain and Upgrade SAS Software on Your PC (Windows 10, 8, or 7)</u></a></li>
<li><a href="https://fox-http.techidaily.com/how-to-prevent-youtube-from-starting-video-before-you-watch/"><u>How to Prevent YouTube From Starting Video Before You Watch</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-corrupt-mp4-and-mov-files-of-vivo-y100-5g-by-stellar-video-repair-mobile-video-repair/"><u>How to Repair corrupt MP4 and MOV files of Vivo Y100 5G?</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722964081742-hp-officejet-3830-driver-download-for-windows-step-by-step-tutorial-included/"><u>HP Officejet 3830 Driver Download for Windows - Step-by-Step Tutorial Included</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-a-quick-guide-to-nubia-red-magic-9-pro-frp-bypass-instantly-by-drfone-android/"><u>In 2024, A Quick Guide to Nubia Red Magic 9 Pro FRP Bypass Instantly</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-masterful-iphone-videography-top-8-expert-filmmaking-advice/"><u>In 2024, Masterful iPhone Videography  Top 8 Expert Filmmaking Advice</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-pc-video-editors-like-gopro-quik-top-picks-and-reviews/"><u>In 2024, PC Video Editors Like GoPro Quik Top Picks and Reviews</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-the-ultimate-guide-to-xiaomi-13t-pro-pattern-lock-screen-everything-you-need-to-know-by-drfone-android/"><u>In 2024, The Ultimate Guide to Xiaomi 13T Pro Pattern Lock Screen Everything You Need to Know</u></a></li>
<li><a href="https://win-dash.techidaily.com/instant-access-secure-brother-mfc-9130cw-driver-software/"><u>Instant Access: Secure Brother MFC-9130CW Driver Software</u></a></li>
<li><a href="https://win-dash.techidaily.com/maintaining-optimal-sound-performance-updating-usb-audio-drivers-in-windows-oses/"><u>Maintaining Optimal Sound Performance: Updating USB Audio Drivers in Windows OSes</u></a></li>
<li><a href="https://win-dash.techidaily.com/master-the-art-of-webcam-driver-updates-for-windows-7-with-these-steps/"><u>Master the Art of Webcam Driver Updates for Windows 7 with These Steps</u></a></li>
<li><a href="https://extra-hints.techidaily.com/mastering-media-manipulation-combining-windows-photos-and-story-remix/"><u>Mastering Media Manipulation  Combining Windows Photos and Story Remix</u></a></li>
<li><a href="https://win-dash.techidaily.com/official-m-audio-fast-track-drivers-for-windows-users-free-download-for-win11-win7-win8-and-win81/"><u>Official M-Audio Fast Track Drivers for Windows Users: Free Download for Win11, Win7, Win8 & Win8.1</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722978171100-optimize-your-pcs-wireless-networking-with-the-latest-intel-wi-fi-6-ax200-driver-update-for-windows-users/"><u>Optimize Your PC's Wireless Networking with the Latest Intel Wi-Fi 6 AX200 Driver Update for Windows Users</u></a></li>
<li><a href="https://win-dash.techidaily.com/optimizing-your-productivity-with-logiteeck-mx-master-setup-guide/"><u>Optimizing Your Productivity with Logiteeck MX Master Setup Guide</u></a></li>
<li><a href="https://win-dash.techidaily.com/samsung-c460-driver-installation-fast-and-simple-steps/"><u>Samsung C460 Driver Installation - Fast and Simple Steps</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722964396407-step-by-step-download-of-intel-cpugpu-drivers-instant-access/"><u>Step-by-Step Download of Intel CPU/GPU Drivers - Instant Access</u></a></li>
<li><a href="https://win-dash.techidaily.com/step-by-step-guide-successfully-installing-your-epson-xp-830-printer-drivers/"><u>Step-by-Step Guide: Successfully Installing Your Epson XP-830 Printer Drivers</u></a></li>
<li><a href="https://win-dash.techidaily.com/successful-strategies-for-installing-latest-amd-radeon-driver-updates/"><u>Successful Strategies for Installing Latest AMD Radeon Driver Updates</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722978788569-successfully-update-or-download-new-d-link-drivers-for-windows-quick-fixes-revealed/"><u>Successfully Update or Download New D-Link Drivers for Windows - Quick Fixes Revealed!</u></a></li>
<li><a href="https://win-dash.techidaily.com/update-to-intels-hd-graphics-4400-drivers-now-free-and-easy-to-get/"><u>Update to Intel's HD Graphics 4400 Drivers Now - Free & Easy to Get!</u></a></li>
<li><a href="https://win-dash.techidaily.com/updated-sapphire-driver-software-how-to-install-on-your-windows-system/"><u>Updated Sapphire Driver Software: How to Install on Your Windows System</u></a></li>
</ul></div>
