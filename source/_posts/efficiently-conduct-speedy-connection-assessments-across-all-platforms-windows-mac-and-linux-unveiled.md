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


