---
title: The Essential Tricks to Utilizing Excel's TRUNC Function for Data Handling Accuracy
date: 2024-08-28T01:34:53.080Z
updated: 2024-08-29T01:34:53.080Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/07/stock-lede-microsoft-office_excel-1.png
---

## The Essential Tricks to Utilizing Excel's TRUNC Function for Data Handling Accuracy

### Quick Links

* [What Is the TRUNC Function?](https://extra-resources.techidaily.com/systematic-upgrade-procedures-for-macos-sierra-users/)
* [How to Use the TRUNC Function](https://data-wizards.techidaily.com/immediate-fix-to-freezing-problem-in-vlc/)
* [Remove the Time from a Date-Time Stamp](https://fox-direct.techidaily.com/exploring-interconnected-digital-universes-meta-and-omni-for-2024/)
* [Use TRUNC to Shorten Numbers](https://fox-info.techidaily.com/updated-the-ultimate-strategy-for-posting-srt-content-socially/)

 There are a variety of ways in Excel to remove decimal points and shortening number values. In this article, we explain how to use the TRUNC function and what makes it different from other techniques.

##  What Is the TRUNC Function?

 The TRUNC function truncates a number to a specified number of decimal places. The key factor that makes TRUNC different from other functions that remove decimal places is that the TRUNC function does not round values. If you use TRUNC to remove all the decimals from the value 4.68, the result is 4.

 The TRUNC function requires two pieces of information:

=TRUNC(number, [digits])

 The number is the value you want to truncate. Digits are the number of numerals you want to truncate the value to. The digits portion is optional, and if not answered, TRUNC will remove all decimal places.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
##  How to Use the TRUNC Function

 Let's look at examples of the TRUNC function with some sample data. The below example uses the following TRUNC function.

=TRUNC(A2)

 If you do not specify how many digits to truncate, all decimal places will be removed.

![First TRUNC function example](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/03/first-example.png) 

 You can see with the value in cell A2 that the TRUNC function does not apply any rounding. It simply truncates the number to 411.

 Let's see another example. This time we will reduce the values to two decimal places.

=TRUNC(A2,2)

![TRUNC function to two decimal places](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/03/two-decimal-places.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
<!-- affiliate ads end -->
 The TRUNC function will not display extra decimals if you ask it to show more than you have.

 Take the following example, and let's truncate it to two decimal places.

=TRUNC(A2,2)

![No extra decimals shown by TRUNC](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/03/no-extra-decimals.png) 

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793233/19578" target="_top" id="1793233"><img src="//a.impactradius-go.com/display-ad/19578-1793233" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793233/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 The value in cell A4 is reduced to two decimal places, but the values in A2 and A3 stay as they are because they have less than two decimal places already.

 If you want to display the two decimals, the cells will need to be formatted to be forced to show them.

##  Remove the Time from a Date-Time Stamp

 A useful example of TRUNC is to remove the time from a date and time stamp in Excel.

 Imagine having the following date and time stamps, but we just want the date in a column for analysis.

![Date and time sample data](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/03/date-and-time-data.png) 

<!-- affiliate ads begin -->
<span id="1993650">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 The following formula will work to remove the time.

=TRUNC(A2)

![Time removed from a date in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/03/time-removed.png) 

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=1412049&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-200x200.jpg" border="0"></a>
<!-- affiliate ads end -->
 Although the time is removed, the resulting cells will still need to be formatted as a date only.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
<!-- affiliate ads end -->
##  Use TRUNC to Shorten Numbers

 This is a rare technique, but it is worth knowing that the TRUNC function will also accept negative numbers for the digits argument. When you use a negative number, the formula truncates the numbers to the left of the decimal point. However, it does not change the number of digits. It will replace them with zeroes.

 Let's look at the following example.

=TRUNC(A2,-1)

![Entering minus digits for the second argument](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/03/minus-digits.png) 

 You can see in each example that zero was used to replace the number that was removed from the left of the decimal point.

---

 There are multiple ways in Excel to remove decimal places, however, most of these will apply a rounding of some nature. The strength of the TRUNC function is that it does not round values and simply shortens them to the specified decimal place amount.

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


