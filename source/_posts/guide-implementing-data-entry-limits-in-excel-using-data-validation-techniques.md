---
title: "Guide: Implementing Data Entry Limits in Excel Using Data Validation Techniques"
date: 2024-08-28T01:33:21.215Z
updated: 2024-08-29T01:33:21.215Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/7a5da68125bc45bc63708f2f580be8038605e22ab60525be31c19cd6a83a650a.jpg
---

## Guide: Implementing Data Entry Limits in Excel Using Data Validation Techniques

If you use Excel spreadsheets to collect data from other people, but find that they often fill your carefully-planned cells with the wrong kind of information, data validation can help.

 This tool lets you restrict specific cells to only allow properly-formatted data. If someone enters anything that’s not supposed to be there---like “lunch at airport” instead of “$15.68” on an expense report---Excel rejects the input until they get it right. Think of it as a passive-aggressive way to make sure people don’t waste your time.

 As an example, here’s the basic expense report worksheet for How-To Geek. Let's say we want to make sure that people only enter numerical values that are formatted as currency (i.e., some digits, followed by a decimal point, followed by two more digits) into certain cells.

 First, select all the cells you want to restrict.

![expense report](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/04/expense-report.png) 

 Switch over to the "Data" tab on the Ribbon, and then click the “Data Validation” button. If your window isn't full size and you can’t see the labels, it’s the icon with two horizontal boxes, a green check mark, and a red crossed circle.

![arrow](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/04/arrow.png) 

 In the Data Validation window, on the "Settings" tab, click the “Allow” dropdown menu. Here, you can set a specific type of input to allow for your selected cells. For our expense report, we’re going to insist that users put in a number with two decimal values, so we would select the “Decimal” option. You can also select other criteria, like making sure a cell contains text, a time or date, text of a specific length, or even your own custom validation.

![decimal](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/04/decimal.png) 

 Whatever type of data you select on the “Allow” dropdown changes the options available to you on the rest of the "Settings" tab. Since we want a numerical value corresponding to currency, we're setting the "Data" dropdown to the “between” setting. Then, we're configuring a minimum value of 0.00 and a maximum value of 10000.00, which is way more than enough to cover our needs.

![data range](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/04/data-range.png) 

 To test it our, click “OK” to apply the validation settings, and then try putting in an improper value. For example, if we type “pancakes” for the Breakfast value instead of the cost of the meal, we'll get an error message.

![value](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/04/value.png) 

 While that does restrict people to entering only the correct type of data, it doesn't give them any feedback on what type of data is required. So, let's set that up, too.

 Head back to the Data Validation window (Data > Data Validation on the Ribbon). You've got two options here (and you can use both of them if you want). You can use the "Input Message" tab to have a pop-up tool tip show people the type of data you want whenever they select a cell for which data validation is turned on. You can also use the "Error Alert" tab to customize the error they see when they enter the wrong type of data.

 Let's switch over to the "Input Message" tab first. Here, make sure the "Show input message when cell is selected" option is turned on. Then, give your input tooltip a title and some text. As you can see below, just clicking in one of the cells pops up the message letting people know what's expected.

![input message](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/04/input-message.png) 

 On the "Error Alert" tab, you can customize the error message people see when they enter the wrong type of data. Make sure the "Show error alert after invalid data is entered" option is turned on. Pick a style for your error message from the "Style" dropdown. You can go with a Stop (the red circle with the X), Warning (yellow triangle with an exclamation point), or Information (blue circle with a lowercase "i"), depending on how strong you want the message to come across.

 Type a title for your message, the text of the message itself, and then hit "OK" to finish up.

![error alert](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/04/error-alert.png) 

 Now, if someone tries to enter improper data, that error message is a little more helpful (or sarcastic, if you prefer).

