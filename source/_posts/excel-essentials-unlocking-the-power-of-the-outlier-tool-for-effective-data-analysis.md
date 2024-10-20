---
title: "Excel Essentials: Unlocking the Power of the Outlier Tool for Effective Data Analysis"
date: 2024-10-13T17:39:22.732Z
updated: 2024-10-20T17:20:12.525Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/f7c3dfb51630ea312d0721a61ab19847e1113bba58f7b17ac94759c2d0864364.jpg
---

## Excel Essentials: Unlocking the Power of the Outlier Tool for Effective Data Analysis

### Quick Links

* [A Quick Example](https://sound-issues.techidaily.com/how-to-fix-windows-speaker-sound-distortion-issue/)
* [How to Find Outliers in your Data](https://some-techniques.techidaily.com/hands-on-crafting-unique-movie-closures-for-pennies-for-2024/)
* [Ignoring the Outliers when Calculating the Mean Average](https://screen-sharing-recording.techidaily.com/new-essential-techniques-for-recording-and-preserving-itunes-videos-for-2024/)

## 

 An outlier is a value that is significantly higher or lower than most of the values in your data. When using Excel to analyze data, outliers can skew the results. For example, the mean average of a data set might truly reflect your values. Excel provides a few useful functions to help manage your outliers, so let's take a look.

##  A Quick Example

 In the image below, the outliers are reasonably easy to spot---the value of two assigned to Eric and the value of 173 assigned to Ryan. In a data set like this, it's easy enough to spot and deal with those outliers manually.

![Range of values containing outliers](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/dataset-border.png) 

 In a larger set of data, that will not be the case. Being able to identify the outliers and remove them from statistical calculations is important---and that's what we'll be looking at how to do in this article.

##  How to Find Outliers in your Data

 To find the outliers in a data set, we use the following steps:

1. Calculate the 1st and 3rd quartiles (we'll be talking about what those are in just a bit).
2. Evaluate the interquartile range (we'll also be explaining these a bit further down).
3. Return the upper and lower bounds of our data range.
4. Use these bounds to identify the outlying data points.

 The cell range on the right of the data set seen in the image below will be used to store these values.

![Range for quartiles](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/quartile-cells-border.png) 

 Let's get started.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130875/7443" target="_top" id="2130875">
  <img src="//a.impactradius-go.com/display-ad/7443-2130875" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130875/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

###  Step One: Calculate the Quartiles

 If you divide your data into quarters, each of those sets is called a quartile. The lowest 25% of numbers in the range make up the 1st quartile, the next 25% the 2nd quartile, and so on. We take this step first because the most widely-used definition of an outlier is a data point that is more than 1.5 interquartile ranges (IQRs) below the 1st quartile, and 1.5 interquartile ranges above the 3rd quartile. To determine those values, we first have to figure out what the quartiles are.

 Excel provides a QUARTILE function to calculate quartiles. It requires two pieces of information: the array and the quart.

=QUARTILE(array, quart)

 The array is the range of values that you are evaluating. And the quart is a number that represents the quartile you wish to return (e.g., 1 for the 1st quartile, 2 for the 2nd quartile, and so on).

**Note:** In Excel 2010, Microsoft released the QUARTILE.INC and QUARTILE.EXC functions as improvements to the QUARTILE function. QUARTILE is more backward compatible when working across multiple versions of Excel.

 Let's return to our example table.

![Range for quartiles](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/quartile-cells-border.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135395/19272" target="_top" id="2135395">
  <img src="//a.impactradius-go.com/display-ad/19272-2135395" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135395/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To calculate the 1st Quartile we can use the following formula in cell F2.

=QUARTILE(B2:B14,1)

 As you enter the formula, Excel provides a list of options for the quart argument.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/quartile-with-border-1.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049378/7443" target="_top" id="2049378">
  <img src="//a.impactradius-go.com/display-ad/7443-2049378" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049378/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 To calculate the 3rd quartile, we can enter a formula like the previous one in cell F3, but using a three instead of a one.

=QUARTILE(B2:B14,3)

 Now, we've got the quartile data points displayed in the cells.

![1st and 3rd quartile values](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/1st-and-3rd-quartiles-border.png) 

<!-- affiliate ads begin -->
<span id="1983473">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983473.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983473">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983473.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983473%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983473/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

###  Step Two: Evaluate the Interquartile Range

 The interquartile range (or IQR) is the middle 50% of values in your data. It is calculated as the difference between the 1st quartile value and the 3rd quartile value.

 We're going to use a simple formula into cell F4 that subtracts the 1st quartile from the 3rd quartile:

=F3-F2

 Now, we can see our interquartile range displayed.

![Interquartile value](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/iqr-border.png) 

###  Step Three: Return the Lower and Upper Bounds

 The lower and upper bounds are the smallest and largest values of the data range that we want to use. Any values smaller or larger than these bound values are the outliers.

 We'll calculate the lower bound limit in cell F5 by multiplying the IQR value by 1.5 and then subtracting it from the Q1 data point:

=F2-(1.5*F4)

![Excel formula for lower bound value](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/l-bound-border.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1902273/19272" target="_top" id="1902273">
  <img src="//a.impactradius-go.com/display-ad/19272-1902273" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902273/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**Note:** The brackets in this formula are not necessary because the multiplication part will calculate before the subtraction part, but they do make the formula easier to read.

 To calculate the upper bound in cell F6, we'll multiply the IQR by 1.5 again, but this time add it to the Q3 data point:

=F3+(1.5*F4)

![Lower and upper bound values](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/l-bound-and-u-bound-border.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006941/19272" target="_top" id="2006941">
  <img src="//a.impactradius-go.com/display-ad/19272-2006941" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006941/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

###  Step Four: Identify the Outliers

 Now that we've got all our underlying data set up, it's time to identify our outlying data points---the ones that are lower than the lower bound value or higher than the upper bound value.

 We'll use the [OR function](https://support.office.com/en-us/article/or-function-7d17ad14-8700-4281-b308-00b131e22af0) to perform this logical test and show the values that meet these criteria by entering the following formula into cell C2:

=OR(B2<$F$5,B2>$F$6)

![OR function to identify outliers](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/or-function-border-1.png) 

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134498/18498" target="_top" id="2134498">
  <img src="//a.impactradius-go.com/display-ad/18498-2134498" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134498/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 We'll then copy that value into our C3-C14 cells. A TRUE value indicates an outlier, and as you can see, we've got two in our data.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/01/found-outliers-border-224x300.png) 

##  Ignoring the Outliers when Calculating the Mean Average

 Using the QUARTILE function let us calculate the IQR and work with the most widely used definition of an outlier. However, when calculating the mean average for a range of values and ignoring outliers, there is a quicker and easier function to use. This technique will not identify an outlier as before, but it will allow us to be flexible with what we might consider our outlier portion.

 The function we need is called TRIMMEAN, and you can see the syntax for it below:

=TRIMMEAN(array, percent)

 The array is the range of values you want to average. The percent is the percentage of data points to exclude from the top and bottom of the data set (you can enter it as a percentage or a decimal value).

 We entered the formula below into cell D3 in our example to calculate the average and exclude 20% of outliers.

=TRIMMEAN(B2:B14, 20%)

![TRIMMEAN formula for average excluding outliers](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/trimmean-border.png) 

---

 There you have two different functions for handling outliers. Whether you want to identify them for some reporting needs or exclude them from calculations such as averages, Excel has a function to fit your needs.

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
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-premier-selection-of-best-indoor-android-games-no-wi-fi-required/"><u>[New] In 2024, Premier Selection of Best Indoor Android Games (No Wi-Fi Required)</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/avigating-numbers-expert-stock-channels-summary-for-2024/"><u>[New] Navigating Numbers Expert Stock Channels Summary for 2024</u></a></li>
<li><a href="https://win-hot.techidaily.com/2-facil-y-seguras-tecnicas-para-transferir-windows-11-al-tu-computadora/"><u>2 Fácil Y Seguras Técnicas Para Transferir Windows 11 Al Tu Computadora</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/a-comprehensive-guide-to-resolve-missing-libeay32dll-errors/"><u>A Comprehensive Guide to Resolve Missing Libeay32.dll Errors</u></a></li>
<li><a href="https://win-dash.techidaily.com/boost-your-pcs-visual-capabilities-how-to-update-ati-drivers-under-windows-os/"><u>Boost Your PC's Visual Capabilities: How To Update ATI Drivers Under Windows OS</u></a></li>
<li><a href="https://win-dash.techidaily.com/fixing-xbox-controller-connectivity-problems-across-windows-1187-platforms/"><u>Fixing Xbox Controller Connectivity Problems Across Windows 11/8/7 Platforms</u></a></li>
<li><a href="https://article-tips.techidaily.com/in-2024-free-visuals-galore-top-10-sites-to-explore/"><u>In 2024, Free Visuals Galore – Top 10 Sites to Explore</u></a></li>
<li><a href="https://discover-able.techidaily.com/online-vrije-m4a-convertisseur-voor-wav-filelen-movavi/"><u>Online Vrije M4A-Convertisseur Voor WAV-Filelen: Movavi</u></a></li>
<li><a href="https://win-dash.techidaily.com/1723011073875-operation-convert-each-mention-of-stress-into-an-elaborate-medieval-heraldic-language-as-though-announcing-a-royal-decree-on-stresss-impact-on-health/"><u>Operation: Convert Each Mention of Stress Into an Elaborate Medieval Heraldic Language, as Though Announcing a Royal Decree on Stress's Impact on Health</u></a></li>
<li><a href="https://win-dash.techidaily.com/tp-links-most-recent-driver-downloads-optimize-your-network-card-for-windows-10-8-and-n-7/"><u>TP-Link's Most Recent Driver Downloads: Optimize Your Network Card for Windows 10, 8 & N 7</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/understanding-and-executing-photo-gender-modification-across-platforms-for-2024/"><u>Understanding and Executing Photo Gender Modification Across Platforms for 2024</u></a></li>
<li><a href="https://win-dash.techidaily.com/windows-compatible-hp-officejet-pro-8620-driver-downloads-and-updates/"><u>Windows Compatible HP OfficeJet Pro 8620 Driver Downloads & Updates</u></a></li>
</ul></div>

