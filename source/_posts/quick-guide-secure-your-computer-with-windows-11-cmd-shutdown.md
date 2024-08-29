---
title: "Quick Guide: Secure Your Computer with Windows 11 CMD Shutdown"
date: 2024-08-28T01:30:49.866Z
updated: 2024-08-29T01:30:49.866Z
tags:
  - windows
categories:
  - tech
thumbnail: https://thmb.techidaily.com/fea69578f265b77158961ce9649233eee0ace50ab1ad8d0ca655a5decd1786bf.jpg
---

## Quick Guide: Secure Your Computer with Windows 11 CMD Shutdown

### Quick Links

* [Lock Your Windows 10 PC Using Command Prompt](https://vp-tips.techidaily.com/new-audiovisual-adaptability-in-free-fire-for-2024/)
* [Set the Lock Screen Timeout Setting Using Command Prompt](https://eaxpv-info.techidaily.com/new-finding-a-different-way-to-naming-your-channel-with-filmora-for-2024/)

### Key Takeaways

* To lock your Windows PC using Command Prompt, run "**Rundll32.exe user32.dll,LockWorkStation"** in the Command Prompt
* To set the lock screen timeout, run "**powercfg.exe /SETACVALUEINDEX SCHEME\_CURRENT SUB\_VIDEO VIDEOCONLOCK <time>"** in Command Prompt as Admin
* Activate the lock screen timeout setting by running "**powercfg.exe /SETACTIVE SCHEME\_CURRENT"** after you set the timeout.

 One of the first rules of cyber security is to always lock your PC before stepping away. While it may not be the quickest way to lock your Windows 10 PC, you can do it using the Command Prompt.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=22741618&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.diskpart.com/resource/images/index/dp-index-img-banner-people@2x.png" border="0">Easy and Safe Partition Software & Hard Disk Manager</a>
<!-- affiliate ads end -->
##  Lock Your Windows 10 PC Using Command Prompt

 First, [open the Command Prompt](https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-oppo-a78-frp-by-drfone-android/) on your PC by opening the Start menu, typing “cmd” in the Windows Search bar, and then selecting “Command Prompt” from the search results.

![Click the Start button, search for 'cmd,' then open 'Command Prompt.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/1-launch-cmd.png) 

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
 Command Prompt will now open. Here, run this command to lock your Windows 10 PC.

Rundll32.exe user32.dll,LockWorkStation

![Locking your PC with Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-lock-pc-command-prompt.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Once executed, your PC will be locked. You'll have to sign back in with your PIN, password, or whatever sign-in method you usually use.

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072199/17885" target="_top" id="2072199"><img src="//a.impactradius-go.com/display-ad/17885-2072199" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072199/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Set the Lock Screen Timeout Setting Using Command Prompt

 Once you’ve locked your PC, the lock screen will generally be displayed for a certain amount of time before it time outs. You can set the amount of time that needs to pass before timing out using the Command Prompt.

 To do this, you’ll need to [open Command Prompt as an admin](https://screen-mirror.techidaily.com/how-to-screen-mirroring-xiaomi-14-ultra-drfone-by-drfone-android/). Do so by typing “cmd” in the Windows Search bar and then right-clicking “Command Prompt” from the results. Next, select “Run As Administrator” from the menu that appears.

![Launching Command Prompt as admin.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/3-launch-cmd.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152810&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/842ca578342915ccb8ae069595ba7233/products/copy_bootit-ss1_178x139.jpg" border="0">The BootIt Collection covers multi-booting, partitioning, and disk imaging on traditional PC's using the standard BIOS and  newer PC's using UEFI.   The collection includes BootIt Bare Metal (BIBM) for standard BIOS systems and BootIt UEFI (BIU) for UEFI system. 
</a>
<!-- affiliate ads end -->
 With Command Prompt open, run this command.

powercfg.exe /SETACVALUEINDEX SCHEME_CURRENT SUB_VIDEO VIDEOCONLOCK <time>

 Replace `<time>` with your desired amount of time in seconds. That means if you want to time out the lock screen after two minutes, you’d enter this command:

powercfg.exe /SETACVALUEINDEX SCHEME_CURRENT SUB_VIDEO VIDEOCONLOCK 120

![Change the timeout to 120.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/4-changing-timeout-to-120.png) 

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BOST%2BRecovery"><img src="https://www.systoolsgroup.com/box/ost-recovery.png" border="0"></a>
<!-- affiliate ads end -->
 This command sets the lock screen timeout setting for your PC if it’s plugged in to a power source. To set the lock screen timeout setting for your PC if it’s running on battery, change`/SETACVALUEINDEX` to`/SETDCVALUEINDEX` and run the command as normal.

 Next, run this command:

powercfg.exe /SETACTIVE SCHEME_CURRENT

![Apply the setting to the currently active scheme.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/5-set-active.png) 

 Now your [lock screen](https://driver-download.techidaily.com/1722977751917-synaptics-drivers-download-and-update-for-windows-easily/) will timeout after the set amount of time. Give it a try!

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
<li><a href="https://screen-sharing-recording.techidaily.com/new-whats-new-with-bandicam-the-2023-expert-analysis/"><u>[New] What's New with Bandicam – The 2023 Expert Analysis</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-in-2024-from-novice-to-specialist-a-step-by-step-journey-through-adobe-ps-background-removal-techniques/"><u>[Updated] In 2024, From Novice to Specialist  A Step-by-Step Journey Through Adobe PS Background Removal Techniques</u></a></li>
<li><a href="https://win-dash.techidaily.com/amd-graphics-card-rx-instruction-what-is-the-meaning-of-the-phrase-to-be-or-not-to-be/"><u>AMD Graphics Card RX # Instruction: What Is the Meaning of the Phrase to Be or Not to Be</u></a></li>
<li><a href="https://win-dash.techidaily.com/boost-your-data-protection-expert-tips-on-using-the-seagate-backup-plus/"><u>Boost Your Data Protection: Expert Tips on Using the Seagate Backup Plus</u></a></li>
<li><a href="https://win-dash.techidaily.com/complete-download-pack-latest-lenovo-x1-carbon-device-drivers-for-windows-users-versions-10-11-and-7/"><u>Complete Download Pack: Latest Lenovo X1 Carbon Device Drivers for Windows Users (Versions 10, 11 & 7)</u></a></li>
<li><a href="https://extra-tips.techidaily.com/conquering-low-light-shots-on-iphone/"><u>Conquering Low-Light Shots on iPhone</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722973338230-download-the-newest-nvidia-quadro-rtx-8000-drivers-compatible-with-windows-11-10-and-7/"><u>Download the Newest Nvidia Quadro RTX 8000 Drivers: Compatible with Windows 11, 10, and 7</u></a></li>
<li><a href="https://win-dash.techidaily.com/downloadable-xbox-360-driving-game-with-compatible-controllers/"><u>Downloadable Xbox 360 Driving Game with Compatible Controllers</u></a></li>
<li><a href="https://fox-http.techidaily.com/dynamic-book-trailers-illustration-for-2024/"><u>Dynamic Book Trailers Illustration for 2024</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722977788742-enhance-your-gameplay-update-nvidia-geforce-gtx-1660-ti-graphics-card-drivers/"><u>Enhance Your Gameplay: Update NVIDIA GeForce GTX 1660 Ti Graphics Card Drivers</u></a></li>
<li><a href="https://win-dash.techidaily.com/expert-tips-to-overcome-challenges-with-your-realtek-universal-video-controller/"><u>Expert Tips to Overcome Challenges with Your Realtek Universal Video Controller</u></a></li>
<li><a href="https://win-dash.techidaily.com/fix-guide-addressing-compatibility-and-functionality-flaws-of-the-realtek-rtl8723be-driver/"><u>Fix Guide: Addressing Compatibility and Functionality Flaws of the Realtek RTL8723BE Driver</u></a></li>
<li><a href="https://win-dash.techidaily.com/free-download-ultimate-driver-setup-for-msi-x470-motherboards/"><u>Free Download: Ultimate Driver Setup for MSI X470 Motherboards</u></a></li>
<li><a href="https://win-dash.techidaily.com/free-installation-of-amd-radeon-hd-drivers-compatible-with-windows-eight/"><u>Free Installation of AMD Radeon HD Drivers Compatible with Windows Eight</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-newest-razer-naga-software-updates-and-download-for-windows-users/"><u>Get the Newest Razer Naga Software Updates & Download for Windows Users</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-your-hp-officejet-pro-8740-up-and-running-drivers-for-windows-11108/"><u>Get Your HP Officejet Pro 8740 Up and Running: Drivers for Windows 11/10/8</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722978312690-get-your-realtek-rtl8188cu-wireless-network-adapter-driver-for-win-107-today/"><u>Get Your Realtek RTL8188CU Wireless Network Adapter Driver for Win 10/7 Today</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-your-windows-compatible-epson-et-2750-printing-drivers-instantly/"><u>Get Your Windows Compatible Epson ET-2750 Printing Drivers Instantly!</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-install-updated-broadcom-bluetooth-software-on-windows-versions-11-8-and-7/"><u>How to Install Updated Broadcom Bluetooth Software on Windows Versions 11, 8 and 7</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-obtain-and-install-logitech-g402-custom-trackball-drivers-and-tools/"><u>How to Obtain and Install Logitech G402 Custom Trackball Drivers & Tools</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-engage-followers-effective-strategies-for-fb-slideshows/"><u>In 2024, Engage Followers  Effective Strategies for FB Slideshows</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-methods-to-change-gps-location-on-vivo-v30-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Methods to Change GPS Location On Vivo V30 Pro | Dr.fone</u></a></li>
<li><a href="https://win-dash.techidaily.com/install-logitech-g920-mouse-drivers-on-your-pc-compatible-with-windows-versions-including-111087/"><u>Install Logitech G920 Mouse Drivers on Your PC - Compatible with Windows Versions Including 11/10/8/7</u></a></li>
<li><a href="https://some-guidance.techidaily.com/lossless-conversion-tactics-transforming-hd-m2ts-files-into-high-quality-mkv-format/"><u>Lossless Conversion Tactics: Transforming HD M2TS Files Into High-Quality MKV Format</u></a></li>
<li><a href="https://win-dash.techidaily.com/say-goodbye-to-additional-installations-windows-1ebshtml)11-os-brings-in-built-in-scanners-and-printer-drivers/"><u>Say Goodbye to Additional Installations: Windows 1Ebs/Html>11 OS Brings in Built-In Scanners and Printer Drivers</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/sustaining-a-dynamic-facebook-experience-for-2024/"><u>Sustaining a Dynamic Facebook Experience for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-best-video-cameras-of-2024/"><u>The Best Video Cameras of 2024</u></a></li>
<li><a href="https://win-dash.techidaily.com/ultimate-guide-to-using-your-seagate-backup-plus-essential-advice-and-hacks/"><u>Ultimate Guide to Using Your Seagate Backup Plus - Essential Advice & Hacks</u></a></li>
<li><a href="https://some-skills.techidaily.com/understanding-luts-transforming-images-magic-for-2024/"><u>Understanding LUTs  Transforming Images Magic for 2024</u></a></li>
<li><a href="https://win-dash.techidaily.com/understanding-the-fix-microsofts-solution-to-the-acpi-compliant-battery-driver-error/"><u>Understanding the Fix: Microsoft's Solution to the ACPI-Compliant Battery Driver Error.</u></a></li>
<li><a href="https://win-dash.techidaily.com/update-your-nvidia-quadro-rtx-4000-card-direct-links-to-new-drivers/"><u>Update Your NVIDIA Quadro RTX 4000 Card: Direct Links to New Drivers</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-2024-approved-windows-10-webcam-recording-top-10-software-options/"><u>Updated 2024 Approved Windows 10 Webcam Recording Top 10 Software Options</u></a></li>
</ul></div>
