---
title: "Mastering Conditional Logic: A Step-by-Step Guide to Utilizing the IFS Formula in Excel"
date: 2024-08-28T01:35:10.828Z
updated: 2024-08-29T01:35:10.828Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/f1294d51d8e0560c6776b360116bd819890055c0bb65c23b15603692f6dffac9.jpg
---

## Mastering Conditional Logic: A Step-by-Step Guide to Utilizing the IFS Formula in Excel

### Quick Links

* [Use the IFS Function in Excel](https://extra-lessons.techidaily.com/eliminating-oculus-sickness-key-tactics/)

 If you're familiar with using the IF function in Excel, then you might be ready to check out the IFS function. With it, you can test multiple conditions at once, instead of using nested IF statements.

 Using IFS, you can test up to 127 conditions in a single Excel formula. Although this number of tests is probably much more than you need, the [function](https://games-able.techidaily.com/is-premium-play-on-demand-worth-it/) is ideal for checking several conditions. The formula then returns the value you specify for the first true condition in the statement.

##  Use the IFS Function in Excel

 The syntax for the function is 

        `IFS(test1, if_true1, test2, if_true2,...)`
    
 where you enter the condition for each 

        `test`
    
 argument and the value to return if the test is true for each 

        `true`
    
 argument.

 Let's look at a few basic examples.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BConverter%2BBox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/8020c1dc-518e-3bdf-6e7b-e6d1bdf1597b.jpg" border="0"></a>
<!-- affiliate ads end -->
###  Return Cell Reference Values

 Here, the condition looks at the ID number in cell C2\. When the formula finds the matching condition, 1 through 5, it returns the corresponding name.

=IFS(C2=1,A2,C2=2,A3,C2=3,A4,C2=4,A5,C2=5,A6)

 To break down the formula, if the value in cell C2 is 1, return the value in A2, if it's 2, return the value in A3, if it's 3, return the value in A4, if it's 4, return the value in A5, and if it's 5, return the value in A6.

![IFS function with cell reference value results](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/CellReferenceValue-ExcelIFSFunction.png) 

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=38658749&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/pa_500.png" border="0">ZoneAlarm Pro Antivirus + Firewall NextGen</a>
<!-- affiliate ads end -->
 If you were to use a nested IF statement instead of the IFS function, your formula would look like this:

=IF(C2=1,A2,IF(C2=2,A3,IF(C2=3,A4,IF(C2=4, A5,IF(C2=5,A6)))))

 While you obtain the same result using either option, the formula for the IFS function is a little less confusing and doesn't take as much time [to assemble](https://youtube-docs.techidaily.com/n-2024-automate-playlist-retrieval-from-youtube-directly/).

![Nested IF statement for cell reference value results](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/CellReferenceValueNested-ExcelIFSFunction.png) 

Related: [The Basics of Structuring Formulas in Microsoft Excel](https://youtube-docs.techidaily.com/n-2024-automate-playlist-retrieval-from-youtube-directly/) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
###  Return Numbers

 For another IFS example, we'll apply bonuses to our salespeople based on their sales totals. Here's the formula:

=IFS(F2>100000,1000,F2>75000,750,F2>50000,500)

 To break down this formula, if the total in cell F2 is greater than 100,000, return 1,000, if it's greater than 75,000, return 750, and if it's greater than 50,000, return 500.

![IFS function with number results](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/Number-ExcelIFSFunction.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
<!-- affiliate ads end -->
 You can use the fill handle to [copy the same IFS formula](https://extra-tips.techidaily.com/in-2024-converting-personal-memories-from-stillness-to-motion/) to adjacent cells.

 To compare again, here is what the formula looks like as a nested IF statement instead:

=IF(F2>100000,1000,IF(F2>75000,750,IF(F2>50000,500)))

 By using the formula for the IFS function, you eliminate the need to repeatedly type IF with an opening parenthesis and remember the correct number of closing parentheses at the end.

![Nested IF statement for number results](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/NumberNested-ExcelIFSFunction.png) 

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633309&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/3_premium-icon.png" border="0"> Take advantage of PREMIUM features for 12 months. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Yearly Membership</a>
<!-- affiliate ads end -->
###  Return Text Values

 In this next example, we have a list of employees who haven't finished their training. We'll display [a text result](https://video-screen-grab.techidaily.com/updated-the-art-of-smooth-video-transitioning-for-2024/) based on the percent complete in cell B2\. Note that the text values must be in quotes.

=IFS(B2<50,"Less than half",B2=50,"Half",B2>50,"More than half")

 To break down this formula, if the value in cell B2 is less than 50, return "Less than half," if it equals 50, return "Half," and if it's more than 50, return "More than half."

![IFS function with text results](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/TextValue-ExcelIFSFunction.png) 

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 For one more comparison, here is what the nested IF statement looks like to obtain the same result:

=IF(B2<50,"Less than half",IF(B2=50,"Half",IF(B2>50,"More than half")))

 It can be especially difficult to troubleshoot [formulas errors](https://extra-lessons.techidaily.com/step-into-premium-sound-quality-garageband-edition/) in lengthy statements or those that needs extra care like including quotation marks. This is just one more reason to consider using the IFS function instead of a nested IF formula.

![Nested IF statement for text results](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/TextValueNested-ExcelIFSFunction.png) 

 As [Microsoft explains](https://support.microsoft.com/en-us/office/if-function-nested-formulas-and-avoiding-pitfalls-0b22ff44-f149-44ba-aeb5-4ef99da241c8):

> Multiple IF statements require a great deal of thought to build correctly and make sure that their logic can calculate correctly through each condition all the way to the end. If you don't nest your formula 100% accurately, then it might work 75% of the time, but return unexpected results 25% of the time.

 Microsoft goes on to say that nested IF statements can be hard to maintain. This is another consideration for using the IFS function, especially if you're [working on your spreadsheet with others](https://instagram-video-files.techidaily.com/2024-approved-a-step-by-step-approach-for-flawless-instagrams/).

 When you want to test several conditions for a cell, or even a cell range, consider using the IFS function. For more, learn how to use the other [logical functions in Excel like AND, OR, and XOR](https://extra-skills.techidaily.com/in-2024-spark-engagement-the-ultimate-list-of-video-text-effects/).

| |  Mastering Excel Functions |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |  |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |  |
| Functions                    | [AVERAGE](https://win-able.techidaily.com/fixing-overwatch-startup-issues-how-to-get-rid-of-the-persistent-black-screen/) **·** [CONCATENATE](https://fake-location.techidaily.com/is-pgsharp-legal-when-you-are-playing-pokemon-on-xiaomi-redmi-13c-5g-drfone-by-drfone-virtual-android/) **·** [COUNT](https://android-location-track.techidaily.com/how-to-track-a-lost-xiaomi-redmi-note-12t-pro-for-free-drfone-by-drfone-virtual-android/) **·** [COUNTIF](https://win-forum.techidaily.com/complete-tutorial-clearing-out-windows-10-memory-dump-data/) **·** [DATEDIF](https://youtube-data.techidaily.com/n-2024-explore-the-best-historian-content-top-10-youtube-recommendations/) **·** [FILTER](https://youtube-sure.techidaily.com/024-approved-the-ultimate-guide-to-youtube-live-streaming/) **·** [FREQUENCY](https://digital-screen-recording.techidaily.com/new-ideal-low-impact-recording-devices-for-eco-conscious-filmmakers/) **·** [FV](https://on-screen-recording.techidaily.com/updated-2024-approved-enhancing-gaming-experience-with-steam-switch-control/) **·** [HYPERLINK](https://some-guidance.techidaily.com/updated-the-minimalists-guide-to-aerial-imagery-with-dji-spark/) **·** [IF](https://android-unlock.techidaily.com/in-2024-how-to-use-google-assistant-on-your-lock-screen-of-huawei-phone-by-drfone-android/) **·** [IFS](https://screen-recording.techidaily.com/updated-ultimate-techniques-for-precise-iptv-screen-imaging/) **·** [IMAGE](https://screen-mirror.techidaily.com/top-10-airplay-apps-in-xiaomi-redmi-note-12-5g-for-streaming-drfone-by-drfone-android/) **·** [INDEX](https://youtube-help.techidaily.com/in-2024-the-full-course-on-becoming-a-yt-creator-expert/) **·** [IS](https://win-amazing.techidaily.com/new-release-gtx-1650-super-driver-updates-compatible-with-windows-11/) **·** [LEN](https://extra-hints.techidaily.com/scalable-and-stylish-type-in-ae-with-top-choices/) **·** [MATCH](https://extra-guidance.techidaily.com/mirthful-missions-delving-into-the-goofy-movie-vhs-for-2024/) **·**[MEDIAN](https://some-techniques.techidaily.com/in-2024-from-novice-to-expert-the-complete-powerdirector-journey/) **·** [RAND](https://instagram-video-recordings.techidaily.com/updated-master-igtv-edits-top-10-tools-ranked/) **·** [ROUND](https://youtube-zero.techidaily.com/ed-2024-approved-the-quick-pathway-to-establishing-a-video-channel-on-your-phone/) **·** [RRI](https://vp-tips.techidaily.com/2024-approved-quick-cash-on-reddit-here-are-13-ways-for-new-users/) **·** [SORT](https://some-techniques.techidaily.com/2024-approved-gopro-versus-polaroid-editing-faces-vs-cameras-that-shoot-them/) **·** [SQRT](https://screen-video-capture.techidaily.com/in-2024-master-guide-ultimate-tips-for-maximizing-mobizens-screen-capture/) **·** [SUBSTITUTE](https://screen-sharing-recording.techidaily.com/updated-maiden-shoot-revelations-and-critique-for-2024/) **·** [SUBTOTAL](https://phone-solutions.techidaily.com/in-2024-prank-your-friends-easy-ways-to-fake-and-share-google-maps-location-on-oppo-a78-5g-drfone-by-drfone-virtual-android/) **·** [SUM](https://instagram-videos.techidaily.com/updated-steps-to-instagram-verification-and-fan-growth-in-under-150-characters/) **·** [SUMIF](https://on-screen-recording.techidaily.com/pinnacle-platforms-transforming-online-interaction/) **·** [TODAY](https://some-guidance.techidaily.com/2024-approved-unlock-spark-ars-full-potential-with-personalized-lut-implementations/) **·** [TRIM](https://graphic-issues.techidaily.com/regaining-access-to-nvidia-writable-displays/) **·** [TRUNC](https://windows11.techidaily.com/balancing-cpu-and-memory-use-after-news-downloads/) **·** [VLOOKUP](https://extra-tips.techidaily.com/integrate-sound-and-sight-web-studio/) **·** [WEEKDAY](https://youtube-tips.techidaily.com/n-2024-virtual-voyage-youtubes-premier-10-vr-video-experience/) **·** [XLOOKUP](https://android-transfer.techidaily.com/in-2024-5-ways-to-transfer-music-from-asus-rog-phone-7-ultimate-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/) **·** [YEAR](https://facebook-record-videos.techidaily.com/updated-in-2024-captivating-content-the-basics-of-removing-background-from-videos/) |  |
| Types                        | [Basic](https://visual-screen-recording.techidaily.com/in-2024-a-step-by-step-recorder-for-discord-enthusiasts/) **·** [Budgeting](https://easy-unlock-android.techidaily.com/in-2024-how-to-reset-a-realme-narzo-60-pro-5g-phone-that-is-locked-by-drfone-android/) **·** [Data Entry](https://vimeo-videos.techidaily.com/in-2024-high-end-downloads-best-10-apps-for-extracting-vimeo-videos/) **·** [Logical](https://extra-skills.techidaily.com/in-2024-spark-engagement-the-ultimate-list-of-video-text-effects/) **·** [Text](https://video-screen-grab.techidaily.com/updated-the-art-of-smooth-video-transitioning-for-2024/) **·** [Time and Date](https://extra-lessons.techidaily.com/kickstart-your-telegram-promotion-journey-tips-for-newbies/)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |  |
| Explained                    | [Copying Formulas](https://extra-tips.techidaily.com/in-2024-converting-personal-memories-from-stillness-to-motion/) **·** [Evaluating Formulas](https://youtube-blog.techidaily.com/ed-the-role-of-youtube-images-in-video-promotion-and-discovery-for-2024/) **·** [Finding Functions](https://win11.techidaily.com/renaissance-pc-refresh-with-atlasos/) **·** [Fixing Formula Errors](https://extra-lessons.techidaily.com/step-into-premium-sound-quality-garageband-edition/) **·** [Functions vs Formulas](https://games-able.techidaily.com/is-premium-play-on-demand-worth-it/) **·** [Comparing Lookup Functions](https://tech-revival.techidaily.com/examining-codegpts-capabilities-in-tech-innovation/) **·** [Locking Formulas](https://some-guidance.techidaily.com/in-2024-unveiling-effective-sales-methods/) **·** [Structuring Formulas](https://youtube-docs.techidaily.com/n-2024-automate-playlist-retrieval-from-youtube-directly/) **·** [Translating Formulas](https://extra-tips.techidaily.com/techniques-to-reduce-nausea-while-in-vr/)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |  |

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


