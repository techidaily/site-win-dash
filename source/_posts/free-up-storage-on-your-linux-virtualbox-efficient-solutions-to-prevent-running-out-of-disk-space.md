---
title: "Free Up Storage on Your Linux VirtualBox: Efficient Solutions to Prevent Running Out of Disk Space"
date: 2024-08-28T01:32:24.717Z
updated: 2024-08-29T01:32:24.717Z
tags:
  - windows
categories:
  - tech
thumbnail: https://thmb.techidaily.com/f13aeea6c73457fbc5bbd1b6bff4a0c00a428af0a90b0cd758e49ef9cfc3066d.jpg
---

## Free Up Storage on Your Linux VirtualBox: Efficient Solutions to Prevent Running Out of Disk Space

### Key Takeaways

* VirtualBox doesn't automatically shrink Linux guest disks, but you can manually reclaim disk space by zeroing out data and compacting the volume.
* You should enable dynamic allocation in VirtualBox and back up your data before proceeding with the disk compacting process.
* Use the "dd" command to zero-out empty space in the Linux guest and then use VBoxManage to compact the virtual disk image.

 VirtualBox lets you run Linux in a virtual machine, and you'll often find your virtual disks continually growing in size, even though you've been clearing them of files. I'll show you how to shrink these volumes back down to size, compacting them and saving your disk space.