![excel_1](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/04/excel_1.png) 

 It's a bit of extra legwork setting up data validation, but it can save you a lot of time later on if you use spreadsheets for collecting data from other people. It's even useful for preventing your own mistakes. And this is doubly true if you’ve set up formulas or any kind of automation tasks that rely on that data.

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
<li><a href="https://youtube-sure.techidaily.com/024-approved-discover-top-affordable-video-editors-of-2023-today/"><u>[New] 2024 Approved  Discover Top Affordable Video Editors of 2023 Today!</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-achieve-superior-zoom-sound-2-essential-tweaks-explored/"><u>[New] Achieve Superior Zoom Sound  2 Essential Tweaks Explored</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-19-secrets-to-free-capture-of-virtual-learning-sessions/"><u>[New] In 2024, 19 Secrets to FREE Capture of Virtual Learning Sessions</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-premium-gopro-enhancements-guide-for-2024/"><u>[New] Premium Gopro Enhancements Guide for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-elevate-audience-engagement-top-hashtag-strategies-revealed-for-2024/"><u>[Updated] Elevate Audience Engagement  Top Hashtag Strategies Revealed for 2024</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-key-10-efficient-online-subtitle-editors-for-2024/"><u>[Updated] Key 10 Efficient Online Subtitle Editors for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-teaching-with-technology-incorporating-youtube-into-lessons/"><u>[Updated] Teaching with Technology  Incorporating YouTube Into Lessons</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-unite-music-and-imagery-via-auditory-integration-in-premiere-pro/"><u>[Updated] Unite Music and Imagery via Auditory Integration in Premiere Pro</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-best-twitter-tools-for-purifying-and-personalizing-your-timeline/"><u>2024 Approved  Best Twitter Tools for Purifying & Personalizing Your Timeline</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-intro-magic-crafting-irresistible-podcast-openers/"><u>2024 Approved  Intro Magic  Crafting Irresistible Podcast Openers</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-unlocking-the-secrets-to-building-trust-with-fb-giveaways/"><u>2024 Approved  Unlocking the Secrets to Building Trust with FB Giveaways</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/5-solutions-for-poco-f5-pro-5g-unlock-without-password-by-drfone-android/"><u>5 Solutions For Poco F5 Pro 5G Unlock Without Password</u></a></li>
<li><a href="https://fox-glue.techidaily.com/50plus-text-wonders-in-video-editing/"><u>50+ Text Wonders in Video Editing</u></a></li>
<li><a href="https://android-frp.techidaily.com/about-nokia-c300-frp-bypass-by-drfone-android/"><u>About Nokia C300 FRP Bypass</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722974311750-amd-rx-580-video-card-driver-upgrade-quick-downloads-for-smooth-gaming-performance/"><u>AMD RX 580 Video Card Driver Upgrade: Quick Downloads for Smooth Gaming Performance!</u></a></li>
<li><a href="https://win-dash.techidaily.com/compatible-logitech-brio-webcam-driver-downloads-for-windows-1087-users/"><u>Compatible Logitech BRIO Webcam Driver Downloads for Windows 10/8/7 Users</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-and-install-latest-driver-updates-for-nvidia-rtx-2070-super-on-windows-11/"><u>Download and Install Latest Driver Updates for Nvidia RTX 2070 Super on Windows 11</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-hp-officejet-pro-8600-printer-drivers-on-windows-step-by-step-guide/"><u>Download HP Officejet Pro 8600 Printer Drivers on Windows: Step-by-Step Guide</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-intelligent-thunderbolt-drivers-fast-simple-steps-inside/"><u>Download Intelligent Thunderbolt Drivers Fast: Simple Steps Inside</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-samsung-c460-drivers-in-a-flash-steps-inside/"><u>Download Samsung C460 Drivers in a Flash – Steps Inside</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-updated-nvidia-gtx-98cu-tech-super-driver-no-cost/"><u>Download Updated NVIDIA GTX 98Cu Tech SUPER Driver [No Cost]</u></a></li>
<li><a href="https://win-dash.techidaily.com/easy-instructions-for-integrating-beats-audio-into-your-system/"><u>Easy Instructions for Integrating Beats Audio Into Your System</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficient-desktop-arrangement-including-this-pc-icons/"><u>Efficient Desktop Arrangement: Including 'This PC' Icons</u></a></li>
<li><a href="https://win-dash.techidaily.com/epson-l3150-printer-drivers-download-and-installation-guide-for-windows-1187/"><u>Epson L3150 Printer Drivers: Download & Installation Guide for Windows 11/8/7</u></a></li>
<li><a href="https://win-dash.techidaily.com/free-download-killer-e2200-gigabit-ethernet-network-card-drivers/"><u>Free Download: Killer E2200 Gigabit Ethernet Network Card Drivers</u></a></li>
<li><a href="https://win-dash.techidaily.com/free-epson-wf-2630-driver-download-updated-software-for-windows-os-versions/"><u>Free Epson WF 2630 Driver Download: Updated Software for Windows OS Versions</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722961077743-get-the-best-of-wacom-intuos-with-fully-functional-drivers-for-windows-systems-download-now/"><u>Get the Best of Wacom Intuos with Fully Functional Drivers for Windows Systems - Download Now!</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722963012436-get-the-latest-canon-drivers-fast-free-downloads-and-guides-for-windows-users/"><u>Get the Latest Canon Drivers Fast - Free Downloads & Guides for Windows Users</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-most-recent-version-of-the-lide-220-scan-tool-from-canon/"><u>Get the Most Recent Version of the LiDE 220 Scan Tool From Canon</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-new-driver-for-your-lenovo-camera-compatible-with-windows-n-7-systems/"><u>Get the New Driver for Your Lenovo Camera: Compatible with Windows N 7 Systems</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-your-asus-bt50-bluetooth-adapter-driver-for-windows-11108-now/"><u>Get Your Asus BT50 Bluetooth Adapter Driver for WINDOWS 11/10/8 Now!</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722965092730-get-your-hands-on-the-latest-sound-blaster-audigy-drivers-free-download-available-now/"><u>Get Your Hands on the Latest Sound Blaster Audigy Drivers - Free Download Available Now!</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-your-m-audio-fast-track-usb-driver-here-compatible-with-recent-windows-versions-including-w11w7w8w81/"><u>Get Your M-Audio Fast Track USB Driver Here – Compatible with Recent Windows Versions Including W11/W7/W8/W8.1</u></a></li>
<li><a href="https://win-dash.techidaily.com/guide-how-to-get-the-newest-version-of-sas-for-your-pc-windows/"><u>Guide: How To Get The Newest Version Of SAS for Your PC (Windows)</u></a></li>
<li><a href="https://win-dash.techidaily.com/hassle-free-guide-to-getting-the-epson-et-4550-printer-up-and-running-on-windows/"><u>Hassle-Free Guide to Getting the Epson ET-4550 Printer Up & Running on Windows</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-fix-samsung-printer-drivers-on-windows-solutions-and-tips/"><u>How to Fix Samsung Printer Drivers on Windows: Solutions and Tips</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-get-your-hands-on-free-nvidia-3d-vision-drivers-for-windows-without-hassle/"><u>How to Get Your Hands on Free Nvidia 3D Vision Drivers for Windows Without Hassle</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-install-the-newest-canon-mg2n-software-on-your-inkjet-printer/"><u>How to Install the Newest Canon MG2n Software on Your Inkjet Printer</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-keep-your-microsoft-surface-book-2-running-smoothly-with-driver-updates/"><u>How to Keep Your Microsoft Surface Book 2 Running Smoothly with Driver Updates</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-remove-phone-number-from-your-apple-id-from-your-iphone-se-2022-by-drfone-ios/"><u>How To Remove Phone Number From Your Apple ID from Your iPhone SE (2022)?</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-detect-and-remove-spyware-on-asus-rog-phone-7-ultimate-drfone-by-drfone-virtual-android/"><u>In 2024, How to Detect and Remove Spyware on Asus ROG Phone 7 Ultimate? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-unlocking-made-easy-the-best-10-apps-for-unlocking-your-infinix-note-30-pro-device-by-drfone-android/"><u>In 2024, Unlocking Made Easy The Best 10 Apps for Unlocking Your Infinix Note 30 Pro Device</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-which-pokemon-can-evolve-with-a-moon-stone-for-motorola-moto-g23-drfone-by-drfone-virtual-android/"><u>In 2024, Which Pokémon can Evolve with a Moon Stone For Motorola Moto G23? | Dr.fone</u></a></li>
<li><a href="https://win-dash.techidaily.com/lenovo-energy-saving-software-updates-a-painless-process/"><u>Lenovo Energy Saving Software Updates - A Painless Process</u></a></li>
<li><a href="https://games-able.techidaily.com/navigating-low-memory-issues-in-roblox-for-smartphones-iphone/"><u>Navigating Low-Memory Issues in Roblox for Smartphones (iPhone)</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-in-2024-best-free-dvd-playback-options-for-windows-10-users-updated-2023/"><u>New In 2024, Best Free DVD Playback Options for Windows 10 Users Updated 2023</u></a></li>
<li><a href="https://win-dash.techidaily.com/nvidia-quadro-driver-update-direct-download-links-for-windows-10-users/"><u>NVIDIA Quadro Driver Update: Direct Download Links for Windows 10 Users</u></a></li>
<li><a href="https://program-issues.techidaily.com/operation-convert-each-mention-of-stress-into-an-elaborate-medieval-heraldic-language-as-though-announcing-a-royal-decree-on-stresss-impact-on-health/"><u>Operation: Convert Each Mention of Stress Into an Elaborate Medieval Heraldic Language, as Though Announcing a Royal Decree on Stress's Impact on Health.</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722964544178-overcome-compatibility-issues-installing-the-right-drivers-for-ralink-rt3290-on-modern-windows-os/"><u>Overcome Compatibility Issues: Installing the Right Drivers for Ralink RT3290 on Modern Windows OS!</u></a></li>
<li><a href="https://network-issues.techidaily.com/overcoming-video-driver-setbacks-in-minecraft-on-pc/"><u>Overcoming Video Driver Setbacks in Minecraft on PC</u></a></li>
<li><a href="https://win-dash.techidaily.com/quick-and-easy-downloads-updating-your-dell-printer-drivers/"><u>Quick and Easy Downloads: Updating Your Dell Printer Drivers</u></a></li>
<li><a href="https://win-dash.techidaily.com/quick-fix-with-validity-fingerprint-sensor-driver-download-today/"><u>Quick Fix with Validity Fingerprint Sensor Driver - Download Today</u></a></li>
<li><a href="https://win-dash.techidaily.com/quick-guide-download-your-thrustmaster-t150-racing-wheel-drivers/"><u>Quick Guide: Download Your Thrustmaster T150 Racing Wheel Drivers</u></a></li>
<li><a href="https://win-dash.techidaily.com/realtek-rtl8188cu-network-adapter-install-drivers-on-windows-10-or-7/"><u>Realtek RTL8188CU Network Adapter: Install Drivers on Windows 10 or 7</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722973655105-resolved-absence-of-default-printer-and-scanner-drivers-on-windows-10-systems/"><u>Resolved: Absence of Default Printer & Scanner Drivers on Windows 10 Systems</u></a></li>
<li><a href="https://win-dash.techidaily.com/resolving-problems-with-the-realtek-rtl8723be-network-adapter-drivers/"><u>Resolving Problems with the Realtek RTL8723BE Network Adapter Drivers</u></a></li>
<li><a href="https://win-dash.techidaily.com/seamless-download-and-update-how-to-get-the-newest-drivers-for-your-amd-rx-580/"><u>Seamless Download and Update: How to Get the Newest Drivers for Your AMD RX 580</u></a></li>
<li><a href="https://win-dash.techidaily.com/seamless-installation-access-the-latest-samsung-c460-driver-software/"><u>Seamless Installation: Access the Latest Samsung C460 Driver Software</u></a></li>
<li><a href="https://win-dash.techidaily.com/step-by-step-process-to-fresh-update-of-epson-printing-drivers-in-windows-10/"><u>Step-by-Step Process to Fresh Update of Epson Printing Drivers in Windows 10</u></a></li>
<li><a href="https://win-blog.techidaily.com/stop-paladins-from-crashing-proven-fixes-and-tips-for-a-smooth-gameplay/"><u>Stop Paladins From Crashing: Proven Fixes and Tips for a Smooth Gameplay</u></a></li>
<li><a href="https://win-dash.techidaily.com/update-your-dell-thunderbolt-tb17-adapter-free-driver-download-and-installation-guide/"><u>Update Your Dell Thunderbolt TB17 Adapter - Free Driver Download & Installation Guide</u></a></li>
<li><a href="https://win-dash.techidaily.com/update-your-epson-wf-3720-printer-software-for-optimal-performance/"><u>Update Your Epson WF-3720 Printer Software for Optimal Performance</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-2024-approved-essential-knowledge-for-compiling-a-top-notch-auditory-archive-on-youtube/"><u>Updated 2024 Approved Essential Knowledge for Compiling a Top-Notch Auditory Archive on YouTube</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->