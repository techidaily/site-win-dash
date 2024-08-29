---
title: The Essential Tricks to Utilizing Excel's TRUNC Function for Data Handling Accuracy
date: 2024-08-27 15:44:29
updated: 2024-08-29 12:45:31
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

##  How to Use the TRUNC Function

 Let's look at examples of the TRUNC function with some sample data. The below example uses the following TRUNC function.

=TRUNC(A2)

 If you do not specify how many digits to truncate, all decimal places will be removed.

![First TRUNC function example](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/03/first-example.png) 

 You can see with the value in cell A2 that the TRUNC function does not apply any rounding. It simply truncates the number to 411.

 Let's see another example. This time we will reduce the values to two decimal places.

=TRUNC(A2,2)

![TRUNC function to two decimal places](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/03/two-decimal-places.png) 

 The TRUNC function will not display extra decimals if you ask it to show more than you have.

 Take the following example, and let's truncate it to two decimal places.

=TRUNC(A2,2)

![No extra decimals shown by TRUNC](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/03/no-extra-decimals.png) 

 The value in cell A4 is reduced to two decimal places, but the values in A2 and A3 stay as they are because they have less than two decimal places already.

 If you want to display the two decimals, the cells will need to be formatted to be forced to show them.

##  Remove the Time from a Date-Time Stamp

 A useful example of TRUNC is to remove the time from a date and time stamp in Excel.

 Imagine having the following date and time stamps, but we just want the date in a column for analysis.

![Date and time sample data](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/03/date-and-time-data.png) 

 The following formula will work to remove the time.

=TRUNC(A2)

![Time removed from a date in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/03/time-removed.png) 

 Although the time is removed, the resulting cells will still need to be formatted as a date only.

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