##  Why Your VirtualBox Linux Guest Isn’t Automatically Shrinking

 If you've used [VirtualBox](https://remote-screen-capture.techidaily.com/updated-2024-approved-little-gamers-treasure-trove-of-joy/) with Windows guests (in virtual machine terminology the "guest" is the operating system running within the virtual machine), you're probably used to your VirtualBox disk volumes shrinking as you delete files from them, so that they only use up as much space on your physical disk as they need to contain the files in them.

 This is the intended purpose of VirtualBox's dynamic allocation feature, but it doesn't work with [Linux guests](https://extra-guidance.techidaily.com/updated-snapshot-sophistication-editing-to-dazzle/). When using a Linux guests, many users find the disks grow to their full size, and then never shrink back down as files are deleted from them.

 This is due to how Linux manages its filesystems and how it interacts with its VirtualBox host. Linux doesn't "zero out" (overwrite with empty data) files when they are deleted for performance reasons, so VirtualBox has no way to tell what data on a virtual disk is active data and which is deleted.

 You can solve this issue by zeroing that data yourself, and telling VirtualBox to compact the volume, bringing it back down to its actual size. Here's how it's done.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  How to Reclaim Disk Space From a Linux Virtual Machine in VirtualBox

 The first thing you need to do to reclaim disk space from your Linux guests' virtual disks is ensure that dynamic allocation is enabled. If it is not, you will need to [convert your disk to a dynamically allocated disk](https://fox-info.techidaily.com/new-visualize-verve-vocalize-laughter-kapwings-toolkit/).

![How to find out whether 'Dynamically allocated storage' is enabled for your virtual disk.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/vbox-dynamic-disk-1.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->
 Next, [back up your virtual disk](https://extra-information.techidaily.com/mac-and-pcs-top-10-supercharged-srt-systems-unveiled/). If something goes wrong (like a mistyped command, or your power going out part way through the process), you risk losing all the data in your Linux guest.

 Next, on your Linux guest [run the following command in the terminal](https://vimeo-videos.techidaily.com/updated-boost-your-income-with-effective-vimeo-monetization-techniques-for-2024/):

sudo dd if=/dev/zero of=/var/deleteme

 This command will write zero'd out (empty) data to the file /var/deleteme until the disk is completely full. This overwrites all of your previously deleted files, solving the problem that Linux doesn't overwrite deleted data automatically.

 Be careful using the dd command as it will overwrite data without warning! Check your commands and paths carefully before running them.

 This process could take some time depending on the size of the volume, so be patient and do not interrupt it. Once it has finished, the process will exit (possibly with an error saying that it is out of space). Once this has happened, you can delete the zeroed-out file and shut down your Linux guest:

sudo rm -rf /var/deleteme

    
                    sudo shutdown now -h

 Now the unused space on your virtual disk is zeroed out and VirtualBox will be able to reclaim the space on your host by shrinking it. The final step is to use the vboxmanage command to compact the virtual disk image. Do this by running:

        `vboxmanage modifymedium disk /path/to/image.vdi -compact`
    
 You must change /path/to/image.vdi to the path of the virtual disk you want to compact. If you are on Windows, you will need to use VBoxManage.exe like so:

VBoxManage.exe modifymedium disk /path/to/image.vdi -compact

 If VBoxManage.exe is not available from the command line on your Windows system, read on for instructions on how to enable it.

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  What Did the dd Linux Command Do?

 This method for compacting a VirtualBox Linux guest utilizes the dd command to write an empty file to disk so that empty space can be identified by VirtualBox.

 The [dd](https://ss64.com/bash/dd.html) (data duplicator) command converts and copies files, and can also be used to write data. The "if" option passed to it supplies the input file (in this case /dev/zero supplies a constant stream of zero-value data or null data). The "of" option specifies the output file, and this stream of zero data is written to it. This will continue until the disk is full as /dev/zero never stops providing null data.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
##  Using VboxManage.exe in Windows

 By default, VBoxManage.exe isn't available on the Windows command line. You can add it by [updating your Windows system path](https://screen-mirroring-recording.techidaily.com/updated-ideal-systems-for-recording-and-streaming-athletic-competitions-for-2024/) to include the VirtualBox installation directory, or calling the full path to the executable when using it:

& "C:/Path/To/VBoxManage.exe" modifymedium disk /path/to/image.vdi -compact

 The "&" symbol, called the call operator, that executes the quoted command. This lets you use spaces in path to the executable.

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920047/21774" target="_top" id="1920047"><img src="//a.impactradius-go.com/display-ad/21774-1920047" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920047/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  More About Managing VirtualBox Guests

 As your guests grow, you can [increase the size](https://tech-recovery.techidaily.com/the-ultimate-guide-16-best-free-sources-for-learning-american-sign-language/) of their virtual disks as well as [reduce them](https://screen-video-capture.techidaily.com/new-vocalvoyage-listening-and-recording-expedition-for-2024/). [Snapshotting](https://facebook-video-recording.techidaily.com/updated-fb-video-downloader-extraordinaire-mp4-transformation-for-2024/) lets you take the state of your virtual machine at a certain point in time and save it; if you later want to go back to how things were at that exact moment (for example after testing a configuration change), you can simply roll back and everything will be as it was.

 VirtualBox is a powerful virtualization tool that is used both professionally by developers to build and test software, and home users to run older software and games on modern computers, or run other operating systems without having to purchase a second machine. You can run [Windows](https://some-skills.techidaily.com/the-secrets-of-selecting-a-powerful-streaming-device-for-2024/), [Linux](https://extra-guidance.techidaily.com/updated-snapshot-sophistication-editing-to-dazzle/), [ChromeOS](https://ios-unlock.techidaily.com/in-2024-unlocking-iphone-xs-max-passcode-without-a-computer-by-drfone-ios/), Android, and other operating systems on MacOS, Windows, and Linux Hosts.

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
<li><a href="https://fox-info.techidaily.com/new-2024-approved-mastering-money-making-top-13-strategies-for-novice-reddit-users/"><u>[New] 2024 Approved  Mastering Money-Making  Top 13 Strategies for Novice Reddit Users</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-expert-tips-for-mac-users-audacitys-audio-recording-features-for-2024/"><u>[New] Expert Tips for Mac Users  Audacity's Audio Recording Features for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-from-fast-life-to-leisrances-iphone-slow-motion-tips/"><u>[Updated] In 2024, From Fast Life to Leisrances  IPhone Slow Motion Tips</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-introduction-to-professional-audio-recording-a-mac-and-audacity-approach/"><u>[Updated] Introduction to Professional Audio Recording  A Mac & Audacity Approach</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-the-premier-ranking-comprehensive-8k-tv-analysis-for-2024/"><u>[Updated] The Premier Ranking  Comprehensive 8K TV Analysis for 2024</u></a></li>
<li><a href="https://win-dash.techidaily.com/arduino-projects-and-compatibility-finding-the-right-usb-driver-for-windows-devices/"><u>Arduino Projects and Compatibility: Finding the Right USB Driver for Windows Devices</u></a></li>
<li><a href="https://win-dash.techidaily.com/complete-driver-package-downloaded-optimize-your-pc-with-msi-x470-gaming-plus/"><u>Complete Driver Package Downloaded - Optimize Your PC with MSI X470 Gaming Plus</u></a></li>
<li><a href="https://win-dash.techidaily.com/complete-guide-to-downloading-and-installing-iphone-drivers-on-windows-10-systems/"><u>Complete Guide to Downloading & Installing iPhone Drivers on Windows 10 Systems</u></a></li>
<li><a href="https://win-dash.techidaily.com/complete-guide-downloading-the-hp-universal-print-driver-compatible-with-windows/"><u>Complete Guide: Downloading the HP Universal Print Driver Compatible with Windows</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/dissecting-the-eus-digital-strategy-the-potential-impact-on-chatgpt-technology/"><u>Dissecting the EU's Digital Strategy: The Potential Impact on ChatGPT Technology</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-and-install-a-detailed-walkthrough-of-focusrite-scarlett-solo-driver-for-pc/"><u>Download & Install: A Detailed Walkthrough of Focusrite Scarlett Solo Driver for PC</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-thunderbolt-driver-software-compatible-with-windows-os/"><u>Download Thunderbolt Driver Software Compatible with Windows OS</u></a></li>
<li><a href="https://win-dash.techidaily.com/easy-steps-to-find-and-install-updated-dell-thunderbolt-tb17-dock-drivers/"><u>Easy Steps to Find and Install Updated Dell Thunderbolt TB17 Dock Drivers</u></a></li>
<li><a href="https://win-dash.techidaily.com/effortless-fixes-resolving-compatibility-issues-between-i2c-and-hid-device-drivers/"><u>Effortless Fixes: Resolving Compatibility Issues Between I2C and HID Device Drivers</u></a></li>
<li><a href="https://win-dash.techidaily.com/enhanced-connectivity-awaits-downloading-improved-wireless-network-drivers/"><u>Enhanced Connectivity Awaits - Downloading Improved Wireless Network Drivers</u></a></li>
<li><a href="https://win-dash.techidaily.com/free-download-quick-and-simple-guide-to-installing-easycap-driver/"><u>Free Download: Quick & Simple Guide to Installing EasyCap Driver</u></a></li>
<li><a href="https://win-dash.techidaily.com/free-download-steelseries-keyboard-drivers-and-software/"><u>Free Download: SteelSeries Keyboard Drivers & Software</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-newest-epson-l3150-printer-drivers-for-windows-operating-systems-xenial-and-high-sierra-released/"><u>Get the Newest Epson L3150 Printer Drivers for Windows Operating Systems: Xenial & High Sierra Released</u></a></li>
<li><a href="https://win-dash.techidaily.com/hassle-free-update-for-your-amd-ryzen-5-2400-gpu-drivers/"><u>Hassle-Free Update for Your AMD Ryzen 5 지대 2400까지 GPU Drivers</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/how-to-eliminate-live-sharing-on-devices-for-2024/"><u>How to Eliminate Live Sharing on Devices for 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-android-app-not-installed-error-on-samsung-galaxy-f04-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android App Not Installed Error on Samsung Galaxy F04 Quickly? | Dr.fone</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-install-official-toshiba-printer-software-on-your-pc-a-step-by-step-guide/"><u>How to Install Official Toshiba Printer Software on Your PC: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-install-the-latest-canon-printer-software-on-your-windows-pc/"><u>How to Install the Latest Canon Printer Software on Your Windows PC</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/how-watermarks-safeguard-your-digital-pictures-for-2024/"><u>How Watermarks Safeguard Your Digital Pictures for 2024</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-7-top-ways-to-resolve-apple-id-not-active-issue-for-apple-iphone-15-by-drfone-ios/"><u>In 2024, 7 Top Ways To Resolve Apple ID Not Active Issue For Apple iPhone 15</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-life360-notify-when-you-log-out-on-vivo-y100t-drfone-by-drfone-virtual-android/"><u>In 2024, Does Life360 Notify When You Log Out On Vivo Y100t? | Dr.fone</u></a></li>
<li><a href="https://win-dash.techidaily.com/install-today-qualcomms-top-notch-atheros-ar3011-bluetooth-30-support-software/"><u>Install Today: Qualcomm's Top-Notch Atheros AR3011 Bluetooth 3.0 Support Software</u></a></li>
<li><a href="https://win-dash.techidaily.com/instant-access-to-razer-mamba-drivers-fast-and-hassle-free/"><u>Instant Access to Razer Mamba Drivers – Fast and Hassle-Free</u></a></li>
<li><a href="https://win-dash.techidaily.com/instant-improvement-to-audio-quality-new-version-of-nahimic-driver/"><u>Instant Improvement to Audio Quality - New Version of Nahimic Driver</u></a></li>
<li><a href="https://win-dash.techidaily.com/latest-firmware-and-drivers-for-canon-mg2900-printers-available-here/"><u>Latest Firmware & Drivers for Canon MG2900 Printers Available Here</u></a></li>
<li><a href="https://win-dash.techidaily.com/latest-hp-laserjet-p1link-1006-printer-drivers-quick-and-secure-download-options/"><u>Latest HP LaserJet P1([link]) 1006 Printer Drivers - Quick and Secure Download Options</u></a></li>
<li><a href="https://win-dash.techidaily.com/latest-intel-ac-9560-wireless-driver-update-for-optimal-performance/"><u>Latest Intel AC 9560 Wireless Driver Update for Optimal Performance</u></a></li>
<li><a href="https://win-dash.techidaily.com/locate-their-support-page-and-select-drivers/"><u>Locate Their Support Page and Select 'Drivers.'</u></a></li>
<li><a href="https://win-dash.techidaily.com/msi-gs65-latest-driver-download-guide-compatible-with-windows-os/"><u>MSI GS65 Latest Driver Download Guide - Compatible with Windows OS</u></a></li>
<li><a href="https://android-unlock.techidaily.com/pattern-locks-are-unsafe-secure-your-vivo-y27-4g-phone-now-with-these-tips-by-drfone-android/"><u>Pattern Locks Are Unsafe Secure Your Vivo Y27 4G Phone Now with These Tips</u></a></li>
<li><a href="https://win-dash.techidaily.com/quick-download-guide-get-your-lexar-usb-driver-now/"><u>Quick Download Guide: Get Your Lexar USB Driver Now</u></a></li>
<li><a href="https://win-dash.techidaily.com/seamless-update-process-for-epson-xp-440-drivers-heres-how/"><u>Seamless Update Process for Epson XP-440 Drivers - Here's How</u></a></li>
<li><a href="https://win-dash.techidaily.com/secure-your-data-with-updated-intel-raid-controllers-for-all-windows-operating-systems/"><u>Secure Your Data with Updated Intel RAID Controllers for All Windows Operating Systems</u></a></li>
<li><a href="https://extra-skills.techidaily.com/smirkscribbler-visual-laughter-hub-for-2024/"><u>SmirkScribbler  Visual Laughter Hub for 2024</u></a></li>
<li><a href="https://android-location-track.techidaily.com/solutions-to-spy-on-motorola-razr-40-ultra-with-and-without-jailbreak-drfone-by-drfone-virtual-android/"><u>Solutions to Spy on Motorola Razr 40 Ultra with and without jailbreak | Dr.fone</u></a></li>
<li><a href="https://win-dash.techidaily.com/step-by-step-guide-to-updating-your-amd-vega-driver-boosting-games-like-never-before/"><u>Step-by-Step Guide to Updating Your AMD Vega Driver - Boosting Games Like Never Before!</u></a></li>
<li><a href="https://win-dash.techidaily.com/step-by-step-guide-solving-realtek-wireless-connection-error-in-windows-operating-systems/"><u>Step-by-Step Guide: Solving Realtek Wireless Connection Error in Windows Operating Systems</u></a></li>
<li><a href="https://win-dash.techidaily.com/step-by-step-guide-updating-your-graphics-card-drivers-in-windows-11/"><u>Step-by-Step Guide: Updating Your Graphics Card Drivers in Windows 11</u></a></li>
<li><a href="https://win-dash.techidaily.com/step-by-step-instructions-for-downloading-brother-l2700dw-printer-software-windows-version/"><u>Step-by-Step Instructions for Downloading Brother L2700DW Printer Software (Windows Version)</u></a></li>
<li><a href="https://win-dash.techidaily.com/step-by-step-tutorial-on-how-to-update-or-download-surface-book-drivers-easily/"><u>Step-by-Step Tutorial on How to Update or Download Surface Book Drivers Easily!</u></a></li>
<li><a href="https://win-dash.techidaily.com/step-by-step-tutorial-installing-new-firmware-on-wireless-adapters-in-windows-1110/"><u>Step-by-Step Tutorial: Installing New Firmware on Wireless Adapters in Windows 11/10</u></a></li>
<li><a href="https://win-dash.techidaily.com/troubleshooting-how-to-fix-windows-11-usb-connection-issues/"><u>Troubleshooting: How to Fix Windows 11 USB Connection Issues</u></a></li>
<li><a href="https://win-dash.techidaily.com/update-and-install-the-newest-logitech-keyboard-software-compatible-with-windows/"><u>Update and Install the Newest Logitech Keyboard Software Compatible with Windows</u></a></li>
<li><a href="https://win-dash.techidaily.com/update-your-razer-graphics-driver-on-windows-10-8-7-xp-and-vista-step-by-step-guide-to-downloading-new-versions/"><u>Update Your Razer Graphics Driver on Windows 10, 8, 7, XP & Vista: Step-by-Step Guide to Downloading New Versions.</u></a></li>
<li><a href="https://change-location.techidaily.com/what-pokemon-evolve-with-a-dawn-stone-for-samsung-galaxy-f15-5g-drfone-by-drfone-virtual-android/"><u>What Pokémon Evolve with A Dawn Stone For Samsung Galaxy F15 5G? | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-when-lava-storm-5g-has-black-screen-of-death-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do When Lava Storm 5G Has Black Screen of Death? | Dr.fone</u></a></li>
</ul></div>
