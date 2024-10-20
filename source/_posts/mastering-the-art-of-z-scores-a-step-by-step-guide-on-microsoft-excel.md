---
title: "Mastering the Art of Z-Scores: A Step-by-Step Guide on Microsoft Excel"
date: 2024-10-17T16:46:19.820Z
updated: 2024-10-20T16:31:19.848Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/102ab1b6aae4e1817df5a3836c10cfedb2eea5b3cb906b121a8d1c61752ad28b.jpg
---

## Mastering the Art of Z-Scores: A Step-by-Step Guide on Microsoft Excel

### Quick Links

* [What is a Z-Score and what do the AVERAGE, STDEV.S, and STDEV.P functions do?](https://youtube-data.techidaily.com/ed-crafting-engaging-youtube-video-layouts-for-2024/)
* [Let's Look at an Example](https://youtube-lab.techidaily.com/ed-scriptwriting-mastery-elevate-your-youtube-channels-content-quality/)
* [Calculating the Z-Score without using 'Helper' Cells](https://android-pokemon-go.techidaily.com/in-2024-how-to-use-pokemon-emerald-master-ball-cheat-on-motorola-moto-g24-drfone-by-drfone-virtual-android/)

 A Z-Score is a statistical value that tells you how many standard deviations a particular value happens to be from the mean of the entire data set. You can use AVERAGE and STDEV.S or STDEV.P formulas to calculate the mean and standard deviation of your data and then use those results to determine the Z-Score of each value.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886048/19272" target="_top" id="1886048">
  <img src="//a.impactradius-go.com/display-ad/19272-1886048" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886048/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  What is a Z-Score and what do the AVERAGE, STDEV.S, and STDEV.P functions do?

 A Z-Score is a simple way of comparing values from two different data sets. It is defined as the number of standard deviations away from the mean a data point lies. The general formula looks like this:

=(DataPoint-AVERAGE(DataSet))/STDEV(DataSet)

 Here's an example to help clarify. Say you wanted to compare the test results of two Algebra students taught by different teachers. You know the first student got a 95% on the final exam in one class, and the student in the other class scored 87%.

 At first glance, the 95% grade is more impressive, but what if the teacher of the second class gave a more difficult exam? You could calculate the Z-Score of each student's score based on the average scores in each class and the standard deviation of the scores in each class. Comparing the Z-Scores of the two students could reveal that the student with the 87% score did better in comparison to the rest of their class than the student with the 98% score did in comparison to the rest of their class.

 The first statistical value you need is the 'mean' and Excel's "AVERAGE" function calculates that value. It simply adds up all of the values in a cell range and divides that sum by the number of cells containing numerical values (it ignores blank cells).

 The other statistical value we need is the 'standard deviation' and Excel has two different functions to calculate the standard deviation in slightly different ways.

 Previous versions of Excel only had the "STDEV" function, which calculates the standard deviation while treating the data as a 'sample' of a population. Excel 2010 broke that into two functions that calculate the standard deviation:

* **STDEV.S:** This function is identical to the previous "STDEV" function. It calculates the standard deviation while treating the data as a 'sample' of a population. A sample of a population might be something like the particular mosquitoes collected for a research project or cars that were set aside and used for crash safety testing.
* **STDEV.P:** This function calculates the standard deviation while treating the data as the entire population. An entire population would be something like all mosquitoes on Earth or every car in a production run of a specific model.

 Which you choose is based on your data set. The difference will usually be small, but the result of the "STDEV.P" function will always be smaller than the result of the "STDEV.S" function for the same data set. It is a more conservative approach to assume there is more variability in the data.

##  Let's Look at an Example

 For our example, we have two columns ("Values" and "Z-Score")and three "helper" cells for storing the results of the "AVERAGE," "STDEV.S," and "STDEV.P" functions. The "Values" column contains ten random numbers centered around 500, and the "Z-Score" column is where we will calculate the Z-Score using the results stored in the 'helper' cells.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Z-Score-01.png) 

 First, we will calculate the mean of the values using the "AVERAGE" function. Select the cell where you will store the result of the "AVERAGE" function.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Z-Score-02.png) 

 Type in the following formula and press enter -or- use the "Formulas" menu.

=AVERAGE(E2:E13)

 To access the function through the "Formulas" menu, select the "More Functions" drop-down, select the "Statistical" option, and then click on "AVERAGE."

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Z-Score-03.png) 

 In the Function Arguments window, select all of the cells in the "Values" column as the input for the "Number1" field. You don't need to worry about the "Number2" field.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Z-Score-04.png) 

 Now press "OK."

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Z-Score-05-1.png) 

 Next, we need to calculate the standard deviation of the values using either the "STDEV.S" or "STDEV.P" function. In this example, we will show you how to calculate both values, starting with "STDEV.S." Select the cell where the result will be stored.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Z-Score-06.png) 

 To calculate the standard deviation using the "STDEV.S" function, type in this formula and press Enter (or access it through the "Formulas" menu).

