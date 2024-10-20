---
title: "Efficiently Organizing Your PC: A Step-by-Step Guide to Creating Folders & Text Files with CMD in Windows"
date: 2024-10-13T17:03:21.695Z
updated: 2024-10-20T17:42:49.856Z
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

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134223/18498" target="_top" id="2134223">
  <img src="//a.impactradius-go.com/display-ad/18498-2134223" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134223/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Key Takeaways

* To create a folder with Command Prompt, use the mkdir command followed by the folder name.
* Mkdir can also be used to create nested folders, multiple folders simultaneously, or a combination of both.
* If you want to create a file, enter type in Command Prompt, followed by nul > filename.ext, replacing ".ext" with the file type you want.

 Whether you’re looking to create a script, make several folders at once, or you simply prefer command-line methods over graphical ones, it’s quick and easy to make folders or files using Command Prompt. We’ll show you how to do it on your Windows 11 or Windows 10 PC.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137208/26400" target="_top" id="2137208">
  <img src="//a.impactradius-go.com/display-ad/26400-2137208" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137208/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Before You Begin: Copy the Folder Path and Launch Command Prompt

 To use the following methods, you must first copy the path of the folder where you’ll create new folders or files, and then run the Command Prompt utility.

 To copy a folder’s full path, [launch File Explorer](https://pokemon-go-android.techidaily.com/how-to-get-and-use-pokemon-go-promo-codes-on-realme-c67-4g-drfone-by-drfone-virtual-android/) using Windows+E and find your folder. Hold down the Shift key on your keyboard, right-click your folder, and choose "Copy as Path."

!['Copy as Path' highlighted for a folder on a Windows PC.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/1-copy-folder-path-windows.jpg) 

 To [open Command Prompt](https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-oppo-a78-frp-by-drfone-android/), click the Start button, search for **command prompt**, then click the relevant result or press Enter. While making folders, if you encounter an error, [run Command Prompt as an admin](https://instagram-videos.techidaily.com/updated-2024-approved-unlocking-instagram-potential-a-comprehensible-guide/) by right-clicking the utility and choosing "Run as Administrator." Make sure to select "Yes" in the User Account Control prompt.

!['Run as Administrator' highlighted for Command Prompt in Start Menu.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-open-command-prompt-as-admin.jpg) 

 After opening Command Prompt, type **cd**, press Spacebar, paste the folder path you copied by pressing Ctrl+V, and press Enter. This [makes your chosen folder the current working directory](https://extra-information.techidaily.com/quick-and-easy-iphone-burst-techniques/) in the tool. Each command you run will perform the specified action in this directory.

!['cd' command typed in Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/3-change-current-directory-command-prompt.jpg) 

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134218/18498" target="_top" id="2134218">
  <img src="//a.impactradius-go.com/display-ad/18498-2134218" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134218/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Create a Single Folder

 To make a single folder, type the following command, replacing "FolderName" with the name you want to assign to your folder. Then, press Enter.

mkdir FolderName

 For example, to make a folder named "Mahesh", use the following command:

mkdir Mahesh

![Create a single folder from Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/4-create-single-folder-cmd.jpg) 

 To create a folder that has spaces in its name, enclose the name with double quotes like this:

mkdir “Mahesh Makvana”

##  Create a Folder Inside Another Folder (Subfolder)

 One way to make a folder inside another folder is to make that other folder the current working directory. To do that, type **cd**, press Spacebar, enter the name of the folder in which you want to create a new folder, and press Enter. Then, type the following command, replace "MyFolder" with the name you want to give to your new folder, and press Enter.

mkdir MyFolder

 Another way to create a folder inside a folder is to specify the other folder right in the mkdir command itself. For example, if you have a subfolder named "Photos" and you want to create a new folder named "Personal" inside it, use the following command:

mkdir Photos\Personal

![Create a subfolder using Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/5-create-subfolder-cmd.jpg) 

##  Create Multiple Folders at Once

 To [make several folders at once](https://phone-solutions.techidaily.com/in-2024-what-are-location-permissions-life360-on-motorola-razr-40-ultra-drfone-by-drfone-virtual-android/), add the required folder names to the mkdir command.

 For example, to create three separate folders named Documents, Photos, and Videos, use the following command:

mkdir Documents Photos Videos

![Create multiple folders with Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/6-create-multiple-folders-cmd.jpg) 

 Make sure to enclose the folder name with double quotes if its name has spaces.

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/1995803/22899" target="_top" id="1995803">
  <img src="//a.impactradius-go.com/display-ad/22899-1995803" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/1995803/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Create a File with Command Prompt

 Command Prompt allows you to create empty files, which you can then use with appropriate apps. The syntax for creating a new file is as follows:

type nul > name.ext

 Here, "name" is the name of the file you want to create and "ext" is the [extension of the file](https://twitter-videos.techidaily.com/updated-the-dos-and-donts-of-youtube-videos-on-twitter-for-2024/).

 For example, to make a text file named document.txt, you’ll use the following command:

type nul > document.txt

![Create a file with Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/7-create-file-cmd.jpg) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925549/19272" target="_top" id="1925549">
  <img src="//a.impactradius-go.com/display-ad/19272-1925549" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925549/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-sure.techidaily.com/n-2024-how-to-harness-youtubes-creative-commons-in-video-making/"><u>[New] In 2024, How to Harness YouTube's Creative Commons in Video Making</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-in-2024-the-entrepreneurs-handbook-quick-channel-creation-on-the-go-with-mobile-devices/"><u>[Updated] In 2024, The Entrepreneur's Handbook Quick Channel Creation on the Go with Mobile Devices</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-quick-acting-impression-review-for-2024/"><u>[Updated] Quick Acting Impression Review for 2024</u></a></li>
<li><a href="https://fox-ssl.techidaily.com/comment-resoudre-le-probleme-de-non-reconnaissance-du-ssd-nvme-dans-windows-11/"><u>Comment Résoudre Le Problème De Non-Reconnaissance Du SSD NVMe Dans Windows 11 ?</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-latest-drivers-for-insignia-ns-pcy5bma2-supported-by-windows-11-10-and-earlier-versions/"><u>Download Latest Drivers for Insignia NS-PCY5BMA2: Supported by Windows 11, 10 & Earlier Versions</u></a></li>
<li><a href="https://extra-hints.techidaily.com/expert-advice-for-mastering-full-screen-in-ppro/"><u>Expert Advice for Mastering Full Screen in PPro</u></a></li>
<li><a href="https://win-dash.techidaily.com/fast-and-simple-download-for-amd-ryzen-5-2600-driver-update/"><u>Fast & Simple Download for AMD Ryzen 5 2600 Driver Update</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722966149373-get-your-latest-amd-radeon-professional-w5700-drivers-for-windows-versions-update-now/"><u>Get Your Latest AMD Radeon Professional W5700 Drivers for Windows Versions - Update Now</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-swiftly-update-your-intel-iris-plus-graphics-640-software/"><u>How to Swiftly Update Your Intel Iris Plus Graphics 640 Software</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-top-15-augmented-reality-games-like-pokemon-go-to-play-on-lava-yuva-3-drfone-by-drfone-virtual-android/"><u>In 2024, Top 15 Augmented Reality Games Like Pokémon GO To Play On Lava Yuva 3 | Dr.fone</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722954112865-latest-update-released-for-logitech-extreme-3d/"><u>Latest Update Released for Logitech Extreme 3D</u></a></li>
<li><a href="https://win-solutions.techidaily.com/mastering-the-fix-overcoming-divison-2s-startup-issues/"><u>Mastering the Fix: Overcoming Divison 2'S Startup Issues</u></a></li>
<li><a href="https://win-dash.techidaily.com/quick-steps-to-download-and-update-microsoft-drivers-on-windows-11-8-or-7/"><u>Quick Steps to Download & Update Microsoft Drivers on Windows 11, 8 or 7</u></a></li>
<li><a href="https://win-dash.techidaily.com/resolving-common-errors-with-the-samsung-universal-print-driver-for-windows-users/"><u>Resolving Common Errors with the Samsung Universal Print Driver for Windows Users</u></a></li>
<li><a href="https://android-unlock.techidaily.com/rootjunky-apk-to-bypass-google-frp-lock-for-vivo-y77t-by-drfone-android/"><u>Rootjunky APK To Bypass Google FRP Lock For Vivo Y77t</u></a></li>
<li><a href="https://hardware-help.techidaily.com/secure-your-print-jobs-with-updated-brother-hl-l2350dw-printer-drivers-download-today/"><u>Secure Your Print Jobs with Updated Brother HL-L2350DW Printer Drivers - Download Today!</u></a></li>
<li><a href="https://win-dash.techidaily.com/step-by-step-guide-downloading-and-updating-razer-software-for-win-1087xpvista/"><u>Step-by-Step Guide: Downloading & Updating Razer Software for Win 10/8/7/XP/Vista</u></a></li>
<li><a href="https://win-dash.techidaily.com/steps-to-install-the-latest-version-of-intel-hd-graphics-5500-drivers/"><u>Steps to Install the Latest Version of Intel HD Graphics 5500 Drivers</u></a></li>
<li><a href="https://extra-hints.techidaily.com/unlock-audience-attention-top-6-video-styles/"><u>Unlock Audience Attention Top 6 Video Styles</u></a></li>
</ul></div>

