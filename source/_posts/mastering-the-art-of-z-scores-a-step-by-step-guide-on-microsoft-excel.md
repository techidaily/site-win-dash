---
title: "Mastering the Art of Z-Scores: A Step-by-Step Guide on Microsoft Excel"
date: 2024-08-28T01:33:39.733Z
updated: 2024-08-29T01:33:39.733Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/102ab1b6aae4e1817df5a3836c10cfedb2eea5b3cb906b121a8d1c61752ad28b.jpg
---

## Mastering the Art of Z-Scores: A Step-by-Step Guide on Microsoft Excel

### Quick Links

* [What is a Z-Score and what do the AVERAGE, STDEV.S, and STDEV.P functions do?](https://youtube-data.techidaily.com/ed-crafting-engaging-youtube-video-layouts-for-2024/)
* [Let's Look at an Example](https://youtube-lab.techidaily.com/ed-scriptwriting-mastery-elevate-your-youtube-channels-content-quality/)
* [Calculating the Z-Score without using 'Helper' Cells](https://android-pokemon-go.techidaily.com/in-2024-how-to-use-pokemon-emerald-master-ball-cheat-on-motorola-moto-g24-drfone-by-drfone-virtual-android/)

 A Z-Score is a statistical value that tells you how many standard deviations a particular value happens to be from the mean of the entire data set. You can use AVERAGE and STDEV.S or STDEV.P formulas to calculate the mean and standard deviation of your data and then use those results to determine the Z-Score of each value.

##  What is a Z-Score and what do the AVERAGE, STDEV.S, and STDEV.P functions do?

 A Z-Score is a simple way of comparing values from two different data sets. It is defined as the number of standard deviations away from the mean a data point lies. The general formula looks like this:

=(DataPoint-AVERAGE(DataSet))/STDEV(DataSet)

 Here's an example to help clarify. Say you wanted to compare the test results of two Algebra students taught by different teachers. You know the first student got a 95% on the final exam in one class, and the student in the other class scored 87%.

 At first glance, the 95% grade is more impressive, but what if the teacher of the second class gave a more difficult exam? You could calculate the Z-Score of each student's score based on the average scores in each class and the standard deviation of the scores in each class. Comparing the Z-Scores of the two students could reveal that the student with the 87% score did better in comparison to the rest of their class than the student with the 98% score did in comparison to the rest of their class.

 The first statistical value you need is the 'mean' and Excel's "AVERAGE" function calculates that value. It simply adds up all of the values in a cell range and divides that sum by the number of cells containing numerical values (it ignores blank cells).

 The other statistical value we need is the 'standard deviation' and Excel has two different functions to calculate the standard deviation in slightly different ways.

 Previous versions of Excel only had the "STDEV" function, which calculates the standard deviation while treating the data as a 'sample' of a population. Excel 2010 broke that into two functions that calculate the standard deviation:

* **STDEV.S:** This function is identical to the previous "STDEV" function. It calculates the standard deviation while treating the data as a 'sample' of a population. A sample of a population might be something like the particular mosquitoes collected for a research project or cars that were set aside and used for crash safety testing.
* **STDEV.P:** This function calculates the standard deviation while treating the data as the entire population. An entire population would be something like all mosquitoes on Earth or every car in a production run of a specific model.

 Which you choose is based on your data set. The difference will usually be small, but the result of the "STDEV.P" function will always be smaller than the result of the "STDEV.S" function for the same data set. It is a more conservative approach to assume there is more variability in the data.

##  Let's Look at an Example

 For our example, we have two columns ("Values" and "Z-Score")and three "helper" cells for storing the results of the "AVERAGE," "STDEV.S," and "STDEV.P" functions. The "Values" column contains ten random numbers centered around 500, and the "Z-Score" column is where we will calculate the Z-Score using the results stored in the 'helper' cells.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Z-Score-01.png) 

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
 First, we will calculate the mean of the values using the "AVERAGE" function. Select the cell where you will store the result of the "AVERAGE" function.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Z-Score-02.png) 

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873313/18544" target="_top" id="1873313"><img src="//a.impactradius-go.com/display-ad/18544-1873313" border="0" alt="" width="1080" height="1263"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873313/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Type in the following formula and press enter -or- use the "Formulas" menu.

=AVERAGE(E2:E13)

 To access the function through the "Formulas" menu, select the "More Functions" drop-down, select the "Statistical" option, and then click on "AVERAGE."

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Z-Score-03.png) 

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1678785/12108" target="_top" id="1678785"><img src="//a.impactradius-go.com/display-ad/12108-1678785" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
 In the Function Arguments window, select all of the cells in the "Values" column as the input for the "Number1" field. You don't need to worry about the "Number2" field.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Z-Score-04.png) 

