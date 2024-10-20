---
title: "Guide: Implementing Data Entry Limits in Excel Using Data Validation Techniques"
date: 2024-10-16T16:32:10.979Z
updated: 2024-10-20T17:04:02.401Z
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
<li><a href="https://instagram-video-recordings.techidaily.com/new-enhancing-instagram-presence-vimeo-videos-included-for-2024/"><u>[New] Enhancing Instagram Presence Vimeo Videos Included for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-high-quality-android-photoshoppers-for-2024/"><u>[Updated] High-Quality Android Photoshoppers for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-pinnacle-gadgets-the-leading-smartphones-for-artists/"><u>[Updated] Pinnacle Gadgets The Leading Smartphones for Artists</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-an-overview-and-comparative-study-of-googles-augmented-reality-stickers/"><u>2024 Approved An Overview and Comparative Study of Google's Augmented Reality Stickers</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-logitech-g920-mouse-drivers-compatible-with-windows-11-10-8-and-7/"><u>Download Logitech G920 Mouse Drivers: Compatible with Windows 11, 10, 8 & 7</u></a></li>
<li><a href="https://buynow-info.techidaily.com/expert-reviews-unveiling-the-most-durable-and-stylish-11-ipad-air-cases-for-this-year/"><u>Expert Reviews: Unveiling the Most Durable & Stylish 11 iPad Air Cases for This Year</u></a></li>
<li><a href="https://win-dash.techidaily.com/free-download-compatible-msi-bluetooth-drivers-for-windows-11-and-windows-10/"><u>Free Download: Compatible MSI Bluetooth Drivers for Windows 11 & Windows 10</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/free-music-making-software-the-top-10-picks-for-2024/"><u>Free Music Making Software The Top 10 Picks for 2024</u></a></li>
<li><a href="https://win-dash.techidaily.com/guide-resolve-compatibility-issues-between-hp-monitors-and-windows-1087-drivers/"><u>Guide: Resolve Compatibility Issues Between HP Monitors & Windows 10/8/7 Drivers</u></a></li>
<li><a href="https://win-dash.techidaily.com/hassle-free-msi-graphics-driver-installation-guide-for-windows-117/"><u>Hassle-Free MSI Graphics Driver Installation Guide for Windows 11/7</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-update-your-pcs-sound-card-software-on-windows-platform/"><u>How to Update Your PC's Sound Card Software on Windows Platform</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-easy-guide-to-capturing-youtube-content/"><u>In 2024, Easy Guide to Capturing YouTube Content</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-xiaomi-14-pro-frp-in-3-different-ways-by-drfone-android/"><u>In 2024, How To Bypass Xiaomi 14 Pro FRP In 3 Different Ways</u></a></li>
<li><a href="https://win-dash.techidaily.com/install-the-newest-intel-network-driver-software-for-windows-operating-systems-11-10-and-nv7/"><u>Install the Newest Intel Network Driver Software for Windows Operating Systems: 11, 10 & Nv7</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-animation-drawing-made-easy-top-7-software-solutions/"><u>New In 2024, Animation Drawing Made Easy Top 7 Software Solutions</u></a></li>
<li><a href="https://win-dash.techidaily.com/step-by-step-instructions-for-downloading-and-setting-up-epson-xp-400-drivers/"><u>Step-by-Step Instructions for Downloading and Setting Up Epson XP-400 Drivers</u></a></li>
<li><a href="https://win-dash.techidaily.com/tp-link-wireless-nic-drivers-for-windows-1087-download-latest-versions/"><u>TP-Link Wireless NIC Drivers for Windows 10/8/7 - Download Latest Versions</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137209/26400" target="_top" id="2137209">
  <img src="//a.impactradius-go.com/display-ad/26400-2137209" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137209/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