=STDEV.S(E3:E12)

 To access the function through the "Formulas" menu, select the "More Functions" drop-down, select the "Statistical" option, scroll down a bit, and then click the "STDEV.S" command.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Z-Score-07.png) 

 In the Function Arguments window, select all of the cells in the "Values" column as the input for the "Number1" field. You don't need to worry about the "Number2" field here, either.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Z-Score-08.png) 

<!-- affiliate ads begin -->
<span id="1770776">
					<video width="240" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1770776.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/20702-1770776">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1770776.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftokenmetrics.sjv.io%2Fc%2F5597632%2F1770776%2F20702'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1770776/20702" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now press "OK."

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Z-Score-09.png) 

 Next, we will calculate the standard deviation using the "STDEV.P" function. Select the cell where the result will be stored.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Z-Score-10.png) 

 To calculate the standard deviation using the "STDEV.P" function, type in this formula and press Enter (or access it through the "Formulas" menu).

 \=STDEV.P(E3:E12)

 To access the function through the "Formulas" menu, select the "More Functions" drop-down, select the "Statistical" option, scroll down a bit, and then click the "STDEV.P" formula.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Z-Score-11.png) 

<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/1943647/22993" target="_top" id="1943647">
  <img src="//a.impactradius-go.com/display-ad/22993-1943647" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://homestyler.sjv.io/i/5597632/1943647/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In the Function Arguments window, select all of the cells in the "Values" column as the input for the "Number1" field. Again, you won't need to worry about the "Number2" field.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Z-Score-12.png) 

 Now press "OK."

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Z-Score-13-1.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100529/7443" target="_top" id="2100529">
  <img src="//a.impactradius-go.com/display-ad/7443-2100529" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now that we have calculated the mean and standard deviation of our data, we have all we need to calculate the Z-Score. We can use a simple formula that references the cells containing the results of the "AVERAGE" and "STDEV.S" or "STDEV.P" functions.

 Select the first cell in the "Z-Score" column. We will use the result of the "STDEV.S" function for this example, but you could also use the result from "STDEV.P."

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Z-Score-14.png) 

 Type in the following formula and hit Enter:

=(E3-$G$3)/$H$3

 Alternatively, you could use the following steps to enter the formula instead of typing:

1. Click cell F3 and type `=(`
2. Select cell E3\. (You can press the left-arrow-key once or use the mouse)
3. Type the minus sign `-`
4. Select cell G3 then press F4 to add the "$" characters to make an 'absolute' reference to the cell (it will cycle through "G3" > "**$**G**$**3" > "G**$**3" > "**$**G3" > "G3" if you continue pressing F4)
5. Type `)/`
6. Select cell H3 (or I3 if you are using "STDEV.P") and press F4 to add the two "$" characters.
7. Press Enter

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Z-Score-15.png) 

 The Z-Score has been calculated for the first value. It is 0.15945 standard deviations below the mean. To check the results, you can multiply the standard deviation by this result (6.271629 \* -0.15945) and check that the result is equal to the difference between the value and the mean (499-500). Both results are equal, so the value makes sense.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Z-Score-16.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094422/7443" target="_top" id="2094422">
  <img src="//a.impactradius-go.com/display-ad/7443-2094422" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094422/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Let's calculate the Z-Scores of the rest of the values. Highlight the whole 'Z-Score' column starting with the cell containing the formula.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Z-Score-17.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541">
  <img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Press Ctrl+D, which copies the formula in the top cell down through all the other selected cells.