<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->
 Now press "OK."

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Z-Score-05-1.png) 

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084399/18498" target="_top" id="2084399"><img src="//a.impactradius-go.com/display-ad/18498-2084399" border="0" alt="" width="1125" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084399/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Next, we need to calculate the standard deviation of the values using either the "STDEV.S" or "STDEV.P" function. In this example, we will show you how to calculate both values, starting with "STDEV.S." Select the cell where the result will be stored.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Z-Score-06.png) 

 To calculate the standard deviation using the "STDEV.S" function, type in this formula and press Enter (or access it through the "Formulas" menu).

=STDEV.S(E3:E12)

 To access the function through the "Formulas" menu, select the "More Functions" drop-down, select the "Statistical" option, scroll down a bit, and then click the "STDEV.S" command.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Z-Score-07.png) 

 In the Function Arguments window, select all of the cells in the "Values" column as the input for the "Number1" field. You don't need to worry about the "Number2" field here, either.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Z-Score-08.png) 

 Now press "OK."

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Z-Score-09.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-office-pdf-editor-1x.890dbda.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
 Next, we will calculate the standard deviation using the "STDEV.P" function. Select the cell where the result will be stored.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Z-Score-10.png) 

 To calculate the standard deviation using the "STDEV.P" function, type in this formula and press Enter (or access it through the "Formulas" menu).

 \=STDEV.P(E3:E12)

 To access the function through the "Formulas" menu, select the "More Functions" drop-down, select the "Statistical" option, scroll down a bit, and then click the "STDEV.P" formula.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Z-Score-11.png) 

 In the Function Arguments window, select all of the cells in the "Values" column as the input for the "Number1" field. Again, you won't need to worry about the "Number2" field.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Z-Score-12.png) 

 Now press "OK."

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Z-Score-13-1.png) 

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Now that we have calculated the mean and standard deviation of our data, we have all we need to calculate the Z-Score. We can use a simple formula that references the cells containing the results of the "AVERAGE" and "STDEV.S" or "STDEV.P" functions.

 Select the first cell in the "Z-Score" column. We will use the result of the "STDEV.S" function for this example, but you could also use the result from "STDEV.P."

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Z-Score-14.png) 

 Type in the following formula and hit Enter:

=(E3-$G$3)/$H$3

 Alternatively, you could use the following steps to enter the formula instead of typing:

1. Click cell F3 and type `=(`
2. Select cell E3\. (You can press the left-arrow-key once or use the mouse)
3. Type the minus sign `-`
4. Select cell G3 then press F4 to add the "$" characters to make an 'absolute' reference to the cell (it will cycle through "G3" > "**$**G**$**3" > "G**$**3" > "**$**G3" > "G3" if you continue pressing F4)
5. Type `)/`
6. Select cell H3 (or I3 if you are using "STDEV.P") and press F4 to add the two "$" characters.
7. Press Enter

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Z-Score-15.png) 

<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 The Z-Score has been calculated for the first value. It is 0.15945 standard deviations below the mean. To check the results, you can multiply the standard deviation by this result (6.271629 \* -0.15945) and check that the result is equal to the difference between the value and the mean (499-500). Both results are equal, so the value makes sense.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Z-Score-16.png) 

 Let's calculate the Z-Scores of the rest of the values. Highlight the whole 'Z-Score' column starting with the cell containing the formula.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Z-Score-17.png) 

 Press Ctrl+D, which copies the formula in the top cell down through all the other selected cells.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Z-Score-18.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4694919&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/jutoh-logo-1200x1600.jpg" border="0">Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. </a>
<!-- affiliate ads end -->
 Now the formula has been 'filled-down' to all of the cells, and each will always reference the correct "AVERAGE" and "STDEV.S" or "STDEV.P" cells because of the "$" characters. If you get errors, go back and make sure the "$" characters are included in the formula you entered.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068407/7443" target="_top" id="2068407"><img src="//a.impactradius-go.com/display-ad/7443-2068407" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Calculating the Z-Score without using 'Helper' Cells

 Helper cells store a result, like the ones storing the results of the "AVERAGE," "STDEV.S," and "STDEV.P" functions. They can be useful but aren't always necessary. You can skip them altogether when calculating a Z-Score by using the following generalized formulas, instead.

 Here's one using the "STDEV.S" function:

=(Value-AVERAGE(Values))/STDEV.S(Values)

 And one using the "STEV.P" function:

