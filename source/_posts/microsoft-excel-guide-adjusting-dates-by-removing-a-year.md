---
title: "Microsoft Excel Guide: Adjusting Dates by Removing a Year"
date: 2024-10-15T18:34:59.053Z
updated: 2024-10-20T18:43:20.801Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/82e91f7db84fddd0d0cd74fd53de4decc4bc8c46a25aa2285ca573b91b9719e8.jpg
---

## Microsoft Excel Guide: Adjusting Dates by Removing a Year

### Quick Links

* [Custom Number Formatting](https://bypass-frp.techidaily.com/in-2024-a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-itel-p40plus-by-drfone-android/)
* [CONCATENATE Function](https://extra-information.techidaily.com/2024-approved-a-beginners-guide-making-your-podcasts-rss-feed/)

 There are a couple of ways you can remove the year from a date shown in Microsoft Excel. You can use custom cell formatting to hide it or use various functions like CONCATENATE to remove it completely. Here's how.

##  Custom Number Formatting

 While a date value in an Excel cell is technically a number, Microsoft Excel uses a particular type of formatting to display it. The same is true for currency values, where currency symbols are added to values to show that they relate to money. When you add a date in Excel in a format that it recognizes, Excel automatically changes the cell number format to the "Date" type.

 You can customize this type to display the date value in different ways. For instance, you can switch between "11/02/2021" (in the DD/MM/YYYY format commonly used in the U.K.) and "2021-02-11" for 11 February 2021.

![An example of various custom date formats in Microsoft Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/02/Excel-Custom-Date-Formats.png) 

<!-- affiliate ads begin -->
<span id="1975658">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975658.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975658">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975658.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975658%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975658/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can customize this number format, however, to remove the year entirely from view. The value itself won't change, but Excel won't [show the year value](https://facebook-record-videos.techidaily.com/updated-in-2024-captivating-content-the-basics-of-removing-background-from-videos/) thanks to custom number formatting.

 To do this, highlight the cells containing your original date values, then select the "Home" tab on the ribbon bar. From there, select the arrow next to the number format drop-down menu and choose the "More Number Formats" option.

![In Excel, select your date values, then press Home &gt; Number Format &gt; More Number Formats.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/02/Excel-More-Number-Formats-Option.png) 

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139117/17108" target="_top" id="2139117">
  <img src="//a.impactradius-go.com/display-ad/17108-2139117" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139117/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In the "Format Cells" menu, select a style of formatting that you like from the "Date" options provided. Once that's selected, choose the "Custom" option.

![In the &quot;Format Cells&quot; menu, select your date value type from the &quot;Date&quot; menu before pressing the &quot;Custom&quot; option.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/02/Excel-Set-Custom-Date-Format.png) 

 In the "Custom" option, you'll see the date number formatting style shown as text in the "Type" box. For instance, "11/02/2021" would show as "dd/mm/yyyy" in this box.

 To remove the year, make sure to remove any references to "yyyy" or "yy" in the "Type" box as well as any surplus delimiters, such as a dash or forward slash. For instance, "11/02/2021" would require you to remove "/yyyy" from the "dd/mm/yyyy" type box, leaving "dd/mm" in place.

 Once you've made your changes, select the "OK" button.

![Remove &quot;yy&quot; or &quot;yyyy&quot; from the &quot;Type&quot; box, then press &quot;OK&quot; to confirm.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/02/Excel-Remove-Year-From-Cell-Formatting.png) 

 Changing the cell number type will hide the year, but it won't remove it. If you want to restore the year, change your cell number type to a date type that includes the year again.

##  CONCATENATE Function

 Concatenation is a term that basically means to link or combine two or more pieces of data. In Microsoft Excel terms, concatenation can be used to add various text strings, numbers, or cell values together in a new cell.

![An example of various text strings combined using the Excel CONCATENATE function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/02/Excel-CONCATENATE-Example.png) 

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137974/21526" target="_top" id="2137974">
  <img src="//a.impactradius-go.com/display-ad/21526-2137974" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137974/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you want to remove the year from a date in Excel, you could combine the output from two functions (such as DAY or MONTH) together using CONCATENATE. Rather than hiding the year from view using custom number formatting, CONCATENATE (with DAY and MONTH) allows you to create a separate value that doesn't include the year at all.

 To do this, open an Excel workbook containing your date values, or create a new workbook and place date values in separate cells. To use CONCATENATE with DAY and MONTH, insert a new function using this structure, replacing the cell reference (A2) with a reference to the cell containing your date:

=CONCATENATE(DAY(A2),"/",MONTH(A2))

 The values returned by DAY and MONTH are separated by a special delimiter character, such as a comma or slash, to show that the returned value is a date. Each value (DAY, the delimiter, and MONTH) are separated by a comma in the CONCATENATE function.

 In this example, cell A2 contains a date value (11/12/2021) in the DD/MM/YYYY format. Using CONCATENATE with DAY and MONTH, the day (11) and month (12) from the date value in A2 are placed in another cell separated by the delimiter, which, in this case, is a forward slash.

![An example of various text strings combined using the Excel CONCATENATE function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/02/Excel-CONCATENATE-Example.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105876/7443" target="_top" id="2105876">
  <img src="//a.impactradius-go.com/display-ad/7443-2105876" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105876/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 You can customize this formula to change the order of the day and month values (eg. MM/DD) or to use a different delimiter character. You can also [use the fill handle](https://visual-screen-recording.techidaily.com/new-in-2024-top-5-best-hdmi-21-gaming-monitors-ps5-compatible/) to copy this formula into other cells in your column to remove the year from multiple date values.

Related: [How to Automatically Fill Sequential Data into Excel with the Fill Handle](https://visual-screen-recording.techidaily.com/new-in-2024-top-5-best-hdmi-21-gaming-monitors-ps5-compatible/)

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
<li><a href="https://youtube-tips.techidaily.com/aking-a-splash-with-youtube-ad-banners-and-thumbnails-for-2024/"><u>[New] Making a Splash with YouTube Ad Banners & Thumbnails for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-mastering-vocal-transformations-high-ranked-app-options/"><u>[New] Mastering Vocal Transformations High-Ranked App Options</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-navigating-and-interpreting-twitter-archives/"><u>2024 Approved Navigating and Interpreting Twitter Archives</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-tier-5-speedy-screen-recorders/"><u>2024 Approved Tier 5 Speedy Screen Recorders</u></a></li>
<li><a href="https://win-dash.techidaily.com/complete-instructions-to-obtain-and-update-samsungs-960-evo-drives-on-a-windows-pc/"><u>Complete Instructions to Obtain and Update Samsung's 960 EVO Drives on a Windows PC</u></a></li>
<li><a href="https://win-hacks.techidaily.com/downloading-youtube-videos-in-compatible-formats-for-presentations-with-keynote/"><u>Downloading YouTube Videos in Compatible Formats for Presentations with Keynote</u></a></li>
<li><a href="https://win-dash.techidaily.com/easy-installation-brother-mfc-7360n-driver-update-and-downloads-for-windows-10-8-and-e/"><u>Easy Installation: Brother MFC-7360N Driver Update & Downloads for Windows 10, 8 & E</u></a></li>
<li><a href="https://win-dash.techidaily.com/effortless-driver-management-in-windows-get-started-today/"><u>Effortless Driver Management in Windows - Get Started Today</u></a></li>
<li><a href="https://win-dash.techidaily.com/fixing-device-compatibility-problems-with-rainbow-six-extraction-launcher/"><u>Fixing Device Compatibility Problems with Rainbow Six Extraction Launcher</u></a></li>
<li><a href="https://fake-location.techidaily.com/full-guide-to-fix-itoolab-anygo-not-working-on-poco-m6-pro-5g-drfone-by-drfone-virtual-android/"><u>Full Guide to Fix iToolab AnyGO Not Working On Poco M6 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-latest-logitech-rx250-drivers-here-for-windows-users-on-os-7810/"><u>Get the Latest Logitech RX250 Drivers Here for Windows Users on OS 7/8/10</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-unlock-your-honor-90-pro-phone-with-ease-the-3-best-lock-screen-removal-tools-by-drfone-android/"><u>In 2024, Unlock Your Honor 90 Pro Phone with Ease The 3 Best Lock Screen Removal Tools</u></a></li>
<li><a href="https://win-dash.techidaily.com/latest-nvidia-rtx-2080-super-driver-downloads-for-windows-10-and-11/"><u>Latest NVIDIA RTX 2080 Super Driver Downloads for Windows 10 & 11</u></a></li>
<li><a href="https://win-dash.techidaily.com/lenovo-ideapad-t430-driver-downloads-compatible-with-windows-10-8-and-7-quick-guide/"><u>Lenovo IdeaPad T430 Driver Downloads: Compatible with Windows 10, 8 & 7 - Quick Guide</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/mastering-instagrams-qanda-feature-beyond-the-basics-for-2024/"><u>Mastering Instagram's Q&A Feature Beyond the Basics for 2024</u></a></li>
<li><a href="https://discover-awesome.techidaily.com/professionelle-anleitung-fur-den-einfachen-austausch-der-hardware-bei-lenovos-all-in-one-pcs/"><u>Professionelle Anleitung Für Den Einfachen Austausch Der Hardware Bei Lenovos All-in-One PCs</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/mlit-splendor-hues-and-highlights-technique-for-2024/"><u>Streamlit Splendor Hues and Highlights Technique for 2024</u></a></li>
<li><a href="https://win-dash.techidaily.com/supercharge-gaming-on-acer-predator-helios-nv-gpus-with-latest-drivers/"><u>Supercharge Gaming on Acer Predator Helios Nv GPUs with Latest Drivers</u></a></li>
<li><a href="https://win-dash.techidaily.com/unleash-higher-fps-with-a-new-asus-97n-pro-graphics-card-for-gamers/"><u>Unleash Higher FPS with a New Asus 97N Pro Graphics Card for Gamers</u></a></li>
</ul></div>

