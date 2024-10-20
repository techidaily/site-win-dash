---
title: "Step-by-Step Guide: How to Count Cell Contents with Text in MS Excel"
date: 2024-10-19T17:14:45.811Z
updated: 2024-10-20T16:42:24.964Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/3f22ae9e837b10e05053cf12480b5c15e8d166c20b49b11db4fda3e3ee1b2757.jpg
---

## Step-by-Step Guide: How to Count Cell Contents with Text in MS Excel

### Quick Links

* [Count Cells With Any Text in Excel](https://some-approaches.techidaily.com/2024-approved-the-uav-connoisseurs-guide-to-essential-equipment/)
* [Count Cells With Specific Text in Excel](https://facebook-record-videos.techidaily.com/updated-2024-approved-discover-engaging-youtube-threads/)

 Do you want to [count the number of cells](https://howto.techidaily.com/fix-the-error-of-unfortunately-the-processcomandroidphone-has-stopped-on-vivo-v29-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/) that contain any or specific text while ignoring all other cells? If so, Microsoft Excel has a dedicated function to help you do that. We'll show you how to use it.

 In Excel, you can [use the COUNTIF function](https://win-forum.techidaily.com/complete-tutorial-clearing-out-windows-10-memory-dump-data/) to count either cells containing any text or cells containing specific text. Use the method below that works for your specific situation.

##  Count Cells With Any Text in Excel

 To count the number of cells that contain any text, but ignore any numbers, blank cells, and [errors](https://ios-unlock.techidaily.com/in-2024-iphone-12-pro-asking-for-passcode-after-ios-1714-update-what-to-do-by-drfone-ios/), use the method here.

 First, open your spreadsheet with Microsoft Excel. In the spreadsheet, select the cell in which you want to display the result.

![Select a cell in an Excel spreadsheet.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/1-select-cell-3.png) 

 In the selected cell, type the following `COUNTIF` function and press Enter. Make sure to replace `D2` and `D6` in this function with the range where your cells to be counted are.

=COUNTIF(D2:D6,"*")

 Here, the \* (asterisk) argument tells the function to only count cells containing text.

![Enter the COUNTIF function to count all text cells.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/2-countif-count-text-cells.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118311/7443" target="_top" id="2118311">
  <img src="//a.impactradius-go.com/display-ad/7443-2118311" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118311/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can also count the cells that contain anything but text. To do so, use the following modified version of the `COUNTIF` function. In this function, the argument specifies that only the non-text cells should be counted.

 If a cell has a mix of both text and numbers, it won't be counted.

=COUNTIF(D2:D6,"<>*")

![Enter the COUNTIF function to count all non-text cells.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/3-countif-count-non-text-cells.png) 

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/857865/11832" target="_top" id="857865">
  <img src="//a.impactradius-go.com/display-ad/11832-857865" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/857865/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 This is the result you will see when you use the COUNTIF function to count the number of cells containing any text.

![The number of cells containing any text.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/4-countif-result.png) 

Related: [How to Highlight Blanks or Errors in Microsoft Excel](https://ios-unlock.techidaily.com/in-2024-iphone-12-pro-asking-for-passcode-after-ios-1714-update-what-to-do-by-drfone-ios/) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997630/19272" target="_top" id="1997630">
  <img src="//a.impactradius-go.com/display-ad/19272-1997630" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997630/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Count Cells With Specific Text in Excel

 To make Excel only count the cells that contain specific text, use an argument with the `COUNTIF` function.

 First, in your spreadsheet, select the cell in which you want to display the result.

![Select a cell in an Excel spreadsheet.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/1-select-cell-3.png) 

 In the selected cell, type the following `COUNTIF` function and press Enter. In the function, replace `D2` and `D6` with the [range](https://video-screen-grab.techidaily.com/updated-playful-pioneers-the-kids-game-bazaar-for-2024/) where your cells are. Also, replace `a` with any character or word that your cell should have for it to be counted.

 The below function counts all cells that contain the letter `a`. This means, in our example, it will count both `Mahesh` and `David` as both these names have the letter `a` in them.

=COUNTIF(D2:D6,"*a*")

![Enter the COUNTIF function to count cells containing specific text.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/5-countif-count-specific-text-cells.png) 

 Here's the result:

![The number of cells containing specific text.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/6-countif-specific-text-result.png) 

 To make the function count those cells that only have your specified character or word in them, remove the \* (asterisk) sign from before and after your character or word, as follows.

=COUNTIF(D2:D6,"a")

![Enter the COUNTIF function to count cells only containing specific text.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/7-countif-count-only-specific-text-cells.png) 

 In our example, the count result is `0` because there are no cells that only contain the character `a` in them.

![The number of cells containing only specific text.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/8-countif-only-specific-text-cell-result.png) 

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123508/26400" target="_top" id="2123508">
  <img src="//a.impactradius-go.com/display-ad/26400-2123508" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123508/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 And that's how you specify what cells to consider for calculation in your Microsoft Excel spreadsheets. Very useful!

---

 Did you know Excel can also [count blank or empty cells](https://fox-blue.techidaily.com/2024-approved-revel-in-richness-your-pcs-pathway-to-exceptional-video-quality/) in your spreadsheets? Check that out if you're interested.

Related: [How to Add Text to a Cell With a Formula in Excel](https://buynow-reviews.techidaily.com/a-comprehensive-review-top-long-reach-routers-dominating-the-market-in-ebytes/)

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
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-elite-selections-8-incredible-tools-to-elevate-your-4k-video/"><u>[New] 2024 Approved Elite Selections 8 Incredible Tools to Elevate Your 4K Video</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-experience-the-joy-sorrow-merge-with-these-ten-meme-ig-accounts-for-2024/"><u>[New] Experience the Joy-Sorrow Merge with These Ten Meme IG Accounts for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-top-youtube-hashtag-strategies-for-boosting-your-contents-visibility/"><u>[Updated] Top Youtube Hashtag Strategies for Boosting Your Content's Visibility</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-tecno-spark-20-drfone-by-drfone-virtual-android/"><u>15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Tecno Spark 20 | Dr.fone</u></a></li>
<li><a href="https://win-dash.techidaily.com/arduino-uno-software-fix-correcting-driver-errors-on-windows-machines/"><u>Arduino Uno Software Fix: Correcting Driver Errors on Windows Machines</u></a></li>
<li><a href="https://tech-hub.techidaily.com/chatbot-showdown-determining-the-top-contender-between-google-bard-and-bing-chat/"><u>Chatbot Showdown: Determining the Top Contender Between Google Bard and Bing Chat</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722975622535-download-logitech-drivers-fast-compatible-with-windows-systems/"><u>Download Logitech Drivers Fast: Compatible with Windows Systems!</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-updated-nvidia-geforce-rtx-2070-drivers-compatible-with-windows-11107/"><u>Download Updated NVIDIA GeForce RTX 2070 Drivers: Compatible with Windows 11/10/7</u></a></li>
<li><a href="https://win-dash.techidaily.com/easy-update-canon-mx492-printer-drivers-for-windows-operating-systems-step-by-step-tutorial/"><u>Easy Update: Canon MX492 Printer Drivers for Windows Operating Systems - Step-by-Step Tutorial</u></a></li>
<li><a href="https://win-dash.techidaily.com/enhance-canon-imageclass-mf-s1340dwmf-lide-secure-the-latest-driver-download-and-update/"><u>Enhance Canon ImageCLASS MF S1340dw/Mf (LiDE) - Secure the Latest Driver Download and Update</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-newest-rtx-nv-rdlc43157-full-drivers-for-your-pc-running-on-windows-11-download-and-update/"><u>Get the Newest RTX Nv-RDLC_431.57 Full Drivers for Your PC Running on Windows 11 (Download & Update)</u></a></li>
<li><a href="https://techidaily.com/how-to-exit-dfu-mode-on-apple-iphone-15-pro-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Exit DFU Mode on Apple iPhone 15 Pro? | Dr.fone</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-install-insignia-ns-pcy5bma2-driver-compatible-with-windows-1117-users/"><u>How to Install Insignia NS-PCY5BMA2 Driver: Compatible with Windows 11/1#/#7 Users</u></a></li>
<li><a href="https://fox-glue.techidaily.com/in-2024-the-most-popular-stock-photo-meme-and-their-stories/"><u>In 2024, The Most Popular Stock Photo Meme and Their Stories</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/plotting-your-way-through-successful-instagram-video-marketing/"><u>Plotting Your Way Through Successful Instagram Video Marketing</u></a></li>
</ul></div>

