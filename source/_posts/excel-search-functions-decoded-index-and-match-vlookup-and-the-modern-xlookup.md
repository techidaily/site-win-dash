---
title: "Excel Search Functions Decoded: INDEX & MATCH, VLOOKUP, and the Modern XLOOKUP"
date: 2024-08-28T01:33:15.296Z
updated: 2024-08-29T01:33:15.296Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/4be59755ae7994bb626513b3614a3ec947be3b56430323187fb64d462d24a601.jpg
---

## Excel Search Functions Decoded: INDEX & MATCH, VLOOKUP, and the Modern XLOOKUP

### Quick Links

* [Using INDEX and MATCH](https://android-transfer.techidaily.com/in-2024-5-ways-to-transfer-music-from-samsung-galaxy-z-flip-5-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/)
* [Using VLOOKUP](https://fox-blue.techidaily.com/2024-approved-top-10-jpg-to-gif-converters-online-free/)
* [Using XLOOKUP](https://on-screen-recording.techidaily.com/new-2024-approved-streamline-your-zoom-meetings-screen-sharing-essentials/)
* [Which Is Better?](https://extra-guidance.techidaily.com/updated-quick-fix-techniques-for-social-media-collaborative-art/)

 Lookup [functions in Microsoft Excel](https://vimeo-videos.techidaily.com/in-2024-high-end-downloads-best-10-apps-for-extracting-vimeo-videos/) are ideal for finding what you need when you have a large amount of data. There are three common ways to do this; INDEX and MATCH, VLOOKUP, and XLOOKUP. But what's the difference?

 INDEX and MATCH, VLOOKUP, and XLOOKUP each serve the purpose of looking up data and returning a result. They each work a bit differently and require a specific syntax for the formula. When should you use which? Which is better? Let's take a look so you know the best option for you.

##  Using INDEX and MATCH

 Obviously, the INDEX and MATCH combination is a mixture of the two named functions. You can take a look at our how-tos for the [INDEX function](https://youtube-help.techidaily.com/in-2024-the-full-course-on-becoming-a-yt-creator-expert/) and [MATCH function](https://extra-guidance.techidaily.com/mirthful-missions-delving-into-the-goofy-movie-vhs-for-2024/) for specific details on using them individually.

 To use this duo, the syntax for each is 

        `INDEX(array, row_number, column_number)`
    
 and 

        `MATCH(value, array, match_type)`
    
 .

 When you combine the two, you'll have a syntax like this: 

        `INDEX(return_array, MATCH(lookup_value, lookup_array))`
    
 in its most basic form. It's easiest to look at some examples.

 To find a value in cell G2 in the range A2 through A8 and provide the matching result in the range B2 through B8, you would use this formula:

=INDEX(B2:B8,MATCH(G2,A2:A8))

![INDEX and MATCH with a cell reference](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/04/IndexMatchCell-ExcelLookupFunctions.png) 

 If you prefer to insert the value you want to find instead of using the cell reference, the formula looks like this where 2B is the lookup value:

=INDEX(B2:B8,MATCH("2B",A2:A8))

 Our result is Houston for both formulas.

![INDEX and MATCH with a value](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/04/IndexMatchValue-ExcelLookupFunctions.png) 

 We also have a tutorial that goes into detail on [using INDEX and MATCH](https://os-tips.techidaily.com/reviving-ipad-connectivity-essential-steps-for-reactivating-the-usb-driver/) should that be your choice.

Related: [How to Use INDEX and MATCH in Microsoft Excel](https://os-tips.techidaily.com/reviving-ipad-connectivity-essential-steps-for-reactivating-the-usb-driver/) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
##  Using VLOOKUP

 VLOOKUP has been a popular reference function in Excel for some time. The V stands for Vertical, so with VLOOKUP, you're doing a vertical lookup and it's from left to right.

 The syntax is `VLOOKUP(lookup_value, lookup_array, column_number, range_lookup)` with the last argument optional as True (approximate match) or False (exact match).

 Using the same data as that for INDEX and MATCH, we'll look up the value in cell G2 in the range A2 through D8 and return the value in the second column that matches. You'd use this formula:

=VLOOKUP(G2,A2:D8,2)

![VLOOKUP with a cell reference](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/04/VLOOKUPCell-ExcelLookupFunctions.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
 As you can see, the result using VLOOKUP is the same as using INDEX and MATCH, Houston. The difference is that VLOOKUP uses a much simpler formula. For more [details on VLOOKUP](https://win-able.techidaily.com/1723001670706-troubleshooting-genshin-impact-fix-stability-issues-and-stop-pc-crashes/), check out our how-to.

Related: [How to Use VLOOKUP on a Range of Values](https://win-able.techidaily.com/1723001670706-troubleshooting-genshin-impact-fix-stability-issues-and-stop-pc-crashes/) 

 So why would anyone use INDEX and MATCH instead of VLOOKUP? The answer is because VLOOKUP only works when your lookup value is to the left of the return value you want.

 If we did the reverse and wanted to look up a value in the fourth column and return the matching value in the second column, we would not receive the result we want and may even receive an error. As Microsoft [writes](https://support.microsoft.com/en-us/office/vlookup-function-0bbc8083-26fe-4963-8ab8-93a18ad188a1):

> Remember that the lookup value should always be in the first column in the range for VLOOKUP to work correctly. For example, if your lookup value is in cell C2 then your range should start with C.

 INDEX and MATCH covers the entire cell range or array making it a more robust lookup option even if the formula is a bit more complicated.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4631056&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/997e65474a248252883b485717f7d098/products/buy-windows.png" border="0">Allavsoft Batch Download Online Videos, Music Offline to MP4, MP3, MOV, etc format </a>
<!-- affiliate ads end -->
##  Using XLOOKUP

 XLOOKUP is a reference function that arrived in Excel after VLOOKUP and the counterpart HLOOKUP (horizontal lookup). The difference between XLOOKUP and VLOOKUP is that XLOOKUP works no matter where the lookup and return values reside in your cell range or array.

 The syntax is `XLOOKUP(lookup_value, lookup_array, return_array, not_found, match_mode, search_mode)`. The first three arguments are required and are similar to that in the VLOOKUP function. XLOOKUP offers three optional arguments at the end for giving a text result if the value isn't found, a mode for the type of match, and a mode for how to perform the search.

 For the purpose of this article, we'll concentrate on the first three required arguments.

 Back to our cell range from earlier, we'll look up the value in G2 in the range A2 through A8 and return the matching value from the range B2 through B8 with this formula:

=XLOOKUP(G2,A2:A8,B2:B8)

![XLOOKUP with a cell reference](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/04/XLOOKUPCell-ExcelLookupFunctions.png) 

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920054/21774" target="_top" id="1920054"><img src="//a.impactradius-go.com/display-ad/21774-1920054" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920054/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 And like with INDEX and MATCH as well as VLOOKUP, our formula returned Houston.

 We can also use a value in the fourth column as the lookup value and receive the correct result in the second column:

=XLOOKUP(20745,D2:D8,B2:B8)

![XLOOKUP from right to left](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/04/GoodXLOOKUP-ExcelLookupFunctions.png) 

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
<!-- affiliate ads end -->
 With this in mind, you can see that XLOOKUP is a better option than VLOOKUP simply because you can arrange your data any way you like and still receive your desired result. For a full [tutorial on XLOOKUP](https://android-transfer.techidaily.com/in-2024-5-ways-to-transfer-music-from-asus-rog-phone-7-ultimate-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/), head over to our how-to.

Related: [How to Use the XLOOKUP Function in Microsoft Excel](https://android-transfer.techidaily.com/in-2024-5-ways-to-transfer-music-from-asus-rog-phone-7-ultimate-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/) 

 So now you're wondering, should I use XLOOKUP or INDEX and MATCH, right? Here are some things to consider.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
##  Which Is Better?

 If you already use the INDEX and MATCH functions separately and have used them together to lookup values, then you may be more familiar with how they work. By all means, if it's not broken, don't fix it, and keep using what makes you comfortable.

 And of course, if your data is structured to work with VLOOKUP and you've used that function for years, you can continue using it or make the easy transition to XLOOKUP leaving INDEX and MATCH in the dust.

 If you want to a simple, easy-to-build formula in any direction, XLOOKUP is the way to go and can replace INDEX and MATCH. You don't have to worry about combining arguments from two functions into one or rearranging your data.

 One last consideration, [XLOOKUP does offer those three optional arguments](https://support.microsoft.com/en-us/office/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929) which may come in handy for your needs.

 Over to you! Which lookup option will you use in Microsoft Excel? Or maybe, you'll use all three depending on your needs? No matter what, it's nice to have options!

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
<li><a href="https://facebook-record-videos.techidaily.com/new-tutorial-unmask-your-youtube-audience/"><u>[New] Tutorial  Unmask Your YouTube Audience</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-increase-engagement-must-try-youtube-seo-tools/"><u>[Updated] Increase Engagement  Must-Try YouTube SEO Tools</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-pinnacle-apps-androids-ultimate-cloud-keepsakes/"><u>2024 Approved  Pinnacle Apps  Android's Ultimate Cloud Keepsakes</u></a></li>
<li><a href="https://win-dash.techidaily.com/advanced-research-in-wpc-technology-includes-the-development-of-nanocomposites-with-enhanced-properties-using-nanocellulose-or-other-nanofillers-to-further-83/"><u>Advanced Research in WPC Technology Includes the Development of Nanocomposites with Enhanced Properties Using Nanocellulose or Other Nanofillers to Further Improve Performance Characteristics</u></a></li>
<li><a href="https://win-dash.techidaily.com/amd-graphics-card-rx-instruction-what-is-the-meaning-of-the-phrase-to-be-or-not-to-be/"><u>AMD Graphics Card RX # Instruction: What Is the Meaning of the Phrase to Be or Not to Be</u></a></li>
<li><a href="https://win-dash.techidaily.com/boost-your-data-protection-expert-tips-on-using-the-seagate-backup-plus/"><u>Boost Your Data Protection: Expert Tips on Using the Seagate Backup Plus</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/classic-console-charisma-best-ps1-emulation-tools-reviewed-for-2024/"><u>Classic Console Charisma - Best PS1 Emulation Tools Reviewed for 2024</u></a></li>
<li><a href="https://win-dash.techidaily.com/complete-download-pack-latest-lenovo-x1-carbon-device-drivers-for-windows-users-versions-10-11-and-7/"><u>Complete Download Pack: Latest Lenovo X1 Carbon Device Drivers for Windows Users (Versions 10, 11 & 7)</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/copyright-confusion-suddenly-no-more-videos-for-2024/"><u>Copyright Confusion  Suddenly No More Videos for 2024</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-logitech-momo-racer-wheel-game-drivers-pc-compatible/"><u>Download Logitech MOMO Racer Wheel Game Drivers - PC Compatible</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-the-latest-epson-xp-330-driver-for-optimal-printing-performance/"><u>Download the Latest Epson XP-330 Driver for Optimal Printing Performance</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722973338230-download-the-newest-nvidia-quadro-rtx-8000-drivers-compatible-with-windows-11-10-and-7/"><u>Download the Newest Nvidia Quadro RTX 8000 Drivers: Compatible with Windows 11, 10, and 7</u></a></li>
<li><a href="https://win-dash.techidaily.com/downloadable-xbox-360-driving-game-with-compatible-controllers/"><u>Downloadable Xbox 360 Driving Game with Compatible Controllers</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722977788742-enhance-your-gameplay-update-nvidia-geforce-gtx-1660-ti-graphics-card-drivers/"><u>Enhance Your Gameplay: Update NVIDIA GeForce GTX 1660 Ti Graphics Card Drivers</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/essential-insights-for-integrating-hashtags-into-game-focused-yt-content/"><u>Essential Insights for Integrating Hashtags Into Game-Focused YT Content</u></a></li>
<li><a href="https://win-dash.techidaily.com/expert-tips-to-overcome-challenges-with-your-realtek-universal-video-controller/"><u>Expert Tips to Overcome Challenges with Your Realtek Universal Video Controller</u></a></li>
<li><a href="https://win-dash.techidaily.com/fix-guide-addressing-compatibility-and-functionality-flaws-of-the-realtek-rtl8723be-driver/"><u>Fix Guide: Addressing Compatibility and Functionality Flaws of the Realtek RTL8723BE Driver</u></a></li>
<li><a href="https://win-dash.techidaily.com/free-download-ultimate-driver-setup-for-msi-x470-motherboards/"><u>Free Download: Ultimate Driver Setup for MSI X470 Motherboards</u></a></li>
<li><a href="https://win-dash.techidaily.com/free-installation-of-amd-radeon-hd-drivers-compatible-with-windows-eight/"><u>Free Installation of AMD Radeon HD Drivers Compatible with Windows Eight</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-latest-canon-mx340-drivers-support-for-win-10-8-and-7-systems/"><u>Get the Latest Canon MX340 Drivers: Support for Win 10, 8 and 7 Systems</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-newest-razer-naga-software-updates-and-download-for-windows-users/"><u>Get the Newest Razer Naga Software Updates & Download for Windows Users</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-your-hp-officejet-pro-8740-up-and-running-drivers-for-windows-11108/"><u>Get Your HP Officejet Pro 8740 Up and Running: Drivers for Windows 11/10/8</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722978312690-get-your-realtek-rtl8188cu-wireless-network-adapter-driver-for-win-107-today/"><u>Get Your Realtek RTL8188CU Wireless Network Adapter Driver for Win 10/7 Today</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-your-windows-compatible-epson-et-2750-printing-drivers-instantly/"><u>Get Your Windows Compatible Epson ET-2750 Printing Drivers Instantly!</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-install-updated-broadcom-bluetooth-software-on-windows-versions-11-8-and-7/"><u>How to Install Updated Broadcom Bluetooth Software on Windows Versions 11, 8 and 7</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-obtain-and-install-logitech-g402-custom-trackball-drivers-and-tools/"><u>How to Obtain and Install Logitech G402 Custom Trackball Drivers & Tools</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-tips-and-tricks-for-setting-up-your-zte-phone-pattern-lock-by-drfone-android/"><u>In 2024, Tips and Tricks for Setting Up your ZTE Phone Pattern Lock</u></a></li>
<li><a href="https://win-dash.techidaily.com/install-logitech-g920-mouse-drivers-on-your-pc-compatible-with-windows-versions-including-111087/"><u>Install Logitech G920 Mouse Drivers on Your PC - Compatible with Windows Versions Including 11/10/8/7</u></a></li>
<li><a href="https://win-dash.techidaily.com/install-new-software-steelseries-engine-update-for-your-keyboard/"><u>Install New Software: SteelSeries Engine Update for Your Keyboard</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/optimal-speech-recognition-the-google-methodology-for-2024/"><u>Optimal Speech Recognition  The Google Methodology for 2024</u></a></li>
<li><a href="https://win-dash.techidaily.com/quick-and-simple-guide-download-the-right-keyboard-driver-for-your-windows-7-pc/"><u>Quick and Simple Guide: Download the Right Keyboard Driver for Your Windows 7 PC</u></a></li>
<li><a href="https://win-dash.techidaily.com/say-goodbye-to-additional-installations-windows-1ebshtml)11-os-brings-in-built-in-scanners-and-printer-drivers/"><u>Say Goodbye to Additional Installations: Windows 1Ebs/Html>11 OS Brings in Built-In Scanners and Printer Drivers</u></a></li>
<li><a href="https://win-dash.techidaily.com/step-by-step-guide-to-downloading-the-pioneer-dj-ddj-sx2-controller-driver/"><u>Step-by-Step Guide to Downloading the Pioneer DJ DDJ-SX2 Controller Driver</u></a></li>
<li><a href="https://win-dash.techidaily.com/step-by-step-tutorial-update-wifi-card-software-on-windows-11-or-10-systems/"><u>Step-by-Step Tutorial: Update WiFi Card Software on Windows 11 or 10 Systems</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-power-of-quantum-hdr-in-visual-arts/"><u>The Power of Quantum HDR in Visual Arts</u></a></li>
<li><a href="https://win-dash.techidaily.com/ultimate-guide-to-using-your-seagate-backup-plus-essential-advice-and-hacks/"><u>Ultimate Guide to Using Your Seagate Backup Plus - Essential Advice & Hacks</u></a></li>
<li><a href="https://win-dash.techidaily.com/understanding-the-fix-microsofts-solution-to-the-acpi-compliant-battery-driver-error/"><u>Understanding the Fix: Microsoft's Solution to the ACPI-Compliant Battery Driver Error.</u></a></li>
<li><a href="https://win-dash.techidaily.com/update-your-nvidia-quadro-rtx-4000-card-direct-links-to-new-drivers/"><u>Update Your NVIDIA Quadro RTX 4000 Card: Direct Links to New Drivers</u></a></li>
<li><a href="https://data-recovery.techidaily.com/your-backups-guardian-instant-retrieval-solutions/"><u>Your Backup's Guardian: Instant Retrieval Solutions</u></a></li>
</ul></div>