![](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/12/Excel-Z-Score-18.png) 

 Now the formula has been 'filled-down' to all of the cells, and each will always reference the correct "AVERAGE" and "STDEV.S" or "STDEV.P" cells because of the "$" characters. If you get errors, go back and make sure the "$" characters are included in the formula you entered.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130528/26400" target="_top" id="2130528">
  <img src="//a.impactradius-go.com/display-ad/26400-2130528" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130528/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Calculating the Z-Score without using 'Helper' Cells

 Helper cells store a result, like the ones storing the results of the "AVERAGE," "STDEV.S," and "STDEV.P" functions. They can be useful but aren't always necessary. You can skip them altogether when calculating a Z-Score by using the following generalized formulas, instead.

 Here's one using the "STDEV.S" function:

=(Value-AVERAGE(Values))/STDEV.S(Values)

 And one using the "STEV.P" function:

=(Value-AVERAGE(Values))/STDEV.P(Values)

 When entering the cell ranges for the "Values" in the functions, be sure to add absolute references ("$" using F4) so that when you 'fill-down' you aren't calculating the average or standard deviation of a different range of cells in every formula.

 If you have a large data set, it may be more efficient to use helper cells because it doesn't calculate the result of the "AVERAGE" and "STDEV.S" or "STDEV.P" functions each time, saving processor resources and speeding up the time it takes to calculate the results.

 Also, "$G$3" takes fewer bytes to store and less RAM to load than "AVERAGE($E$3:$E$12).". This is important because the standard 32-bit version of Excel is limited to 2GB of RAM (the 64-bit version does not have any limitations on how much RAM can be used).

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
<li><a href="https://fox-cloud.techidaily.com/new-enthralling-evaluation-and-secondary-recommendations-for-2024/"><u>[New] Enthralling Evaluation & Secondary Recommendations for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-groupgaze-video-extractor/"><u>[Updated] 2024 Approved GroupGaze Video Extractor</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-foray-into-video-fidelity-an-initialists-perspective/"><u>[Updated] Foray Into Video Fidelity An Initialist's Perspective</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-experience-beyond-reality-choosing-the-premier-10-headsets-for-360-video-on-pc/"><u>2024 Approved Experience Beyond Reality Choosing the Premier 10 Headsets for 360 Video on PC</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/exhaustive-explanation-whats-behind-google-podcast/"><u>Exhaustive Explanation What's Behind Google Podcast?</u></a></li>
<li><a href="https://howto.techidaily.com/fix-unfortunately-settings-has-stopped-on-samsung-galaxy-a34-5g-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Unfortunately Settings Has Stopped on Samsung Galaxy A34 5G Quickly | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/from-capture-to-share-reviewing-the-newest-sprout-version/"><u>From Capture to Share Reviewing the Newest Sprout Version</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-newest-toshiba-drivers-and-upgrades-on-your-windows-pc-easily/"><u>Get the Newest Toshiba Drivers and Upgrades on Your Windows PC Easily</u></a></li>
<li><a href="https://win-dash.techidaily.com/realtek-rtl8188cu-wifi-driver-installation-ideal-for-windows-107-users/"><u>Realtek RTL8188CU WiFi Driver Installation - Ideal for Windows 10/7 Users</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/simple-steps-to-updating-your-sata-ahci-controllers-software/"><u>Simple Steps to Updating Your SATA AHCI Controller's Software</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/step-by-step-live-tweeting-tactics-for-2024/"><u>Step-by-Step Live Tweeting Tactics for 2024</u></a></li>
<li><a href="https://win-dash.techidaily.com/step-by-step-tutorial-downloading-and-setting-up-asus-atk0100-acpi-drivers/"><u>Step-by-Step Tutorial: Downloading and Setting Up ASUS ATK0100 ACPI Drivers</u></a></li>
<li><a href="https://win-dash.techidaily.com/unveiling-the-solution-wn722n-detected-after-previously-going-unseen-by-windows/"><u>Unveiling the Solution: WN722N Detected After Previously Going Unseen by Windows</u></a></li>
</ul></div>

