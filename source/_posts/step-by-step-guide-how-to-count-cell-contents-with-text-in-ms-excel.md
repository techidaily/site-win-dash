---
title: "Step-by-Step Guide: How to Count Cell Contents with Text in MS Excel"
date: 2024-08-28T01:33:52.468Z
updated: 2024-08-29T01:33:52.468Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/3f22ae9e837b10e05053cf12480b5c15e8d166c20b49b11db4fda3e3ee1b2757.jpg
---

## Step-by-Step Guide: How to Count Cell Contents with Text in MS Excel

### Quick Links

* [Count Cells With Any Text in Excel](https://some-approaches.techidaily.com/2024-approved-the-uav-connoisseurs-guide-to-essential-equipment/)
* [Count Cells With Specific Text in Excel](https://facebook-record-videos.techidaily.com/updated-2024-approved-discover-engaging-youtube-threads/)

 Do you want to [count the number of cells](https://howto.techidaily.com/fix-the-error-of-unfortunately-the-processcomandroidphone-has-stopped-on-vivo-v29-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/) that contain any or specific text while ignoring all other cells? If so, Microsoft Excel has a dedicated function to help you do that. We'll show you how to use it.

 In Excel, you can [use the COUNTIF function](https://win-forum.techidaily.com/complete-tutorial-clearing-out-windows-10-memory-dump-data/) to count either cells containing any text or cells containing specific text. Use the method below that works for your specific situation.

##  Count Cells With Any Text in Excel

 To count the number of cells that contain any text, but ignore any numbers, blank cells, and [errors](https://ios-unlock.techidaily.com/in-2024-iphone-12-pro-asking-for-passcode-after-ios-1714-update-what-to-do-by-drfone-ios/), use the method here.

 First, open your spreadsheet with Microsoft Excel. In the spreadsheet, select the cell in which you want to display the result.

![Select a cell in an Excel spreadsheet.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/1-select-cell-3.png) 

 In the selected cell, type the following `COUNTIF` function and press Enter. Make sure to replace `D2` and `D6` in this function with the range where your cells to be counted are.

=COUNTIF(D2:D6,"*")

 Here, the \* (asterisk) argument tells the function to only count cells containing text.

![Enter the COUNTIF function to count all text cells.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/2-countif-count-text-cells.png) 

 You can also count the cells that contain anything but text. To do so, use the following modified version of the `COUNTIF` function. In this function, the argument specifies that only the non-text cells should be counted.

 If a cell has a mix of both text and numbers, it won't be counted.

=COUNTIF(D2:D6,"<>*")

![Enter the COUNTIF function to count all non-text cells.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/3-countif-count-non-text-cells.png) 

 This is the result you will see when you use the COUNTIF function to count the number of cells containing any text.

![The number of cells containing any text.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/4-countif-result.png) 

Related: [How to Highlight Blanks or Errors in Microsoft Excel](https://ios-unlock.techidaily.com/in-2024-iphone-12-pro-asking-for-passcode-after-ios-1714-update-what-to-do-by-drfone-ios/) 

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Count Cells With Specific Text in Excel

 To make Excel only count the cells that contain specific text, use an argument with the `COUNTIF` function.

 First, in your spreadsheet, select the cell in which you want to display the result.

![Select a cell in an Excel spreadsheet.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/1-select-cell-3.png) 

<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->
 In the selected cell, type the following `COUNTIF` function and press Enter. In the function, replace `D2` and `D6` with the [range](https://video-screen-grab.techidaily.com/updated-playful-pioneers-the-kids-game-bazaar-for-2024/) where your cells are. Also, replace `a` with any character or word that your cell should have for it to be counted.

 The below function counts all cells that contain the letter `a`. This means, in our example, it will count both `Mahesh` and `David` as both these names have the letter `a` in them.

=COUNTIF(D2:D6,"*a*")

![Enter the COUNTIF function to count cells containing specific text.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/5-countif-count-specific-text-cells.png) 

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
 Here's the result:

![The number of cells containing specific text.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/6-countif-specific-text-result.png) 

<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2042332/17092" target="_top" id="2042332"><img src="//a.impactradius-go.com/display-ad/17092-2042332" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="960" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042332/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 To make the function count those cells that only have your specified character or word in them, remove the \* (asterisk) sign from before and after your character or word, as follows.

=COUNTIF(D2:D6,"a")

![Enter the COUNTIF function to count cells only containing specific text.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/7-countif-count-only-specific-text-cells.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 In our example, the count result is `0` because there are no cells that only contain the character `a` in them.

![The number of cells containing only specific text.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/8-countif-only-specific-text-cell-result.png) 

<!-- affiliate ads begin -->
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 And that's how you specify what cells to consider for calculation in your Microsoft Excel spreadsheets. Very useful!

---

 Did you know Excel can also [count blank or empty cells](https://fox-blue.techidaily.com/2024-approved-revel-in-richness-your-pcs-pathway-to-exceptional-video-quality/) in your spreadsheets? Check that out if you're interested.

Related: [How to Add Text to a Cell With a Formula in Excel](https://buynow-reviews.techidaily.com/a-comprehensive-review-top-long-reach-routers-dominating-the-market-in-ebytes/)

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
<li><a href="https://win-dash.techidaily.com/instant-download-epson-wf-7710-printer-drivers-fully-tested-on-win-118187/"><u>[INSTANT DOWNLOAD] Epson WF-7710 Printer Drivers Fully Tested on Win 11/8.1/8/7</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-hands-on-guide-to-optimize-your-youtube-channels-with-adsense/"><u>[New] 2024 Approved  Hands-On Guide to Optimize Your YouTube Channels with AdSense</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-tailored-tv-experience-via-social-media-content/"><u>[New] 2024 Approved  Tailored TV Experience via Social Media Content</u></a></li>
<li><a href="https://extra-resources.techidaily.com/new-breaking-down-sync-a-thorough-review-of-lgs-uhd68-display/"><u>[New] Breaking Down Sync  A Thorough Review of LG's UHD68 Display</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-revolutionize-your-ig-feed-with-these-elite-grid-creation-apps-for-2024/"><u>[New] Revolutionize Your IG Feed with These Elite Grid Creation Apps for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-the-quick-fix-guide-to-instagram-popularity-accelerate-your-visibility-with-15-tricks-of-the-trade/"><u>[Updated] 2024 Approved  The Quick-Fix Guide to Instagram Popularity  Accelerate Your Visibility with 15 Tricks of the Trade</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-from-dreamer-to-doer-sign-up-for-a-youtube-channel-for-2024/"><u>[Updated] From Dreamer To Doer  Sign Up for a YouTube Channel for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-how-to-craft-contagious-instagram-visuals/"><u>[Updated] In 2024, How to Craft Contagious Instagram Visuals</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-in-2024-how-to-get-more-likes-on-your-tiktok-unboxing-video/"><u>[Updated] In 2024, How to Get More Likes on Your TikTok Unboxing Video?</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-moviemakermag-comprehensive-editor-review/"><u>[Updated] MovieMakerMag  Comprehensive Editor Review</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-secure-and-fast-instagram-to-mp4-conversion-for-windowsmac-users-for-2024/"><u>[Updated] Secure & Fast Instagram to MP4 Conversion for Windows/Mac Users for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-ultimate-iphone-hdr-insights-for-stunning-images/"><u>[Updated] Ultimate iPhone HDR Insights for Stunning Images</u></a></li>
<li><a href="https://howto.techidaily.com/6-solutions-to-fix-error-505-in-google-play-store-on-poco-m6-pro-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Solutions to Fix Error 505 in Google Play Store on Poco M6 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://win-dash.techidaily.com/comprehensive-tutorial-on-installing-the-latest-zebra-zp450-printer-drivers/"><u>Comprehensive Tutorial on Installing the Latest Zebra ZP450 Printer Drivers</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/vering-the-most-reliable-youtube-downloader-apps-for-android-for-2024/"><u>Discovering the Most Reliable YouTube Downloader Apps for Android for 2024</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-nvidias-official-geforce-rtx-3070-ti-driver-for-windows-operating-systems/"><u>Download NVIDIA's Official GeForce RTX 3070 Ti Driver for Windows Operating Systems</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-techkey-bluetooth-driver-compatible-with-windows-11-7-and-8/"><u>Download Techkey Bluetooth Driver: Compatible with Windows 11, 7 & 8</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-the-latest-canon-mf743cdw-printer-drivers-for-your-pc/"><u>Download the Latest Canon MF743CDW Printer Drivers for Your PC</u></a></li>
<li><a href="https://win-dash.techidaily.com/easy-installation-obtain-brother-hl-l2340dw-windows-compatible-printing-software-now/"><u>Easy Installation: Obtain Brother HL-L2340DW Windows Compatible Printing Software Now!</u></a></li>
<li><a href="https://win-dash.techidaily.com/easy-instructions-for-upgrading-the-epson-et-3760-printer-software-on-your-windows-device/"><u>Easy Instructions for Upgrading the Epson ET-#3760 Printer Software on Your Windows Device</u></a></li>
<li><a href="https://win-dash.techidaily.com/easy-tips-and-tricks-for-refreshing-motherboard-software-on-pcs-running-windows/"><u>Easy Tips & Tricks for Refreshing Motherboard Software on PCs Running Windows</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722969379361-effortless-install-of-nvidia-geforce-rtx-drivers-for-windows-10-direct-download-page/"><u>Effortless Install of NVIDIA GeForce RTX Drivers for Windows 10 - Direct Download Page</u></a></li>
<li><a href="https://win-dash.techidaily.com/effortlessly-upgrade-msi-graphics-card-drivers-for-windows-107-users/"><u>Effortlessly Upgrade MSI Graphics Card Drivers for Windows 10/7 Users</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722967336310-enhance-gameplay-with-the-latest-geforce-rtx-2080-ti-drivers-update-now/"><u>Enhance Gameplay with the Latest GeForce RTX 2080 Ti Drivers - Update Now!</u></a></li>
<li><a href="https://win-dash.techidaily.com/enhance-your-pc-with-free-amd-radeon-hd-driver-update-for-windows-8/"><u>Enhance Your PC with Free AMD Radeon HD Driver Update for Windows 8</u></a></li>
<li><a href="https://win-dash.techidaily.com/enhance-your-printing-experience-download-updated-epson-wf-3620-drivers-for-windows-os-1087/"><u>Enhance Your Printing Experience: Download Updated Epson WF-3620 Drivers for Windows OS 10/8/7</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/forgot-your-poco-lock-screen-pattern-pin-or-password-here-s-what-to-do-by-drfone-android-unlock-android-unlock/"><u>Forgot your Poco lock screen pattern, PIN or password? Here’s what to do</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722972828626-get-the-best-webcam-drivers-for-windows-7-fast-downloads-and-smooth-operations/"><u>Get the Best Webcam Drivers for Windows 7: Fast Downloads & Smooth Operations</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-right-amd-graphics-software-updated-now/"><u>Get the Right AMD Graphics Software Updated Now</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-updated-geforce-rtx-3080-driver-for-your-pc-running-windows-10-8-or-7/"><u>Get the Updated GeForce RTX 3080 Driver for Your PC Running Windows 10, 8 or 7</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-your-logitech-g510-downloaded-supports-windows-7-to-10-systems/"><u>Get Your Logitech G510 Downloaded - Supports Windows 7 to 10 Systems</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-reset-iphone-se-without-itunes-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Reset iPhone SE Without iTunes? | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-xiaomi-redmi-k70-pro-by-drfone-android/"><u>In 2024, AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Xiaomi Redmi K70 Pro</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-check-distance-and-radius-on-google-maps-for-your-motorola-g54-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Check Distance and Radius on Google Maps For your Motorola G54 5G | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-polarr-editor-explained-the-ultimate-visual-enhancement-pathway/"><u>In 2024, Polarr Editor Explained  The Ultimate Visual Enhancement Pathway</u></a></li>
<li><a href="https://win-dash.techidaily.com/install-brother-hl-228n-dot-printer-driver-compatible-for-windows-operating-systems-including-111087/"><u>Install Brother HL-228n DOT Printer Driver - Compatible for Windows Operating Systems Including 11/10/8/7</u></a></li>
<li><a href="https://win-dash.techidaily.com/magicard-rio-pro-driver-update-now-available-for-all-windows-platforms-including-11-81-and-7-free-download/"><u>Magicard Rio Pro Driver Update Now Available for All Windows Platforms Including 11, 8.1 & 7 - Free Download</u></a></li>
<li><a href="https://fix-guide.techidaily.com/motorola-g24-power-not-connecting-to-wi-fi-12-quick-ways-to-fix-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Motorola G24 Power Not Connecting to Wi-Fi? 12 Quick Ways to Fix | Dr.fone</u></a></li>
<li><a href="https://win-dash.techidaily.com/people-rely-on-hunting-and-agriculture-for-food-traditional-economies-are-often-based-in-rural-areas-where-people-depend-heavily-on-natural-resources-for-su218/"><u>People Rely on Hunting and Agriculture for Food: Traditional Economies Are Often Based in Rural Areas Where People Depend Heavily on Natural Resources for Survival. Hunting, Fishing, and Subsistence Farming Are Common Means of Obtaining Food</u></a></li>
<li><a href="https://win-dash.techidaily.com/quick-solutions-troubleshooting-common-problems-with-i2c-based-hid-drivers/"><u>Quick Solutions: Troubleshooting Common Problems with I2C-Based HID Drivers</u></a></li>
<li><a href="https://win-dash.techidaily.com/solve-hp-laserjet-1020-drivers-errors-on-windows-quickly-and-efficiently/"><u>Solve HP LaserJet 1020 Drivers Errors on Windows Quickly and Efficiently</u></a></li>
<li><a href="https://win-dash.techidaily.com/speedy-installation-of-your-brother-hl-3170cdw-printer-software/"><u>Speedy Installation of Your Brother HL-3170CDW Printer Software</u></a></li>
<li><a href="https://win-dash.techidaily.com/step-by-step-tutorial-on-downloading-the-epson-xp-400-drivers/"><u>Step-by-Step Tutorial on Downloading the Epson XP-400 Drivers</u></a></li>
<li><a href="https://win-dash.techidaily.com/step-by-step-tutorial-to-install-hp-scanner-software-on-your-windows-device/"><u>Step-by-Step Tutorial to Install HP Scanner Software on Your Windows Device</u></a></li>
<li><a href="https://win-dash.techidaily.com/successfully-installing-the-latest-amd-radeon-graphics-card-drivers/"><u>Successfully Installing the Latest AMD Radeon Graphics Card Drivers</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722967839431-the-best-way-to-obtain-and-install-samsung-c460-printer-drivers-no-hassle/"><u>The Best Way to Obtain & Install Samsung C460 Printer Drivers - No Hassle</u></a></li>
<li><a href="https://win-dash.techidaily.com/toshiba-multifunction-printer-driver-software-for-windows-operating-systems/"><u>Toshiba Multifunction Printer Driver Software for Windows Operating Systems</u></a></li>
<li><a href="https://win-dash.techidaily.com/troubleshooting-guide-for-pci-encryption-management-tool-corrections/"><u>Troubleshooting Guide for PCI Encryption Management Tool Corrections</u></a></li>
<li><a href="https://win-dash.techidaily.com/troubleshooting-tips-for-lenovo-system-driver-updates-made-easy/"><u>Troubleshooting Tips for Lenovo System Driver Updates Made Easy</u></a></li>
<li><a href="https://win-dash.techidaily.com/ultimate-tutorial-how-to-get-arduino-drivers-compatible-with-windows-operating-system/"><u>Ultimate Tutorial: How to Get Arduino Drivers Compatible with Windows Operating System</u></a></li>
<li><a href="https://some-skills.techidaily.com/unlocking-the-potential-a-compreayers-guide-to-batched-video-downloads-from-tiktok-for-2024/"><u>Unlocking the Potential  A Compreayer's Guide to Batched Video Downloads From TikTok for 2024</u></a></li>
<li><a href="https://win-dash.techidaily.com/usb-to-vga-conversion-for-insignia-devices-installing-the-right-drivers-and-software/"><u>USB to VGA Conversion for Insignia Devices: Installing the Right Drivers & Software</u></a></li>
<li><a href="https://win-dash.techidaily.com/windows-11-compatible-realtek-rtl81cu-wifi-drivers-download-latest-version-available/"><u>Windows 11 Compatible Realtek RTL81#CU WiFi Drivers Download - Latest Version Available</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/windows-stellar-standard-file-wiping-tool-with-automated-schedule-settings/"><u>Windows Stellar Standard File Wiping Tool with Automated Schedule Settings</u></a></li>
</ul></div>
