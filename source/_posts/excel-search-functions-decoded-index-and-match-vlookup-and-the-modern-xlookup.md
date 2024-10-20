---
title: "Excel Search Functions Decoded: INDEX & MATCH, VLOOKUP, and the Modern XLOOKUP"
date: 2024-10-17T17:34:05.203Z
updated: 2024-10-20T16:05:05.075Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/4be59755ae7994bb626513b3614a3ec947be3b56430323187fb64d462d24a601.jpg
---

## Excel Search Functions Decoded: INDEX & MATCH, VLOOKUP, and the Modern XLOOKUP

### Quick Links

* [Using INDEX and MATCH](https://android-transfer.techidaily.com/in-2024-5-ways-to-transfer-music-from-samsung-galaxy-z-flip-5-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/)
* [Using VLOOKUP](https://fox-blue.techidaily.com/2024-approved-top-10-jpg-to-gif-converters-online-free/)
* [Using XLOOKUP](https://on-screen-recording.techidaily.com/new-2024-approved-streamline-your-zoom-meetings-screen-sharing-essentials/)
* [Which Is Better?](https://extra-guidance.techidaily.com/updated-quick-fix-techniques-for-social-media-collaborative-art/)

 Lookup [functions in Microsoft Excel](https://vimeo-videos.techidaily.com/in-2024-high-end-downloads-best-10-apps-for-extracting-vimeo-videos/) are ideal for finding what you need when you have a large amount of data. There are three common ways to do this; INDEX and MATCH, VLOOKUP, and XLOOKUP. But what's the difference?

 INDEX and MATCH, VLOOKUP, and XLOOKUP each serve the purpose of looking up data and returning a result. They each work a bit differently and require a specific syntax for the formula. When should you use which? Which is better? Let's take a look so you know the best option for you.

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1001453/11832" target="_top" id="1001453">
  <img src="//a.impactradius-go.com/display-ad/11832-1001453" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1001453/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Using INDEX and MATCH

 Obviously, the INDEX and MATCH combination is a mixture of the two named functions. You can take a look at our how-tos for the [INDEX function](https://youtube-help.techidaily.com/in-2024-the-full-course-on-becoming-a-yt-creator-expert/) and [MATCH function](https://extra-guidance.techidaily.com/mirthful-missions-delving-into-the-goofy-movie-vhs-for-2024/) for specific details on using them individually.

 To use this duo, the syntax for each is 

        `INDEX(array, row_number, column_number)`
    
 and 

        `MATCH(value, array, match_type)`
    
 .

 When you combine the two, you'll have a syntax like this: 

        `INDEX(return_array, MATCH(lookup_value, lookup_array))`
    
 in its most basic form. It's easiest to look at some examples.

 To find a value in cell G2 in the range A2 through A8 and provide the matching result in the range B2 through B8, you would use this formula:

=INDEX(B2:B8,MATCH(G2,A2:A8))

![INDEX and MATCH with a cell reference](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/04/IndexMatchCell-ExcelLookupFunctions.png) 

 If you prefer to insert the value you want to find instead of using the cell reference, the formula looks like this where 2B is the lookup value:

=INDEX(B2:B8,MATCH("2B",A2:A8))

 Our result is Houston for both formulas.

![INDEX and MATCH with a value](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/04/IndexMatchValue-ExcelLookupFunctions.png) 

 We also have a tutorial that goes into detail on [using INDEX and MATCH](https://os-tips.techidaily.com/reviving-ipad-connectivity-essential-steps-for-reactivating-the-usb-driver/) should that be your choice.

Related: [How to Use INDEX and MATCH in Microsoft Excel](https://os-tips.techidaily.com/reviving-ipad-connectivity-essential-steps-for-reactivating-the-usb-driver/) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2044583/7443" target="_top" id="2044583">
  <img src="//a.impactradius-go.com/display-ad/7443-2044583" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2044583/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Using VLOOKUP

 VLOOKUP has been a popular reference function in Excel for some time. The V stands for Vertical, so with VLOOKUP, you're doing a vertical lookup and it's from left to right.

 The syntax is `VLOOKUP(lookup_value, lookup_array, column_number, range_lookup)` with the last argument optional as True (approximate match) or False (exact match).

 Using the same data as that for INDEX and MATCH, we'll look up the value in cell G2 in the range A2 through D8 and return the value in the second column that matches. You'd use this formula:

=VLOOKUP(G2,A2:D8,2)

![VLOOKUP with a cell reference](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/04/VLOOKUPCell-ExcelLookupFunctions.png) 

 As you can see, the result using VLOOKUP is the same as using INDEX and MATCH, Houston. The difference is that VLOOKUP uses a much simpler formula. For more [details on VLOOKUP](https://win-able.techidaily.com/1723001670706-troubleshooting-genshin-impact-fix-stability-issues-and-stop-pc-crashes/), check out our how-to.

Related: [How to Use VLOOKUP on a Range of Values](https://win-able.techidaily.com/1723001670706-troubleshooting-genshin-impact-fix-stability-issues-and-stop-pc-crashes/) 

 So why would anyone use INDEX and MATCH instead of VLOOKUP? The answer is because VLOOKUP only works when your lookup value is to the left of the return value you want.

 If we did the reverse and wanted to look up a value in the fourth column and return the matching value in the second column, we would not receive the result we want and may even receive an error. As Microsoft [writes](https://support.microsoft.com/en-us/office/vlookup-function-0bbc8083-26fe-4963-8ab8-93a18ad188a1):

> Remember that the lookup value should always be in the first column in the range for VLOOKUP to work correctly. For example, if your lookup value is in cell C2 then your range should start with C.

 INDEX and MATCH covers the entire cell range or array making it a more robust lookup option even if the formula is a bit more complicated.

##  Using XLOOKUP

 XLOOKUP is a reference function that arrived in Excel after VLOOKUP and the counterpart HLOOKUP (horizontal lookup). The difference between XLOOKUP and VLOOKUP is that XLOOKUP works no matter where the lookup and return values reside in your cell range or array.

 The syntax is `XLOOKUP(lookup_value, lookup_array, return_array, not_found, match_mode, search_mode)`. The first three arguments are required and are similar to that in the VLOOKUP function. XLOOKUP offers three optional arguments at the end for giving a text result if the value isn't found, a mode for the type of match, and a mode for how to perform the search.

 For the purpose of this article, we'll concentrate on the first three required arguments.

 Back to our cell range from earlier, we'll look up the value in G2 in the range A2 through A8 and return the matching value from the range B2 through B8 with this formula:

=XLOOKUP(G2,A2:A8,B2:B8)

![XLOOKUP with a cell reference](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/04/XLOOKUPCell-ExcelLookupFunctions.png) 

 And like with INDEX and MATCH as well as VLOOKUP, our formula returned Houston.

 We can also use a value in the fourth column as the lookup value and receive the correct result in the second column:

=XLOOKUP(20745,D2:D8,B2:B8)

![XLOOKUP from right to left](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/04/GoodXLOOKUP-ExcelLookupFunctions.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1896505/19272" target="_top" id="1896505">
  <img src="//a.impactradius-go.com/display-ad/19272-1896505" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896505/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 With this in mind, you can see that XLOOKUP is a better option than VLOOKUP simply because you can arrange your data any way you like and still receive your desired result. For a full [tutorial on XLOOKUP](https://android-transfer.techidaily.com/in-2024-5-ways-to-transfer-music-from-asus-rog-phone-7-ultimate-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/), head over to our how-to.

Related: [How to Use the XLOOKUP Function in Microsoft Excel](https://android-transfer.techidaily.com/in-2024-5-ways-to-transfer-music-from-asus-rog-phone-7-ultimate-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/) 

 So now you're wondering, should I use XLOOKUP or INDEX and MATCH, right? Here are some things to consider.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137226/26400" target="_top" id="2137226">
  <img src="//a.impactradius-go.com/display-ad/26400-2137226" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137226/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Which Is Better?

 If you already use the INDEX and MATCH functions separately and have used them together to lookup values, then you may be more familiar with how they work. By all means, if it's not broken, don't fix it, and keep using what makes you comfortable.

 And of course, if your data is structured to work with VLOOKUP and you've used that function for years, you can continue using it or make the easy transition to XLOOKUP leaving INDEX and MATCH in the dust.

 If you want to a simple, easy-to-build formula in any direction, XLOOKUP is the way to go and can replace INDEX and MATCH. You don't have to worry about combining arguments from two functions into one or rearranging your data.

 One last consideration, [XLOOKUP does offer those three optional arguments](https://support.microsoft.com/en-us/office/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929) which may come in handy for your needs.

 Over to you! Which lookup option will you use in Microsoft Excel? Or maybe, you'll use all three depending on your needs? No matter what, it's nice to have options!

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
<li><a href="https://win-dash.techidaily.com/1722977594115-free-elevate-your-gameplay-with-official-corsair-mouse-software-install-now/"><u>[Free] Elevate Your Gameplay with Official Corsair Mouse Software - Install Now</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-step-up-your-game-techniques-for-bordered-instagram-videos/"><u>[New] 2024 Approved Step Up Your Game Techniques for Bordered Instagram Videos</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-rapid-runners-prime-fastest-titles-for-pc-mobile-devices/"><u>[New] Rapid Runners Prime Fastest Titles for PC, Mobile Devices</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-boosting-facebook-video-performance/"><u>[Updated] Boosting Facebook Video Performance</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-the-angle-artistry-guide-mastering-the-craft-of-video-spinning-on-social-sites/"><u>[Updated] In 2024, The Angle Artistry Guide Mastering the Craft of Video Spinning on Social Sites</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-mastering-youtube-channel-lockdowns-device-specific-tips-for-2024/"><u>[Updated] Mastering YouTube Channel Lockdowns Device-Specific Tips for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-tunetrekker-venturing-past-dacast/"><u>2024 Approved TuneTrekker Venturing Past DaCast</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-unblemished-visuals-buying-high-quality-images/"><u>2024 Approved Unblemished Visuals Buying High-Quality Images</u></a></li>
<li><a href="https://win-dash.techidaily.com/easy-installation-of-epson-wf-2540-printers-on-your-laptopdesktop-with-win7-81-and-10/"><u>Easy Installation of Epson WF 2540 Printers on Your Laptop/Desktop with Win7, 8.1 & 10</u></a></li>
<li><a href="https://win-dash.techidaily.com/easy-installation-of-intel-cpu-drivers-quick-guide-for-users/"><u>Easy Installation of Intel CPU Drivers – Quick Guide for Users</u></a></li>
<li><a href="https://win-dash.techidaily.com/experience-smooth-graphics-on-any-device-download-the-new-nvidia-gtx-980-ti-driver-software-now/"><u>Experience Smooth Graphics on Any Device – Download The New NVIDIA GTX 980 Ti Driver Software Now!</u></a></li>
<li><a href="https://win-dash.techidaily.com/free-hp-audio-driver-downloads-effortless-step-by-step-install-guide/"><u>Free HP Audio Driver Downloads | Effortless, Step-by-Step Install Guide</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-updated-ch340-g-chip-drivers-compatible-with-windows-10-systems/"><u>Get Updated CH3#40 G Chip Drivers - Compatible with Windows 10 Systems</u></a></li>
<li><a href="https://win-dash.techidaily.com/install-logitechs-elite-racing-wheel-software-on-your-computer-compatible-with-windows-7-10-and-11/"><u>Install Logitech's Elite Racing Wheel Software on Your Computer – Compatible with Windows 7, 10 & 11</u></a></li>
<li><a href="https://win-dash.techidaily.com/install-the-most-recent-driver-update-for-your-epson-l3150-a-step-by-step-guide-for-win11-8-and-7-users/"><u>Install the Most Recent Driver Update for Your Epson L3150: A Step-by-Step Guide for Win11, 8 & 7 Users</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722971930819-latest-geforce-rtx-3090-graphics-card-driver-for-win-11-8-and-7-get-it-now/"><u>Latest GeForce RTX 3090 Graphics Card Driver for Win 11, 8 & 7 – Get It Now</u></a></li>
<li><a href="https://some-guidance.techidaily.com/progetto-completo-guida-pratica-per-linstallazione-e-la-configurazione-di-windows-dvd/"><u>Progetto Completo: Guida Pratica per L'installazione E La Configurazione Di Windows DVD</u></a></li>
<li><a href="https://fox-that.techidaily.com/reclaim-your-forgotten-words-methods-for-getting-back-accidentally-erased-iphone-notes/"><u>Reclaim Your Forgotten Words: Methods for Getting Back Accidentally Erased iPhone Notes</u></a></li>
<li><a href="https://technical-tips.techidaily.com/troubleshooting-the-msstdfmtdll-missing-error-on-your-computer/"><u>Troubleshooting The Msstdfmt.dll Missing Error on Your Computer</u></a></li>
</ul></div>

