---
title: "Step-by-Step Guide: Consolidating Full Names Using Microsoft Excel Functions"
date: 2024-10-19T17:10:10.354Z
updated: 2024-10-20T18:16:43.735Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/9f80d4896e94eaecc9b9d2fa222d6b7ea517f0365f103fdcf83c4e1528970c2b.jpg
---

## Step-by-Step Guide: Consolidating Full Names Using Microsoft Excel Functions

### Quick Links

* [Method 1: Use Flash Fill](https://extra-lessons.techidaily.com/sharpening-screen-views-for-improved-virtual-interactions/)
* [Method 2: Use the & (Ampersand) Symbol](https://www.howtogeek.com/866786/how-to-combine-first-and-last-names-in-microsoft-excel/#method-2-use-the-amp-ampersand-symbol)
* [Method 3: Use the CONCAT Function](https://apple-account.techidaily.com/in-2024-how-to-fix-when-apple-account-locked-from-iphone-13-pro-by-drfone-ios/)
* [Method 4: Use the TEXTJOIN Function](https://facebook-video-content.techidaily.com/updated-2024-approved-can-you-challenge-facebooks-video-copyright-holdouts/)
* [Method 5: Use Power Query](https://location-fake.techidaily.com/6-ways-to-change-spotify-location-on-your-apple-iphone-12-pro-max-drfone-by-drfone-virtual-ios/)

### Key Takeaways

 To merge first and last names in Excel, type the first combined name how you'd like it to appear, then use Flash Fill to combine the rest of the names automatically. Alternatively, get finer control by combining your name cells using a formula or the Power Query tool.

 Do you want to bring the first and last names that are in [separate cells into a single cell](https://facebook-clips.techidaily.com/new-elevate-your-facebook-profile-with-these-11-superior-tools/)? Combining text is easy in Excel, and we'll show you five different ways to combine names.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1884021/19272" target="_top" id="1884021">
  <img src="//a.impactradius-go.com/display-ad/19272-1884021" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1884021/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Method 1: Use Flash Fill

[Flash Fill is an Excel feature](https://location-social.techidaily.com/how-to-change-location-on-facebook-dating-for-your-honor-magic-6-drfone-by-drfone-virtual-android/) that automatically fills your cells by recognizing the fill pattern. You manually fill a cell with the kind of data you want, and the feature senses that data and fills all your selected cells accordingly. No formula is necessary with Flash Fill.

 In the case of combining names, you manually merge the first and last names for a single record, and Flash Fill recognizes that pattern and merges the names for all your other records automatically.

 To use start using Flash Fill, in your spreadsheet, select the first cell where you want to display the combined names. In this cell, type the first and last names together as you'd like them to appear.

![Manually enter the first and last name.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/01/5-manually-merge-name.png) 

 Go down a row and start typing the first and last name for your second record. As soon as you begin typing, Flash Fill will sense the pattern and fill all your records in gray color. To confirm you want these cells filled, press Enter on your keyboard.

![Press Enter.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/01/6-flash-fill-auto-complete.png) 

 If a Flash Fill prompt doesn't appear, use the Ctrl+E shortcut to force a Flash Fill.

 And that's it. [Excel has automatically merged](https://extra-approaches.techidaily.com/new-meme-creation-at-its-peak-10-templates-unveiled/) the first and last names for all your records.

![Merged first and last names.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/01/7-flash-fill-merged-names.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075483/7443" target="_top" id="2075483">
  <img src="//a.impactradius-go.com/display-ad/7443-2075483" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075483/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938750/19272" target="_top" id="1938750">
  <img src="//a.impactradius-go.com/display-ad/19272-1938750" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938750/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Method 2: Use the & (Ampersand) Symbol

 If you prefer to use an [Excel formula](https://games-able.techidaily.com/is-premium-play-on-demand-worth-it/) to combine names, a simple method for [bringing multiple cells' content into a single cell](https://location-social.techidaily.com/in-2024-how-to-sharefake-location-on-whatsapp-for-realme-narzo-60x-5g-drfone-by-drfone-virtual-android/) is to use the `&` (ampersand) operator. This operator combines the content of your specified cells, allowing you to merge all the cell data you want.

 To use this method, in your spreadsheet, select the cell where you want to see the merged names.

![Choose a cell.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/01/1-combine-name-select-cell.png) 

 In the selected cell, type the following formula and press Enter. Here, replace `B2` with the cell containing the first name and `C2` with the cell that has the last name.

=B2&" "&C2

 Note that we've added a space enclosed with double quotes so that there's a space between the first and the last name in the resulting cell.

 In your selected cell, you'll see the first and last names combined.

![Combined names.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/01/2-enter-combine-name-formula.png) 

 To [copy this formula for all your records](https://extra-tips.techidaily.com/in-2024-converting-personal-memories-from-stillness-to-motion/), from the bottom-right corner of the cell where you've entered the formula, click and drag downwards covering all your records.

 If you have a middle name or initial in a separate column and you'd like to merge that as well, add that cell as an argument to the formula. Here, we'll combine the contents of the cell `B2` , `C2` , and `D2` (in that order), with each cell content separated by a space.

=B2&" "&C2&" "&D2

 Alternatively, if you want to combine names so that the last name appears first followed by a comma, use a formula like this.

=D2&", "&B2&" "&C2

Related: [How to Merge Two Columns in Microsoft Excel](https://location-social.techidaily.com/in-2024-how-to-sharefake-location-on-whatsapp-for-realme-narzo-60x-5g-drfone-by-drfone-virtual-android/) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100542/7443" target="_top" id="2100542">
  <img src="//a.impactradius-go.com/display-ad/7443-2100542" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100542/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Method 3: Use the CONCAT Function

 Excel's `CONCAT` function works just like the `&` operator and lets you combine multiple cells' content into a single cell. Using a function instead of an operator can sometimes make your formula easier for others to read and understand.

 To merge your first and last names with `CONCAT`, in your spreadsheet, select the cell where you'd like to see the combined names.

![Select a cell.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/01/3-merge-names-choose-cell.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043593/7443" target="_top" id="2043593">
  <img src="//a.impactradius-go.com/display-ad/7443-2043593" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043593/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In the selected cell, enter the following function and press Enter. In this function, replace `B2` with your cell that has the first name and `C2` with the cell that contains the last name. Note that we've separated the first and the last name with a space in this function.

=CONCAT(B2," ",C2)

 Once you press Enter, in your selected cell, you'll see both your names merged. You can copy the function for all your records by dragging downwards from the bottom-right corner of the cell where the function exists.

![Merged name.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/01/4-excel-concat-function.png) 

 If you'd like to merge the middle name or initial as well, use the function as follows. Here, `C2` denotes the middle name cell, while `D2` contains the last name.

=CONCAT(B2," ",C2," ",D2)

 If, instead, you want the last name to come first, try changing around the formula and inserting a comma like this:

=CONCAT(D2,", ",B2," ",C2)

 And that's it.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1972679/19272" target="_top" id="1972679">
  <img src="//a.impactradius-go.com/display-ad/19272-1972679" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1972679/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Method 4: Use the TEXTJOIN Function

 With the `TEXTJOIN` function, you can combine your names using your specified delimiter. This function also offers the option to ignore empty cells. You'll find it a little more complicated to use than `CONCAT`, but it's also a more powerful function.

 To use `TEXTJOIN`, in your spreadsheet, click the cell where you want to display the merged names. Then, type the following function in the cell. Here, replace `B2` with the cell that has the first name and `C2` with the cell containing the last name. To ignore empty cells, change `FALSE` to `TRUE` .

=TEXTJOIN(" ",FALSE,B2,C2)

![Merge names with TEXTJOIN.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/01/8-textjoin-merge-names.png) 

 If your dataset has first name, middle name, and last name in the `B2` , `C2` , and `D2` cells, respectively, then you can join them using the following function:

=TEXTJOIN(" ",FALSE,B2,C2,D2)

##  Method 5: Use Power Query

 Power Query is an Excel feature that helps you [combine data from multiple](https://youtube-zero.techidaily.com/024-approved-stepwise-strategy-for-transforming-your-youtube-videos-with-imovie/) worksheets and workbooks. You can use this option to merge your columns as well.

 To use this method, first, click a cell in your dataset. Then, from Excel's ribbon at the top, select Data > From Table/Range.

![Choose Data > From Table/Range.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/01/9-excel-data-from-table-range.png) 

 In the "Create Table" box, ensure the correct dataset range is specified. If your dataset has column headers, enable the "My Table Has Headers" option. Then, select "OK."

![Verify the data range and select "OK."](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/01/10-excel-create-table.png) 

 A "Power Query Editor" window will open. Here, hold down Ctrl (Windows) or Command (Mac) key and select your first name and last name columns. Then, [right-click](https://desktop-recording.techidaily.com/updated-the-art-of-recording-fun-6-techniques-to-document-minecraft-for-2024/) either column and choose "Merge Columns."

![Select "Merge Columns" in the menu.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/01/11-excel-merge-columns.png) 

 On the "Merge Columns" window, click the "Separator" drop-down menu and choose "Space." Optionally, in the "New Column Name" field, enter the name of the column that'll have your merged names. Then, select "OK."

![Customize merging and select "OK."](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/01/12-excel-name-separator.png) 

 In the "Power Query Editor" window's top-left corner, click "Close & Load."

![Select "Close & Load" at the top-left corner.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/01/13-excel-apply-power-query.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037475/7443" target="_top" id="2037475">
  <img src="//a.impactradius-go.com/display-ad/7443-2037475" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037475/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In your workbook, Power Query has added a new worksheet that contains your merged names.

![Merged columns with Power Query.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/01/14-excel-merged-columns.png) 

 You now have a spreadsheet complete with readable full names for each entry. If you're entering a lot of names and other data, learn [the best Excel functions for data entry](https://vimeo-videos.techidaily.com/in-2024-high-end-downloads-best-10-apps-for-extracting-vimeo-videos/).

Related: [How to Combine Data From Spreadsheets in Microsoft Excel](https://extra-approaches.techidaily.com/new-meme-creation-at-its-peak-10-templates-unveiled/)

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
<li><a href="https://facebook-video-files.techidaily.com/new-2024-approved-expert-video-grabbing-extras-fb-and-firefox-edition/"><u>[New] 2024 Approved Expert Video Grabbing Extras FB & Firefox Edition</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-2024-approved-high-tech-vr-handhelds-our-top-10-list/"><u>[New] 2024 Approved High-Tech VR Handhelds Our Top 10 List</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-exclusive-catalogue-free-to-use-stock-media-sites/"><u>[New] Exclusive Catalogue Free-to-Use Stock Media Sites</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-the-final-act-steps-for-permanent-instagram-account-removal-for-2024/"><u>[New] The Final Act Steps for Permanent Instagram Account Removal for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-elusive-story-viewers-mobile-hacks/"><u>[Updated] In 2024, Elusive Story Viewers' Mobile Hacks</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-top-notch-mac-visual-archiver/"><u>[Updated] In 2024, Top-Notch Mac Visual Archiver</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-in-2024-ultimate-10-filter-combos-making-tiktoks-pop-up/"><u>[Updated] In 2024, Ultimate 10 Filter Combos Making TikToks Pop Up</u></a></li>
<li><a href="https://win-dash.techidaily.com/asus-z170-motherboard-freshest-drivers-for-windows-10-8-and-eb-quick-guide-and-downloads/"><u>ASUS Z170 Motherboard - Freshest Drivers for Windows 10, 8 & Eb: Quick Guide and Downloads</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722971642348-canon-pixma-ts3322-obtain-new-driver-version-now/"><u>Canon PIXMA TS3322 - Obtain New Driver Version Now!</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/digital-media-seeker/"><u>Digital Media Seeker</u></a></li>
<li><a href="https://win-dash.techidaily.com/easy-install-guide-updated-epson-wf-3620-driver-for-modern-operating-systems-windows-11-8-and-7/"><u>Easy Install Guide: Updated Epson WF-3620 Driver for Modern Operating Systems - Windows 11, 8 & 7</u></a></li>
<li><a href="https://discover-advanced.techidaily.com/enhanced-user-experience-with-smart-cookiebot-technology/"><u>Enhanced User Experience with Smart Cookiebot Technology</u></a></li>
<li><a href="https://win-dash.techidaily.com/ensure-seamless-bluetooth-connectivity-updated-mpow-drivers-for-windows-users-windows-1187/"><u>Ensure Seamless Bluetooth Connectivity: Updated MPOW Drivers for Windows Users (Windows 11/8/7)</u></a></li>
<li><a href="https://win-dash.techidaily.com/guide-to-optimizing-your-pc-with-new-ati-graphics-card-drivers-on-windows/"><u>Guide to Optimizing Your PC with New ATI Graphics Card Drivers on Windows</u></a></li>
<li><a href="https://win-dash.techidaily.com/improve-connectivity-update-samsung-usb-drivers-for-smartphones/"><u>Improve Connectivity: Update Samsung USB Drivers for Smartphones</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-3-effective-methods-to-fake-gps-location-on-android-for-your-vivo-v30-pro-drfone-by-drfone-virtual/"><u>In 2024, 3 Effective Methods to Fake GPS location on Android For your Vivo V30 Pro | Dr.fone</u></a></li>
<li><a href="https://win-dash.techidaily.com/latest-geforce-rtx-3080-ti-windows-drivers-compatible-with-windows-10-8-and-7-download-now/"><u>Latest GeForce RTX 3080 Ti Windows Drivers: Compatible with Windows 10, 8 & 7 – Download Now</u></a></li>
<li><a href="https://win-dash.techidaily.com/new-magicard-rio-pro-driver-update-now-available-for-modern-windows-systems/"><u>New Magicard Rio Pro Driver Update Now Available for Modern Windows Systems</u></a></li>
<li><a href="https://win-dash.techidaily.com/troubleshooting-why-your-pc-cant-find-the-wireless-adapter-tl-wn722n/"><u>Troubleshooting: Why Your PC Can't Find the Wireless Adapter (TL-WN722N)</u></a></li>
</ul></div>

