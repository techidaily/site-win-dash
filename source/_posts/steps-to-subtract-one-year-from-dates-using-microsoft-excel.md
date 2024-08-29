---
title: Steps to Subtract One Year From Dates Using Microsoft Excel
date: 2024-08-28T01:34:49.887Z
updated: 2024-08-29T01:34:49.887Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/07/stock-lede-microsoft-office_excel-1.png
---

## Steps to Subtract One Year From Dates Using Microsoft Excel

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
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  CONCATENATE Function

 Concatenation is a term that basically means to link or combine two or more pieces of data. In Microsoft Excel terms, concatenation can be used to add various text strings, numbers, or cell values together in a new cell.

![An example of various text strings combined using the Excel CONCATENATE function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/02/Excel-CONCATENATE-Example.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726960&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/forexrobotronbox.gif" border="0">Forex Robotron Basic Package</a>
<!-- affiliate ads end -->
 If you want to remove the year from a date in Excel, you could combine the output from two functions (such as DAY or MONTH) together using CONCATENATE. Rather than hiding the year from view using custom number formatting, CONCATENATE (with DAY and MONTH) allows you to create a separate value that doesn't include the year at all.

 To do this, open an Excel workbook containing your date values, or create a new workbook and place date values in separate cells. To use CONCATENATE with DAY and MONTH, insert a new function using this structure, replacing the cell reference (A2) with a reference to the cell containing your date:

=CONCATENATE(DAY(A2),"/",MONTH(A2))

 The values returned by DAY and MONTH are separated by a special delimiter character, such as a comma or slash, to show that the returned value is a date. Each value (DAY, the delimiter, and MONTH) are separated by a comma in the CONCATENATE function.

 In this example, cell A2 contains a date value (11/12/2021) in the DD/MM/YYYY format. Using CONCATENATE with DAY and MONTH, the day (11) and month (12) from the date value in A2 are placed in another cell separated by the delimiter, which, in this case, is a forward slash.

![An example of various text strings combined using the Excel CONCATENATE function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/02/Excel-CONCATENATE-Example.png) 

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048963/16384" target="_top" id="2048963"><img src="//a.impactradius-go.com/display-ad/16384-2048963" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048963/16384" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-mastering-screen-capture-expert-take-on-showmore-software/"><u>[New] 2024 Approved  Mastering Screen Capture  Expert Take on ShowMore Software</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-in-2024-breaking-boundaries-in-video-content-creation-within-limit/"><u>[New] In 2024, Breaking Boundaries in Video Content Creation (Within Limit)</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-insiders-choice-the-ultimate-list-of-screen-recorders/"><u>[New] In 2024, Insider's Choice  The Ultimate List of Screen Recorders</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-2024-approved-the-essence-of-vimeo-user-friendly-video-service/"><u>[Updated] 2024 Approved  The Essence of Vimeo  User-Friendly Video Service</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-initiating-live-channels-your-comprehensive-guide-for-2024/"><u>[Updated] Initiating Live Channels  Your Comprehensive Guide for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-is-minimizing-unstable-movement-in-photoshop-beneficial/"><u>[Updated] Is Minimizing Unstable Movement in Photoshop Beneficial?</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-luxury-sedan-sj4000s-best-kept-secrets-gear-up/"><u>[Updated] Luxury Sedan SJ4000's Best-Kept Secrets  Gear Up</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-master-the-switch-making-your-graphic-style-a-sticker-on-every-platform-for-2024/"><u>[Updated] Master the Switch  Making Your Graphic Style a Sticker on Every Platform for 2024</u></a></li>
<li><a href="https://win-dash.techidaily.com/1992-unforgiven-with-eastwood-as-william-munny-an-aging-former-gunfighter-who-is-persuaded-to-go-out-for-one-last-job-to-take-revenge-against-a-prostitute-a179/"><u>1992 - Unforgiven, with Eastwood as William Munny, an Aging Former Gunfighter Who Is Persuaded to Go Out for One Last Job: To Take Revenge Against a Prostitute and Her Boss. The Film Was Based on David Webb Peoples' Screenplay ''The Cut-Whore Killings.'</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-the-gamers-blueprint-securing-memorable-moments-with-4-methods/"><u>2024 Approved  The Gamers' Blueprint  Securing Memorable Moments with 4 Methods</u></a></li>
<li><a href="https://win-dash.techidaily.com/achieve-seamless-trackpad-operation-download-and-enhance-synaptics-drivers/"><u>Achieve Seamless Trackpad Operation: Download & Enhance Synaptics Drivers</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/bypassing-google-account-with-vnrom-bypass-for-oneplus-ace-2-by-drfone-android/"><u>Bypassing Google Account With vnROM Bypass For OnePlus Ace 2</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/discover-the-ultimate-camcorders-for-your-windows-system-for-2024/"><u>Discover the Ultimate Camcorders for Your Windows System for 2024</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-and-install-usb-to-rs-232-cable-driver-for-windows-step-by-step-guide/"><u>Download & Install USB to RS-232 Cable Driver for Windows - Step by Step Guide</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-and-update-guide-epson-wf-3520-printer-driver-on-windows/"><u>Download & Update Guide: Epson WF-3520 Printer Driver on Windows</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-and-install-atheros-network-adapter-drivers-on-windows-systems/"><u>Download and Install Atheros Network Adapter Drivers on Windows Systems</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-intel-processor-drivers-instantly-simple-guide/"><u>Download Intel Processor Drivers Instantly - Simple Guide</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-the-newest-hd-graphics-drivers-by-amd-for-your-pc-running-on-windows-os/"><u>Download the Newest HD Graphics Drivers by AMD for Your PC Running on Windows OS</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-the-perfect-driver-for-your-samsung-850-evo-solid-state-drive-today/"><u>Download the Perfect Driver for Your Samsung 850 EVO Solid State Drive Today!</u></a></li>
<li><a href="https://win-dash.techidaily.com/easy-download-of-epson-workforce-ds-30-printer-software-for-windows-users-windows-10-8-and-7/"><u>Easy Download of Epson WorkForce DS 30 Printer Software for Windows Users (Windows 10, 8 & 7)</u></a></li>
<li><a href="https://win-dash.techidaily.com/easy-download-of-official-hp-wifi-driver-software-on-windows-computers/"><u>Easy Download of Official HP WiFi Driver Software on Windows Computers</u></a></li>
<li><a href="https://win-dash.techidaily.com/easy-steps-to-downloading-the-epson-gt-s50-printer-driver-for-all-windows-users-7810/"><u>Easy Steps to Downloading the Epson GT-S50 Printer Driver for All Windows Users (7/8/10)</u></a></li>
<li><a href="https://win-dash.techidaily.com/effortless-installation-of-new-surface-driver-software/"><u>Effortless Installation of New Surface Driver Software</u></a></li>
<li><a href="https://win-dash.techidaily.com/free-downloads-compatible-drivers-for-your-epson-scanning-device/"><u>Free Downloads: Compatible Drivers for Your Epson Scanning Device</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/full-guide-to-catch-100-iv-pokemon-using-a-map-on-nokia-c12-plus-drfone-by-drfone-virtual-android/"><u>Full Guide to Catch 100 IV Pokémon Using a Map On Nokia C12 Plus | Dr.fone</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-latest-epson-l3110-drivers-supports-win11-win10-and-win7-systems/"><u>Get the Latest Epson L3110 Drivers - Supports Win11, Win10 & Win7 Systems</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-most-recent-driver-updates-for-your-ricoh-mpc3003/"><u>Get the Most Recent Driver Updates for Your Ricoh MPC3003</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-your-logitech-g29-racing-wheel-drivers-on-windows-11-10-or-7/"><u>Get Your Logitech G29 Racing Wheel Drivers on Windows 11, 10 or 7</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722970249419-how-gene-therapy-might-work/"><u>How Gene Therapy Might Work</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722971281702-how-to-easily-install-or-update-d-link-drivers-in-windows-solution-found/"><u>How to Easily Install or Update D-Link Drivers in Windows - SOLUTION FOUND</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-easily-obtain-nvidia-driver-updates-for-windows-10-7-and-ebitron/"><u>How to Easily Obtain Nvidia Driver Updates for Windows 10, 7 & Ebitron</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-successfully-install-or-update-ralink-driver-software-in-windows-systems/"><u>How to Successfully Install or Update Ralink Driver Software in Windows Systems</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-best-anti-tracker-software-for-samsung-galaxy-z-fold-5-drfone-by-drfone-virtual-android/"><u>In 2024, Best Anti Tracker Software For Samsung Galaxy Z Fold 5 | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-film-timeframe-determining-gb-storage-requirement/"><u>In 2024, Film Timeframe  Determining GB Storage Requirement</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-change-lock-screen-wallpaper-on-realme-narzo-n53-by-drfone-android/"><u>In 2024, How to Change Lock Screen Wallpaper on Realme Narzo N53</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-check-distance-and-radius-on-google-maps-for-your-realme-note-50-drfone-by-drfone-virtual-android/"><u>In 2024, How to Check Distance and Radius on Google Maps For your Realme Note 50 | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-infuse-kinetic-smear-into-photos-in-photoshop/"><u>In 2024, Infuse Kinetic Smear Into Photos in Photoshop</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/in-2024-websites-for-downloading-copyright-free-gaming-music/"><u>In 2024, Websites for Downloading Copyright -Free Gaming Music</u></a></li>
<li><a href="https://win-dash.techidaily.com/install-epson-gt-s50-printer-driver-download-guide-for-windows-operating-systems/"><u>Install Epson GT S50 Printer Driver - Download Guide for Windows Operating Systems</u></a></li>
<li><a href="https://win-dash.techidaily.com/instant-install-thrustmaster-t150-controller-software-and-drivers/"><u>Instant Install: Thrustmaster T150 Controller Software and Drivers</u></a></li>
<li><a href="https://driver-install.techidaily.com/lenovo-g580-seamless-driver-updates/"><u>Lenovo G580: Seamless Driver Updates!</u></a></li>
<li><a href="https://fake-location.techidaily.com/methods-to-change-gps-location-on-motorola-moto-g-stylus-2023-drfone-by-drfone-virtual-android/"><u>Methods to Change GPS Location On Motorola Moto G Stylus (2023) | Dr.fone</u></a></li>
<li><a href="https://win-dash.techidaily.com/microsoft-releases-update-for-fixed-acpi-battery-driver-problems-enhancing-device-efficiency/"><u>Microsoft Releases Update for Fixed ACPI Battery Driver Problems, Enhancing Device Efficiency</u></a></li>
<li><a href="https://win-dash.techidaily.com/netgear-a6100-wifi-card-drivers-download-and-installation-guide-on-windows-1087/"><u>Netgear A6100 WiFi Card Drivers Download & Installation Guide on Windows 10/8/7</u></a></li>
<li><a href="https://win-dash.techidaily.com/perfect-wacom-intuos-3-driver-setup-for-windows-systems-a-step-by-step-success-tutorial/"><u>Perfect Wacom Intuos 3 Driver Setup for Windows Systems: A Step-by-Step Success Tutorial!</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722963795475-quick-steps-to-get-the-newest-driver-for-your-wacom-cintiq-install-now/"><u>Quick Steps to Get the Newest Driver for Your Wacom Cintiq: Install Now!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-login-issues-restoring-keyboard-functionality-pre-login/"><u>Resolving Login Issues: Restoring Keyboard Functionality Pre-Login</u></a></li>
<li><a href="https://win-dash.techidaily.com/revitalizing-your-usb-to-serial-adapters-communication-pathway-software/"><u>Revitalizing Your USB-to-Serial Adapter's Communication Pathway Software</u></a></li>
<li><a href="https://win-dash.techidaily.com/roccat-mousedeck-installer-where-to-find-and-download-the-latest-version/"><u>Roccat Mousedeck Installer: Where to Find and Download the Latest Version</u></a></li>
<li><a href="https://win-dash.techidaily.com/seamless-printing-with-hp-officejet-3830-download-and-install-windows-drivers-today/"><u>Seamless Printing with HP OfficeJet 3830 - Download & Install Windows Drivers Today</u></a></li>
<li><a href="https://win-dash.techidaily.com/seamless-upgrade-installing-the-latest-intel-iris-plus-graphics-drivers-in-no-time/"><u>Seamless Upgrade: Installing the Latest Intel Iris Plus Graphics #Drivers in No Time</u></a></li>
<li><a href="https://win-dash.techidaily.com/seamless-upgrading-how-to-install-cutting-edge-msi-audio-drivers-on-windows-systems/"><u>Seamless Upgrading: How to Install Cutting-Edge MSI Audio Drivers on Windows Systems</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722956684671-step-by-step-installation-hp-envy-5660-printer-software-get-yours-free/"><u>Step-by-Step Installation: HP Envy 5660 Printer Software – Get Yours Free</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/the-path-to-autoplay-configuring-youtube-content-for-uninterrupted-streaming-for-2024/"><u>The Path to Autoplay  Configuring Youtube Content for Uninterrupted Streaming for 2024</u></a></li>
<li><a href="https://win-dash.techidaily.com/unravel-the-secrets-of-the-makeblock-mbot-stem-kit-assemble-and-code-a-charming-interactive-robot/"><u>Unravel the Secrets of the Makeblock mBot STEM Kit: Assemble & Code a Charming Interactive Robot</u></a></li>
<li><a href="https://win-dash.techidaily.com/update-your-intel-integrated-graphics-driver-on-windows-11-free-download/"><u>Update Your Intel Integrated Graphics Driver on Windows 11 - Free Download</u></a></li>
<li><a href="https://win-dash.techidaily.com/update-your-printer-downloading-brother-hl-l2370dw-driver-version/"><u>Update Your Printer: Downloading Brother HL-L2370DW Driver Version</u></a></li>
<li><a href="https://win-dash.techidaily.com/upgrade-to-the-latest-download-and-setup-for-scansnap-s1300i-drivers/"><u>Upgrade to the Latest: Download and Setup for ScanSnap S1300i Drivers</u></a></li>
<li><a href="https://win-dash.techidaily.com/urban-creation-mastery-diving-into-the-captivating-world-of-cities-skylines/"><u>Urban Creation Mastery: Diving Into the Captivating World of Cities: Skylines</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/what-to-binge-on-max-our-top-show-recommendations-now/"><u>What to Binge on MAX: Our Top Show Recommendations Now</u></a></li>
</ul></div>
