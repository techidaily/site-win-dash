---
title: "Step-by-Step Guide: Consolidating Full Names Using Microsoft Excel Functions"
date: 2024-08-28T01:33:47.253Z
updated: 2024-08-29T01:33:47.253Z
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4665597&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pcclean.io/wp-content/uploads/2018/03/winutilities-box-130521.png" border="0">WinUtilities Pro</a>
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

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B300x600%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-300x600.gif" border="0"></a>
<!-- affiliate ads end -->
 To [copy this formula for all your records](https://extra-tips.techidaily.com/in-2024-converting-personal-memories-from-stillness-to-motion/), from the bottom-right corner of the cell where you've entered the formula, click and drag downwards covering all your records.

 If you have a middle name or initial in a separate column and you'd like to merge that as well, add that cell as an argument to the formula. Here, we'll combine the contents of the cell `B2` , `C2` , and `D2` (in that order), with each cell content separated by a space.

=B2&" "&C2&" "&D2

 Alternatively, if you want to combine names so that the last name appears first followed by a comma, use a formula like this.

=D2&", "&B2&" "&C2

Related: [How to Merge Two Columns in Microsoft Excel](https://location-social.techidaily.com/in-2024-how-to-sharefake-location-on-whatsapp-for-realme-narzo-60x-5g-drfone-by-drfone-virtual-android/) 

##  Method 3: Use the CONCAT Function

 Excel's `CONCAT` function works just like the `&` operator and lets you combine multiple cells' content into a single cell. Using a function instead of an operator can sometimes make your formula easier for others to read and understand.

 To merge your first and last names with `CONCAT`, in your spreadsheet, select the cell where you'd like to see the combined names.

![Select a cell.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/01/3-merge-names-choose-cell.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=22741618&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.diskpart.com/resource/images/index/dp-index-img-banner-people@2x.png" border="0">Easy and Safe Partition Software & Hard Disk Manager</a>
<!-- affiliate ads end -->
 In the selected cell, enter the following function and press Enter. In this function, replace `B2` with your cell that has the first name and `C2` with the cell that contains the last name. Note that we've separated the first and the last name with a space in this function.

=CONCAT(B2," ",C2)

 Once you press Enter, in your selected cell, you'll see both your names merged. You can copy the function for all your records by dragging downwards from the bottom-right corner of the cell where the function exists.

![Merged name.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/01/4-excel-concat-function.png) 

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->
 If you'd like to merge the middle name or initial as well, use the function as follows. Here, `C2` denotes the middle name cell, while `D2` contains the last name.

=CONCAT(B2," ",C2," ",D2)

 If, instead, you want the last name to come first, try changing around the formula and inserting a comma like this:

=CONCAT(D2,", ",B2," ",C2)

 And that's it.

##  Method 4: Use the TEXTJOIN Function

 With the `TEXTJOIN` function, you can combine your names using your specified delimiter. This function also offers the option to ignore empty cells. You'll find it a little more complicated to use than `CONCAT`, but it's also a more powerful function.

 To use `TEXTJOIN`, in your spreadsheet, click the cell where you want to display the merged names. Then, type the following function in the cell. Here, replace `B2` with the cell that has the first name and `C2` with the cell containing the last name. To ignore empty cells, change `FALSE` to `TRUE` .

=TEXTJOIN(" ",FALSE,B2,C2)

![Merge names with TEXTJOIN.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/01/8-textjoin-merge-names.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082538/7443" target="_top" id="2082538"><img src="//a.impactradius-go.com/display-ad/7443-2082538" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If your dataset has first name, middle name, and last name in the `B2` , `C2` , and `D2` cells, respectively, then you can join them using the following function:

=TEXTJOIN(" ",FALSE,B2,C2,D2)

##  Method 5: Use Power Query

 Power Query is an Excel feature that helps you [combine data from multiple](https://youtube-zero.techidaily.com/024-approved-stepwise-strategy-for-transforming-your-youtube-videos-with-imovie/) worksheets and workbooks. You can use this option to merge your columns as well.

 To use this method, first, click a cell in your dataset. Then, from Excel's ribbon at the top, select Data > From Table/Range.

![Choose Data > From Table/Range.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/01/9-excel-data-from-table-range.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
 In the "Create Table" box, ensure the correct dataset range is specified. If your dataset has column headers, enable the "My Table Has Headers" option. Then, select "OK."

![Verify the data range and select "OK."](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/01/10-excel-create-table.png) 

 A "Power Query Editor" window will open. Here, hold down Ctrl (Windows) or Command (Mac) key and select your first name and last name columns. Then, [right-click](https://desktop-recording.techidaily.com/updated-the-art-of-recording-fun-6-techniques-to-document-minecraft-for-2024/) either column and choose "Merge Columns."

![Select "Merge Columns" in the menu.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/01/11-excel-merge-columns.png) 

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1678785/12108" target="_top" id="1678785"><img src="//a.impactradius-go.com/display-ad/12108-1678785" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
 On the "Merge Columns" window, click the "Separator" drop-down menu and choose "Space." Optionally, in the "New Column Name" field, enter the name of the column that'll have your merged names. Then, select "OK."

![Customize merging and select "OK."](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/01/12-excel-name-separator.png) 

 In the "Power Query Editor" window's top-left corner, click "Close & Load."

![Select "Close & Load" at the top-left corner.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/01/13-excel-apply-power-query.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-blog.techidaily.com/024-approved-filmmakers-pathway-youtube-trailer-creation-with-filmora/"><u>[New] 2024 Approved  Filmmaker's Pathway  YouTube Trailer Creation with Filmora</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-step-by-step-for-sports-video-compilation/"><u>[New] Step-by-Step for Sports Video Compilation</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-unleash-premium-zoom-audio-quality-with-simple-adjustments/"><u>[Updated] 2024 Approved  Unleash Premium Zoom Audio Quality with Simple Adjustments</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-cheapest-android-calls-top-free-apps-rated/"><u>[Updated] Cheapest Android Calls  Top Free Apps Rated</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-virtual-valor-vault-excelling-with-top-adventures-in-gaming/"><u>[Updated] In 2024, Virtual Valor Vault  Excelling with Top Adventures in Gaming</u></a></li>
<li><a href="https://win-dash.techidaily.com/brother-mfc7360n-drivers-download-and-update-in-windows-1087-easily/"><u>Brother MFC7360N Drivers Download & Update in Windows 10/8/7 EASILY</u></a></li>
<li><a href="https://win-dash.techidaily.com/diagnosing-and-repairing-complications-in-realtek-rtl8811au-wireless-adapter-software-drivers/"><u>Diagnosing and Repairing Complications in Realtek RTL8811AU Wireless Adapter Software Drivers</u></a></li>
<li><a href="https://win-dash.techidaily.com/direct-download-of-updated-realtek-rtl8188cu-network-card-driver-for-pcs/"><u>Direct Download of Updated Realtek RTL8188CU Network Card Driver for PCs</u></a></li>
<li><a href="https://win-dash.techidaily.com/discover-how-to-set-up-your-behringer-usb-audio-driver-with-our-free-guide/"><u>Discover How to Set Up Your Behringer USB Audio Driver with Our Free Guide</u></a></li>
<li><a href="https://tech-revival.techidaily.com/discover-the-leading-open-source-solutions-for-artificial-intelligence-image-generation/"><u>Discover the Leading Open Source Solutions for Artificial Intelligence Image Generation</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722959693178-easy-access-to-your-msi-x470-gaming-performance-optimizers-download-here/"><u>Easy Access to Your MSI X470 Gaming Performance Optimizers - Download Here</u></a></li>
<li><a href="https://win-dash.techidaily.com/easy-guide-installing-updated-dell-thunderbolt-tb17-usb-c-adapter-drivers-on-your-pc/"><u>Easy Guide: Installing Updated Dell Thunderbolt (TB17) USB-C Adapter Drivers on Your PC</u></a></li>
<li><a href="https://howto.techidaily.com/fixing-persistent-pandora-crashes-on-lava-blaze-2-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixing Persistent Pandora Crashes on Lava Blaze 2 | Dr.fone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/from-canvas-to-cryptos-select-7-nft-creating-powerhouses/"><u>From Canvas to Cryptos  Select 7 NFT-Creating Powerhouses</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-newest-2024-update-for-hp-officejet-4500-printer-drivers-download-now/"><u>Get the Newest 2024 Update for HP OfficeJet 4500 Printer Drivers - Download Now</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-your-konica-minolta-printer-running-on-any-windows-os-free-drivers-available-here/"><u>Get Your Konica Minolta Printer Running on Any Windows OS - Free Drivers Available Here!</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-your-samsung-blu-ray-player-running-again-with-these-proven-solutions/"><u>Get Your Samsung Blu-Ray Player Running Again with These Proven Solutions</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-install-or-upgrade-brother-mfc-l2n690d-wireless-printer-drivers-guide-and-resources/"><u>How to Install or Upgrade Brother MFC-L2n690d Wireless Printer Drivers - Guide and Resources</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-corrupt-excel-workbook-by-stellar-guide/"><u>How to Repair Corrupt Excel Workbook?</u></a></li>
<li><a href="https://win-dash.techidaily.com/hp-pagewide-pro-477dw-official-driver-download-for-windows-11108-users/"><u>HP PageWide Pro 477DW - Official Driver Download for Windows 11/10/8 Users</u></a></li>
<li><a href="https://win-dash.techidaily.com/latest-amd-rx-480-gpu-drivers-free-download-installation-and-update-instructions-for-gamers/"><u>Latest AMD RX 480 GPU Drivers - Free Download, Installation & Update Instructions for Gamers</u></a></li>
<li><a href="https://win-dash.techidaily.com/latest-graphics-card-software-get-your-geforce-rtx-amoled-3090-driver-for-windows-users/"><u>Latest Graphics Card Software: Get Your GeForce RTX Amoled 3090 Driver for Windows Users!</u></a></li>
<li><a href="https://win-dash.techidaily.com/latest-nvidia-quadro-windows-1er-10-graphics-drivers-free-download-oem-and-retail/"><u>Latest Nvidia Quadro Windows 1Er 10 Graphics Drivers Free Download | OEM & Retail</u></a></li>
<li><a href="https://win-dash.techidaily.com/mediatek-usb-vcom-drivers-fast-and-simple-installation-guide/"><u>MediaTek USB VCOM Drivers: Fast & Simple Installation Guide</u></a></li>
<li><a href="https://tech-haven.techidaily.com/navigating-around-key-errors-mastering-content-creation-with-chatgpt/"><u>Navigating Around Key Errors: Mastering Content Creation with ChatGPT</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-color-correction-mastery-blending-video-clips-seamlessly-in-powerdirector/"><u>New In 2024, Color Correction Mastery Blending Video Clips Seamlessly in PowerDirector</u></a></li>
<li><a href="https://games-able.techidaily.com/pairing-ps-controllers-with-switch-console-easily/"><u>Pairing PS Controllers with Switch Console Easily</u></a></li>
<li><a href="https://win-blog.techidaily.com/pc-gaming-fixed-no-more-scavengers-crashes-a-comprehensive-guide/"><u>PC Gaming Fixed: No More Scavengers Crashes – A Comprehensive Guide</u></a></li>
<li><a href="https://win-dash.techidaily.com/quick-download-and-installation-tips-for-the-wacom-intuos-pro-driver-with-windows-11-compatibility/"><u>Quick Download and Installation Tips for the Wacom Intuos Pro Driver with Windows 11 Compatibility</u></a></li>
<li><a href="https://screen-recording.techidaily.com/screenflow-uncovered-mastering-video-editing-on-a-mac-for-2024/"><u>ScreenFlow Uncovered  Mastering Video Editing on a Mac for 2024</u></a></li>
<li><a href="https://data-wizards.techidaily.com/stars-align-stellar-rebuilding-anywhere-dbs/"><u>Stars Align: Stellar Rebuilding Anywhere DBs</u></a></li>
<li><a href="https://win-dash.techidaily.com/step-by-step-tutorial-on-downloading-and-setting-up-a-dell-mouse-driver-fix/"><u>Step-by-Step Tutorial on Downloading and Setting Up a Dell Mouse Driver Fix</u></a></li>
<li><a href="https://win-dash.techidaily.com/step-by-step-tutorial-on-refreshing-usb-drivers-for-samsung-devices/"><u>Step-by-Step Tutorial on Refreshing USB Drivers for Samsung Devices</u></a></li>
<li><a href="https://win-answers.techidaily.com/the-definitive-solution-combat-pausing-problems-and-unfreeze-your-warframe/"><u>The Definitive Solution: Combat Pausing Problems & Unfreeze Your Warframe</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/top-10-terraria-game-boosters-for-2024/"><u>Top 10 Terraria Game Boosters for 2024</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-free-video-cutting-tools-for-mp4-expert-approved-options-for-2024/"><u>Updated Free Video Cutting Tools for MP4 Expert-Approved Options for 2024</u></a></li>
<li><a href="https://win-dash.techidaily.com/upgrade-your-pcs-performance-with-new-sata-driver-downloads-and-setup-on-windows/"><u>Upgrade Your PC's Performance with New SATA Driver Downloads and Setup on Windows</u></a></li>
</ul></div>
