---
title: "Mastering Excel: A Step-by-Step Guide to Applying Conditional Formatting on Rows"
date: 2024-08-28T01:34:25.765Z
updated: 2024-08-29T01:34:25.765Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/f55494b1c8843bed72fd409a0474603bdb628f91806cf12974c661e4f3ab93d8.jpg
---

## Mastering Excel: A Step-by-Step Guide to Applying Conditional Formatting on Rows

### Quick Links

* [Step One: Create Your Table](https://techidaily.com/automated-conversion-tracking-with-cookiebot-enhancing-your-analytics/)
* [Step Two: Format Your Table](https://blog-min.techidaily.com/how-to-migrate-android-data-from-nokia-c32-to-new-android-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/)
* [Step Three: Create The Conditional Formatting Rules](https://facebook-video-footage.techidaily.com/updated-2024-approved-enlightening-editing-paths-to-audience-appealing-descriptors/)

 Conditional formatting lets you format cells in an Excel spreadsheet based on the cells' content. For example, you could have a cell turn red when it contains a number lower than 100\. You can also use conditional formatting to highlight an entire row?

Related: [Using Conditional Cell Formatting in Excel 2007](https://android-pokemon-go.techidaily.com/top-15-augmented-reality-games-like-pokemon-go-to-play-on-sony-xperia-1-v-drfone-by-drfone-virtual-android/) 

 If you've never used Conditional Formatting before, you might want to look at [Using Conditional Cell Formatting in Excel 2007](https://android-pokemon-go.techidaily.com/top-15-augmented-reality-games-like-pokemon-go-to-play-on-sony-xperia-1-v-drfone-by-drfone-virtual-android/). It's for an earlier version of Excel, but the interface really hasn't changed much. That guide talks about formatting specific cells based on their content. For example, say you use a spreadsheet to track hours that employees have worked. You could use conditional formatting to color cells red where an employee has worked more than eight hours in a particular day.

 But what if you wanted to use a cell's value to highlight other cells? In the example we're using for this article, we've got a small spreadsheet with movies and just a couple of details about those movies (to keep thinks simple). We're going to use conditional formatting to highlight all the rows with movies made before 1980.

##  Step One: Create Your Table

 Obviously, the first thing you need is a simple table containing your data. The data doesn't have to be text-only; you can use formulas freely. At this point, your table has no formatting at all:

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2017/11/ecf_1.png) 

##  Step Two: Format Your Table

 Now it's time to format your table, if you want. You can use Excel's "simple" formatting tools or take a more hands-on approach, but it's best only to format only those parts that won't be affected by conditional formatting. In our case, we can safely set a border for the table, as well as format the header line.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2017/11/ecf_2.png) 

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
##  Step Three: Create The Conditional Formatting Rules

 Now we come to the meat and potatoes. As we said at the outset, if you've never used conditional formatting before, you should probably check out our [earlier primer on the subject](https://android-pokemon-go.techidaily.com/top-15-augmented-reality-games-like-pokemon-go-to-play-on-sony-xperia-1-v-drfone-by-drfone-virtual-android/) and once you've got that down, come back here. If you're already somewhat familiar with conditional formatting (or just adventurous), let's forge on.

 Select the first cell in the first row you'd like to format, click the "Conditional Formatting" button in the "Styles" section of the "Home" tab, and then select "Manage Rules" from the dropdown menu.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2017/11/ecf_3.png) 

 In the "Conditional Formatting Rules Manager" window, click the "New Rule" button.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2017/11/ecf_4.png) 

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=4596923&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_468X60.png" border="0"></a>
<!-- affiliate ads end -->
 In the "New Formatting Rule" window, select the "Use a formula to determine which cells to format" option. This is the trickiest part. Your formula must evaluate to "True" for the rule to apply, and must be flexible enough so you could use it across your entire table later on. Here, we're using the formula:

=$D4<1980

 The `=$D4` part of the formula denotes the address of the cell I want to examine. `D` is the column (with the movie release date), and `4` is my current row. Note the dollar sign before the `D` . If you don't include this symbol, then when you apply conditional formatting to the next cell, it would examine E5\. Instead, you need to specify have a "fixed" column (`$D`) but a "flexible" row (`4`), because you are going to apply this formula across multiple rows.

 The `<1980` part of the formula is the condition that has to be met. In this case, we're going for a simple condition---the number in the release date column should be less than 1980\. Of course, you can use much more complex formulas if you need to.

 So in English, our formula is true whenever the cell in column D in the current row has a value less than 1980.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2017/11/ecf_5.png) 

 Next, you'll define the formatting that happens if the formula is true. In the same "New Formatting Rule" window, click the "Format" button.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2017/11/ecf_6.png) 

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 In the "Format Cells" window, go through the tabs and tweak the settings until you get the look you want. In our example, we're just going to change the fill color to green on the "Fill" tab. When you're done applying your formatting, click the "OK" button.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2017/11/ecf_7.png) 

 Back in the "New Formatting Rule" window, you can now see a preview of your cell. If you're happy with the way everything looks, click the "OK" button.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2017/11/ecf_8.png) 

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
<!-- affiliate ads end -->
 You should now be back to the "Conditional Formatting Rules Manager" window. Move the window a bit until you can see your spreadsheet behind it, and then click the "Apply" button. If the formatting of your selected cell changes, that means your formula is correct. If the formatting doesn't change, you need to go a few steps back and tweak your formula until it does work. Here, you can see that our formula worked, and the cell we selected is now filled in green.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2017/11/ecf_9.png) 

 Now that you have a working formula, it's time to apply it across the entire table. As you can see above, right now the formatting applies only to the cell we started off with. In the "Conditional Formatting Rules Manager" window (which should still be open), click the up arrow to the right of the "Applies To" field.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2017/11/ecf_1.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 The "Conditional Formatting Rules Manager" window collapses, giving you access to your spreadsheet. Drag to resize the current selection across the entire table (except for the headings).

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2017/11/ecf_1.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851691&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
 When you're done, click the down arrow to the right of the address field to get back to the full "Conditional Formatting Rules Manager" window.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2017/11/ecf_1.png) 

<!-- affiliate ads begin -->

<!-- affiliate ads end -->
 Note that the "Applies to" field now contains a range of cells instead of just a single address. Click the "Apply" button again, and you should see the whole table formatted according to your rule. In our example, you can see that the whole rows that contain movies made before 1980 are filled with green.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2017/11/ecf_1.png) 

 That's it! If you have more complex needs, you can create additional formulas. And, of course, you can make your formulas a whole lot more complex than the simple example we've used here. You can even use conditional formatting between different spreadsheets, so that cells or rows in one spreadsheet are formatted differently depending on the data in a whole different sheet. Play around with the techniques we've covered, and in no time you'll be creating intricate spreadsheets with data that pops right off the screen.

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


