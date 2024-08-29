---
title: Discovering Days of the Week Based on Specific Dates with Microsoft Excel Tips
date: 2024-08-27 20:52:50
updated: 2024-08-29 11:57:59
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/09/microsoft_excel_hero_1200x675.jpg
---

## Discovering Days of the Week Based on Specific Dates with Microsoft Excel Tips

### Quick Links

* [Ways to Find the Weekday From a Date in Excel](https://facebook-clips.techidaily.com/updated-in-2024-stream-like-a-pro-setting-up-your-dslr-on-personal-computers/)
* [Find the Day of the Week as a Number](https://youtube-videos.techidaily.com/flavor-forge-30-epicurean-titles-that-resonate/)
* [Find the Day of the Week as a Name](https://ios-unlock.techidaily.com/in-2024-3-ways-to-unlock-iphone-14-pro-max-without-passcode-or-face-id-by-drfone-ios/)
* [Convert Dates to Days of the Week](https://extra-resources.techidaily.com/mastering-360-video-making-with-ios-devices/)

 Do you have a [date in your spreadsheet](https://youtube-web.techidaily.com/ed-2024-approved-ultimate-guide-to-the-best-10-video-saving-devices/) that you want to turn into the day of the week? If so, Microsoft Excel has multiple features and functions to help you do that. We'll show you how to use them.

##  Ways to Find the Weekday From a Date in Excel

 To find the day of the week from a date, you have basically three ways. The first method is to turn your date into the day of the week in a numerical form. In this method, Sunday is displayed as number 1, Monday is number 2, and so on. This is calculated with Excel's WEEKDAY function.

 The second method displays the actual name of the day of week, like Sunday, Monday, and so on. This method uses Excel's `TEXT` function that [converts your date to the day format](https://screen-mirror.techidaily.com/how-to-screen-mirroring-samsung-galaxy-xcover-7-drfone-by-drfone-android/).

 The third method re-formats your actual dates and displays them as the names of the day of week, like Sunday, Monday, and so on. If you use this method, you do not need a separate column to display the days, as your existing date is overwritten.

##  Find the Day of the Week as a Number

 To find the day of the week as a number, use Excel's `WEEKDAY` function as follows. The count starts from Sunday, where it is numbered 1\. However, you can make the [function](https://win11.techidaily.com/renaissance-pc-refresh-with-atlasos/) count from any chosen day (like Monday), as we'll explain below.

 To start, first, open your spreadsheet with Microsoft Excel. In the spreadsheet, make sure you have at least one date. Then select the cell in which you want to display the day of the week.

![Select a cell in an Excel spreadsheet.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/1-select-cell-2.png) 

 In the selected cell, type the following `WEEKDAY` function and press Enter. In this function, replace `B2` with the cell where you have your date.

=WEEKDAY(B2)

![Enter the WEEKDAY function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/2-enter-weekday-function.png) 

 If you'd like to use the date directly in the function, type the following `WEEKDAY` function with your date in it and press Enter. Keep double quotes around your date.

=WEEKDAY("24/5/2021")

![Enter the WEEKDAY function with direct values.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/3-direct-values-weekday-function.png) 

 And in the selected cell, you will see the day of the week for your date as a number.

![The result of the WEEKDAY function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/4-weekday-function-result.png) 

 To make the function count days so that Monday is number 1, modify the function as follows. The number `2` in the function argument tells it to start counting from Monday.

=WEEKDAY(B2,2)

![Type the custom WEEKDAY function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/5-custom-weekday-function.png) 

 Here's how your result now looks like:

![The result of the custom WEEKDAY function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/6-custom-weekday-function-result.png) 

 To copy the function to other cells, [drag downwards](https://visual-screen-recording.techidaily.com/new-in-2024-top-5-best-hdmi-21-gaming-monitors-ps5-compatible/) from the bottom-right corner of the cell where you typed the function.

![Copy the WEEKDAY function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/7-copy-weekday-function.png) 

Related: [How to Sort by Date in Microsoft Excel](https://screen-sharing-recording.techidaily.com/updated-2024-approved-economical-pc-playback-devices/) 

##  Find the Day of the Week as a Name

 To display a date's day of the week as the day name, like Monday, use Excel's `TEXT` function. In this function, you tell Excel to [format your date](https://video-capture.techidaily.com/new-from-playback-to-printout-top-five-methods-of-documenting-minecraft-on-a-mac-for-2024/) in the day format. You can choose the shortened day name (like Mon) or full day name (like Monday).

 Start by opening your spreadsheet with Microsoft Excel. Then select the cell in which you want to display the day of week.

![Click a cell in an Excel spreadsheet.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/8-choose-cell.png) 

 In the selected cell, type the following `TEXT` function and press Enter. In this function, replace `B2` with the cell where your date is.

=TEXT(B2,"dddd")

![Enter the TEXT function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/9-enter-text-function.png) 

 The selected cell will display the day of the week. If you'd prefer a shortened day name, like "Mon" for Monday, remove one `d` from the function argument as follows:

=TEXT(B2,"ddd")

![Type the custom TEXT function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/10-custom-text-function.png) 

 And you now have the shortened day name in your selected cell.

![The result of the custom TEXT function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/11-text-function-result.png) 

 Depending on how you like to style your sheets, you may want to [format your dates using periods in Excel](https://youtube-videos.techidaily.com/diy-delights-in-motion-personalized-animation-artistry-for-2024/).

##  Convert Dates to Days of the Week

 To convert your dates to days of weeks without [using a separate column](https://tiktok-clips.techidaily.com/2024-approved-speeding-up-tiktok-videos-made-simple/), use Excel's custom number format. This displays the day of week by its full or shortened name.

 To do so, first, open your spreadsheet with Microsoft Excel. Then select the cells containing dates.

![Select the date cells.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/12-select-dates.png) 

 In [Excel's ribbon at the top](https://screen-mirror.techidaily.com/in-2024-how-to-mirror-honor-play-40c-to-mac-drfone-by-drfone-android/), click the "Home" tab.

![Click the "Home" tab in Excel.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/13-excel-home-tab.png) 

 In the "Home" tab, from the "Number" section, select "Number Format" (an arrow icon).

![Select &quot;Number Format&quot; in the &quot;Home&quot; tab.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/14-excel-number-format.png) 

 A "Format Cells" window will open. On this window, from the "Category" list on the left, select "Custom."

![Select &quot;Custom&quot; on the &quot;Format Cells&quot; window.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/15-custom-number-format.png) 

 On the right, click the "Type" box and enter "dddd" (without quotes) for full day names (like Monday) or "ddd" for shortened day names (like Mon). Then, at the bottom, click "OK."

![Specify the date format.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/16-enter-number-format.png) 

 Excel will turn your selected dates into days of the week.

![Dates turned into days of week.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/11/17-number-format-result.png) 

 And that's how you know what day it was on a specific date in Microsoft Excel. Very useful!

---

 Did you know you can use Excel to [calculate someone's age](https://youtube-data.techidaily.com/n-2024-explore-the-best-historian-content-top-10-youtube-recommendations/), too? It's equally easy to do that.

Related: [How to Calculate Age in Microsoft Excel](https://youtube-data.techidaily.com/n-2024-explore-the-best-historian-content-top-10-youtube-recommendations/)

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
