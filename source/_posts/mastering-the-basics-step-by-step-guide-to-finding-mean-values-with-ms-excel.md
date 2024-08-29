---
title: "Mastering the Basics: Step-by-Step Guide to Finding Mean Values with MS Excel"
date: 2024-08-28T01:30:43.892Z
updated: 2024-08-29T01:30:43.892Z
tags:
  - windows
categories:
  - tech
thumbnail: https://thmb.techidaily.com/c6867ae9c4f4e3df3c9379b15f4163ebd35319a50b7aab7a2fe4029be64b0298.jpg
---

## Mastering the Basics: Step-by-Step Guide to Finding Mean Values with MS Excel

### Quick Links

* [How Many Average Functions Are There in Excel?](https://instagram-video-files.techidaily.com/updated-in-2024-rapid-route-learning-the-ins-and-outs-of-insta-talks/)
* [How to Use AVERAGE in Excel](https://data-safeguard.techidaily.com/photoshop-cs8-installation-tutorial-for-windows-users-start-editing/)
* [How to Use AVERAGEA in Excel](https://android-location-track.techidaily.com/in-2024-best-anti-tracker-software-for-huawei-p60-drfone-by-drfone-virtual-android/)
* [How to Use AVERAGEIF in Excel](https://program-issues.techidaily.com/solving-the-mystery-a-step-by-step-guide-to-resolve-dev-error-6034-on-pc-and-xbox/)
* [How to Use AVERAGEIFS in Excel](https://extra-hints.techidaily.com/slowly-quieting-tracks-with-fl-studio/)

 Excel has hundreds of functions that can help you to quickly and accurately perform calculations, among which are the AVERAGE functions. You might want to calculate the average sales figures, get the average of a group of data that contains numbers and text, or work out the average of all student scores over a certain number.

##  How Many Average Functions Are There in Excel?

 There are four AVERAGE functions and each has different uses:

* **AVERAGE**: This produces the arithmetic mean (the sum of all numbers divided by the number of values) of a set of data, ignoring anything that isn't a number.
* **AVERAGEA**: This returns the mean of a set of numbers, text, and logical arguments.
* **AVERAGEIF**: This calculates the arithmetic mean of a set of numerical data that fulfill a single criterion.
* **AVERAGEIFS**: This tells you the arithmetic mean of a set of numerical data that fulfill several criteria.

 Let's explore these in more detail.

<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  How to Use AVERAGE in Excel

 To calculate the average in Excel, use the following syntax:

=AVERAGE(A,B)

 where A is the first number, cell reference, or range, and B is up to a maximum of 255 additional numbers, cell references, or ranges to include in the average calculation.

 In this example, we have a set of seven students and want to calculate their average exam score.

![Excel sheet showing a table with two columns: column A contains student names and column B contains their exam scores. Next to this table is an 'average' cell, where their average scores will be calculated using the AVERAGE function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/average-uncalculated.png) 

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 As you can see, Student C scored 0 and Student F has yet to take the exam. As a result, we want Excel to work out the scores of those who have taken the exam (all students except for Student F).

 To do this, we would type the following formula into cell D2:

=AVERAGE(B2:B8)

![Excel sheet showing a table with two columns: column A contains student names and column B contains their exam scores. Next to this table is an 'average' cell, where their average scores has been calculated using the AVERAGE function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/average-calculated-1.png) 

 The AVERAGE function includes 0 within its calculations, but ignores all empty cells, text, and logical values (TRUE or FALSE). So, we can be confident that this calculation will include Student C's score, but ignore Student F's score.

 If any of the values being used in the AVERAGE calculation were to contain [one of Excel's formula errors](https://extra-lessons.techidaily.com/step-into-premium-sound-quality-garageband-edition/), the calculation would not work.

 To save time, you can instead calculate the average through a few simple clicks. First, select your data to average, click the "Home" tab on the ribbon, and in the "Editing" group, click on the drop-down arrow next to the sigma (Σ) symbol. From there, click "Average". The result will appear at the end of your data.

##  How to Use AVERAGEA in Excel

 AVERAGEA works in a very similar way to AVERAGE, but includes more than just numbers within the calculation. Here's the syntax for this function:

=AVERAGE(A,B)

 where A is the first value (including numbers, logical values such as TRUE or FALSE, and text), and B is up to a maximum of 255 additional values to include in the average calculation.

 The AVERAGEA function is useful if you have a mixed set of data containing numbers, logical values, and text, and you want to include them all within your calculation.

 Taking the same set of data that we used in the example above, we now want to work out the average using AVERAGEA.

![Excel sheet showing a table with two columns: column A contains student names and column B contains their exam scores. Next to this table is the average of the scores, calculated using AVERAGE, and a space where their average scores will be calculated using the AVERAGEA function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/averagea-uncalculated.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 In cell D5, we would type the following formula:

=AVERAGEA(B2:B8)

![Excel sheet showing a table with two columns: column A contains student names and column B contains their exam scores. Next to this table is the average of the scores, calculated using AVERAGE, and their average scores, calculated using the AVERAGEA function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/averagea-calculated.png) 

 Unlike the AVERAGE function, which ignores logical values, the AVERAGEA calculation includes FALSE within the calculation as 0\. If this were instead TRUE, this would be counted as 1\. As a result, in our example, Student C's score of 0 is included, and Student F is also calculated as having scored 0\. This is why the result is lower for this calculation than the previous one.

 AVERAGEA counts any other text as 0 (for example, if you type FOUR, this is still represented as 0, and not 4), and ignores empty cells.

 As with AVERAGE, if any of the values being used in the AVERAGEA calculation were to contain [one of Excel's formula errors](https://extra-lessons.techidaily.com/step-into-premium-sound-quality-garageband-edition/), the calculation would return an error.

##  How to Use AVERAGEIF in Excel

 AVERAGEIF effectively performs two calculations in one go, first identifying data that meet a certain criterion before then finding the average of these data. AVERAGEIF uses the following syntax:

=AVERAGEIF(A,B,C)

 where A is the range of values or cells to include in the average, B is the criterion, and C (optional) is the actual set of cells to average. Confusing? Let's look at this example.

 We want to work out two things from this table. First, we want to find the average score of all students who scored more than 10 in the exam, and second, we want to work out the average scores of all students over 12 years of age.

![Excel sheet showing a table with three columns: column A contains student names, column B contains their exam scores, and column C contains their ages. Next to this table are cells where the AVERAGEIF functions will be tested.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/averageif-uncalculated.png) 

 To work out the average score of all students who scored more than 10, we would use the following formula:

=AVERAGEIF(B2:B8,">10")

 Notice two things in this formula. First, the criteria must always be enclosed in double quotes. Second, we've only included two arguments within the parentheses, as there's no need to refer to any other data elsewhere within our calculation.

![Excel sheet showing a table with three columns: column A contains student names, column B contains their exam scores, and column C contains their ages. Next to this table, the first AVERAGEIF calculation has been performed.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/averageif-calculated-1.png) 

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 This has correctly picked up the scores of Students A, B, D, and E, as these are all more than 10.

 To work out the average scores of all students over 12 years of age, we would use the following formula:

=AVERAGEIF(C2:C8,">12",B2:B8)

 Notice the difference between the two formulas. Where the previous calculation contained two arguments, this one contains three, as we are assessing two sets of data.

 The "C2:C8" part of the formula tells Excel to look in that range (the students' ages) for the criteria, the ">12" part tells Excel to identify any values over 12 in the C2:C8 range (the students' ages), and "B2:B8" (the students' scores) is the part being averaged.

![Excel sheet showing a table with three columns: column A contains student names, column B contains their exam scores, and column C contains their ages. Next to this table, both AVERAGEIF calculations have been performed.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/averageif-calculated-2-1.png) 

 This has correctly picked up the scores of Students A, B, D, and E, as they are all over 12 years of age. The calculation also ignores logical values, which is why it hasn't considered Student F, even though they are over 12 years old.

 The criteria used in AVERAGEIF can use one of Excel's six logical operators—these are > (greater than), < (less than), = (equal to), <= (less than or equal to), >= (greater than or equal to), or <> (not equal to)—and wildcards (\* and ?). If you want to include an actual question mark or asterisk, add a tilde (\~) before the character.

<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  How to Use AVERAGEIFS in Excel

 The AVERAGEIFs function allows you to include several criteria to assess before calculating the average. It works using the following syntax:

=AVERAGEIFS(A,B,C)

 where A identifies the cells to average, B is the cells used to identify the criteria, and C is the criteria. There can be up to 127 criteria, so multiple pairs of cells (B) and criteria (C) can be used.

 Take this example, where we want to work out the exam scores of students in Green House over the age of 10.

![Excel sheet showing a table with four columns: column A contains student names, column B contains their exam scores, column C contains their house, and column D contains their age. Next to this table is a cell where AVERAGEIFS will be performed.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/averageifs-uncalculated.png) 

<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 To do this, we would use the following formula:

=AVERAGEIFS(B2:B8,C2:C8,"Green",D2:D8,">10")

 "B2:B8" contains the data to be averaged (the students' scores), "C2:C8" is the first range to be tested with the criterion of "Green" (the student's house), and "D2:D18" is the second range to be tested with the criterion of ">10" (the student's age).

![Excel sheet showing a table with four columns: column A contains student names, column B contains their exam scores, column C contains their house, and column D contains their age. Next to this table is a cell where an AVERAGEIFS calculation has been performed.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/averageifs-calculated-1.png) 

 This has correctly averaged the scores of Students D and G, as they are both in Green House and are over 10 years old.

 Other things to note about AVERAGEIFS:

* TRUE is counted as 1, and FALSE is counted as 0.
* In the criteria, you can use a question mark (?) as a wildcard to match any single character, or an asterisk (\*) as a wildcard to match any sequence of characters. Use a tilde (\~) before the character if you're looking to identify an actual question mark or asterisk.

---

 As well as using AVERAGEIF and AVERAGEIFS, you can [sort and filter data in Excel](https://facebook-video-share.techidaily.com/free-audio-treasures-to-amplify-youtube-in-2024/) to only show certain figures within your tables.

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
<li><a href="https://facebook-record-videos.techidaily.com/new-creating-continuous-viewing-pleasure-on-television-for-2024/"><u>[New] Creating Continuous Viewing Pleasure on Television for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-maximizing-obs-broadcasts-to-facebook-feed/"><u>[New] In 2024, Maximizing OBS Broadcasts to Facebook Feed</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-budding-creators-set-up-a-profitable-youtube-chanel/"><u>[Updated] 2024 Approved  Budding Creators  Set Up a Profitable YouTube Chanel</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-essential-hashtag-analyzers-facebook-twitter-and-instagram-edition/"><u>[Updated] In 2024, Essential Hashtag Analyzers  Facebook, Twitter & Instagram Edition</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-gadget-guidance-getting-into-googles-video-conference/"><u>[Updated] In 2024, Gadget Guidance  Getting Into Google's Video Conference</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-next-level-immersion-top-10-innovative-pc-vr-headsets-for-360-views/"><u>2024 Approved  Next-Level Immersion  Top 10 Innovative PC VR Headsets for 360 Views</u></a></li>
<li><a href="https://android-unlock.techidaily.com/7-ways-to-unlock-a-locked-htc-u23-phone-by-drfone-android/"><u>7 Ways to Unlock a Locked HTC U23 Phone</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722966902576-a-decision-must-cause-harm-to-someone/"><u>A Decision Must Cause Harm to Someone</u></a></li>
<li><a href="https://win-dash.techidaily.com/amd-radeon-rx-470-drivers-upgrade-step-by-step-guide-for-a-smooth-graphics-performance/"><u>AMD Radeon RX 470 Drivers Upgrade - Step-by-Step Guide for a Smooth Graphics Performance</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/best-performing-8-recording-software-picks/"><u>Best Performing 8 Recording Software Picks</u></a></li>
<li><a href="https://win-dash.techidaily.com/boost-performance-now-overclock-the-nvidia-rtx-3090-for-ultimate-gaming-thrills/"><u>Boost Performance Now: Overclock the NVIDIA RTX 3090 for Ultimate Gaming Thrills</u></a></li>
<li><a href="https://win-dash.techidaily.com/complete-guide-to-downloading-and-installing-focusrite-scarlett-2i4-drivers-for-windows-computers/"><u>Complete Guide to Downloading & Installing Focusrite Scarlett 2I4 Drivers for Windows Computers</u></a></li>
<li><a href="https://win-dash.techidaily.com/comprehensive-guide-fixing-intel-vga-driver-problems-for-windows-users/"><u>Comprehensive Guide: Fixing Intel VGA Driver Problems for Windows Users</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-and-update-ch340g-serial-port-drivers-for-windows-11/"><u>Download & Update CH340G Serial Port Drivers for Windows 11</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722978110006-download-m-audio-fast-track-drivers-compatible-with-windows-117881-get-your-audio-setup-ready/"><u>Download M-Audio Fast Track Drivers Compatible with Windows 11/7/8/8.1 – Get Your Audio Setup Ready!</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-latest-epson-xp-440-drivers-instantly-a-step-by-step-guide/"><u>Get the Latest Epson XP-440 Drivers Instantly – A Step-by-Step Guide</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722978284224-get-your-sound-blaster-audigy-latest-drivers-available-here/"><u>Get Your Sound Blaster Audigy - Latest Drivers Available Here</u></a></li>
<li><a href="https://win-dash.techidaily.com/how-to-successfully-update-and-repair-intel-hd-graphics-card-drivers-in-windows/"><u>How to Successfully Update and Repair Intel HD Graphics Card Drivers in Windows</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-after-switching-from-oppo-k11-5g-to-latest-samsung-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data After Switching From Oppo K11 5G to Latest Samsung | Dr.fone</u></a></li>
<li><a href="https://win-dash.techidaily.com/hp-scanjet-drivers-update-enhanced-functionality-for-windows-users-download/"><u>HP Scanjet Drivers Update: Enhanced Functionality for Windows Users [Download]</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-10-indispensable-fcp-enhancing-plugins/"><u>In 2024, 10 Indispensable FCP-Enhancing Plugins</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-best-anti-tracker-software-for-oneplus-nord-n30-se-drfone-by-drfone-virtual-android/"><u>In 2024, Best Anti Tracker Software For OnePlus Nord N30 SE | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-which-ones-right-for-you-obs-or-twitch-studio-reviewed/"><u>In 2024, Which One's Right for You? - OBS or Twitch Studio Reviewed</u></a></li>
<li><a href="https://win-dash.techidaily.com/install-the-right-epson-stylus-nx420-printer-driver-on-windows-7-8-or-10-expert-tips-and-tricks/"><u>Install the Right Epson Stylus NX420 Printer Driver on Windows 7, 8 or 10: Expert Tips & Tricks</u></a></li>
<li><a href="https://win-dash.techidaily.com/latest-techniques-for-enhancing-wi-fi-connectivity-with-driver-updates-in-windows-1110/"><u>Latest Techniques for Enhancing Wi-Fi Connectivity with Driver Updates in Windows 11/10</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/melodic-milestones-unveiling-top-sources-for-harmonious-opens/"><u>Melodic Milestones  Unveiling Top Sources for Harmonious Opens</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-from-snapshots-to-masterpieces-best-online-photo-and-video-collage-creators/"><u>New In 2024, From Snapshots to Masterpieces Best Online Photo and Video Collage Creators</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/quick-fix-update-your-windows-10-drivers-with-these-simple-steps/"><u>Quick Fix: Update Your Windows 10 Drivers with These Simple Steps</u></a></li>
<li><a href="https://win-dash.techidaily.com/seamless-logitech-driver-setup-top-methods-for-windows-operating-systems/"><u>Seamless Logitech Driver Setup – Top Methods for Windows Operating Systems</u></a></li>
<li><a href="https://win-dash.techidaily.com/seamless-update-of-canon-printerscanner-drivers-on-microsoft-windows-tips-and-tricks/"><u>Seamless Update of Canon Printer/Scanner Drivers on Microsoft Windows: Tips and Tricks</u></a></li>
<li><a href="https://win-dash.techidaily.com/solving-driver-problems-with-your-hp-officejet-pro-6978-printer/"><u>Solving Driver Problems with Your HP OfficeJet Pro 6978 Printer</u></a></li>
<li><a href="https://win-dash.techidaily.com/the-perfect-walkthrough-to-download-and-install-soundmax-for-windows-users/"><u>The Perfect Walkthrough to Download and Install SoundMax for Windows Users</u></a></li>
<li><a href="https://win-dash.techidaily.com/toshiba-satellite-drivers-download-and-update-in-windows/"><u>Toshiba Satellite Drivers Download and Update in Windows</u></a></li>
<li><a href="https://tech-revival.techidaily.com/transform-your-data-analysis-with-these-6-techniques-using-chatgpt/"><u>Transform Your Data Analysis with These 6 Techniques Using ChatGPT</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/standing-and-proficiently-implementing-cc-copyrights-for-2024/"><u>Understanding and Proficiently Implementing CC Copyrights for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/unlocking-the-secrets-to-effective-screen-capturing-with-apeaksoft-for-2024/"><u>Unlocking the Secrets to Effective Screen Capturing with Apeaksoft for 2024</u></a></li>
<li><a href="https://win-dash.techidaily.com/update-your-razer-devices-easily-with-compatible-drivers-in-windows-os-10-8-7-xp-and-vista/"><u>Update Your Razer Devices Easily with Compatible Drivers in Windows OS (10, 8, 7, XP & Vista)</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/video-talk-with-ease-how-to-utilize-whatsapp-web-on-your-notebook/"><u>Video Talk with Ease  How to Utilize WhatsApp Web on Your Notebook</u></a></li>
</ul></div>
