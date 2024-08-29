---
title: "Windows 11 Guide: Discovering Your Computer's RAM Specifications - Type & Capacity"
date: 2024-08-26 17:37:56
updated: 2024-08-29 10:27:10
tags:
  - windows
categories:
  - tech
thumbnail: https://thmb.techidaily.com/26237c0b8cf6f930c119cd7d58abe423d11d796e2ad6cf886d90c9a4679357e1.jpg
---

## Windows 11 Guide: Discovering Your Computer's RAM Specifications - Type & Capacity

### Quick Links

* [How to Check How Much RAM You Have in Windows 11](https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-contacts-from-sony-by-fonelab-android-recover-contacts/)
* [How to Check RAM Speed and Type in Windows 11](https://facebook-video-content.techidaily.com/updated-in-2024-unlock-social-potential-sharing-panoramic-content-with-facebook/)
* [Get More Details Using PowerShell](https://fox-glue.techidaily.com/new-gb-required-for-one-full-movie-hour-by-hour-for-2024/)

### Key Takeaways

 To check how much RAM is installed in your Windows 11 PC, open the Settings app, navigate to System > About, and then open the "Device Specifications" section. Alternatively, press Ctrl+Shift+Esc to open Task Manager, then navigate to Performance > Memory to view real-time RAM usage and the RAM's speed.

 System [memory](https://android-location-track.techidaily.com/in-2024-how-to-turn-off-google-location-to-stop-tracking-you-on-xiaomi-redmi-note-12r-drfone-by-drfone-virtual-android/), or RAM, is an essential part of any PC running Windows 11\. Too little RAM and your PC might be sluggish, so [more RAM is almost always better](https://tech-revival.techidaily.com/1722056013565-gpt-4-open-for-everyone-plus-still-boasts-6-exclusive-features/). Here's how to check how much RAM you have (and what type and speed it is) in Windows 11.

##  How to Check How Much RAM You Have in Windows 11

 To check your RAM on Windows 11, launch Settings by pressing Windows+i on your keyboard. When Settings opens, click "System" in the sidebar, then select "About."

![The System tab selected, with 'About' indicated.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/click-system-go-to-about.png) 

 On the System > About screen, expand the "Device Specifications" section at the top of the list by clicking it. Just below that, you'll see how much RAM your PC has in the "Installed RAM" section. ("16.0 GB" in our example.)

Close 

 This same screen often comes in handy because it [also shows what type of CPU your PC has](https://network-issues.techidaily.com/how-to-fix-lenovo-laptop-screen-flickering-problem/) in the "Processor" category. If you need to copy these specs to share them later, click the "Copy" button and you can paste them in a message or email as needed.

##  How to Check RAM Speed and Type in Windows 11

 Knowing the [type and speed](https://win-answers.techidaily.com/expert-tips-to-overcome-bless-unleashed-performance-dips-and-elevate-your-gameplay-experience-on-pc/) of the RAM in your PC is essential when [upgrading your RAM](https://fox-that.techidaily.com/effective-solutions-restoring-sync-functionality-for-icloud-photos-on-iphone/). The easiest way to find out is by using Task Manager. To do so, first [open Task Manager](https://on-screen-recording.techidaily.com/new-top-sandbox-adventures-not-to-skip-in-2024/) by right-clicking the Start button and selecting "Task Manager" in the menu. You can also press Ctrl+Shift+Esc to open the Task Manager.

![The Power User Menu on Windows 11.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/right-click-start-menu-task-manager.png) 

 When Task Manager opens, click the "Performance" button on the left, then select "Memory" in the sidebar. If you don't see the Performance tab on the left, click on the hamburger icon towards the upper-left corner of the screen.

![Information about RAM shown in the 'Memory' section of the 'Performance' window.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/ram-shown-in-task-manager.png) 

 On the Memory information screen, look in the upper-right corner of the window. There, you'll see the[total RAM capacity of your PC](https://easy-unlock-android.techidaily.com/in-2024-full-guide-to-unlock-your-oppo-a1x-5g-by-drfone-android/) (such as "16.0 GB," for example). To [see the speed](https://android-location-track.techidaily.com/how-do-i-stop-someone-from-tracking-my-vivo-v27-drfone-by-drfone-virtual-android/) and [type of memory](https://win-answers.techidaily.com/expert-tips-to-overcome-bless-unleashed-performance-dips-and-elevate-your-gameplay-experience-on-pc/) you have installed, look toward the bottom center of Task Manager's "Memory" display. There, you'll find a short list that tells you the [speed](https://youtube-video-recordings.techidaily.com/in-2024-amplify-your-voice-on-youtube-mastery-through-tubebuddy/) and form factor of your [RAM](https://youtube-web.techidaily.com/ed-2024-approved-unlocking-youtube-success-top-video-strategies-to-explode-views/) and also how many [physical RAM slots it uses](https://techidaily.com/how-to-perform-hard-reset-on-samsung-galaxy-a24-drfone-by-drfone-reset-android-reset-android/).

Close 

 Generally, [faster RAM will result in better performance](https://youtube-video-recordings.techidaily.com/in-2024-amplify-your-voice-on-youtube-mastery-through-tubebuddy/), and it is an [easy upgrade](https://fox-that.techidaily.com/effective-solutions-restoring-sync-functionality-for-icloud-photos-on-iphone/) if you're looking to improve your PC's performance.

 When you're done, close Task Manager.

##  Get More Details Using PowerShell

 The user interface in Windows only exposes so much information about your RAM. It won't tell you what type it is (say, DDR4 or DDR5), which slot it is using on your motherboard, nor what the make of your RAM is. If you want that information, you'll need to use PowerShell via the Windows Terminal.

 Open the Start Menu and search **PowerShell**, then select the top result. Alternatively, you can press Window+X and select "Terminal." You don't need to run anything as an administrator, but it won't hurt if you do either.

Close 

 Paste the following command into the Terminal.

Get-CimInstance win32_physicalmemory | Format-Table Manufacturer, @{Name = ‘Speed’;Expression = {“$($_.Speed)” + ‘MHz’}}, @{Name = ‘Capacity’;Expression = {“$($_.Capacity / 1gb)” + ‘GB’}}, MemoryType, Banklabel,Devicelocator,Partnumber -autosize

![The output of our RAM Command.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/output-of-command.png) 

 MemoryType should return a number that tells you what type of RAM you have. For example, 0 means "Unknown," but common values are 25 (DDR3), 26 (DDR4), or 27 (DDR5). If it does return 0, you can just look up the part number to figure out what type of RAM you have instead.

 Check back any time you need to see what kind of RAM you're running. Good luck!

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
