---
title: "Efficiently Organizing Your PC: A Step-by-Step Guide to Creating Folders & Text Files with CMD in Windows"
date: 2024-08-28T01:30:29.006Z
updated: 2024-08-29T01:30:29.006Z
tags:
  - windows
categories:
  - tech
thumbnail: https://thmb.techidaily.com/1fd143d9eb4d07db9c9ac9863a1f2f928a907a725320b5c8de27b0428ee29e3e.jpg
---

## Efficiently Organizing Your PC: A Step-by-Step Guide to Creating Folders & Text Files with CMD in Windows

### Quick Links

* [Before You Begin: Copy the Folder Path and Launch Command Prompt](https://desktop-recording.techidaily.com/updated-iphone-filmmaking-101-capturing-time-in-pixels/)
* [Create a Single Folder](https://howto.techidaily.com/troubleshooting-guide-how-to-fix-an-unresponsive-honor-x7b-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/)
* [Create a Folder Inside Another Folder (Subfolder)](https://www.howtogeek.com/how-to-create-folders-and-files-from-windows-command-prompt/#create-a-folder-inside-another-folder-subfolder)
* [Create Multiple Folders at Once](https://apple-account.techidaily.com/how-to-delete-icloud-account-on-apple-iphone-xr-without-password-by-drfone-ios/)
* [Create a File with Command Prompt](https://fake-location.techidaily.com/thinking-about-changing-your-netflix-region-without-a-vpn-on-infinix-hot-40i-drfone-by-drfone-virtual-android/)

### Key Takeaways

* To create a folder with Command Prompt, use the mkdir command followed by the folder name.
* Mkdir can also be used to create nested folders, multiple folders simultaneously, or a combination of both.
* If you want to create a file, enter type in Command Prompt, followed by nul > filename.ext, replacing ".ext" with the file type you want.

 Whether you’re looking to create a script, make several folders at once, or you simply prefer command-line methods over graphical ones, it’s quick and easy to make folders or files using Command Prompt. We’ll show you how to do it on your Windows 11 or Windows 10 PC.

##  Before You Begin: Copy the Folder Path and Launch Command Prompt

 To use the following methods, you must first copy the path of the folder where you’ll create new folders or files, and then run the Command Prompt utility.

 To copy a folder’s full path, [launch File Explorer](https://pokemon-go-android.techidaily.com/how-to-get-and-use-pokemon-go-promo-codes-on-realme-c67-4g-drfone-by-drfone-virtual-android/) using Windows+E and find your folder. Hold down the Shift key on your keyboard, right-click your folder, and choose "Copy as Path."

!['Copy as Path' highlighted for a folder on a Windows PC.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/1-copy-folder-path-windows.jpg) 

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399"><img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 To [open Command Prompt](https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-oppo-a78-frp-by-drfone-android/), click the Start button, search for **command prompt**, then click the relevant result or press Enter. While making folders, if you encounter an error, [run Command Prompt as an admin](https://instagram-videos.techidaily.com/updated-2024-approved-unlocking-instagram-potential-a-comprehensible-guide/) by right-clicking the utility and choosing "Run as Administrator." Make sure to select "Yes" in the User Account Control prompt.

!['Run as Administrator' highlighted for Command Prompt in Start Menu.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-open-command-prompt-as-admin.jpg) 

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803115/14559" target="_top" id="1803115"><img src="//a.impactradius-go.com/display-ad/14559-1803115" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803115/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 After opening Command Prompt, type **cd**, press Spacebar, paste the folder path you copied by pressing Ctrl+V, and press Enter. This [makes your chosen folder the current working directory](https://extra-information.techidaily.com/quick-and-easy-iphone-burst-techniques/) in the tool. Each command you run will perform the specified action in this directory.

!['cd' command typed in Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/3-change-current-directory-command-prompt.jpg) 

##  Create a Single Folder

 To make a single folder, type the following command, replacing "FolderName" with the name you want to assign to your folder. Then, press Enter.

mkdir FolderName

 For example, to make a folder named "Mahesh", use the following command:

mkdir Mahesh

![Create a single folder from Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/4-create-single-folder-cmd.jpg) 

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296740&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/biu/Nero_BackItUp_Screen_2.webp" border="0"></a>
<!-- affiliate ads end -->
 To create a folder that has spaces in its name, enclose the name with double quotes like this:

mkdir “Mahesh Makvana”

##  Create a Folder Inside Another Folder (Subfolder)

 One way to make a folder inside another folder is to make that other folder the current working directory. To do that, type **cd**, press Spacebar, enter the name of the folder in which you want to create a new folder, and press Enter. Then, type the following command, replace "MyFolder" with the name you want to give to your new folder, and press Enter.

mkdir MyFolder

 Another way to create a folder inside a folder is to specify the other folder right in the mkdir command itself. For example, if you have a subfolder named "Photos" and you want to create a new folder named "Personal" inside it, use the following command:

mkdir Photos\Personal

![Create a subfolder using Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/5-create-subfolder-cmd.jpg) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2337838&QTY=1&AFFILIATE=108875&CART=1"><iframe width="640" height="390" src="https://www.youtube.com/embed/rzZwphIv4RM" title="APFill - Ink and Toner Coverage Calculator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></a>
<!-- affiliate ads end -->
##  Create Multiple Folders at Once

 To [make several folders at once](https://phone-solutions.techidaily.com/in-2024-what-are-location-permissions-life360-on-motorola-razr-40-ultra-drfone-by-drfone-virtual-android/), add the required folder names to the mkdir command.

 For example, to create three separate folders named Documents, Photos, and Videos, use the following command:

mkdir Documents Photos Videos

![Create multiple folders with Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/6-create-multiple-folders-cmd.jpg) 

 Make sure to enclose the folder name with double quotes if its name has spaces.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->
##  Create a File with Command Prompt

 Command Prompt allows you to create empty files, which you can then use with appropriate apps. The syntax for creating a new file is as follows:

type nul > name.ext

 Here, "name" is the name of the file you want to create and "ext" is the [extension of the file](https://twitter-videos.techidaily.com/updated-the-dos-and-donts-of-youtube-videos-on-twitter-for-2024/).

 For example, to make a text file named document.txt, you’ll use the following command:

type nul > document.txt

![Create a file with Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/7-create-file-cmd.jpg) 

<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 To create a text file and add some actual text to it, use the following command. Replace "Welcome to How-To Geek" with the text you want to add and "howtogeek" with the name you want to use for the file.

echo Welcome to How-To Geek > howtogeek.txt

 When you open howtogeek.txt in a text editor you'll find it has "Welcome to How-To Geek" written in it. 

---

 And that’s how you make folders and files without using graphical tools on your Windows machine.

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
<li><a href="https://youtube-web.techidaily.com/0-best-youtube-keyword-tools-to-get-more-views/"><u>[New] 10 Best YouTube Keyword Tools to Get More Views</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-mastering-minecraft-recording-on-mac-a-step-by-step-guide/"><u>[New] In 2024, Mastering Minecraft Recording on Mac  A Step-by-Step Guide</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-the-ultimate-guide-to-iphone-gif-management/"><u>[New] The Ultimate Guide to iPhone GIF Management</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-2024-approved-watch-in-style-top-8-best-mobile-movies-for-iphones/"><u>[Updated] 2024 Approved  Watch in Style  Top 8 Best Mobile Movies for iPhones</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-getting-the-most-out-of-your-game-with-fraps-for-2024/"><u>[Updated] Getting the Most Out of Your Game with Fraps for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-nikon-d500-and-its-stance-on-high-quality-imaging/"><u>[Updated] Nikon D500 and Its Stance on High-Quality Imaging</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-extensive-analysis-the-complete-gear-360-camera-experience/"><u>2024 Approved  Extensive Analysis  The Complete Gear 360 Camera Experience</u></a></li>
<li><a href="https://win-dash.techidaily.com/achieve-next-level-control-and-comfort-with-steelseries-engine-on-windows-11-start-your-free-download-now/"><u>Achieve Next-Level Control & Comfort with SteelSeries Engine on Windows 11 - Start Your Free Download Now</u></a></li>
<li><a href="https://win-dash.techidaily.com/asus-mouse-pad-driver-for-windows-free-download-and-installation-tips/"><u>ASUS Mouse Pad Driver for Windows - Free Download & Installation Tips</u></a></li>
<li><a href="https://win-dash.techidaily.com/asus-touchpad-compatibility-downloading-and-configuring-drivers-on-windows-11-efficiently/"><u>ASUS Touchpad Compatibility: Downloading and Configuring Drivers on Windows 11 Efficiently</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/bulk-image-uploads-on-facebook-a-step-by-step-guide/"><u>Bulk Image Uploads on Facebook: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-dash.techidaily.com/complete-solution-for-retrieving-latest-hp-elitebook-8460p-drivers-on-your-windows-device-downloading-and-installation-guide/"><u>Complete Solution for Retrieving Latest HP EliteBook 8460P Drivers on Your Windows Device - Downloading & Installation Guide</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ng-edge-identifying-the-best-10-free-online-art-schools-on-youtube-for-2024/"><u>Cutting Edge  Identifying the Best 10 Free Online Art Schools on YouTube for 2024</u></a></li>
<li><a href="https://facebook.techidaily.com/did-facebook-expose-your-contact-info/"><u>Did Facebook Expose Your Contact Info?</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-hp-envy-5660-drivers-fast-step-by-step-guide-to-hassle-free-installation/"><u>Download HP Envy 5660 Drivers Fast! Step-by-Step Guide to Hassle-Free Installation.</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722976294784-download-updated-drivers-for-your-eveo-bluetooth-adapter-today/"><u>Download Updated Drivers for Your Eveo Bluetooth Adapter Today</u></a></li>
<li><a href="https://win-dash.techidaily.com/easy-setup-for-asus-tuf-gaming-z370-w-motherboard-drivers-and-tools/"><u>Easy Setup for Asus TUF Gaming Z370-W Motherboard Drivers & Tools</u></a></li>
<li><a href="https://win-dash.techidaily.com/ensure-seamless-printing-with-the-latest-hp-officejet-pro-9015-drivers-download/"><u>Ensure Seamless Printing with the Latest HP Officejet Pro 9015 Drivers Download</u></a></li>
<li><a href="https://win-dash.techidaily.com/expert-guide-addressing-hp-officejet-pro-6978-driver-troubles-effectively/"><u>Expert Guide: Addressing HP OfficeJet Pro 6978 Driver Troubles Effectively</u></a></li>
<li><a href="https://win-dash.techidaily.com/find-and-install-logitech-m525-mouse-software-for-optimal-performance/"><u>Find & Install Logitech M525 Mouse Software for Optimal Performance</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-newest-canon-pixma-mg2522-driver-version-for-enhanced-functionality/"><u>Get the Newest Canon PIXMA MG2522 Driver Version for Enhanced Functionality</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-your-intel-ac-7260-wifi-card-ready-simple-guide-to-downloading-the-latest-drivers/"><u>Get Your Intel AC 7260 WiFi Card Ready: Simple Guide to Downloading the Latest Drivers!</u></a></li>
<li><a href="https://win-dash.techidaily.com/getting-your-scansnap-ix500-up-to-date-windows-software-update-made-easy/"><u>Getting Your ScanSnap iX500 Up to Date: Windows Software Update Made Easy</u></a></li>
<li><a href="https://win-dash.techidaily.com/guidelines-for-fixing-xbox-gamepad-connection-issues-in-win11-win87-environments/"><u>Guidelines for Fixing Xbox Gamepad Connection Issues in Win11, Win8/7 Environments</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-get-your-brother-hl-l2380dw-ready-on-pc-download-the-latest-driver-pack/"><u>How to Get Your Brother HL-L2380DW Ready on PC - Download the Latest Driver Pack</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-quick-and-efficient-download-and-installation-of-nvidias-gtx-1080-ti-graphics-card-drivers/"><u>How To: Quick & Efficient Download and Installation Of NVIDIA's GTX 1080 Ti Graphics Card Drivers</u></a></li>
<li><a href="https://win-dash.techidaily.com/install-the-updated-drivers-for-epson-wf-3520-and-enhance-your-windows-experience/"><u>Install the Updated Drivers for Epson WF 3520 and Enhance Your Windows Experience</u></a></li>
<li><a href="https://win-dash.techidaily.com/instant-access-download-the-official-pioneer-dj-ddj-sx2-software/"><u>Instant Access: Download the Official Pioneer DJ DDJ-SX2 Software</u></a></li>
<li><a href="https://win-dash.techidaily.com/instant-setup-for-your-ms-ergo-keyboard-4000-driver-download-tutorial/"><u>Instant Setup for Your MS Ergo Keyboard 4000 - Driver Download Tutorial</u></a></li>
<li><a href="https://win-dash.techidaily.com/latest-geforce-rtx-2070-driver-download-for-windows-11-8-7/"><u>Latest Geforce RTX 2070 Driver Download for Windows 11, 8, 7</u></a></li>
<li><a href="https://win-dash.techidaily.com/latest-hp-networking-drivers-for-windows-operating-systems-win10-win7-win8/"><u>Latest HP Networking Drivers for Windows Operating Systems: Win10, Win7, Win8</u></a></li>
<li><a href="https://win-dash.techidaily.com/latest-nvidia-geforce-rtx-3070-drivers-download-and-update-for-windows-1011/"><u>Latest NVIDIA GeForce RTX 3070 Drivers Download & Update for Windows 10/11</u></a></li>
<li><a href="https://win-dash.techidaily.com/lenovo-ideapad-100-windows-11-drivers-download-and-update-guide-for-enhanced-functionality/"><u>Lenovo IdeaPad 100 Windows 11 Drivers: Download & Update Guide for Enhanced Functionality</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/navigate-the-transfer-of-social-media-photos-to-hard-drive/"><u>Navigate the Transfer of Social Media Photos to Hard Drive</u></a></li>
<li><a href="https://win-dash.techidaily.com/quick-fix-get-the-newest-asus-bluetooth-driver-software-right-now/"><u>Quick Fix: Get the Newest ASUS Bluetooth Driver Software Right Now</u></a></li>
<li><a href="https://win-dash.techidaily.com/safe-installation-of-corsair-keyboard-drivers-for-pc-users-download-guide/"><u>Safe Installation of Corsair Keyboard Drivers for PC Users - Download Guide</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/summary-of-short-videos-simplicity-included/"><u>Summary of Short Videos, Simplicity Included</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/why-does-instagram-keep-flipping-my-video-for-2024/"><u>Why Does Instagram Keep Flipping My Video for 2024</u></a></li>
</ul></div>
