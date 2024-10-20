---
title: "Quick Guide: Secure Your Computer with Windows 11 CMD Shutdown"
date: 2024-10-18T17:49:02.633Z
updated: 2024-10-20T17:58:33.891Z
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

##  Lock Your Windows 10 PC Using Command Prompt

 First, [open the Command Prompt](https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-oppo-a78-frp-by-drfone-android/) on your PC by opening the Start menu, typing “cmd” in the Windows Search bar, and then selecting “Command Prompt” from the search results.

![Click the Start button, search for 'cmd,' then open 'Command Prompt.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/1-launch-cmd.png) 

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1167086/14483" target="_top" id="1167086">
  <img src="//a.impactradius-go.com/display-ad/14483-1167086" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://electronicx.pxf.io/i/5597632/1167086/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Command Prompt will now open. Here, run this command to lock your Windows 10 PC.

Rundll32.exe user32.dll,LockWorkStation

![Locking your PC with Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-lock-pc-command-prompt.png) 

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528693/16446" target="_top" id="1528693">
  <img src="//a.impactradius-go.com/display-ad/16446-1528693" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528693/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once executed, your PC will be locked. You'll have to sign back in with your PIN, password, or whatever sign-in method you usually use.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105882/7443" target="_top" id="2105882">
  <img src="//a.impactradius-go.com/display-ad/7443-2105882" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105882/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Set the Lock Screen Timeout Setting Using Command Prompt

 Once you’ve locked your PC, the lock screen will generally be displayed for a certain amount of time before it time outs. You can set the amount of time that needs to pass before timing out using the Command Prompt.

 To do this, you’ll need to [open Command Prompt as an admin](https://screen-mirror.techidaily.com/how-to-screen-mirroring-xiaomi-14-ultra-drfone-by-drfone-android/). Do so by typing “cmd” in the Windows Search bar and then right-clicking “Command Prompt” from the results. Next, select “Run As Administrator” from the menu that appears.

![Launching Command Prompt as admin.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/3-launch-cmd.png) 

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2135316/14409" target="_top" id="2135316">
  <img src="//a.impactradius-go.com/display-ad/14409-2135316" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2135316/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 With Command Prompt open, run this command.

powercfg.exe /SETACVALUEINDEX SCHEME_CURRENT SUB_VIDEO VIDEOCONLOCK <time>

 Replace `<time>` with your desired amount of time in seconds. That means if you want to time out the lock screen after two minutes, you’d enter this command:

powercfg.exe /SETACVALUEINDEX SCHEME_CURRENT SUB_VIDEO VIDEOCONLOCK 120

![Change the timeout to 120.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/4-changing-timeout-to-120.png) 

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
<li><a href="https://facebook-video-footage.techidaily.com/new-does-youtube-offer-frequent-payments-to-you-for-2024/"><u>[New] Does YouTube Offer Frequent Payments to You for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-in-2024-next-gen-skyborne-a-deep-dive-into-h501s-x4/"><u>[New] In 2024, Next-Gen Skyborne A Deep Dive Into H501S X4</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-capture-cinematic-moments-seamlessly-across-pcs-and-smartphones/"><u>[Updated] 2024 Approved Capture Cinematic Moments Seamlessly Across PCs & Smartphones</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-exclusive-selection-of-vr-for-drone-pilots/"><u>[Updated] Exclusive Selection of VR for Drone Pilots</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-pros-hunters-rate-action-camera-winners/"><u>2024 Approved Pros Hunters Rate Action Camera Winners</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-top-screen-captures-in-firefox-land/"><u>2024 Approved Top Screen Captures in Firefox Land</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/direct-technique-swap-film-direction-in-media-player-for-2024/"><u>Direct Technique Swap Film Direction in Media Player for 2024</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722967508562-download-epson-v700-printer-drivers-compatible-with-windows-7-81-and-10/"><u>Download Epson V700 Printer Drivers: Compatible with Windows 7, 8.1 & 10</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-sound-blaster-z-drivers-compatible-with-windows-11-easy-steps/"><u>Download Sound Blaster Z Drivers Compatible with Windows 11 - Easy Steps</u></a></li>
<li><a href="https://win-dash.techidaily.com/guide-to-securing-latest-hp-840-g3-graphics-card-drivers-for-optimal-performance/"><u>Guide to Securing Latest HP 840 G3 Graphics Card Drivers for Optimal Performance</u></a></li>
<li><a href="https://win-dash.techidaily.com/hassle-free-download-wacom-graphics-tablet-drivers-installed-in-minutes/"><u>Hassle-Free Download: Wacom Graphics Tablet Drivers Installed in Minutes</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-successfully-download-and-setup-epson-et-4550-printer-driver-on-your-windows-machine/"><u>How to Successfully Download and Setup Epson ET-4550 Printer Driver on Your Windows Machine</u></a></li>
<li><a href="https://win-dash.techidaily.com/latest-drivers-for-your-amd-vega-64-graphics-card-compatible-with-windows-systems/"><u>Latest Drivers for Your AMD Vega 64 Graphics Card - Compatible with Windows Systems</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ize-traffic-essential-youtube-seo-equipment-for-2024/"><u>Maximize Traffic - Essential YouTube SEO Equipment for 2024</u></a></li>
<li><a href="https://win-dash.techidaily.com/step-by-step-process-to-download-and-install-nvme-drives-on-windows/"><u>Step-by-Step Process to Download & Install NVMe Drives on Windows</u></a></li>
<li><a href="https://screen-recording.techidaily.com/streamlined-recording-of-academic-sessions-on-macs/"><u>Streamlined Recording of Academic Sessions on Macs</u></a></li>
<li><a href="https://win-dash.techidaily.com/updated-epson-wf-7710-driver-software-for-windows-operating-systems-windows-10-81-8-and-7/"><u>Updated Epson WF-7710 Driver Software for Windows Operating Systems (Windows 10, 8.1, 8 & 7)</u></a></li>
</ul></div>

