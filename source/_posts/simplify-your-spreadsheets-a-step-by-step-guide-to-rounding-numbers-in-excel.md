---
title: "Simplify Your Spreadsheets: A Step-by-Step Guide to Rounding Numbers in Excel"
date: 2024-08-28T01:34:39.582Z
updated: 2024-08-29T01:34:39.582Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/03446fa7c6c4437cc78cf994a5cd500e9e19b7398656e9b5a14acb95e0d9c21d.jpg
---

## Simplify Your Spreadsheets: A Step-by-Step Guide to Rounding Numbers in Excel

### Quick Links

* [Round Off Decimal Values Using the ROUND Function](https://extra-support.techidaily.com/in-2024-instantaneous-darkness-creation/)
* [Round Numbers Up or Down Using the ROUNDUP or ROUNDDOWN Functions](https://remote-screen-capture.techidaily.com/new-privacy-protection-in-videos-a-guide-to-obscuring/)

 If you don't want to show decimal values in Excel, you can simplify your numerical data using the ROUND functions. Excel offers three functions: ROUND, ROUNDUP, and ROUNDDOWN. Let's take a look at how they work.

 Using the ROUND functions in Excel is different than changing the number's format. When you change how a number is formatted, you're just changing how it looks in your workbook. When you change a number using the ROUND functions, you're changing how it looks and how it's stored.

 The ROUND function rounds numbers to a specified number of decimal places. It rounds a number down if the digit in the next decimal place to the right is between zero and four, and it rounds up if that digit is five to nine. And as you might expect, the ROUNDUP function always rounds up and the ROUNDDOWN function always rounds down.

##  Round Off Decimal Values Using the ROUND Function

 The ROUND function rounds numbers to a certain number of decimal places that you configure. If the next digit to the right is between zero and four, it rounds down. So, for example, if you were rounding down to two decimal places, 8.532 would become 8.53\. If the next digit is between five and nine, it rounds up. So, 8.538 would become 8.54\. The ROUND function can round numbers to the right or left of the decimal point.

 You can apply the format to empty cells or to cells that already have numbers in them. You can also use ROUND as part of a more complicated formula if you want to. For example, you could create a formula that adds two columns together using the SUM function, and then rounds the result.

 For this example, we've got a column of numbers named "Values" that contains our raw numbers. We're creating a second column named "Results" that we're going to use to round down the numbers in the "Values" column to three digits.

![img_5b2ad361f3557](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2ad361f3557.png) 

 Select the cell where you want your rounded results to go.

![img_5b2ad3ab41779](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2ad3ab41779.png) 

 Navigate to the "Formulas" menu on the main ribbon.

![img_5b2cd18c7eadf](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd18c7eadf.png) 

 Click the "Math & Trig" formulas drop-down menu.

![img_5b2cd1c366409](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd1c366409.png) 

 On the "Math & Trig" drop-down menu, click the "ROUND" function.

![img_5b2cd1fd04448](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd1fd04448.png) 

 This pops up the Function Arguments window with the fields you'll use for setting the ROUND function.

![img_5b2cd2396400b](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd2396400b.png) 

 Use the "Number" field for the number you want to round. You can use type a straight up number in this field to round it, but more often you'll want to call a number from an existing cell in your sheet. Here, we're using B6 to specify the top cell in our "Values" column.

![img_5b2cd2b3cdd05](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd2b3cdd05.png) 

 Use the "Num\_Digits" field to specify how many digits the resulting number should have. You have some choices here:

* **Positive Integer:** Use a positive integer (such as 1, 2, and so on) to specify the number of digits _after_ the decimal place to which you want to round. For example, entering "3" would round to three places after the decimal point.
* **Zero:** Enter "0" to round to the nearest integer.
* **Negative Integer:** Use a negative integer (such as -1, -2, and so on) to round to left of the decimal place. For example, if you were rounding the number 328.25 and input "-1" here, it would round you number to 330.

 In our example, we're inputting "3" so that it will round our result to three places after the decimal point.

![img_5b2cd3206405a](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd3206405a.png) 

 When you're done, click the "OK" button.

![img_5b2cd34191bd1](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd34191bd1.png) 

 And as you can see, our number is now rounded in the Results column.

![img_5b2cd362a665a](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd362a665a.png) 

 You can easily apply this formula to the rest of the numbers in your set by first clicking on the bottom right corner of the cell.

![img_5b2cd3c46b79d](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd3c46b79d.png) 

 And then dragging to select the rest of the rows that you want to round.

![img_5b2cd3fe8560e](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd3fe8560e.png) 

 All of your values will now be rounded using the same properties you selected. You can also copy the cell to which you've already applied rounding, and then paste to other cells to copy the formula there.

![img_5b2cd431f381d](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd431f381d.png) 

 You can also do all this just using Excel's Function bar if you want.

 Select the column where you want your rounded numbers to go.

![img_5b2ad3ab41779](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2ad3ab41779.png) 

 Click the Function bar to activate it.

![img_5b2cd5a995ad0](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd5a995ad0.png) 

 Type in your formula using the syntax:

=ROUND(number,num_digits)

 Where "number" is the cell you want to round and "num\_digits" identifies the number of digits to which you want to round.

 For example, here's how we'd type the same rounding formula we previously applied using the dialog box.

![img_5b2cd5d70eb57](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd5d70eb57.png) 

 Hit Enter (or Return) after typing your formula, and your number is now rounded.

![img_5b2cd5fc8316a](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd5fc8316a.png) 

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
##  Round Numbers Up or Down Using the ROUNDUP or ROUNDDOWN Functions

 Sometimes, you may want your numbers to just round numbers up or down instead of having the next digit decide that for you. That's what the ROUNDUP and ROUNDDOWN functions are for, and and using them is pretty much identical to using the ROUND function.

 Click the cell where you want your rounded result to go.

![img_5b2ad3ab41779](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2ad3ab41779.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Head to Formulas > Math & Trig, and then choose either the "ROUNDUP" or "ROUNDDOWN" function from the dropdown menu.

![Untitled](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/Untitled.png) 

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Enter the number (or cell) you want to round in the "Number" field. Enter the number of digits to which you want to round in the "Num\_digits" field. And the same rules apply as with the ROUND function. A positive integer rounds to the right of the decimal point, zero rounds to the nearest integer, and a negative integer rounds to the left of the decimal point.

 Click "OK" when you've got things set up.

![img_5b2cd7d91b50f](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/06/img_5b2cd7d91b50f.png) 

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<!-- affiliate ads end -->
 And just like with the ROUND function, you can also set up the ROUNDUP and ROUNDDOWN functions by typing them into the Function bar, and you can use them as parts of a larger formula.

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
<li><a href="https://eaxpv-info.techidaily.com/new-hitting-high-notes-enhance-your-youtube-content-with-music-edits-for-2024/"><u>[New] Hitting High Notes  Enhance Your YouTube Content with Music Edits for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-the-essential-guide-to-signing-up-for-twitter/"><u>[New] In 2024, The Essential Guide to Signing Up for Twitter</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/n-2024-which-video-sharing-platform-prevails-analyzing-igtv-vs-youtube/"><u>[New] In 2024, Which Video Sharing Platform Prevails? Analyzing IGTV Vs. YouTube</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-maximizing-streaming-experience-with-two-screen-viewing-on-netflix/"><u>[New] Maximizing Streaming Experience with Two-Screen Viewing on Netflix</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-2024s-guide-to-superior-soundtracks-adding-srt-to-mp4-files/"><u>[Updated] 2024’S Guide to Superior Soundtracks – Adding SRT to MP4 Files</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-how-to-record-screen-with-vidmore-screen-recorder/"><u>[Updated] In 2024, How to Record Screen with Vidmore Screen Recorder</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-instagram-story-wizardry-secrets-revealed-for-2024/"><u>[Updated] Instagram Story Wizardry  Secrets Revealed for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-perfect-picture-presentation-tools/"><u>[Updated] Perfect Picture Presentation Tools</u></a></li>
<li><a href="https://win-dash.techidaily.com/amd-radeon-rx-amo-easy-download-and-update-of-drivers/"><u>AMD Radeon RX Amo - Easy Download and Update of Drivers</u></a></li>
<li><a href="https://win-dash.techidaily.com/compatible-logitech-brio-webcam-driver-downloads-for-windows-1087-users/"><u>Compatible Logitech BRIO Webcam Driver Downloads for Windows 10/8/7 Users</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722972308990-cost-efficiency/"><u>Cost Efficiency</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-and-install-latest-driver-updates-for-nvidia-rtx-2070-super-on-windows-11/"><u>Download and Install Latest Driver Updates for Nvidia RTX 2070 Super on Windows 11</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-and-install-your-logitech-webcam-drivers-on-windows-1011-c623/"><u>Download and Install Your Logitech Webcam Drivers on Windows 10/11 (C623)</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-hp-officejet-pro-8600-printer-drivers-on-windows-step-by-step-guide/"><u>Download HP Officejet Pro 8600 Printer Drivers on Windows: Step-by-Step Guide</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-intels-official-usb-30-drivers-for-seamless-integration-with-windows-11/"><u>Download Intel's Official USB 3.0 Drivers for Seamless Integration with Windows 11</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-intelligent-thunderbolt-drivers-fast-simple-steps-inside/"><u>Download Intelligent Thunderbolt Drivers Fast: Simple Steps Inside</u></a></li>
<li><a href="https://win-dash.techidaily.com/easy-instructions-for-integrating-beats-audio-into-your-system/"><u>Easy Instructions for Integrating Beats Audio Into Your System</u></a></li>
<li><a href="https://win-dash.techidaily.com/effortless-installation-of-amds-radeon-rx-470-graphics-driver-software-and-updates/"><u>Effortless Installation of AMD's Radeon RX 470 Graphics Driver Software & Updates</u></a></li>
<li><a href="https://win-dash.techidaily.com/epson-l3150-printer-drivers-download-and-installation-guide-for-windows-1187/"><u>Epson L3150 Printer Drivers: Download & Installation Guide for Windows 11/8/7</u></a></li>
<li><a href="https://network-issues.techidaily.com/fix-screen-tearing-issues-on-pc/"><u>Fix Screen Tearing Issues on PC</u></a></li>
<li><a href="https://win-dash.techidaily.com/free-epson-wf-2630-driver-download-updated-software-for-windows-os-versions/"><u>Free Epson WF 2630 Driver Download: Updated Software for Windows OS Versions</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722961077743-get-the-best-of-wacom-intuos-with-fully-functional-drivers-for-windows-systems-download-now/"><u>Get the Best of Wacom Intuos with Fully Functional Drivers for Windows Systems - Download Now!</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722963012436-get-the-latest-canon-drivers-fast-free-downloads-and-guides-for-windows-users/"><u>Get the Latest Canon Drivers Fast - Free Downloads & Guides for Windows Users</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-new-driver-for-your-lenovo-camera-compatible-with-windows-n-7-systems/"><u>Get the New Driver for Your Lenovo Camera: Compatible with Windows N 7 Systems</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-new-geforce-rtx-3080-ti-windows-support-package-win-1087/"><u>Get the New GeForce RTX 3080 Ti Windows Support Package (Win 10/8/7)</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-newest-drivers-for-your-epson-xp-310-free-download-available-now/"><u>Get the Newest Drivers for Your Epson XP-310 - Free Download Available Now</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-official-msi-z370-a-pro-drivers-for-free-immediate-download/"><u>Get the Official MSI Z370-A Pro Drivers for Free - Immediate Download!</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-your-realtek-rtl8188cu-wireless-network-adapter-driver-for-win-107-today/"><u>Get Your Realtek RTL8188CU Wireless Network Adapter Driver for Win 10/7 Today!</u></a></li>
<li><a href="https://win-dash.techidaily.com/guide-how-to-get-the-newest-version-of-sas-for-your-pc-windows/"><u>Guide: How To Get The Newest Version Of SAS for Your PC (Windows)</u></a></li>
<li><a href="https://win-amazing.techidaily.com/hassle-free-downloads-and-setup-of-your-hp-devices-essential-drivers/"><u>Hassle-Free Downloads & Setup of Your HP Device's Essential Drivers!</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-get-your-hands-on-free-nvidia-3d-vision-drivers-for-windows-without-hassle/"><u>How to Get Your Hands on Free Nvidia 3D Vision Drivers for Windows Without Hassle</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-install-the-newest-canon-mg2n-software-on-your-inkjet-printer/"><u>How to Install the Newest Canon MG2n Software on Your Inkjet Printer</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-keep-your-microsoft-surface-book-2-running-smoothly-with-driver-updates/"><u>How to Keep Your Microsoft Surface Book 2 Running Smoothly with Driver Updates</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-obtain-the-latest-lenovo-thinkpad-t420-drivers-for-seamless-performance-windows/"><u>How to Obtain the Latest Lenovo ThinkPad T420 Drivers for Seamless Performance [Windows]</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-activate-and-use-life360-ghost-mode-on-samsung-galaxy-s23-fe-drfone-by-drfone-virtual-android/"><u>In 2024, How To Activate and Use Life360 Ghost Mode On Samsung Galaxy S23 FE | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-fake-gps-location-spoofer-a-good-choice-on-xiaomi-redmi-note-12-pro-4g-drfone-by-drfone-virtual-android/"><u>In 2024, Is Fake GPS Location Spoofer a Good Choice On Xiaomi Redmi Note 12 Pro 4G? | Dr.fone</u></a></li>
<li><a href="https://win-dash.techidaily.com/install-latest-intel-hd-graphics-drivers-compatible-with-windows-1011-free-downloads/"><u>Install Latest Intel HD Graphics Drivers Compatible with Windows 10/11 - Free Downloads</u></a></li>
<li><a href="https://technical-tips.techidaily.com/meta-quest-3-discover-the-cutting-edge-virtual-reality-headset-news-updates-pricing-info-release-schedule-and-in-depth-spec-comparison/"><u>Meta Quest 3 - Discover the Cutting-Edge Virtual Reality Headset: News Updates, Pricing Info, Release Schedule & In-Depth Spec Comparison</u></a></li>
<li><a href="https://win-dash.techidaily.com/official-guide-to-obtain-and-install-samsung-mobile-device-adb-drivers/"><u>Official Guide to Obtain and Install Samsung Mobile Device Adb Drivers</u></a></li>
<li><a href="https://win11.techidaily.com/optimize-your-workday-the-top-5-apps-to-skyrocket-windows-efficiency/"><u>Optimize Your Workday: The Top 5 Apps to Skyrocket Windows Efficiency</u></a></li>
<li><a href="https://win-dash.techidaily.com/quick-and-easy-downloads-updating-your-dell-printer-drivers/"><u>Quick and Easy Downloads: Updating Your Dell Printer Drivers</u></a></li>
<li><a href="https://win-dash.techidaily.com/quick-fix-with-validity-fingerprint-sensor-driver-download-today/"><u>Quick Fix with Validity Fingerprint Sensor Driver - Download Today</u></a></li>
<li><a href="https://win-dash.techidaily.com/quick-guide-updating-dell-inspiron-g7-drivers-with-speed-and-simplicity/"><u>Quick Guide: Updating Dell Inspiron G7 Drivers with Speed and Simplicity</u></a></li>
<li><a href="https://win-dash.techidaily.com/realtek-rtl8188cu-network-adapter-install-drivers-on-windows-10-or-7/"><u>Realtek RTL8188CU Network Adapter: Install Drivers on Windows 10 or 7</u></a></li>
<li><a href="https://win-dash.techidaily.com/resolving-problems-with-the-realtek-rtl8723be-network-adapter-drivers/"><u>Resolving Problems with the Realtek RTL8723BE Network Adapter Drivers</u></a></li>
<li><a href="https://win-dash.techidaily.com/seamless-download-and-update-how-to-get-the-newest-drivers-for-your-amd-rx-580/"><u>Seamless Download and Update: How to Get the Newest Drivers for Your AMD RX 580</u></a></li>
<li><a href="https://win-dash.techidaily.com/seamless-installation-access-the-latest-samsung-c460-driver-software/"><u>Seamless Installation: Access the Latest Samsung C460 Driver Software</u></a></li>
<li><a href="https://win-dash.techidaily.com/speedy-access-to-optimal-amd-ryzen-5-2600-graphics-driver-software/"><u>Speedy Access to Optimal AMD Ryzen 5 2600 Graphics Driver Software</u></a></li>
<li><a href="https://win-dash.techidaily.com/step-by-step-process-to-fresh-update-of-epson-printing-drivers-in-windows-10/"><u>Step-by-Step Process to Fresh Update of Epson Printing Drivers in Windows 10</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/the-complete-guide-to-infinix-zero-30-5g-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>The Complete Guide to Infinix Zero 30 5G FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://some-approaches.techidaily.com/top-tier-laptops-and-pcs-for-ultimate-comfort-for-2024/"><u>Top-Tier Laptops & PCs for Ultimate Comfort for 2024</u></a></li>
<li><a href="https://win-dash.techidaily.com/up-to-date-konica-minolta-printer-drivers-available-here-tailored-to-work-on-windows-11-down-to-v7/"><u>Up-to-Date Konica Minolta Printer Drivers Available Here: Tailored to Work on Windows 11 Down to V7</u></a></li>
<li><a href="https://win-dash.techidaily.com/update-your-dell-thunderbolt-tb17-adapter-free-driver-download-and-installation-guide/"><u>Update Your Dell Thunderbolt TB17 Adapter - Free Driver Download & Installation Guide</u></a></li>
<li><a href="https://win-dash.techidaily.com/update-your-epson-wf-3720-printer-software-for-optimal-performance/"><u>Update Your Epson WF-3720 Printer Software for Optimal Performance</u></a></li>
</ul></div>
