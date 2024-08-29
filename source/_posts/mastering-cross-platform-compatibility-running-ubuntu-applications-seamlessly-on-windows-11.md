---
title: "Mastering Cross-Platform Compatibility: Running Ubuntu Applications Seamlessly on Windows 11"
date: 2024-08-28T01:30:42.720Z
updated: 2024-08-29T01:30:42.720Z
tags:
  - windows
categories:
  - tech
thumbnail: https://thmb.techidaily.com/7b420d51a7e917d12325acc7124ce448649fcdb3a71e7a06fbd4b66d64319f0c.jpg
---

## Mastering Cross-Platform Compatibility: Running Ubuntu Applications Seamlessly on Windows 11

### Key Takeaways

* Install WSL2 Kernel, activate Virtual Machine Platform, and make sure you have Admin rights before getting Ubuntu on Windows 11.
* Enable Windows Subsystem for Linux, then download and install Ubuntu for WSL via Microsoft Store to run Linux apps on Windows 11.

 Did you know using Ubuntu-exclusive apps doesn't require overwriting your operating system? Unlock the true potential of your Windows desktop by using Ubuntu apps on Windows 11, enhancing your PC experience by blending the power of Linux and Windows.

##  Why Use Ubuntu Apps on Windows 11?

 Adding Ubuntu to Windows 11 enables access to a wide variety of free applications unavailable on Windows alone. These aren't just ordinary programs either; they can accomplish nearly any task on your computer, from enhancing your file management to creative projects. For example, if you're looking for a great photo management tool not found on Windows 11, you might try [Shotwell](https://shotwell-project.org/doc/html/) with WSL. Or, if you're not a fan of the email apps available on Windows, you can install the Ubuntu-native [Geary](https://wiki.gnome.org/Apps/Geary) email client. There are many great exclusive applications for Ubuntu that can level up your Windows PC.

 Furthermore, if you enjoy crafting and coding, the combination of Windows and Ubuntu significantly benefits you. It simplifies the process of working on Linux-oriented projects without the need to leave the Windows environment. This integration reduces complications and amplifies productivity, whether your pursuits involve coding for enjoyment or constructing significant projects.

 Imagine you're a developer working on a cross-platform project. Using Ubuntu apps on Windows means you can quickly and effectively test your new project on Linux and Windows with ease. Take it from me: I write programs in the Go programming language, and being able to test out my code and run it on both Ubuntu and Windows 11 seamlessly is very powerful.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698827&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3REpage-newmainscreenshot.png" border="0">DEX 3 RE is Easy-To-Use DJ Mixing Software for MAC and Windows Designed for Today's Versatile DJ. 

 Mix from your own library of music, iTunes or use the Pulselocker subsciprtion service for in-app access to over 44 million songs. Use with over 85 supported DJ controllers or mix with a keyboard and mouse.  

 DEX 3 RE is everything you need without the clutter - the perfect 2-deck mixing software solution for mobile DJs or hard-core hobbiests.  
 PCDJ DEX 3 RE (DJ Software for Win & MAC - Product Activation For 3 Machines)</a>
<!-- affiliate ads end -->
##  Requirements Before You Begin

 Before you can start using Ubuntu on your Windows 11 system, a few requirements must be met to ensure a smooth process. During my testing, WSL wouldn't work until I installed the latest WSL2 Kernel package installed on Windows 11\. If you're having issues with WSL running on Windows 11 like I did, install this kernel package. It will ensure that WSL v2 operating systems run correctly. You can download and install the EXE file [directly from Microsoft](https://learn.microsoft.com/en-us/windows/wsl/install-manual#step-4---download-the-linux-kernel-update-package).

 In addition to the WSL2 Kernel EXE package, you'll need to enable the "Virtual Machine Platform" feature in the "Windows Features" area of Windows 11\. WSL runs with the help of virtualization, and this feature is a requirement to get the most out of Ubuntu in Windows 11.

 Lastly, ensure you have Administrator rights on your Windows 11 system. Using WSL requires modifying Windows features, and it won't work if you don't have Administrator privileges.

##  Enabling Windows Subsystem for Linux (WSL)

 Windows Subsystem for Linux is not enabled by default on Windows 11\. You'll need to activate this feature on Windows before you can use it to run Ubuntu apps on your Windows PC.

 To start, open the Windows Start Menu on the desktop. Once it is open, type "Turn Windows Features on or off" into the search box. Launch the icon labeled "Control Panel" beneath it to access the "Add/Remove Features" area of Windows 11.

 Inside the "Windows Features" window, scroll down and locate "Windows Subsystem for Linux." After finding it, click on the empty box next to it to activate this feature. Select "OK" after making your selection.

![WSL feature being turned on in Windows 11.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/03/flameshot-wsl-check-box.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Now that the "OK" button has been selected, Windows 11 will begin setting up WSL on your system. This setup process should take a few minutes to complete. When the setup is complete, you must reboot your Windows PC. Select the "Restart now" button to reboot.

 Upon rebooting, log back into your Windows 11 desktop. Once you've logged back in, the Windows Subsystem for Linux will be enabled on Windows 11.

##  Installing Ubuntu

 Ubuntu for WSL is available for Windows 11 via the Microsoft Store, enabling the installation of Ubuntu on your system to run Linux apps within Windows 11.

 To initiate the installation of Ubuntu for WSL, open the Microsoft Store from the Windows 11 desktop. Once open, locate the "Search apps, games, movies, and more" box and click on it.

 In the search box, type "Ubuntu." Upon entering "Ubuntu," the Microsoft Store will display various versions of the Ubuntu app. Select "Ubuntu 22.04.3 LTS" using the mouse.

![The user is searching for Ubuntu WSL 22.04.3 LTS in the Microsoft Store.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/03/wsl-ubuntu-22.png) 

 After selecting "Ubuntu 22.04.3 LTS," you will be directed to its feature page in the Microsoft Store. Locate the "Get" button and click on it. Selecting the "Get" button will initiate the Ubuntu download for Windows 11.

 Downloading Ubuntu 22.04.3 LTS on Windows 11 should be swift, given the program's size is only about 560 MB. Once the download is complete, Ubuntu will be accessible in the Windows Start Menu.

 After Ubuntu 22.04.3 LTS has finished installing on Windows 11, access the Windows Start Menu, search for "Ubuntu 22.04.3 LTS," and launch it. Upon its first launch, Ubuntu will automatically configure itself and prepare for use.

![Ubuntu WSL is installing itself to Windows 11.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/03/wsl-ubuntu-is-installing.png) 

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892107/21290" target="_top" id="1892107"><img src="//a.impactradius-go.com/display-ad/21290-1892107" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892107/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Once Ubuntu has finished its setup on Windows 11, you will see an empty terminal window, ready for you to interact with Ubuntu on your Windows 11 system.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4713565&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Mac： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
##  Basic Configuration Tips

 Here are some basic configuration tips to improve the WSL experience on Windows 11.

###  Windows and Linux File System Integration

 Windows and Linux File System Integration simplifies moving files between your Ubuntu WSL setup and your Windows 11 desktop. Here's how to utilize this feature.

 To access your Ubuntu files from Windows 11, begin by opening Windows Explorer. Once opened, locate the "Linux" penguin icon in the sidebar and select it.

 Upon selecting "Linux," a folder named "Ubuntu-22.04" will appear. Right-click this folder and choose "Pin to Quick access." This action allows you to effortlessly access your Ubuntu files from Windows.

![Ubuntu WSL's file access in the Windows 11 Explorer app.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/03/wsl-selecting-ub.png) 

 To access Windows files from Ubuntu, navigate to the **/mnt/c** folder using the cd command. This method provides interaction with the Windows 11 **C:/** drive.

cd /mnt/c

<!-- affiliate ads begin -->
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
###  Update your Ubuntu WSL app

 It is good practice to update your Ubuntu WSL app from time to time, otherwise programs will stop working. Here's how to do it on Windows 11.

 First, open up the Ubuntu app from the Windows Start Menu. Once it is open, run the apt update command to check for Ubuntu software updates.

sudo apt update

 When you've finished checking for updates, you can use the apt upgrade command to install them.

sudo apt upgrade

![Ubuntu WSL is being updated.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/03/wsl-installing-kdenlive.png) 

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
<!-- affiliate ads end -->
##  Starting and Using Ubuntu

 Ubuntu in Windows 11 has a terminal interface with WSL. WSL is a Linux system layer that is accessible directly from Windows, rather than a Linux desktop on top of the Windows Desktop.

 Using Ubuntu means installing packages to use on Windows 11\. To start Ubuntu, search for "Ubuntu 22.04.3 LTS" in the Windows Start Menu. Once it is opened, it'll be ready to use.

 From here, you can install any app you like. To install an Ubuntu app on your Windows 11 system, start by searching for the name of the app. You can search using the apt search command. For example, to find "wireshark," do:

apt search wireshark

 Look through the search results for the program you wish to install. Then, use the "apt install programname" command. To install Wireshark, for example, it's:

sudo apt install wireshark

 When your program is installed, you can launch it directly from the terminal with the following command:

nohup program_name & disown

![Linux apps Kdenlive and Wireshark are running inside of Windows 11.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/03/wsl-kdenlive-and-wireshark-open.png) 

 Alternatively, applications can be started from the Windows 11 start menu.

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Integration with Windows 11

 When apps are installed through WSL, they integrate into Windows 11 quite well by installing themselves into the Windows 11 Start menu. To access your installed WSL programs from Windows 11, look through your programs. Each integrated application will have a Linux icon.

 The WSL integration with Windows 11 is quite good. However, keep in mind that not every single application is going to create a desktop icon. Sometimes, you may need to launch your Ubuntu programs directly from the terminal. You typically do this by typing its package name and hitting Enter.

##  Troubleshooting Common Setup Issues

 WSL usually installs without a hitch on Windows 11\. However, if you're having issues, there is a quick and easy fix. First, open up PowerShell in Windows 11\. Once it is open, use the update command for WSL. Updating WSL will install various patches and fixes that are sure to alleviate the issues you're experiencing.

wsl --update

 Alternatively, if updating doesn't help, consider re-installing Ubuntu WSL again by following the installation instructions in the "Setup" portion of this guide.

---

 WSL upgrades your Windows 11 experience by bringing Ubuntu apps to your desktop without the hassle of virtualization. Jump into Ubuntu and WSL to enhance the power of your Windows 11 PC and discover new possibilities in computing.

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
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-laughing-up-high-reddit-and-twitters-top-twenty/"><u>[New] 2024 Approved  Laughing Up High  Reddit and Twitter's Top Twenty</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-storytelling-mastery-scriptwriting-secrets-revealed/"><u>[New] Storytelling Mastery  Scriptwriting Secrets Revealed</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solved-counter-strike-2-mic-not-working/"><u>[SOLVED] Counter-Strike 2 Mic Not Working</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-maximize-engagement-with-these-instagram-story-tips/"><u>[Updated] 2024 Approved  Maximize Engagement with These Instagram Story Tips</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-set-up-efficient-live-conversations-on-pc-via-whatsapp-web-for-2024/"><u>[Updated] Set Up Efficient Live Conversations on PC via WhatsApp Web for 2024</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-ultimate-free-choice-high-definition-software-listing/"><u>[Updated] Ultimate Free Choice  High Definition Software Listing</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/approved-easily-download-your-favorites-handpicked-tools-reviewed/"><u>2024 Approved  Easily Download Your Favorites  Handpicked Tools Reviewed</u></a></li>
<li><a href="https://win-dash.techidaily.com/asus-usb-bt500-bluetooth-adapter-get-your-free-compatible-windows-drivers-here/"><u>Asus USB-BT500 Bluetooth Adapter: Get Your Free Compatible Windows Drivers Here</u></a></li>
<li><a href="https://win-dash.techidaily.com/boost-your-gaming-experience-with-steelseries-engine-windows-10-edition/"><u>Boost Your Gaming Experience with SteelSeries Engine Windows 10 Edition</u></a></li>
<li><a href="https://win-blog.techidaily.com/bypassing-the-roblox-load-loop-expert-tips-and-tricks/"><u>Bypassing the Roblox Load Loop - Expert Tips & Tricks</u></a></li>
<li><a href="https://win-dash.techidaily.com/ch340g-driver-download-and-update-on-windows-11/"><u>CH340G Driver Download and Update on Windows 11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/constructing-emotional-resonance-trailer-sound-selection-guide/"><u>Constructing Emotional Resonance  Trailer Sound Selection Guide</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-and-install-epson-xp-310-printer-software-latest-version-available-now/"><u>Download & Install Epson XP 310 Printer Software, Latest Version Available Now</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-and-install-cutting-edge-steelseries-driver-software-today/"><u>Download and Install Cutting-Edge SteelSeries Driver Software Today!</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-the-latest-canon-imageclass-mf6430-printer-driver-for-windows-1187-users/"><u>Download the Latest Canon ImageCLASS MF6430 Printer Driver for Windows 11/8/7 Users</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-the-latest-compatible-epson-ds-ebr-drivers-for-your-windows-11-pc-x64/"><u>Download the Latest Compatible Epson DS-Ebr Drivers for Your Windows 11 PC (X64)</u></a></li>
<li><a href="https://win-dash.techidaily.com/effortless-connection-with-updated-scansnap-s1100-driver-download-and-instructions/"><u>Effortless Connection with Updated Scansnap S1100 Driver Download & Instructions</u></a></li>
<li><a href="https://win-dash.techidaily.com/effortless-webcam-driver-setup-for-windows-7-users-get-started-now/"><u>Effortless Webcam Driver Setup for Windows 7 Users – Get Started Now</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722970481267-effortlessly-install-lenovo-x220-driver-updates-get-them-here/"><u>Effortlessly Install Lenovo X220 Driver Updates – Get Them Here</u></a></li>
<li><a href="https://win-dash.techidaily.com/find-and-apply-newest-lenovo-docking-station-driver-update-seamlessly/"><u>Find and Apply Newest Lenovo Docking Station Driver Update Seamlessly</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-newest-support-for-your-logiteche-mk710-with-these-driver-downloads/"><u>Get the Newest Support for Your Logiteche MK710 with These Driver Downloads</u></a></li>
<li><a href="https://win-dash.techidaily.com/hassle-free-lexar-driver-setup-secure-your-usb-drives-instantly/"><u>Hassle-Free Lexar Driver Setup – Secure Your USB Drives Instantly</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-find-and-install-official-hp-printer-drivers-tips-and-links/"><u>How to Find and Install Official HP Printer Drivers – Tips & Links</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-install-and-upgrade-razer-software-on-windows-111087xpvista/"><u>How to Install and Upgrade Razer Software on Windows 11/10/8/7/XP/Vista</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-samsung-galaxy-s24plus-location-by-number-drfone-by-drfone-virtual-android/"><u>How to Track Samsung Galaxy S24+ Location by Number | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-use-allshare-cast-to-turn-on-screen-mirroring-on-tecno-camon-20-drfone-by-drfone-android/"><u>How To Use Allshare Cast To Turn On Screen Mirroring On Tecno Camon 20 | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-your-oneplus-nord-n30-se-location-on-twitter-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change your OnePlus Nord N30 SE Location on Twitter | Dr.fone</u></a></li>
<li><a href="https://win-dash.techidaily.com/install-your-steelseries-mouse-with-our-official-driver/"><u>Install Your SteelSeries Mouse with Our Official Driver</u></a></li>
<li><a href="https://win-dash.techidaily.com/keep-your-audio-game-strong-updating-corsair-headset-drivers-on-windows/"><u>Keep Your Audio Game Strong: Updating Corsair Headset Drivers on Windows</u></a></li>
<li><a href="https://win-dash.techidaily.com/solve-your-bcm2045a0-driver-woes-instantly-with-these-proven-tips/"><u>Solve Your BCM2045A0 Driver Woes Instantly with These Proven Tips</u></a></li>
<li><a href="https://win-dash.techidaily.com/step-by-step-tutorial-fresh-download-and-latest-version-of-intel-optane-driver-for-windows-systems/"><u>Step-by-Step Tutorial: Fresh Download & Latest Version of Intel Optane Driver for Windows Systems</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/streamlined-techniques-for-capturing-stories-on-instagram-for-2024/"><u>Streamlined Techniques for Capturing Stories on Instagram for 2024</u></a></li>
<li><a href="https://win-dash.techidaily.com/update-lenovo-webcam-software-on-windows-7/"><u>Update Lenovo Webcam Software on Windows 7</u></a></li>
<li><a href="https://win-dash.techidaily.com/updated-hp-officejet-3670-drivers-for-optimal-performance/"><u>Updated HP Officejet 3670 Drivers for Optimal Performance</u></a></li>
</ul></div>
