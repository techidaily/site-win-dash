---
title: Efficiently Conduct Speedy Connection Assessments Across All Platforms - Windows, Mac, and Linux Unveiled
date: 2024-10-19T16:50:38.488Z
updated: 2024-10-20T18:22:10.209Z
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
<a href="https://imp.i357552.net/c/5597632/999558/11832" target="_top" id="999558">
  <img src="//a.impactradius-go.com/display-ad/11832-999558" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/999558/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Run a Speed Test on Windows via Command Prompt

 Installing the speed test CLI on a Windows PC is straightforward. Start by visiting the [Speedtest CLI download page](https://www.speedtest.net/apps/cli). Scroll down to find the download option for Windows. It's important to note that the CLI tool is only available for 64-bit versions of Windows.

![Downloading Speedtest CLI on Windows](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/downloading-speedtest-cli-for-windows-2.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2111995/7443" target="_top" id="2111995">
  <img src="//a.impactradius-go.com/display-ad/7443-2111995" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111995/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 After downloading the installer, unzip the file to find "speedtest.exe." It's a good idea to place this file in a directory like C:\\Program Files\\speedtest.exe as this location is both easy to remember and accessible by all user accounts on your system. For added convenience, consider creating a desktop shortcut or pinning the executable to your taskbar.

 To run the speed test in Command Prompt (hit Start, type "command" and click "Command Prompt" when it appears), all you need to do is type the full path to the executable, encased in quotation marks to prevent conflicts arising from spaces, and hit enter:

        `"C:\Program Files\speedtest.exe"`
    
 To run in [PowerShell (Terminal)](https://techtrends.techidaily.com/what-are-the-stages-in-a-game-of-royal-match/), the syntax is slightly modified. You must prepend an ampersand to run the executable at the given file path, like so:

        `& "C:\Program Files\speedtest.exe"`
    
![Running Speedtest CLI in PowerShell](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/running-speedtest-cli-in-powershell.png) 

 These commands will run the application via the command line, providing you with a quick readout of your current internet speed and related parameters.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2027190/19272" target="_top" id="2027190">
  <img src="//a.impactradius-go.com/display-ad/19272-2027190" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2027190/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1938698/19272" target="_top" id="1938698">
  <img src="//a.impactradius-go.com/display-ad/19272-1938698" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938698/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://vimeo-videos.techidaily.com/new-direct-download-process-from-vimeo-to-mp3-format/"><u>[New] Direct Download Process From Vimeo to MP3 Format</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-strategies-for-maximizing-your-twitter-archive/"><u>2024 Approved Strategies for Maximizing Your Twitter Archive</u></a></li>
<li><a href="https://buynow-info.techidaily.com/antonis-at-127-antenna-review-experience-unparalleled-television-viewing-with-our-sleek-free-digital-broadcast-receiver/"><u>ANTONIS At-127 Antenna Review: Experience Unparalleled Television Viewing With Our Sleek, Free Digital Broadcast Receiver!</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722964853135-download-magicard-rio-pro-driver-now-compatible-with-windows-11817-get-the-new-version/"><u>Download Magicard Rio Pro Driver Now: Compatible with Windows 11/8.1/7 - Get the New Version!</u></a></li>
<li><a href="https://win-dash.techidaily.com/effortless-audio-driver-update-for-your-hp-devices-free-and-fast-download-options/"><u>Effortless Audio Driver Update for Your HP Devices - Free and Fast Download Options!</u></a></li>
<li><a href="https://win-dash.techidaily.com/enhance-your-pcs-webcam-functionality-with-updated-drivers-for-windows-systems/"><u>Enhance Your PC's Webcam Functionality with Updated Drivers for Windows Systems</u></a></li>
<li><a href="https://win-dash.techidaily.com/ensure-your-logitech-t6-mouse-functions-smoothly-downloading-drivers-for-windows-7810/"><u>Ensure Your Logitech T6# Mouse Functions Smoothly – Downloading Drivers for Windows 7/8/10</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-install-iphone-compatible-drivers-on-windows-11-systems/"><u>How to Install iPhone Compatible Drivers on Windows 11 Systems</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-lava-yuva-3-pro-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>How to Track Lava Yuva 3 Pro Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-bypassing-google-account-with-vnrom-bypass-for-poco-m6-pro-5g-by-drfone-android/"><u>In 2024, Bypassing Google Account With vnROM Bypass For Poco M6 Pro 5G</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-unleash-youtube-potential-best-mp4-editors-on-mac/"><u>In 2024, Unleash YouTube Potential Best MP4 Editors on Mac</u></a></li>
<li><a href="https://extra-information.techidaily.com/rapid-fire-creation-of-google-collage-photos/"><u>Rapid-Fire Creation of Google Collage Photos</u></a></li>
<li><a href="https://win-dash.techidaily.com/solving-connectivity-woes-the-ultimate-solution-for-windows/"><u>Solving Connectivity Woes: The Ultimate Solution for Windows</u></a></li>
<li><a href="https://win-dash.techidaily.com/speedy-setup-for-razer-mamba-free-driver-software-here/"><u>Speedy Setup for Razer Mamba - Free Driver Software Here</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-beyond-gopro-studio-top-picks-for-editing-your-adventure-videos-for-2024/"><u>Updated Beyond GoPro Studio Top Picks for Editing Your Adventure Videos for 2024</u></a></li>
</ul></div>

