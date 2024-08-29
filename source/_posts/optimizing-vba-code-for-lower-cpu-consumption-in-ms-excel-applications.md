---
title: Optimizing VBA Code for Lower CPU Consumption in MS Excel Applications
date: 2024-08-28T01:35:19.731Z
updated: 2024-08-29T01:35:19.731Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/01/how-do-you-limit-microsoft-excels-cpu-usage-when-running-vba-functions-00.jpg
---

## Optimizing VBA Code for Lower CPU Consumption in MS Excel Applications

### Quick Links

* [The Question](https://facebook-video-footage.techidaily.com/updated-in-2024-channel-success-strategy-standard-studio-or-beta-edge/)
* [The Answer](https://desktop-recording.techidaily.com/new-innovative-ways-to-record-without-background-sounds-for-2024/)

 If you have a VBA function that turns Microsoft Excel into a CPU munching beast, is it possible to tame things down so that you can continue to use your computer for other activities while Excel is finishing up? Today's SuperUser Q&A post comes to the rescue to help a frustrated reader get Excel back under control.

 Today’s Question & Answer session comes to us courtesy of SuperUser—a subdivision of Stack Exchange, a community-driven grouping of Q&A web sites.

 Alien warrior clip art courtesy of [Clker.com](http://www.clker.com/clipart-alien-warrior.html).

##  The Question

 SuperUser reader learningAsIGo wants to know if there is a way to limit Microsoft Excel's CPU usage while running a VBA script on his computer:

> Is there a way to limit Microsoft Excel's CPU usage when it is running? I have a VBA script that calculates a large amount of giant array formulas. The entire set of calculations takes approximately twenty minutes to complete and uses 100 percent of my CPU. I am unable to use my computer during this time and would rather have Excel 'running in the background' while using about 50 percent of my CPU's capacity so that I can continue to do other things.
> 
> Any suggestions? My computer's operating system is Windows 7 Enterprise 64-bit with a 2007 32-bit version of Excel installed on it.

 Is there a way to limit Microsoft Excel's CPU usage while running VBA functions?

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633309&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/3_premium-icon.png" border="0"> Take advantage of PREMIUM features for 12 months. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Yearly Membership</a>
<!-- affiliate ads end -->
##  The Answer

 SuperUser contributor mtone has the answer for us:

> If a VBA function is called from several formulas or if your script generates or forces the recalculation of several formulas, then this should definitely make use of the multi-threaded calculation feature in Microsoft Excel. Respectively, this would either run multiple instances of your VBA function for each formula, or recalculate multiple cells simultaneously while your VBA script is running on a single thread.
> 
> You can limit the number of threads used by Excel to recalculate formulas by going to Options and selecting the Advanced Section, then scrolling down until you reach the Formulas sub-section.
> 
> ![how-do-you-limit-microsoft-excels-cpu-usage-when-running-vba-functions-01](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/01/how-do-you-limit-microsoft-excels-cpu-usage-when-running-vba-functions-01.jpg) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
---

 Have something to add to the explanation? Sound off in the comments. Want to read more answers from other tech-savvy Stack Exchange users? [Check out the full discussion thread here](http://superuser.com/questions/1025428/limit-excel-cpu-usage).

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
<li><a href="https://article-tips.techidaily.com/new-in-2024-expert-techniques-for-navigating-popular-and-trending-youtube-reactions/"><u>[New] In 2024, Expert Techniques for Navigating Popular and Trending YouTube Reactions</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-ultimate-trailer-treasure-chest-for-2024/"><u>[New] Ultimate Trailer Treasure Chest for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-vloggers-ultimate-guide-to-best-gaming-microphones-for-2024/"><u>[Updated] Vloggers' Ultimate Guide to Best Gaming Microphones for 2024</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-ae-lifesavers-budget-friendly-template-assortment/"><u>2024 Approved  AE Lifesavers  Budget-Friendly Template Assortment</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-optimal-vr-experience-a-review-of-top-oculus-models/"><u>2024 Approved  Optimal VR Experience  A Review of Top Oculus Models</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-prime-premiere-pro-blueprints-best-free-2023/"><u>2024 Approved  Prime Premiere Pro Blueprints - Best Free 2023</u></a></li>
<li><a href="https://win-dash.techidaily.com/amd-rx-480-drivers-quick-download-and-update-process/"><u>AMD RX 480 Drivers: Quick Download & Update Process</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/audio-interface-innovations-for-optimal-podcasting-for-2024/"><u>Audio Interface Innovations for Optimal Podcasting for 2024</u></a></li>
<li><a href="https://win-dash.techidaily.com/brother-mfc-l2740dw-11-drivers-free-windows-downloads-compatible-with-various-versions-of-microsoft-os/"><u>Brother MFC-L2740DW 1/1 Drivers: FREE Windows Downloads - Compatible with Various Versions of Microsoft OS</u></a></li>
<li><a href="https://howto.techidaily.com/cellular-network-not-available-for-voice-calls-on-samsung-galaxy-m14-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Cellular Network Not Available for Voice Calls On Samsung Galaxy M14 5G | Dr.fone</u></a></li>
<li><a href="https://win-dash.techidaily.com/comprehvew-update-guide-navigating-the-latest-amd-driver-releases-on-windows-7-10-and-11/"><u>Comprehvew Update Guide: Navigating the Latest AMD Driver Releases on Windows 7, 10 & 11</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-and-install-for-corsair-k70-essential-driver-pack-available-now/"><u>Download & Install for Corsair K70 – Essential Driver Pack Available Now</u></a></li>
<li><a href="https://win-dash.techidaily.com/easily-install-and-upgrade-logitechs-controllers-with-these-driver-downloads/"><u>Easily Install & Upgrade Logitech's Controllers with These Driver Downloads!</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722976433220-easy-access-to-updated-asus-notebook-drivers-get-them-here/"><u>Easy Access to Updated ASUS Notebook Drivers - Get Them Here</u></a></li>
<li><a href="https://fox-info.techidaily.com/elevate-your-photos-with-these-top-11-tutorials-for-2024/"><u>Elevate Your Photos with These Top 11 Tutorials for 2024</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722977682700-experience-flawless-bluetooth-connections-on-lenovo-pcs-with-authorized-safe-drivers-for-windows-710-download-now/"><u>Experience Flawless Bluetooth Connections on Lenovo PCs with Authorized Safe Drivers for Windows 7/10 - Download Now</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/flash-through-files-on-your-windows-pc-for-2024/"><u>Flash Through Files on Your Windows PC for 2024</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-latest-intel-hd-graphics-4400-driver-free-download/"><u>Get the Latest Intel HD Graphics 4400 Driver - Free Download</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-latest-how-to-install-canon-mp560-driver-software-swiftly/"><u>Get the Latest: How to Install Canon MP560 Driver Software Swiftly</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-newest-mpow-bluetooth-driver-versions-compatible-with-windows-systems/"><u>Get the Newest MPOW Bluetooth Driver Versions Compatible with Windows Systems</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-can-i-use-a-fake-gps-without-mock-location-on-motorola-moto-g-stylus-2023-drfone-by-drfone-virtual-android/"><u>How Can I Use a Fake GPS Without Mock Location On Motorola Moto G Stylus (2023)? | Dr.fone</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-install-the-latest-canon-printer-software-on-your-windows-pc/"><u>How to Install the Latest Canon Printer Software on Your Windows PC</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-perform-a-clean-install-of-windows-11-on-a-new-internal-drive-a-comprehensive-guide/"><u>How to Perform a Clean Install of Windows 11 on a New Internal Drive – A Comprehensive Guide</u></a></li>
<li><a href="https://win-dash.techidaily.com/hp-color-laserjet-pro-m477-support-free-downloads-of-the-latest-printer-drivers/"><u>HP Color LaserJet Pro M477 Support - Free Downloads of the Latest Printer Drivers</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-channel-building-gear-a-quick-start-guide/"><u>In 2024, Channel-Building Gear  A Quick Start Guide</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-detailed-guide-of-ispoofer-for-pogo-installation-on-lenovo-thinkphone-drfone-by-drfone-virtual-android/"><u>In 2024, Detailed guide of ispoofer for pogo installation On Lenovo ThinkPhone | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-methods-to-change-gps-location-on-honor-90-drfone-by-drfone-virtual-android/"><u>In 2024, Methods to Change GPS Location On Honor 90 | Dr.fone</u></a></li>
<li><a href="https://fox-http.techidaily.com/in-2024-the-ultimate-guide-to-choosing-the-best-free-photo-collage-ios-apps/"><u>In 2024, The Ultimate Guide to Choosing the Best FREE Photo Collage iOS Apps</u></a></li>
<li><a href="https://win-dash.techidaily.com/install-and-update-amd-radeon-hd-grove-7870-graphics-card-drivers-compatible-with-windows-11/"><u>Install and Update: AMD Radeon HD Grove 7870 Graphics Card Drivers Compatible with Windows 11</u></a></li>
<li><a href="https://win-dash.techidaily.com/install-fresh-hp-officejet-4500-drivers-updated-guide-and-free-download/"><u>Install Fresh HP Officejet 4500 Drivers - Updated Guide & Free Download</u></a></li>
<li><a href="https://win-dash.techidaily.com/install-the-latest-usb-c-driver-for-seamless-windows-11-integration-downloads-available/"><u>Install the Latest USB-C Driver for Seamless Windows 11 Integration – Downloads Available</u></a></li>
<li><a href="https://win-dash.techidaily.com/install-your-easycap-software-instantly-fast-and-straightforward-downloads-available/"><u>Install Your EasyCap Software Instantly - Fast and Straightforward Downloads Available!</u></a></li>
<li><a href="https://extra-resources.techidaily.com/master-the-art-of-gaming-best-monitors-and-tvs-for-xbox-series-x/"><u>Master the Art of Gaming  Best Monitors & TVs For Xbox Series X</u></a></li>
<li><a href="https://solve-info.techidaily.com/no-coding-experience-required-build-your-own-apps-in-minutes-not-months/"><u>No Coding Experience Required? Build Your Own Apps in Minutes, Not Months!</u></a></li>
<li><a href="https://win-dash.techidaily.com/nonlinear-dynamic-analysis-considers-material-and-geometric-nonlinearity-for-more-accurate-predictions-of-structural-response-under-seismic-loading/"><u>Nonlinear Dynamic Analysis Considers Material and Geometric Nonlinearity for More Accurate Predictions of Structural Response Under Seismic Loading</u></a></li>
<li><a href="https://win-dash.techidaily.com/quick-download-guide-get-your-lexar-usb-driver-now/"><u>Quick Download Guide: Get Your Lexar USB Driver Now</u></a></li>
<li><a href="https://tech-haven.techidaily.com/1722151987203-ransomware-unveiled-secure-your-device-for-just-50-plus-insights-on-how-chatgpt-contributes-to-our-show/"><u>Ransomware Unveiled: Secure Your Device for Just $50 - Plus, Insights on How ChatGPT Contributes to Our Show!</u></a></li>
<li><a href="https://windows11.techidaily.com/reflect-on-one-misconception-about-cultural-relativism-mentioned-in-class-then-describe-how-you-would-address-this-misunderstanding-with-someone-from-a-diff21/"><u>Reflect on One Misconception About Cultural Relativism Mentioned in Class, Then Describe How You Would Address This Misunderstanding with Someone From a Different Culture</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722975438225-secure-and-fast-internet-with-new-gigabyte-ethernet-driver-download-now/"><u>Secure and Fast Internet with New Gigabyte Ethernet Driver - Download Now</u></a></li>
<li><a href="https://win-dash.techidaily.com/step-by-step-driver-update-process-for-razer-blade-17-across-various-windows-versions/"><u>Step-by-Step Driver Update Process for Razer Blade 17 Across Various Windows Versions</u></a></li>
<li><a href="https://win-dash.techidaily.com/step-by-step-guide-to-overcoming-lenovo-usb-recognition-issues/"><u>Step-by-Step Guide to Overcoming Lenovo USB Recognition Issues</u></a></li>
<li><a href="https://win-dash.techidaily.com/the-complete-method-for-upgrading-ati-graphics-driver-software-on-windows-machines/"><u>The Complete Method for Upgrading ATI Graphics Driver Software on Windows Machines</u></a></li>
<li><a href="https://win-dash.techidaily.com/update-your-pcs-bluetooth-connectivity-download-microsoft-drivers-for-win-1187/"><u>Update Your PC's Bluetooth Connectivity - Download Microsoft Drivers for Win 11/8/7</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/young-pilots-guide-the-best-drones-of-all-time/"><u>Young Pilots' Guide  The Best Drones of All Time</u></a></li>
</ul></div>
