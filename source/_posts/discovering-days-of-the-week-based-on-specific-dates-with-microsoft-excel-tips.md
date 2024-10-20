---
title: Discovering Days of the Week Based on Specific Dates with Microsoft Excel Tips
date: 2024-10-17T17:10:56.025Z
updated: 2024-10-20T16:06:36.735Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/09/microsoft_excel_hero_1200x675.jpg
---

## Discovering Days of the Week Based on Specific Dates with Microsoft Excel Tips

### Quick Links

* [Ways to Find the Weekday From a Date in Excel](https://facebook-clips.techidaily.com/updated-in-2024-stream-like-a-pro-setting-up-your-dslr-on-personal-computers/)
* [Find the Day of the Week as a Number](https://youtube-videos.techidaily.com/flavor-forge-30-epicurean-titles-that-resonate/)
* [Find the Day of the Week as a Name](https://ios-unlock.techidaily.com/in-2024-3-ways-to-unlock-iphone-14-pro-max-without-passcode-or-face-id-by-drfone-ios/)
* [Convert Dates to Days of the Week](https://extra-resources.techidaily.com/mastering-360-video-making-with-ios-devices/)

 Do you have a [date in your spreadsheet](https://youtube-web.techidaily.com/ed-2024-approved-ultimate-guide-to-the-best-10-video-saving-devices/) that you want to turn into the day of the week? If so, Microsoft Excel has multiple features and functions to help you do that. We'll show you how to use them.

##  Ways to Find the Weekday From a Date in Excel

 To find the day of the week from a date, you have basically three ways. The first method is to turn your date into the day of the week in a numerical form. In this method, Sunday is displayed as number 1, Monday is number 2, and so on. This is calculated with Excel's WEEKDAY function.

 The second method displays the actual name of the day of week, like Sunday, Monday, and so on. This method uses Excel's `TEXT` function that [converts your date to the day format](https://screen-mirror.techidaily.com/how-to-screen-mirroring-samsung-galaxy-xcover-7-drfone-by-drfone-android/).

 The third method re-formats your actual dates and displays them as the names of the day of week, like Sunday, Monday, and so on. If you use this method, you do not need a separate column to display the days, as your existing date is overwritten.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094429/7443" target="_top" id="2094429">
  <img src="//a.impactradius-go.com/display-ad/7443-2094429" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094429/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Find the Day of the Week as a Number

 To find the day of the week as a number, use Excel's `WEEKDAY` function as follows. The count starts from Sunday, where it is numbered 1\. However, you can make the [function](https://win11.techidaily.com/renaissance-pc-refresh-with-atlasos/) count from any chosen day (like Monday), as we'll explain below.

 To start, first, open your spreadsheet with Microsoft Excel. In the spreadsheet, make sure you have at least one date. Then select the cell in which you want to display the day of the week.

![Select a cell in an Excel spreadsheet.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/1-select-cell-2.png) 

<!-- affiliate ads begin -->
<a href="https://jalbum-affiliate-program.sjv.io/c/5597632/1584040/17916" target="_top" id="1584040">
  <img src="//a.impactradius-go.com/display-ad/17916-1584040" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://jalbum-affiliate-program.sjv.io/i/5597632/1584040/17916" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In the selected cell, type the following `WEEKDAY` function and press Enter. In this function, replace `B2` with the cell where you have your date.

=WEEKDAY(B2)

![Enter the WEEKDAY function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/2-enter-weekday-function.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012401/19272" target="_top" id="2012401">
  <img src="//a.impactradius-go.com/display-ad/19272-2012401" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012401/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you'd like to use the date directly in the function, type the following `WEEKDAY` function with your date in it and press Enter. Keep double quotes around your date.

=WEEKDAY("24/5/2021")

![Enter the WEEKDAY function with direct values.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/3-direct-values-weekday-function.png) 

 And in the selected cell, you will see the day of the week for your date as a number.

![The result of the WEEKDAY function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/4-weekday-function-result.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037356/7443" target="_top" id="2037356">
  <img src="//a.impactradius-go.com/display-ad/7443-2037356" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037356/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To make the function count days so that Monday is number 1, modify the function as follows. The number `2` in the function argument tells it to start counting from Monday.

=WEEKDAY(B2,2)

![Type the custom WEEKDAY function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/5-custom-weekday-function.png) 

 Here's how your result now looks like:

![The result of the custom WEEKDAY function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/6-custom-weekday-function-result.png) 

 To copy the function to other cells, [drag downwards](https://visual-screen-recording.techidaily.com/new-in-2024-top-5-best-hdmi-21-gaming-monitors-ps5-compatible/) from the bottom-right corner of the cell where you typed the function.

![Copy the WEEKDAY function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/7-copy-weekday-function.png) 

Related: [How to Sort by Date in Microsoft Excel](https://screen-sharing-recording.techidaily.com/updated-2024-approved-economical-pc-playback-devices/) 

##  Find the Day of the Week as a Name

 To display a date's day of the week as the day name, like Monday, use Excel's `TEXT` function. In this function, you tell Excel to [format your date](https://video-capture.techidaily.com/new-from-playback-to-printout-top-five-methods-of-documenting-minecraft-on-a-mac-for-2024/) in the day format. You can choose the shortened day name (like Mon) or full day name (like Monday).

 Start by opening your spreadsheet with Microsoft Excel. Then select the cell in which you want to display the day of week.

![Click a cell in an Excel spreadsheet.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/8-choose-cell.png) 

 In the selected cell, type the following `TEXT` function and press Enter. In this function, replace `B2` with the cell where your date is.

=TEXT(B2,"dddd")

![Enter the TEXT function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/9-enter-text-function.png) 

 The selected cell will display the day of the week. If you'd prefer a shortened day name, like "Mon" for Monday, remove one `d` from the function argument as follows:

=TEXT(B2,"ddd")

![Type the custom TEXT function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/10-custom-text-function.png) 

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1006793/11832" target="_top" id="1006793">
  <img src="//a.impactradius-go.com/display-ad/11832-1006793" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1006793/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 And you now have the shortened day name in your selected cell.

![The result of the custom TEXT function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/11-text-function-result.png) 

 Depending on how you like to style your sheets, you may want to [format your dates using periods in Excel](https://youtube-videos.techidaily.com/diy-delights-in-motion-personalized-animation-artistry-for-2024/).

##  Convert Dates to Days of the Week

 To convert your dates to days of weeks without [using a separate column](https://tiktok-clips.techidaily.com/2024-approved-speeding-up-tiktok-videos-made-simple/), use Excel's custom number format. This displays the day of week by its full or shortened name.

 To do so, first, open your spreadsheet with Microsoft Excel. Then select the cells containing dates.

![Select the date cells.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/12-select-dates.png) 

 In [Excel's ribbon at the top](https://screen-mirror.techidaily.com/in-2024-how-to-mirror-honor-play-40c-to-mac-drfone-by-drfone-android/), click the "Home" tab.

![Click the "Home" tab in Excel.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/13-excel-home-tab.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135365/19272" target="_top" id="2135365">
  <img src="//a.impactradius-go.com/display-ad/19272-2135365" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135365/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In the "Home" tab, from the "Number" section, select "Number Format" (an arrow icon).

![Select &quot;Number Format&quot; in the &quot;Home&quot; tab.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/14-excel-number-format.png) 

<!-- affiliate ads begin -->
<span id="1938136">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1938136.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1938136">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1938136.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1938136%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1938136/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 A "Format Cells" window will open. On this window, from the "Category" list on the left, select "Custom."

![Select &quot;Custom&quot; on the &quot;Format Cells&quot; window.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/15-custom-number-format.png) 

 On the right, click the "Type" box and enter "dddd" (without quotes) for full day names (like Monday) or "ddd" for shortened day names (like Mon). Then, at the bottom, click "OK."

![Specify the date format.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/16-enter-number-format.png) 

 Excel will turn your selected dates into days of the week.

![Dates turned into days of week.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/17-number-format-result.png) 

 And that's how you know what day it was on a specific date in Microsoft Excel. Very useful!

---

 Did you know you can use Excel to [calculate someone's age](https://youtube-data.techidaily.com/n-2024-explore-the-best-historian-content-top-10-youtube-recommendations/), too? It's equally easy to do that.

Related: [How to Calculate Age in Microsoft Excel](https://youtube-data.techidaily.com/n-2024-explore-the-best-historian-content-top-10-youtube-recommendations/)

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
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-guide-to-saving-instagram-videos-with-maximum-convenience/"><u>[New] In 2024, Guide to Saving Instagram Videos with Maximum Convenience</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-2024-approved-equipment-guide-for-dynamic-documentary-making/"><u>[Updated] 2024 Approved Equipment Guide for Dynamic Documentary Making</u></a></li>
<li><a href="https://win-dash.techidaily.com/access-new-and-updated-finger-printer-driver-software-for-windows-download-here/"><u>Access New and Updated Finger Printer Driver Software for Windows - Download Here!</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/ambient-weather-ws-2902a-osprey-review/"><u>Ambient Weather WS-2902A Osprey Review</u></a></li>
<li><a href="https://some-guidance.techidaily.com/asf-mp4-asf-mpg/"><u>ASF 파일에서 MP4로의 제공: 가상화, 영화 및 사운드 크리티비저 원활한 이동 - 무료 온라인 ASF MPG 변환기</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breathe-life-into-your-old-videos-using-madvr-in-the-windows-sphere/"><u>Breathe Life Into Your Old Videos: Using MadVR in the Windows Sphere</u></a></li>
<li><a href="https://technical-tips.techidaily.com/discover-these-16-great-resources-for-free-asl-practice-and-study/"><u>Discover These 16 Great Resources for FREE ASL Practice & Study</u></a></li>
<li><a href="https://win-dash.techidaily.com/easy-way-to-get-toshiba-printer-drivers-set-up-in-windows-os/"><u>Easy Way to Get Toshiba Printer Drivers Set Up in Windows OS</u></a></li>
<li><a href="https://win-dash.techidaily.com/free-sm-bus-controller-software-compatible-with-windows-11-10-8-and-7/"><u>Free SM Bus Controller Software: Compatible with Windows 11, 10, 8 & 7</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-best-sound-experience-steelseries-arctis-5-driver-guide-and-download/"><u>Get the Best Sound Experience: SteelSeries Arctis 5 Driver Guide and Download</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-get-brother-hl-2280dw-printer-software-on-your-pc-with-windows-11-10-8-or-7/"><u>How to Get Brother HL 2280DW Printer Software on Your PC with Windows 11, 10, 8 or 7</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-get-the-latest-amd-blockchain-driver-for-your-pc-step-by-step-instructions/"><u>How to Get the Latest AMD Blockchain Driver for Your PC: Step-by-Step Instructions</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-unleash-creativity-masterful-techniques-for-editing-podcasts-in-garageband/"><u>In 2024, Unleash Creativity Masterful Techniques for Editing Podcasts in GarageBand</u></a></li>
<li><a href="https://win-dash.techidaily.com/step-by-step-guide-installing-your-beats-audio-drivers/"><u>Step-by-Step Guide: Installing Your Beats Audio Drivers</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/time-saving-titans-the-8-cutting-edge-schedulers-reviewed-for-2024/"><u>Time-Saving Titans The 8 Cutting-Edge Schedulers Reviewed for 2024</u></a></li>
<li><a href="https://win-dash.techidaily.com/ultimate-guide-to-finding-and-downloading-epson-wf-7710-printer-drivers-for-windows-10-8x-and-earlier-versions/"><u>Ultimate Guide to Finding & Downloading Epson WF-7710 Printer Drivers for Windows 10, 8.x & Earlier Versions</u></a></li>
<li><a href="https://extra-tips.techidaily.com/unlocking-visual-treasures-without-cost/"><u>Unlocking Visual Treasures Without Cost</u></a></li>
</ul></div>

