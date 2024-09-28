---
title: Optimizing VBA Code for Lower CPU Consumption in MS Excel Applications
date: 2024-08-28T01:35:19.731Z
updated: 2024-08-29T01:35:19.731Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/01/how-do-you-limit-microsoft-excels-cpu-usage-when-running-vba-functions-00.jpg
---

## Optimizing VBA Code for Lower CPU Consumption in MS Excel Applications

### Quick Links

* [The Question](https://facebook-video-footage.techidaily.com/updated-in-2024-channel-success-strategy-standard-studio-or-beta-edge/)
* [The Answer](https://desktop-recording.techidaily.com/new-innovative-ways-to-record-without-background-sounds-for-2024/)

 If you have a VBA function that turns Microsoft Excel into a CPU munching beast, is it possible to tame things down so that you can continue to use your computer for other activities while Excel is finishing up? Today's SuperUser Q&A post comes to the rescue to help a frustrated reader get Excel back under control.

 Today’s Question & Answer session comes to us courtesy of SuperUser—a subdivision of Stack Exchange, a community-driven grouping of Q&A web sites.

 Alien warrior clip art courtesy of [Clker.com](http://www.clker.com/clipart-alien-warrior.html).

##  The Question

 SuperUser reader learningAsIGo wants to know if there is a way to limit Microsoft Excel's CPU usage while running a VBA script on his computer:

> Is there a way to limit Microsoft Excel's CPU usage when it is running? I have a VBA script that calculates a large amount of giant array formulas. The entire set of calculations takes approximately twenty minutes to complete and uses 100 percent of my CPU. I am unable to use my computer during this time and would rather have Excel 'running in the background' while using about 50 percent of my CPU's capacity so that I can continue to do other things.
> 
> Any suggestions? My computer's operating system is Windows 7 Enterprise 64-bit with a 2007 32-bit version of Excel installed on it.

 Is there a way to limit Microsoft Excel's CPU usage while running VBA functions?

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633309&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/3_premium-icon.png" border="0"> Take advantage of PREMIUM features for 12 months. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Yearly Membership</a>
<!-- affiliate ads end -->
##  The Answer

 SuperUser contributor mtone has the answer for us:

> If a VBA function is called from several formulas or if your script generates or forces the recalculation of several formulas, then this should definitely make use of the multi-threaded calculation feature in Microsoft Excel. Respectively, this would either run multiple instances of your VBA function for each formula, or recalculate multiple cells simultaneously while your VBA script is running on a single thread.
> 
> You can limit the number of threads used by Excel to recalculate formulas by going to Options and selecting the Advanced Section, then scrolling down until you reach the Formulas sub-section.
> 
> ![how-do-you-limit-microsoft-excels-cpu-usage-when-running-vba-functions-01](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/01/how-do-you-limit-microsoft-excels-cpu-usage-when-running-vba-functions-01.jpg) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
---

 Have something to add to the explanation? Sound off in the comments. Want to read more answers from other tech-savvy Stack Exchange users? [Check out the full discussion thread here](http://superuser.com/questions/1025428/limit-excel-cpu-usage).

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


