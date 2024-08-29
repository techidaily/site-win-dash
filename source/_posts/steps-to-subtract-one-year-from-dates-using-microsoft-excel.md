---
title: Steps to Subtract One Year From Dates Using Microsoft Excel
date: 2024-08-27 10:52:14
updated: 2024-08-29 10:29:39
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/07/stock-lede-microsoft-office_excel-1.png
---

## Steps to Subtract One Year From Dates Using Microsoft Excel

### Quick Links

* [Custom Number Formatting](https://bypass-frp.techidaily.com/in-2024-a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-itel-p40plus-by-drfone-android/)
* [CONCATENATE Function](https://extra-information.techidaily.com/2024-approved-a-beginners-guide-making-your-podcasts-rss-feed/)

 There are a couple of ways you can remove the year from a date shown in Microsoft Excel. You can use custom cell formatting to hide it or use various functions like CONCATENATE to remove it completely. Here's how.

##  Custom Number Formatting

 While a date value in an Excel cell is technically a number, Microsoft Excel uses a particular type of formatting to display it. The same is true for currency values, where currency symbols are added to values to show that they relate to money. When you add a date in Excel in a format that it recognizes, Excel automatically changes the cell number format to the "Date" type.

 You can customize this type to display the date value in different ways. For instance, you can switch between "11/02/2021" (in the DD/MM/YYYY format commonly used in the U.K.) and "2021-02-11" for 11 February 2021.

![An example of various custom date formats in Microsoft Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/02/Excel-Custom-Date-Formats.png) 

 You can customize this number format, however, to remove the year entirely from view. The value itself won't change, but Excel won't [show the year value](https://facebook-record-videos.techidaily.com/updated-in-2024-captivating-content-the-basics-of-removing-background-from-videos/) thanks to custom number formatting.

 To do this, highlight the cells containing your original date values, then select the "Home" tab on the ribbon bar. From there, select the arrow next to the number format drop-down menu and choose the "More Number Formats" option.

![In Excel, select your date values, then press Home &gt; Number Format &gt; More Number Formats.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/02/Excel-More-Number-Formats-Option.png) 

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

 If you want to remove the year from a date in Excel, you could combine the output from two functions (such as DAY or MONTH) together using CONCATENATE. Rather than hiding the year from view using custom number formatting, CONCATENATE (with DAY and MONTH) allows you to create a separate value that doesn't include the year at all.

 To do this, open an Excel workbook containing your date values, or create a new workbook and place date values in separate cells. To use CONCATENATE with DAY and MONTH, insert a new function using this structure, replacing the cell reference (A2) with a reference to the cell containing your date:

=CONCATENATE(DAY(A2),"/",MONTH(A2))

 The values returned by DAY and MONTH are separated by a special delimiter character, such as a comma or slash, to show that the returned value is a date. Each value (DAY, the delimiter, and MONTH) are separated by a comma in the CONCATENATE function.

 In this example, cell A2 contains a date value (11/12/2021) in the DD/MM/YYYY format. Using CONCATENATE with DAY and MONTH, the day (11) and month (12) from the date value in A2 are placed in another cell separated by the delimiter, which, in this case, is a forward slash.

![An example of various text strings combined using the Excel CONCATENATE function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/02/Excel-CONCATENATE-Example.png) 

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
