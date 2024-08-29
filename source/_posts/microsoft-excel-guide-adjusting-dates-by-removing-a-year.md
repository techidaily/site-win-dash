---
title: "Microsoft Excel Guide: Adjusting Dates by Removing a Year"
date: 2024-08-28T01:34:35.782Z
updated: 2024-08-29T01:34:35.782Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/82e91f7db84fddd0d0cd74fd53de4decc4bc8c46a25aa2285ca573b91b9719e8.jpg
---

## Microsoft Excel Guide: Adjusting Dates by Removing a Year

### Quick Links

* [Custom Number Formatting](https://bypass-frp.techidaily.com/in-2024-a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-itel-p40plus-by-drfone-android/)
* [CONCATENATE Function](https://extra-information.techidaily.com/2024-approved-a-beginners-guide-making-your-podcasts-rss-feed/)

 There are a couple of ways you can remove the year from a date shown in Microsoft Excel. You can use custom cell formatting to hide it or use various functions like CONCATENATE to remove it completely. Here's how.

##  Custom Number Formatting

 While a date value in an Excel cell is technically a number, Microsoft Excel uses a particular type of formatting to display it. The same is true for currency values, where currency symbols are added to values to show that they relate to money. When you add a date in Excel in a format that it recognizes, Excel automatically changes the cell number format to the "Date" type.

 You can customize this type to display the date value in different ways. For instance, you can switch between "11/02/2021" (in the DD/MM/YYYY format commonly used in the U.K.) and "2021-02-11" for 11 February 2021.

![An example of various custom date formats in Microsoft Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/02/Excel-Custom-Date-Formats.png) 

 You can customize this number format, however, to remove the year entirely from view. The value itself won't change, but Excel won't [show the year value](https://facebook-record-videos.techidaily.com/updated-in-2024-captivating-content-the-basics-of-removing-background-from-videos/) thanks to custom number formatting.

 To do this, highlight the cells containing your original date values, then select the "Home" tab on the ribbon bar. From there, select the arrow next to the number format drop-down menu and choose the "More Number Formats" option.

![In Excel, select your date values, then press Home &gt; Number Format &gt; More Number Formats.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/02/Excel-More-Number-Formats-Option.png) 

 In the "Format Cells" menu, select a style of formatting that you like from the "Date" options provided. Once that's selected, choose the "Custom" option.

![In the &quot;Format Cells&quot; menu, select your date value type from the &quot;Date&quot; menu before pressing the &quot;Custom&quot; option.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/02/Excel-Set-Custom-Date-Format.png) 

 In the "Custom" option, you'll see the date number formatting style shown as text in the "Type" box. For instance, "11/02/2021" would show as "dd/mm/yyyy" in this box.

 To remove the year, make sure to remove any references to "yyyy" or "yy" in the "Type" box as well as any surplus delimiters, such as a dash or forward slash. For instance, "11/02/2021" would require you to remove "/yyyy" from the "dd/mm/yyyy" type box, leaving "dd/mm" in place.

 Once you've made your changes, select the "OK" button.

![Remove &quot;yy&quot; or &quot;yyyy&quot; from the &quot;Type&quot; box, then press &quot;OK&quot; to confirm.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/02/Excel-Remove-Year-From-Cell-Formatting.png) 

 Changing the cell number type will hide the year, but it won't remove it. If you want to restore the year, change your cell number type to a date type that includes the year again.

<!-- affiliate ads begin -->
<a href="https://estore.macxdvd.com/order/checkout.php?PRODS=4526659&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macxdvd.com/affiliate/new-banner/vcp-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
##  CONCATENATE Function

 Concatenation is a term that basically means to link or combine two or more pieces of data. In Microsoft Excel terms, concatenation can be used to add various text strings, numbers, or cell values together in a new cell.

![An example of various text strings combined using the Excel CONCATENATE function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/02/Excel-CONCATENATE-Example.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901410&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix Pro - Software based live production. vMix Pro includes everything in vMix 4K plus 8 channels of Replay and 8 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
 If you want to remove the year from a date in Excel, you could combine the output from two functions (such as DAY or MONTH) together using CONCATENATE. Rather than hiding the year from view using custom number formatting, CONCATENATE (with DAY and MONTH) allows you to create a separate value that doesn't include the year at all.

 To do this, open an Excel workbook containing your date values, or create a new workbook and place date values in separate cells. To use CONCATENATE with DAY and MONTH, insert a new function using this structure, replacing the cell reference (A2) with a reference to the cell containing your date:

=CONCATENATE(DAY(A2),"/",MONTH(A2))

 The values returned by DAY and MONTH are separated by a special delimiter character, such as a comma or slash, to show that the returned value is a date. Each value (DAY, the delimiter, and MONTH) are separated by a comma in the CONCATENATE function.

 In this example, cell A2 contains a date value (11/12/2021) in the DD/MM/YYYY format. Using CONCATENATE with DAY and MONTH, the day (11) and month (12) from the date value in A2 are placed in another cell separated by the delimiter, which, in this case, is a forward slash.

![An example of various text strings combined using the Excel CONCATENATE function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/02/Excel-CONCATENATE-Example.png) 

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
<!-- affiliate ads end -->
 You can customize this formula to change the order of the day and month values (eg. MM/DD) or to use a different delimiter character. You can also [use the fill handle](https://visual-screen-recording.techidaily.com/new-in-2024-top-5-best-hdmi-21-gaming-monitors-ps5-compatible/) to copy this formula into other cells in your column to remove the year from multiple date values.

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
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-blending-past-and-present-film-aesthetics/"><u>[New] 2024 Approved  Blending Past and Present Film Aesthetics</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-in-2024-deciphering-the-skies-with-yuneecs-typhoon-uav/"><u>[Updated] In 2024, Deciphering the Skies with Yuneec’s Typhoon UAV</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-innovative-approaches-to-iptv-video-logging/"><u>[Updated] Innovative Approaches to IPTV Video Logging</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-mastering-short-form-trimming-videos-for-youtube/"><u>[Updated] Mastering Short-Form  Trimming Videos for YouTube</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-seamless-screenshot-synergy-for-pc-users/"><u>[Updated] Seamless Screenshot Synergy for PC Users</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-secrets-encased-exploring-e-commerce-realms-of-mystery-boxes/"><u>[Updated] Secrets Encased  Exploring E-Commerce Realms of Mystery Boxes</u></a></li>
<li><a href="https://win-dash.techidaily.com/approach-understand-that-specific-heat-capacity-is-an-intrinsic-property-related-to-the-amount-of-energy-needed-to-change-a-substances-temperature-which-can339/"><u>Approach: Understand that Specific Heat Capacity Is an Intrinsic Property Related to the Amount of Energy Needed to Change a Substance's Temperature, Which Can Be Influenced by Mass per Volume.</u></a></li>
<li><a href="https://win-dash.techidaily.com/asus-mouse-pad-driver-for-windows-free-download-and-installation-tips/"><u>ASUS Mouse Pad Driver for Windows - Free Download & Installation Tips</u></a></li>
<li><a href="https://win-dash.techidaily.com/asus-touchpad-compatibility-downloading-and-configuring-drivers-on-windows-11-efficiently/"><u>ASUS Touchpad Compatibility: Downloading and Configuring Drivers on Windows 11 Efficiently</u></a></li>
<li><a href="https://solve-popular.techidaily.com/boost-conversion-rates-using-innovative-cookiebot-tracking-solutions/"><u>Boost Conversion Rates Using Innovative Cookiebot Tracking Solutions</u></a></li>
<li><a href="https://win-dash.techidaily.com/complete-solution-for-retrieving-latest-hp-elitebook-8460p-drivers-on-your-windows-device-downloading-and-installation-guide/"><u>Complete Solution for Retrieving Latest HP EliteBook 8460P Drivers on Your Windows Device - Downloading & Installation Guide</u></a></li>
<li><a href="https://win-dash.techidaily.com/effective-solutions-for-unavailable-dts-format-on-your-preferred-output-device/"><u>Effective Solutions for Unavailable DTS Format on Your Preferred Output Device</u></a></li>
<li><a href="https://extra-resources.techidaily.com/elite-batteries-and-chargers-for-black-gopro-hero5-devices/"><u>Elite Batteries & Chargers for Black GoPro Hero5 Devices</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-newest-canon-pixma-mg2522-driver-version-for-enhanced-functionality/"><u>Get the Newest Canon PIXMA MG2522 Driver Version for Enhanced Functionality</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-newest-epson-wf-3620-driver-software-for-compatible-pcs-running-windows-1087-download-here/"><u>Get the Newest Epson WF-3620 Driver Software for Compatible PCs Running Windows 10/8/7 - Download Here</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-your-intel-ac-7260-wifi-card-ready-simple-guide-to-downloading-the-latest-drivers/"><u>Get Your Intel AC 7260 WiFi Card Ready: Simple Guide to Downloading the Latest Drivers!</u></a></li>
<li><a href="https://win-dash.techidaily.com/getting-and-setting-up-the-newest-dell-v305-aio-printer-driver-in-windows-7/"><u>Getting and Setting Up the Newest Dell V305 AIO Printer Driver in Windows 7</u></a></li>
<li><a href="https://win-dash.techidaily.com/getting-your-scansnap-ix500-up-to-date-windows-software-update-made-easy/"><u>Getting Your ScanSnap iX500 Up to Date: Windows Software Update Made Easy</u></a></li>
<li><a href="https://win-dash.techidaily.com/guidelines-for-fixing-xbox-gamepad-connection-issues-in-win11-win87-environments/"><u>Guidelines for Fixing Xbox Gamepad Connection Issues in Win11, Win8/7 Environments</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-change-your-honor-80-pro-straight-screen-edition-location-on-life360-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>How to Change Your Honor 80 Pro Straight Screen Edition Location on life360 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-get-your-brother-hl-l2380dw-ready-on-pc-download-the-latest-driver-pack/"><u>How to Get Your Brother HL-L2380DW Ready on PC - Download the Latest Driver Pack</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-overcome-realtek-hd-driver-malfunctions-and-enjoy-flawless-gaming-solved/"><u>How to Overcome Realtek HD Driver Malfunctions and Enjoy Flawless Gaming [Solved]</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-quick-and-efficient-download-and-installation-of-nvidias-gtx-1080-ti-graphics-card-drivers/"><u>How To: Quick & Efficient Download and Installation Of NVIDIA's GTX 1080 Ti Graphics Card Drivers</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-easy-video-reversal-top-online-tools/"><u>In 2024, Easy Video Reversal Top Online Tools</u></a></li>
<li><a href="https://win-dash.techidaily.com/install-the-updated-drivers-for-epson-wf-3520-and-enhance-your-windows-experience/"><u>Install the Updated Drivers for Epson WF 3520 and Enhance Your Windows Experience</u></a></li>
<li><a href="https://win-dash.techidaily.com/installing-focusrite-scarlett/"><u>Installing Focusrite Scarlett</u></a></li>
<li><a href="https://win-dash.techidaily.com/installing-nvme-drives-with-windows-drivers-the-ultimate-guide/"><u>Installing NVMe Drives with Windows Drivers: The Ultimate Guide</u></a></li>
<li><a href="https://win-dash.techidaily.com/installing-the-epson-wf-2750-step-by-step-driver-setup-for-optimal-print-quality/"><u>Installing the Epson WF-2750: Step-by-Step Driver Setup for Optimal Print Quality</u></a></li>
<li><a href="https://win-dash.techidaily.com/lenovo-legion-5-pro-16-installing-accurate-drivers/"><u>Lenovo Legion 5 Pro 16 - Installing Accurate Drivers</u></a></li>
<li><a href="https://audio-editing.techidaily.com/moto-g-power-analysis-exceptional-endurance-meets-stylish-design/"><u>Moto G Power Analysis: Exceptional Endurance Meets Stylish Design</u></a></li>
<li><a href="https://win-dash.techidaily.com/netgear-a6100-fresh-drivers-and-updates-for-windows-operating-system/"><u>Netgear A6100 - Fresh Drivers and Updates for Windows Operating System</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/understanding-transparency-in-machine-learning-via-shap-e/"><u>Understanding Transparency in Machine Learning via SHAP E</u></a></li>
<li><a href="https://win-dash.techidaily.com/unexpected-issue-how-to-fix-undetected-tl-wn722n-network-adapter-on-windows-system/"><u>Unexpected Issue: How to Fix Undetected TL-WN722N Network Adapter on Windows System</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-get-animated-top-10-software-for-2d-animation-enthusiasts-for-2024/"><u>Updated Get Animated Top 10 Software for 2D Animation Enthusiasts for 2024</u></a></li>
</ul></div>
