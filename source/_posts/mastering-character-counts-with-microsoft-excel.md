---
title: Mastering Character Counts with Microsoft Excel
date: 2024-08-28T01:34:24.472Z
updated: 2024-08-29T01:34:24.472Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/09/microsoft_excel_hero_1200x675.jpg
---

## Mastering Character Counts with Microsoft Excel

### Quick Links

* [How to Get the Character Count of a Single Cell](https://extra-approaches.techidaily.com/2024-approved-prime-pictures-visuals-for-livestream-excellence/)
* [How to Get the Character Count of Multiple Cells](https://extra-lessons.techidaily.com/reviving-shadows-and-highlights-in-iphone-hdr-footage-with-premiere-pro/)
* [How to Get the Count of a Specific Character in a Cell](https://remote-screen-capture.techidaily.com/new-most-reliable-no-cost-chrome-os-recorder-tools-for-2024/)

 Unlike Word where you can easily [get the document's character count](https://tech-savvy.techidaily.com/ai-and-healthcare-how-can-chatgpt-innovate/) using a tool in the menu bar, you'll need to use the [LEN function](https://extra-hints.techidaily.com/scalable-and-stylish-type-in-ae-with-top-choices/) if you want to get a character count in Excel. Here's how to use it.

##  How to Get the Character Count of a Single Cell

 You can use the LEN function to quickly count the number of characters in a single cell in two different ways.

 To use the LEN function to get the character count, click the cell you would like to place the character count in. After that, type 

        `=LEN(cell)`
    
 , where cell is the actual cell you want to get the character count of. So if you want to get the character count of cell A1, you'd enter:

=LEN(A1)

![Enter the LEN function in a cell.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/10/Enter-the-LEN-function-in-a-cell..png) 

 Click on any other cell and the character count will appear.

![The character count of cell A1.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/10/The-character-count-of-cell-A1..png) 

 Or, you can simply copy the content of the cell you want to get the character count of, paste it in the formula in place of the reference cell, and wrap it in quotation marks. For example:

=LEN("How many characters are in this cell?")

![Paste the content of the cell in the formula.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/10/Paste-the-content-of-the-cell-in-the-formula..png) 

 This will return the same result.

 If you're parsing data, you may also want to [split your text across multiple columns](https://tiktok-clips.techidaily.com/2024-approved-speeding-up-tiktok-videos-made-simple/).

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
##  How to Get the Character Count of Multiple Cells

 The LEN function can also be used in combination with the SUM function to get the character count of multiple cells. First, click the cell you would like to place the word count in. Next, enter this formula:

=SUM(LEN(A1),LEN(A2))

 Replace the cell numbers with your own.

![Enter the LEN and SUM function combination.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/10/Enter-the-LEN-and-SUM-function-combination..png) 

<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1922358/21553" target="_top" id="1922358"><img src="//a.impactradius-go.com/display-ad/21553-1922358" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1922358/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Click on any other cell and the character count will be returned.

![The character count of cells A1 and A2.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/10/The-character-count-of-cells-A1-and-A2..png) 

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->
 You can add as many cells as you like in the formula.

 It's also easy to [combine text](https://fake-location.techidaily.com/is-pgsharp-legal-when-you-are-playing-pokemon-on-xiaomi-redmi-13c-5g-drfone-by-drfone-virtual-android/) from these different cells into one.

Related: [How to Combine Text from Multiple Cells into One Cell in Excel](https://fake-location.techidaily.com/is-pgsharp-legal-when-you-are-playing-pokemon-on-xiaomi-redmi-13c-5g-drfone-by-drfone-virtual-android/) 

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713321&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVDJ1.90-300x188.jpg" border="0">OtsAV DJ Pro</a>
<!-- affiliate ads end -->
##  How to Get the Count of a Specific Character in a Cell

 You can also use the LEN function to get the count of how many times a specific character appears in a cell. Select the cell you'd like the count to be returned in and then enter this formula:

=LEN(A1)-LEN(SUBSTITUTE(A1,"a",""))

 Replace the cell (`A1`) with your reference cell and `a` with the character you'd like to get the count of. In our case, we're searching for how many times `a` appears in cell A1.

![Enter the LEN function to get the specific character count.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/10/Enter-the-LEN-function-to-get-the-specific-character-count..png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Click on any other cell and the count of the specified character will be returned.

![The count of the specified character.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/10/The-count-of-the-specified-character..png) 

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4631722&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2023/05/frontpage2-2048x588.webp" border="0">EmEditor Professional (Lifetime License, non-store app)</a>
<!-- affiliate ads end -->
 That's all there is to it. Excel is full of [extremely useful functions](https://some-techniques.techidaily.com/new-exploring-whatsapp-voice-chat-features/), from the [COUNTIF function](https://win-forum.techidaily.com/complete-tutorial-clearing-out-windows-10-memory-dump-data/) to the [FREQUENCY function](https://digital-screen-recording.techidaily.com/new-ideal-low-impact-recording-devices-for-eco-conscious-filmmakers/) to many [different Logical functions](https://extra-skills.techidaily.com/in-2024-spark-engagement-the-ultimate-list-of-video-text-effects/), all designed to streamline your workflow.

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
<li><a href="https://youtube-videos.techidaily.com/new-cut-color-and-compile-a-deep-dive-into-youtube-studio-video-editing/"><u>[New] Cut, Color & Compile  A Deep Dive Into YouTube Studio Video Editing</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-gaming-revolution-top-5-android-solutions-for-playstation-2-titles-for-2024/"><u>[New] Gaming Revolution  Top 5 Android Solutions for PlayStation 2 Titles for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-2024-approved-infusing-life-into-virtual-scenes-with-spark-ar-and-personalized-lookups/"><u>[Updated] 2024 Approved  Infusing Life Into Virtual Scenes with Spark AR and Personalized Lookups</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-transform-your-online-reputation-and-increase-your-social-media-following/"><u>[Updated] 2024 Approved  Transform Your Online Reputation and Increase Your Social Media Following</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-core-techniques-for-capturing-smartphone-content-for-2024/"><u>[Updated] Core Techniques for Capturing Smartphone Content for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-ultimate-twitch-collection-perfectly-preserve-your-tweets-for-2024/"><u>[Updated] Ultimate Twitch Collection - Perfectly Preserve Your Tweets for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/2-ways-to-monitor-tecno-pova-5-activity-drfone-by-drfone-virtual-android/"><u>2 Ways to Monitor Tecno Pova 5 Activity | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-pro-photo-framegers-to-polish-pictures-online/"><u>2024 Approved  Pro Photo Framegers to Polish Pictures Online</u></a></li>
<li><a href="https://win-dash.techidaily.com/asus-usb-bt500-bluetooth-adapter-get-your-free-compatible-windows-drivers-here/"><u>Asus USB-BT500 Bluetooth Adapter: Get Your Free Compatible Windows Drivers Here</u></a></li>
<li><a href="https://win-dash.techidaily.com/ch340g-driver-download-and-update-on-windows-11/"><u>CH340G Driver Download and Update on Windows 11</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-and-install-epson-xp-310-printer-software-latest-version-available-now/"><u>Download & Install Epson XP 310 Printer Software, Latest Version Available Now</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-startech-usb-vga-driver/"><u>Download | StarTech USB VGA Driver</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-the-latest-canon-imageclass-mf6430-printer-driver-for-windows-1187-users/"><u>Download the Latest Canon ImageCLASS MF6430 Printer Driver for Windows 11/8/7 Users</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-the-latest-compatible-epson-ds-ebr-drivers-for-your-windows-11-pc-x64/"><u>Download the Latest Compatible Epson DS-Ebr Drivers for Your Windows 11 PC (X64)</u></a></li>
<li><a href="https://win-dash.techidaily.com/effortless-webcam-driver-setup-for-windows-7-users-get-started-now/"><u>Effortless Webcam Driver Setup for Windows 7 Users – Get Started Now</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722970481267-effortlessly-install-lenovo-x220-driver-updates-get-them-here/"><u>Effortlessly Install Lenovo X220 Driver Updates – Get Them Here</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/embracing-korean-scripts-a-simplified-guide-to-hangul/"><u>Embracing Korean Scripts: A Simplified Guide to Hangul</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-newest-support-for-your-logiteche-mk710-with-these-driver-downloads/"><u>Get the Newest Support for Your Logiteche MK710 with These Driver Downloads</u></a></li>
<li><a href="https://win-dash.techidaily.com/getting-started-with-hp-universal-printers-on-a-windows-pc/"><u>Getting Started with HP Universal Printers on a Windows PC</u></a></li>
<li><a href="https://techidaily.com/hard-resetting-an-honor-magic-6-lite-device-made-easy-drfone-by-drfone-reset-android-reset-android/"><u>Hard Resetting an Honor Magic 6 Lite Device Made Easy | Dr.fone</u></a></li>
<li><a href="https://win-dash.techidaily.com/hassle-free-lexar-driver-setup-secure-your-usb-drives-instantly/"><u>Hassle-Free Lexar Driver Setup – Secure Your USB Drives Instantly</u></a></li>
<li><a href="https://win-howtos.techidaily.com/high-resource-consumption-of-ntoskrnlexe-solved/"><u>High Resource Consumption of ntoskrnl.exe: Solved</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-find-and-install-official-hp-printer-drivers-tips-and-links/"><u>How to Find and Install Official HP Printer Drivers – Tips & Links</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-install-and-upgrade-razer-software-on-windows-111087xpvista/"><u>How to Install and Upgrade Razer Software on Windows 11/10/8/7/XP/Vista</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-vivo-v27-pro-phone-frp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your Vivo V27 Pro Phone FRP Lock</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-laughlab-design-suite/"><u>In 2024, LaughLab Design Suite</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-master-quick-red-eye-correction-with-this-free-ios-tool/"><u>In 2024, Master Quick Red-Eye Correction with This Free iOS Tool</u></a></li>
<li><a href="https://win-dash.techidaily.com/install-your-steelseries-mouse-with-our-official-driver/"><u>Install Your SteelSeries Mouse with Our Official Driver</u></a></li>
<li><a href="https://win-dash.techidaily.com/mastering-the-art-of-amd-video-drivers-upgrade-without-hiccups/"><u>Mastering the Art of AMD Video Drivers Upgrade Without Hiccups</u></a></li>
<li><a href="https://win-dash.techidaily.com/mp280-driver-setup-for-canon-printer-on-windows-os-versions/"><u>MP280 Driver Setup for Canon Printer on Windows OS Versions</u></a></li>
<li><a href="https://win-dash.techidaily.com/official-hp-network-driver-installation-pack-for-windows-11-7-and-8-users/"><u>Official HP Network Driver Installation Pack for Windows 11, 7 & 8 Users</u></a></li>
<li><a href="https://win-dash.techidaily.com/samsung-960-evo-m2-driver-download-and-install-in-windows/"><u>Samsung 960 EVO M.2 Driver Download and Install in Windows</u></a></li>
<li><a href="https://win-dash.techidaily.com/step-by-step-tutorial-fresh-download-and-latest-version-of-intel-optane-driver-for-windows-systems/"><u>Step-by-Step Tutorial: Fresh Download & Latest Version of Intel Optane Driver for Windows Systems</u></a></li>
<li><a href="https://win-dash.techidaily.com/update-your-hp-laptop-drivers-easily-with-our-step-by-step-guide-for-windows-users/"><u>Update Your HP Laptop Drivers Easily with Our Step-by-Step Guide for Windows Users</u></a></li>
<li><a href="https://win-dash.techidaily.com/updated-hp-officejet-3670-drivers-for-optimal-performance/"><u>Updated HP Officejet 3670 Drivers for Optimal Performance</u></a></li>
</ul></div>
