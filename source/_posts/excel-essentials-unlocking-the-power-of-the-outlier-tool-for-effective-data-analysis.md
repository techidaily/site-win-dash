---
title: "Excel Essentials: Unlocking the Power of the Outlier Tool for Effective Data Analysis"
date: 2024-08-28T01:33:12.909Z
updated: 2024-08-29T01:33:12.909Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/f7c3dfb51630ea312d0721a61ab19847e1113bba58f7b17ac94759c2d0864364.jpg
---

## Excel Essentials: Unlocking the Power of the Outlier Tool for Effective Data Analysis

### Quick Links

* [A Quick Example](https://sound-issues.techidaily.com/how-to-fix-windows-speaker-sound-distortion-issue/)
* [How to Find Outliers in your Data](https://some-techniques.techidaily.com/hands-on-crafting-unique-movie-closures-for-pennies-for-2024/)
* [Ignoring the Outliers when Calculating the Mean Average](https://screen-sharing-recording.techidaily.com/new-essential-techniques-for-recording-and-preserving-itunes-videos-for-2024/)

## 

 An outlier is a value that is significantly higher or lower than most of the values in your data. When using Excel to analyze data, outliers can skew the results. For example, the mean average of a data set might truly reflect your values. Excel provides a few useful functions to help manage your outliers, so let's take a look.

##  A Quick Example

 In the image below, the outliers are reasonably easy to spot---the value of two assigned to Eric and the value of 173 assigned to Ryan. In a data set like this, it's easy enough to spot and deal with those outliers manually.

![Range of values containing outliers](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/dataset-border.png) 

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793237/19578" target="_top" id="1793237"><img src="//a.impactradius-go.com/display-ad/19578-1793237" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793237/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 In a larger set of data, that will not be the case. Being able to identify the outliers and remove them from statistical calculations is important---and that's what we'll be looking at how to do in this article.

##  How to Find Outliers in your Data

 To find the outliers in a data set, we use the following steps:

1. Calculate the 1st and 3rd quartiles (we'll be talking about what those are in just a bit).
2. Evaluate the interquartile range (we'll also be explaining these a bit further down).
3. Return the upper and lower bounds of our data range.
4. Use these bounds to identify the outlying data points.

 The cell range on the right of the data set seen in the image below will be used to store these values.

![Range for quartiles](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/quartile-cells-border.png) 

 Let's get started.

###  Step One: Calculate the Quartiles

 If you divide your data into quarters, each of those sets is called a quartile. The lowest 25% of numbers in the range make up the 1st quartile, the next 25% the 2nd quartile, and so on. We take this step first because the most widely-used definition of an outlier is a data point that is more than 1.5 interquartile ranges (IQRs) below the 1st quartile, and 1.5 interquartile ranges above the 3rd quartile. To determine those values, we first have to figure out what the quartiles are.

 Excel provides a QUARTILE function to calculate quartiles. It requires two pieces of information: the array and the quart.

=QUARTILE(array, quart)

 The array is the range of values that you are evaluating. And the quart is a number that represents the quartile you wish to return (e.g., 1 for the 1st quartile, 2 for the 2nd quartile, and so on).

**Note:** In Excel 2010, Microsoft released the QUARTILE.INC and QUARTILE.EXC functions as improvements to the QUARTILE function. QUARTILE is more backward compatible when working across multiple versions of Excel.

 Let's return to our example table.

![Range for quartiles](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/quartile-cells-border.png) 

 To calculate the 1st Quartile we can use the following formula in cell F2.

=QUARTILE(B2:B14,1)

 As you enter the formula, Excel provides a list of options for the quart argument.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/quartile-with-border-1.png) 

<!-- affiliate ads begin -->
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 To calculate the 3rd quartile, we can enter a formula like the previous one in cell F3, but using a three instead of a one.

=QUARTILE(B2:B14,3)

 Now, we've got the quartile data points displayed in the cells.

![1st and 3rd quartile values](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/1st-and-3rd-quartiles-border.png) 

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=4729507&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/TIU/Nero_TuneItUp_Screen_2.webp" border="0">/a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
###  Step Two: Evaluate the Interquartile Range

 The interquartile range (or IQR) is the middle 50% of values in your data. It is calculated as the difference between the 1st quartile value and the 3rd quartile value.

 We're going to use a simple formula into cell F4 that subtracts the 1st quartile from the 3rd quartile:

=F3-F2

 Now, we can see our interquartile range displayed.

![Interquartile value](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/iqr-border.png) 

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->
###  Step Three: Return the Lower and Upper Bounds

 The lower and upper bounds are the smallest and largest values of the data range that we want to use. Any values smaller or larger than these bound values are the outliers.

 We'll calculate the lower bound limit in cell F5 by multiplying the IQR value by 1.5 and then subtracting it from the Q1 data point:

=F2-(1.5*F4)

![Excel formula for lower bound value](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/l-bound-border.png) 

<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1896607/21553" target="_top" id="1896607"><img src="//a.impactradius-go.com/display-ad/21553-1896607" border="0" alt="" width="750" height="422"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1896607/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**Note:** The brackets in this formula are not necessary because the multiplication part will calculate before the subtraction part, but they do make the formula easier to read.

 To calculate the upper bound in cell F6, we'll multiply the IQR by 1.5 again, but this time add it to the Q3 data point:

=F3+(1.5*F4)

![Lower and upper bound values](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/l-bound-and-u-bound-border.png) 

<!-- affiliate ads begin -->
<iframe id="iframe_672" src="//a.impactradius-go.com/gen-ad-code/5597632/1959812/17834/" width="720" height="300" scrolling="no" frameborder="0" marginheight="0" marginwidth="0"></iframe>
<!-- affiliate ads end -->
###  Step Four: Identify the Outliers

 Now that we've got all our underlying data set up, it's time to identify our outlying data points---the ones that are lower than the lower bound value or higher than the upper bound value.

 We'll use the [OR function](https://support.office.com/en-us/article/or-function-7d17ad14-8700-4281-b308-00b131e22af0) to perform this logical test and show the values that meet these criteria by entering the following formula into cell C2:

=OR(B2<$F$5,B2>$F$6)

![OR function to identify outliers](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/or-function-border-1.png) 

 We'll then copy that value into our C3-C14 cells. A TRUE value indicates an outlier, and as you can see, we've got two in our data.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/found-outliers-border-224x300.png) 

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
<!-- affiliate ads end -->
##  Ignoring the Outliers when Calculating the Mean Average

 Using the QUARTILE function let us calculate the IQR and work with the most widely used definition of an outlier. However, when calculating the mean average for a range of values and ignoring outliers, there is a quicker and easier function to use. This technique will not identify an outlier as before, but it will allow us to be flexible with what we might consider our outlier portion.

 The function we need is called TRIMMEAN, and you can see the syntax for it below:

=TRIMMEAN(array, percent)

 The array is the range of values you want to average. The percent is the percentage of data points to exclude from the top and bottom of the data set (you can enter it as a percentage or a decimal value).

 We entered the formula below into cell D3 in our example to calculate the average and exclude 20% of outliers.

=TRIMMEAN(B2:B14, 20%)

![TRIMMEAN formula for average excluding outliers](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/trimmean-border.png) 

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->
---

 There you have two different functions for handling outliers. Whether you want to identify them for some reporting needs or exclude them from calculations such as averages, Excel has a function to fit your needs.

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
<li><a href="https://youtube-sure.techidaily.com/024-approved-action-packed-shoots-creating-dynamic-video-stories-on-youtube/"><u>[New] 2024 Approved  Action-Packed Shoots  Creating Dynamic Video Stories on YouTube</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-navigating-metaverse-self-representation-a-step-by-step-manual/"><u>[New] Navigating Metaverse Self-Representation  A Step-by-Step Manual</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-the-art-of-gaining-traction-using-hashtags-in-igtv-for-2024/"><u>[New] The Art of Gaining Traction  Using Hashtags in IGTV for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-top-online-sources-for-high-quality-vector-illustrations/"><u>[New] Top Online Sources for High-Quality Vector Illustrations</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-achieve-perfect-youtube-broadcasts-with-superior-webcams-for-2024/"><u>[Updated] Achieve Perfect YouTube Broadcasts with Superior Webcams for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-pro-tips-for-captivating-snapchat-stories-for-2024/"><u>[Updated] Pro Tips for Captivating Snapchat Stories for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-propel-your-visuals-forward-seamlessly-combining-windows-photos-and-storyremix/"><u>[Updated] Propel Your Visuals Forward  Seamlessly Combining Windows, Photos, and StoryRemix</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-supercharge-your-video-subtitling-explore-leading-internet-tools-today/"><u>2024 Approved  Supercharge Your Video Subtitling  Explore Leading Internet Tools Today</u></a></li>
<li><a href="https://extra-resources.techidaily.com/become-a-viral-sensation-with-these-9-proven-instagram-tricks-for-2024/"><u>Become a Viral Sensation with These 9 Proven Instagram Tricks for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/command-prompt-wizardry-opening-srt-in-winosx-for-2024/"><u>Command Prompt Wizardry  Opening SRT in Win/OSX for 2024</u></a></li>
<li><a href="https://win-dash.techidaily.com/complete-driver-package-downloaded-optimize-your-pc-with-msi-x470-gaming-plus/"><u>Complete Driver Package Downloaded - Optimize Your PC with MSI X470 Gaming Plus</u></a></li>
<li><a href="https://fake-location.techidaily.com/complete-tutorial-to-use-vpna-to-fake-gps-location-on-apple-iphone-8-drfone-by-drfone-virtual-ios/"><u>Complete Tutorial to Use VPNa to Fake GPS Location On Apple iPhone 8 | Dr.fone</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-and-install-a-detailed-walkthrough-of-focusrite-scarlett-solo-driver-for-pc/"><u>Download & Install: A Detailed Walkthrough of Focusrite Scarlett Solo Driver for PC</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-thunderbolt-driver-software-compatible-with-windows-os/"><u>Download Thunderbolt Driver Software Compatible with Windows OS</u></a></li>
<li><a href="https://win-dash.techidaily.com/easy-steps-to-find-and-install-updated-dell-thunderbolt-tb17-dock-drivers/"><u>Easy Steps to Find and Install Updated Dell Thunderbolt TB17 Dock Drivers</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/exploring-dac-technology-why-you-should-consider-adding-one-to-your-system/"><u>Exploring DAC Technology: Why You Should Consider Adding One to Your System</u></a></li>
<li><a href="https://tech-hub.techidaily.com/exploring-the-boundaries-what-is-the-maximum-capacity-of-a-chatgpt-exchange/"><u>Exploring the Boundaries: What Is the Maximum Capacity of a ChatGPT Exchange?</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/fix-file-not-loaded-completely-error-in-excel-2000-stellar-by-stellar-guide/"><u>Fix File Not Loaded Completely Error in Excel 2000 | Stellar</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/framing-emotions-through-color-grading-for-2024/"><u>Framing Emotions Through Color Grading for 2024</u></a></li>
<li><a href="https://win-dash.techidaily.com/free-download-steelseries-keyboard-drivers-and-software/"><u>Free Download: SteelSeries Keyboard Drivers & Software</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-newest-epson-l3150-printer-drivers-for-windows-operating-systems-xenial-and-high-sierra-released/"><u>Get the Newest Epson L3150 Printer Drivers for Windows Operating Systems: Xenial & High Sierra Released</u></a></li>
<li><a href="https://win-dash.techidaily.com/hassle-free-update-for-your-amd-ryzen-5-2400-gpu-drivers/"><u>Hassle-Free Update for Your AMD Ryzen 5 지대 2400까지 GPU Drivers</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/honor-90-gt-unlock-tool-remove-android-phone-password-pin-pattern-and-fingerprint-by-drfone-android-unlock-android-unlock/"><u>Honor 90 GT Unlock Tool - Remove android phone password, PIN, Pattern and fingerprint</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-install-official-toshiba-printer-software-on-your-pc-a-step-by-step-guide/"><u>How to Install Official Toshiba Printer Software on Your PC: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-install-the-latest-canon-printer-software-on-your-windows-pc/"><u>How to Install the Latest Canon Printer Software on Your Windows PC</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-ace-the-art-of-game-recordings-in-windows-11/"><u>In 2024, Ace the Art of Game Recordings in Windows 11</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-budgetclouds-vault-spaceful-large-data-sanctuary/"><u>In 2024, BudgetCloud's Vault  Spaceful Large Data Sanctuary</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-find-my-friends-work-on-xiaomi-redmi-12-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Does find my friends work on Xiaomi Redmi 12 5G | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-the-art-of-repeated-imagery-in-instagram-videos/"><u>In 2024, The Art of Repeated Imagery in Instagram Videos</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-the-ultimate-guide-to-htc-u23-pro-pattern-lock-screen-everything-you-need-to-know-by-drfone-android/"><u>In 2024, The Ultimate Guide to HTC U23 Pro Pattern Lock Screen Everything You Need to Know</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-ultimate-guide-on-tecno-spark-go-2023-frp-bypass-by-drfone-android/"><u>In 2024, Ultimate Guide on Tecno Spark Go (2023) FRP Bypass</u></a></li>
<li><a href="https://win-dash.techidaily.com/install-today-qualcomms-top-notch-atheros-ar3011-bluetooth-30-support-software/"><u>Install Today: Qualcomm's Top-Notch Atheros AR3011 Bluetooth 3.0 Support Software</u></a></li>
<li><a href="https://win-dash.techidaily.com/instant-improvement-to-audio-quality-new-version-of-nahimic-driver/"><u>Instant Improvement to Audio Quality - New Version of Nahimic Driver</u></a></li>
<li><a href="https://win-dash.techidaily.com/latest-firmware-and-drivers-for-canon-mg2900-printers-available-here/"><u>Latest Firmware & Drivers for Canon MG2900 Printers Available Here</u></a></li>
<li><a href="https://win-dash.techidaily.com/latest-hp-laserjet-p1link-1006-printer-drivers-quick-and-secure-download-options/"><u>Latest HP LaserJet P1([link]) 1006 Printer Drivers - Quick and Secure Download Options</u></a></li>
<li><a href="https://win-dash.techidaily.com/latest-intel-ac-9560-wireless-driver-update-for-optimal-performance/"><u>Latest Intel AC 9560 Wireless Driver Update for Optimal Performance</u></a></li>
<li><a href="https://win-dash.techidaily.com/msi-gs65-latest-driver-download-guide-compatible-with-windows-os/"><u>MSI GS65 Latest Driver Download Guide - Compatible with Windows OS</u></a></li>
<li><a href="https://win-dash.techidaily.com/quick-download-guide-get-your-lexar-usb-driver-now/"><u>Quick Download Guide: Get Your Lexar USB Driver Now</u></a></li>
<li><a href="https://win-dash.techidaily.com/seamless-update-process-for-epson-xp-440-drivers-heres-how/"><u>Seamless Update Process for Epson XP-440 Drivers - Here's How</u></a></li>
<li><a href="https://win-dash.techidaily.com/secure-your-data-with-updated-intel-raid-controllers-for-all-windows-operating-systems/"><u>Secure Your Data with Updated Intel RAID Controllers for All Windows Operating Systems</u></a></li>
<li><a href="https://win-dash.techidaily.com/step-by-step-guide-to-updating-your-amd-vega-driver-boosting-games-like-never-before/"><u>Step-by-Step Guide to Updating Your AMD Vega Driver - Boosting Games Like Never Before!</u></a></li>
<li><a href="https://win-dash.techidaily.com/step-by-step-guide-updating-your-graphics-card-drivers-in-windows-11/"><u>Step-by-Step Guide: Updating Your Graphics Card Drivers in Windows 11</u></a></li>
<li><a href="https://win-dash.techidaily.com/step-by-step-tutorial-on-how-to-update-or-download-surface-book-drivers-easily/"><u>Step-by-Step Tutorial on How to Update or Download Surface Book Drivers Easily!</u></a></li>
<li><a href="https://win-dash.techidaily.com/step-by-step-tutorial-installing-new-firmware-on-wireless-adapters-in-windows-1110/"><u>Step-by-Step Tutorial: Installing New Firmware on Wireless Adapters in Windows 11/10</u></a></li>
<li><a href="https://win-dash.techidaily.com/troubleshooting-how-to-fix-windows-11-usb-connection-issues/"><u>Troubleshooting: How to Fix Windows 11 USB Connection Issues</u></a></li>
<li><a href="https://fox-direct.techidaily.com/ultimate-collection-highest-ranking-8-4k-players-for-2024/"><u>Ultimate Collection  Highest Ranking 8 4K Players for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unveiling-the-capabilities-of-emotion-recognition-ai-do-machines-genuinely-grasp-our-feelings/"><u>Unveiling the Capabilities of Emotion Recognition AI: Do Machines Genuinely Grasp Our Feelings?</u></a></li>
<li><a href="https://win-dash.techidaily.com/update-and-install-the-newest-logitech-keyboard-software-compatible-with-windows/"><u>Update and Install the Newest Logitech Keyboard Software Compatible with Windows</u></a></li>
<li><a href="https://win-dash.techidaily.com/update-your-razer-graphics-driver-on-windows-10-8-7-xp-and-vista-step-by-step-guide-to-downloading-new-versions/"><u>Update Your Razer Graphics Driver on Windows 10, 8, 7, XP & Vista: Step-by-Step Guide to Downloading New Versions.</u></a></li>
<li><a href="https://change-location.techidaily.com/where-is-the-best-place-to-catch-dratini-on-vivo-v27-pro-drfone-by-drfone-virtual-android/"><u>Where Is the Best Place to Catch Dratini On Vivo V27 Pro | Dr.fone</u></a></li>
</ul></div>
