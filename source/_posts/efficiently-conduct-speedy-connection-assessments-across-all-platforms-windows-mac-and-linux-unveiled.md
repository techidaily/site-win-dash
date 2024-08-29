---
title: Efficiently Conduct Speedy Connection Assessments Across All Platforms - Windows, Mac, and Linux Unveiled
date: 2024-08-28T01:31:16.626Z
updated: 2024-08-29T01:31:16.626Z
tags:
  - windows
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/illustration-of-a-rocket-launching-and-a-connection-speed-bar.jpg
---

## Efficiently Conduct Speedy Connection Assessments Across All Platforms - Windows, Mac, and Linux Unveiled

### Quick Links

* [Run a Speed Test on Mac via Terminal](https://instagram-videos.techidaily.com/new-capture-and-replay-screen-recording-for-instagram-stories-for-2024/)
* [Run a Speed Test on Windows via Command Prompt](https://fake-location.techidaily.com/ispoofer-is-not-working-on-xiaomi-redmi-note-12-proplus-5g-fixed-drfone-by-drfone-virtual-android/)
* [Run a Speed Test on Linux via Terminal](https://games-able.techidaily.com/bring-back-those-good-old-days-why-your-game-needs-pi/)

 Internet speed test websites are often bogged down with ads, slowing down your system. Fortunately, Ookla offers a lightweight Command Line Interface (CLI) version of its speed test so you can test your internet speed without the overhead of a web browser. Here's how to use it on macOS, Windows, and Linux.

##  Run a Speed Test on Mac via Terminal

 To accomplish this on Mac, we will be using [Homebrew](https://visual-screen-recording.techidaily.com/new-breaking-ground-video-capture-breakdown-for-2024/), a [popular macOS package manager](https://screen-activity-recording.techidaily.com/updated-in-2024-virtualvista-viewers-verdict/). If you haven't installed Homebrew yet or if you are unsure, open Terminal (you'll find it under Applications > Utilities) and enter the following command:

        `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
    
 This command will download and install Homebrew. Once installed, you can easily install the speed test CLI by entering:

        `brew install speedtest-cli`
    
 After the installation is complete, you can run the speed test by simply typing:

        `speedtest-cli  
`
    
![Running speedtest cli in macOS Terminal.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/running-speedtest-cli-in-macos-terminal.png) 

 This command will initiate a quick analysis of your internet connection speed, all from within the Terminal. This method not only saves system resources but also eliminates the need for navigating through ad-heavy websites.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Run a Speed Test on Windows via Command Prompt

 Installing the speed test CLI on a Windows PC is straightforward. Start by visiting the [Speedtest CLI download page](https://www.speedtest.net/apps/cli). Scroll down to find the download option for Windows. It's important to note that the CLI tool is only available for 64-bit versions of Windows.

![Downloading Speedtest CLI on Windows](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/downloading-speedtest-cli-for-windows-2.png) 

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
<!-- affiliate ads end -->
 After downloading the installer, unzip the file to find "speedtest.exe." It's a good idea to place this file in a directory like C:\\Program Files\\speedtest.exe as this location is both easy to remember and accessible by all user accounts on your system. For added convenience, consider creating a desktop shortcut or pinning the executable to your taskbar.

 To run the speed test in Command Prompt (hit Start, type "command" and click "Command Prompt" when it appears), all you need to do is type the full path to the executable, encased in quotation marks to prevent conflicts arising from spaces, and hit enter:

        `"C:\Program Files\speedtest.exe"`
    
 To run in [PowerShell (Terminal)](https://techtrends.techidaily.com/what-are-the-stages-in-a-game-of-royal-match/), the syntax is slightly modified. You must prepend an ampersand to run the executable at the given file path, like so:

        `& "C:\Program Files\speedtest.exe"`
    
![Running Speedtest CLI in PowerShell](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/running-speedtest-cli-in-powershell.png) 

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072199/17885" target="_top" id="2072199"><img src="//a.impactradius-go.com/display-ad/17885-2072199" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072199/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 These commands will run the application via the command line, providing you with a quick readout of your current internet speed and related parameters.

<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Run a Speed Test on Linux via Terminal

 Linux users have a slightly different setup process, as the steps can vary depending on the distribution. Here, we'll cover the installation process for one of the [most widely used distributions](https://win11.techidaily.com/the-art-of-merging-your-guide-to-windows-efficiency/): Debian/Ubuntu.

 First, open a Terminal window. Before installing the speed test CLI, you may need to install curl, a command-line tool for transferring data with URLs. If you're unsure whether curl is installed, you can install it by running:

        `sudo apt-get install curl`
    
 Next, add the Ookla repository to your list of package sources. This ensures that you get the latest version of the speed test CLI. Use the following command to do this:

        `curl -s https://packagecloud.io/install/repositories/ookla/speedtest-cli/script.deb.sh | sudo bash`
    
 Once the repository is added, you can install the speed test CLI with:

        `sudo apt-get install speedtest`
    
![Running Speedtest CLI on Ubuntu.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/running-speedtest-cli-on-ubuntu-1.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 After installation, you can test your internet speed by typing "speedtest" in the Terminal and pressing enter. This command will run the test and display the results directly in the window.

---

 Using Ookla's CLI speed test is an efficient way to measure your internet connection speed without the distractions and slowdowns caused by browser-based tools. No matter which OS you're using, this lightweight tool provides accurate and quick results. It's particularly useful when you want to avoid ads or need to integrate speed tests into automated systems or scripts.

 With just a few commands or a shortcut workflow, you can have a reliable tool at your disposal for monitoring and diagnosing your network performance, empowering you to run a network test at the drop of a hat or a hotkey.

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
<li><a href="https://video-capture.techidaily.com/new-free-and-fun-capture-and-convert-skype-calls-mp3-for-2024/"><u>[New] Free & Fun  Capture and Convert Skype Calls (MP3) for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-insearchofimprovedcameratech-beyond-mycam/"><u>[New] InSearchOfImprovedCameraTech Beyond MyCam</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-perfecting-your-reel-integrating-music-on-instagram/"><u>[New] Perfecting Your Reel  Integrating Music on Instagram</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-sharex-overview-top-picks-and-substitutes/"><u>[Updated] In 2024, ShareX Overview  Top Picks & Substitutes</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-best-quality-frames-at-low-motion-velocity/"><u>2024 Approved  Best Quality Frames at Low Motion Velocity</u></a></li>
<li><a href="https://some-techniques.techidaily.com/airdrop-not-working-how-to-fix-it-on-iphone-ipad-and-mac-for-2024/"><u>Airdrop Not Working? How to Fix It on iPhone, iPad, & Mac for 2024</u></a></li>
<li><a href="https://win-dash.techidaily.com/boost-your-mono-laser-printing-a-step-by-step-guide-to-updating-dells-2330d-and-2330dn-printer-drivers/"><u>Boost Your Mono Laser Printing: A Step-by-Step Guide to Updating Dell's 2330D and 2330DN Printer Drivers</u></a></li>
<li><a href="https://win-dash.techidaily.com/brother-hl-l2380dw-obtain-compatible-windows-drivers-for-optimal-print-performance/"><u>Brother HL-L2380DW: Obtain Compatible Windows Drivers for Optimal Print Performance</u></a></li>
<li><a href="https://win-dash.techidaily.com/complete-download-pack-latest-lenovo-x1-carbon-device-drivers-for-windows-users-versions-10-11-and-7/"><u>Complete Download Pack: Latest Lenovo X1 Carbon Device Drivers for Windows Users (Versions 10, 11 & 7)</u></a></li>
<li><a href="https://win-dash.techidaily.com/complete-lenovo-t430-driver-collection-for-windows-10-8-and-7-effortless-downloading-steps/"><u>Complete Lenovo T430 Driver Collection for Windows 10, 8, and 7 - Effortless Downloading Steps</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722957059338-download-broadcom-wireless-drivers-ensuring-compatibility-and-seamless-connectivity/"><u>Download Broadcom Wireless Drivers: Ensuring Compatibility and Seamless Connectivity!</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-logitech-momo-racer-wheel-game-drivers-pc-compatible/"><u>Download Logitech MOMO Racer Wheel Game Drivers - PC Compatible</u></a></li>
<li><a href="https://win-dash.techidaily.com/easy-guide-to-downloading-and-updating-creativitys-webcam-software-on-pc/"><u>Easy Guide to Downloading & Updating Creativity's Webcam Software on PC</u></a></li>
<li><a href="https://win-dash.techidaily.com/effortless-amd-radeon-rx-480-driver-downloads-and-updates-step-by-step-guide/"><u>Effortless AMD Radeon RX 480 Driver Downloads and Updates: Step-by-Step Guide</u></a></li>
<li><a href="https://win-dash.techidaily.com/enhance-your-design-workstation-nvidia-quadro-drivers-for-windows-10-free-download-guide/"><u>Enhance Your Design Workstation: Nvidia Quadro Drivers for Windows 10 - Free Download Guide</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/exploring-the-functionalities-of-the-omnicharge-omni-20-a-versatile-all-in-one-portable-battery-solution-with-innovative-qi-wireless-feature/"><u>Exploring the Functionalities of the Omnicharge Omni 20: A Versatile, All-in-One Portable Battery Solution with Innovative Qi Wireless Feature</u></a></li>
<li><a href="https://win-dash.techidaily.com/fixing-hp-laserjet-p2035-printer-problems-on-windows-a-comprehensive-guide/"><u>Fixing HP LaserJet P2035 Printer Problems on Windows: A Comprehensive Guide</u></a></li>
<li><a href="https://win-dash.techidaily.com/fixing-issues-and-free-downloads-of-nvidia-3d-vision-drivers-tips-for-windows-users/"><u>Fixing Issues & Free Downloads of NVIDIA 3D Vision Drivers - Tips for Windows Users</u></a></li>
<li><a href="https://win-dash.techidaily.com/free-download-behringer-usb-interface-drivers-for-premium-sound/"><u>Free Download: Behringer USB Interface Drivers for Premium Sound</u></a></li>
<li><a href="https://win-dash.techidaily.com/free-download-ultimate-driver-setup-for-msi-x470-motherboards/"><u>Free Download: Ultimate Driver Setup for MSI X470 Motherboards</u></a></li>
<li><a href="https://win-dash.techidaily.com/free-logitech-g35-headset-drivers-compatible-with-windows-7-8-and-10/"><u>Free Logitech G35 Headset Drivers Compatible with Windows 7, 8 & 10</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-latest-canon-mx340-drivers-support-for-win-10-8-and-7-systems/"><u>Get the Latest Canon MX340 Drivers: Support for Win 10, 8 and 7 Systems</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-newest-razer-naga-software-updates-and-download-for-windows-users/"><u>Get the Newest Razer Naga Software Updates & Download for Windows Users</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-updated-logitech-g910-driver-package-for-a-seamless-pc-experience-on-windows-os/"><u>Get the Updated Logitech G910 Driver Package for a Seamless PC Experience on Windows OS</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-your-epson-wf-2750-up-and-running-free-driver-downloads-available-now/"><u>Get Your Epson WF-2750 Up and Running: Free Driver Downloads Available Now!</u></a></li>
<li><a href="https://win-dash.techidaily.com/getting-up-to-date-with-your-hp-laserjet-m5e-series-driver-downloads-and-setup-tips/"><u>Getting Up-to-Date with Your HP Laserjet M5e Series: Driver Downloads & Setup Tips</u></a></li>
<li><a href="https://win-dash.techidaily.com/gtx-780-drivers-download-easily-for-windows/"><u>GTX 780 Drivers Download Easily for Windows</u></a></li>
<li><a href="https://win-dash.techidaily.com/guaranteed-compatibility-simple-way-to-get-wacom-intuos-pro-driver-for-windows-11-installed/"><u>Guaranteed Compatibility: Simple Way to Get Wacom Intuos Pro Driver for Windows 11 Installed</u></a></li>
<li><a href="https://win-dash.techidaily.com/guide-to-easily-solve-hydro-series-h100i-v2-device-recognition-on-pcs/"><u>Guide to Easily Solve Hydro Series H100i v2 Device Recognition on PCs</u></a></li>
<li><a href="https://iphone-location.techidaily.com/how-to-change-your-location-on-apple-iphone-13-pro-drfone-by-drfone-virtual-ios/"><u>How to Change Your Location on Apple iPhone 13 Pro | Dr.fone</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-update-and-repair-faulty-intel-vga-drivers-for-a-stable-window-experience/"><u>How to Update and Repair Faulty Intel VGA Drivers for a Stable Window Experience</u></a></li>
<li><a href="https://win-dash.techidaily.com/hp-officejet-3830-printer-driver-for-windows-users-free-download/"><u>HP OfficeJet 3830 Printer Driver for Windows Users – Free Download</u></a></li>
<li><a href="https://win-dash.techidaily.com/install-or-update-your-epson-wf-3620-printer-drivers-compatible-with-windows-1187-systems/"><u>Install or Update Your Epson WF-3620 Printer Drivers - Compatible with Windows 11/8/7 Systems</u></a></li>
<li><a href="https://win-dash.techidaily.com/install-the-newest-nvidia-geforce-rtx-2070-drivers-on-your-windows-11-8-or-7-machine-today/"><u>Install the Newest NVIDIA GeForce RTX 2070 Drivers on Your Windows 11, 8 or 7 Machine Today!</u></a></li>
<li><a href="https://win-dash.techidaily.com/installing-the-latest-epson-wf-2760-driver-for-your-windows-pc-supports-win11win10win8/"><u>Installing the Latest Epson WF-2760 Driver for Your Windows PC (Supports Win11/Win10/Win8)</u></a></li>
<li><a href="https://win-dash.techidaily.com/latest-hp-deskjet-2600-drivers-easy-download-and-setup-for-windows-7-8-and-10-users/"><u>Latest HP DeskJet 2600 Drivers: Easy Download & Setup for Windows 7, 8 & 10 Users</u></a></li>
<li><a href="https://win-dash.techidaily.com/lenovo-thinkpad-t430-driver-downloads-for-windows-seamless-support-on-windows-1087/"><u>Lenovo ThinkPad T430 Driver Downloads for Windows - Seamless Support on Windows 10/8/7</u></a></li>
<li><a href="https://win-dash.techidaily.com/necrotizing-enterocolitis/"><u>Necrotizing Enterocolitis</u></a></li>
<li><a href="https://win-dash.techidaily.com/quick-download-guide-intel-thunderbolt-chip-driver-software/"><u>Quick Download Guide: Intel Thunderbolt Chip Driver Software</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/remove-device-supervision-from-your-iphone-13-pro-drfone-by-drfone-ios/"><u>Remove Device Supervision From your iPhone 13 Pro | Dr.fone</u></a></li>
<li><a href="https://win-dash.techidaily.com/solved-issue-scanners-and-printers-compatible-with-windows-11-without-separate-drivers/"><u>Solved Issue: Scanners & Printers Compatible with Windows 11 without Separate Drivers</u></a></li>
<li><a href="https://win-dash.techidaily.com/step-by-step-guide-to-downloading-the-pioneer-dj-ddj-sx2-controller-driver/"><u>Step-by-Step Guide to Downloading the Pioneer DJ DDJ-SX2 Controller Driver</u></a></li>
<li><a href="https://extra-tips.techidaily.com/top-13-effortless-revenue-strategies-for-newbies-on-reddit/"><u>Top 13 Effortless Revenue Strategies for Newbies on Reddit</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/top-apps-and-online-tools-to-track-motorola-moto-g24-phone-withwithout-imei-number-by-drfone-android/"><u>Top Apps and Online Tools To Track Motorola Moto G24 Phone With/Without IMEI Number</u></a></li>
<li><a href="https://win-dash.techidaily.com/transform-boundaries-can-cause-dynamic-metamorphism-along-fault-zones/"><u>Transform Boundaries Can Cause Dynamic Metamorphism Along Fault Zones.</u></a></li>
<li><a href="https://win-dash.techidaily.com/update-to-the-latest-free-windows-compatible-asrock-ab350-pro4-graphics-card-drivers/"><u>Update to the Latest: Free Windows-Compatible ASRock AB350 Pro4 Graphics Card Drivers</u></a></li>
</ul></div>