=(Value-AVERAGE(Values))/STDEV.P(Values)

 When entering the cell ranges for the "Values" in the functions, be sure to add absolute references ("$" using F4) so that when you 'fill-down' you aren't calculating the average or standard deviation of a different range of cells in every formula.

 If you have a large data set, it may be more efficient to use helper cells because it doesn't calculate the result of the "AVERAGE" and "STDEV.S" or "STDEV.P" functions each time, saving processor resources and speeding up the time it takes to calculate the results.

 Also, "$G$3" takes fewer bytes to store and less RAM to load than "AVERAGE($E$3:$E$12).". This is important because the standard 32-bit version of Excel is limited to 2GB of RAM (the 64-bit version does not have any limitations on how much RAM can be used).

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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-timeless-triumphs-screen-captures-of-samsungs/"><u>[New] In 2024, Timeless Triumphs  Screen Captures of Samsungs</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/solved-asmtxhcisys-blue-screen-of-death-error/"><u>[SOLVED] asmtxhci.sys Blue Screen Of Death Error</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-quick-guide-to-honor-90-lite-frp-bypass-instantly-by-drfone-android/"><u>A Quick Guide to Honor 90 Lite FRP Bypass Instantly</u></a></li>
<li><a href="https://win-dash.techidaily.com/boost-your-mono-laser-printing-a-step-by-step-guide-to-updating-dells-2330d-and-2330dn-printer-drivers/"><u>Boost Your Mono Laser Printing: A Step-by-Step Guide to Updating Dell's 2330D and 2330DN Printer Drivers</u></a></li>
<li><a href="https://win-dash.techidaily.com/brother-hl-l2380dw-obtain-compatible-windows-drivers-for-optimal-print-performance/"><u>Brother HL-L2380DW: Obtain Compatible Windows Drivers for Optimal Print Performance</u></a></li>
<li><a href="https://win-dash.techidaily.com/complete-download-pack-latest-lenovo-x1-carbon-device-drivers-for-windows-users-versions-10-11-and-7/"><u>Complete Download Pack: Latest Lenovo X1 Carbon Device Drivers for Windows Users (Versions 10, 11 & 7)</u></a></li>
<li><a href="https://win-dash.techidaily.com/complete-lenovo-t430-driver-collection-for-windows-10-8-and-7-effortless-downloading-steps/"><u>Complete Lenovo T430 Driver Collection for Windows 10, 8, and 7 - Effortless Downloading Steps</u></a></li>
<li><a href="https://win-answers.techidaily.com/cracking-the-code-comprehensive-solutions-to-fix-error-727e66ac-in-nba-2k24-guide-updated/"><u>Cracking the Code: Comprehensive Solutions to Fix Error 727E66ac in NBA 2K24 (Guide Updated )</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-logitech-momo-racer-wheel-game-drivers-pc-compatible/"><u>Download Logitech MOMO Racer Wheel Game Drivers - PC Compatible</u></a></li>
<li><a href="https://win-dash.techidaily.com/easy-guide-to-downloading-and-updating-creativitys-webcam-software-on-pc/"><u>Easy Guide to Downloading & Updating Creativity's Webcam Software on PC</u></a></li>
<li><a href="https://win-dash.techidaily.com/effortless-amd-radeon-rx-480-driver-downloads-and-updates-step-by-step-guide/"><u>Effortless AMD Radeon RX 480 Driver Downloads and Updates: Step-by-Step Guide</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/enhance-your-data-collection-through-cookiebot-integration/"><u>Enhance Your Data Collection Through Cookiebot Integration</u></a></li>
<li><a href="https://win-dash.techidaily.com/expert-tips-to-overcome-challenges-with-your-realtek-universal-video-controller/"><u>Expert Tips to Overcome Challenges with Your Realtek Universal Video Controller</u></a></li>
<li><a href="https://win-dash.techidaily.com/fixing-hp-laserjet-p2035-printer-problems-on-windows-a-comprehensive-guide/"><u>Fixing HP LaserJet P2035 Printer Problems on Windows: A Comprehensive Guide</u></a></li>
<li><a href="https://win-dash.techidaily.com/free-download-behringer-usb-interface-drivers-for-premium-sound/"><u>Free Download: Behringer USB Interface Drivers for Premium Sound</u></a></li>
<li><a href="https://win-dash.techidaily.com/free-download-ultimate-driver-setup-for-msi-x470-motherboards/"><u>Free Download: Ultimate Driver Setup for MSI X470 Motherboards</u></a></li>
<li><a href="https://win-dash.techidaily.com/free-logitech-g35-headset-drivers-compatible-with-windows-7-8-and-10/"><u>Free Logitech G35 Headset Drivers Compatible with Windows 7, 8 & 10</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-latest-canon-mx340-drivers-support-for-win-10-8-and-7-systems/"><u>Get the Latest Canon MX340 Drivers: Support for Win 10, 8 and 7 Systems</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-newest-razer-naga-software-updates-and-download-for-windows-users/"><u>Get the Newest Razer Naga Software Updates & Download for Windows Users</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-updated-logitech-g910-driver-package-for-a-seamless-pc-experience-on-windows-os/"><u>Get the Updated Logitech G910 Driver Package for a Seamless PC Experience on Windows OS</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-your-hp-officejet-pro-8740-up-and-running-drivers-for-windows-11108/"><u>Get Your HP Officejet Pro 8740 Up and Running: Drivers for Windows 11/10/8</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722978312690-get-your-realtek-rtl8188cu-wireless-network-adapter-driver-for-win-107-today/"><u>Get Your Realtek RTL8188CU Wireless Network Adapter Driver for Win 10/7 Today</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-your-windows-compatible-epson-et-2750-printing-drivers-instantly/"><u>Get Your Windows Compatible Epson ET-2750 Printing Drivers Instantly!</u></a></li>
<li><a href="https://win-dash.techidaily.com/getting-up-to-date-with-your-hp-laserjet-m5e-series-driver-downloads-and-setup-tips/"><u>Getting Up-to-Date with Your HP Laserjet M5e Series: Driver Downloads & Setup Tips</u></a></li>
<li><a href="https://win-dash.techidaily.com/gtx-780-drivers-download-easily-for-windows/"><u>GTX 780 Drivers Download Easily for Windows</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-customize-the-internet-browser-on-your-samsung-smart-tv-easily/"><u>How To Customize The Internet Browser On Your Samsung Smart TV Easily</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-to-get-and-use-pokemon-go-promo-codes-on-nubia-z50s-pro-drfone-by-drfone-virtual-android/"><u>How to Get and Use Pokemon Go Promo Codes On Nubia Z50S Pro | Dr.fone</u></a></li>
<li><a href="https://win-dash.techidaily.com/hp-officejet-3830-printer-driver-for-windows-users-free-download/"><u>HP OfficeJet 3830 Printer Driver for Windows Users – Free Download</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-ways-to-stop-parent-tracking-your-oneplus-nord-n30-se-drfone-by-drfone-virtual-android/"><u>In 2024, Ways to stop parent tracking your OnePlus Nord N30 SE | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-why-your-whatsapp-live-location-is-not-updating-and-how-to-fix-on-your-tecno-camon-20-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Why Your WhatsApp Live Location is Not Updating and How to Fix on your Tecno Camon 20 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://win-dash.techidaily.com/install-logitech-g920-mouse-drivers-on-your-pc-compatible-with-windows-versions-including-111087/"><u>Install Logitech G920 Mouse Drivers on Your PC - Compatible with Windows Versions Including 11/10/8/7</u></a></li>
<li><a href="https://win-dash.techidaily.com/install-or-update-your-epson-wf-3620-printer-drivers-compatible-with-windows-1187-systems/"><u>Install or Update Your Epson WF-3620 Printer Drivers - Compatible with Windows 11/8/7 Systems</u></a></li>
<li><a href="https://win-dash.techidaily.com/installing-the-latest-epson-wf-2760-driver-for-your-windows-pc-supports-win11win10win8/"><u>Installing the Latest Epson WF-2760 Driver for Your Windows PC (Supports Win11/Win10/Win8)</u></a></li>
<li><a href="https://win-dash.techidaily.com/necrotizing-enterocolitis/"><u>Necrotizing Enterocolitis</u></a></li>
<li><a href="https://win-dash.techidaily.com/quick-download-guide-intel-thunderbolt-chip-driver-software/"><u>Quick Download Guide: Intel Thunderbolt Chip Driver Software</u></a></li>
<li><a href="https://win-dash.techidaily.com/step-by-step-guide-to-downloading-the-pioneer-dj-ddj-sx2-controller-driver/"><u>Step-by-Step Guide to Downloading the Pioneer DJ DDJ-SX2 Controller Driver</u></a></li>
<li><a href="https://android-frp.techidaily.com/the-complete-guide-to-poco-f5-5g-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>The Complete Guide to Poco F5 5G FRP Bypass Everything You Need to Know</u></a></li>
</ul></div>
