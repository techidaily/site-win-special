---
title: EmEditor Version 23.0.5 - Troubleshooting Guide for 'Cannot Open Local Help'
date: 2024-10-07T16:40:42.081Z
updated: 2024-10-08T17:05:37.189Z
tags:
  - product
categories:
  - emeditor
thumbnail: https://thmb.techidaily.com/01781fffdf7ecc74eaf5b3cf4180716493ded8344db51bb91021cea7376b2f5b.jpg
---

## EmEditor Version 23.0.5 - Troubleshooting Guide for 'Cannot Open Local Help'

Viewing 12 posts - 1 through 12 (of 12 total)

* Author  
Posts
* January 11, 2024 at 11:35 pm [#29621](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/05561bcf0e2ddd7cff592202c36eef4f?s=80&d=identicon&r=g)Jamil](https://www.emeditor.com/forums/users/jamil-cloud/ "View Jamil's profile")  
Participant  
Windows 11 Professional on a new computer. Install of 64-bit EmEditor with local help also downloaded and installed: emed\_help\_en\_23.0.5.msi. When I click Help|Search Help Topics I see a dialog asking how do I want to view help. I select Local help option and then must also click a web browser link. My downloaded help is never being opened. After the web help opens I click Help|Search Help Topics a second time for the same dialog asking how do I want to view help to appear again. Locally installed help never opens.  
January 11, 2024 at 11:41 pm [#29622](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/05561bcf0e2ddd7cff592202c36eef4f?s=80&d=identicon&r=g)Jamil](https://www.emeditor.com/forums/users/jamil-cloud/ "View Jamil's profile")  
Participant  
When I click Help|Preference, local help is checked off. It is not being honored.  
January 12, 2024 at 7:47 am [#29623](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
Some issues related to the Help were fixed and improved on the latest preview version. Please update to the latest preview version, and let us know if you still see any issues. Thank you.  
January 13, 2024 at 11:54 am [#29624](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/05561bcf0e2ddd7cff592202c36eef4f?s=80&d=identicon&r=g)Jamil](https://www.emeditor.com/forums/users/jamil-cloud/ "View Jamil's profile")  
Participant  
I installed the preview version to see that local help opens again. Unfortunately, it opens within the EmEditor client that takes real estate from my editing content. It would be helpful if I could undock this help window to make it a floating resizable window. Local help used to do this when I use the editor under Windows 10.  
January 13, 2024 at 2:31 pm [#29625](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
Please go to the Help page of the Customize dialog box, and clear the **Use Web Browser within EmEditor to view Help if available** option. Please also check the **Local Help** option is set. With these settings, the local Help will be displayed in the default browser (such as Microsoft Edge, FireFox, or Chrome). Please note that, starting with version 23.0, the Help file format was changed from a single CHM file to multiple HTML files.  
January 14, 2024 at 12:04 am [#29626](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/05561bcf0e2ddd7cff592202c36eef4f?s=80&d=identicon&r=g)Jamil](https://www.emeditor.com/forums/users/jamil-cloud/ "View Jamil's profile")  
Participant  
Use Web Browser within EmEditor to view Help was never checked. Use local help option is selected. EmEditor continues to open local help within the editor. This is the link that I just copied: file:///C:/ProgramData/Emurasoft/EmEditor/Help/en/index.html. It is not using my default browser that would be FIrefox. I have version Version 23.0.908 installed now.  
January 14, 2024 at 4:41 am [#29627](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/05561bcf0e2ddd7cff592202c36eef4f?s=80&d=identicon&r=g)Jamil](https://www.emeditor.com/forums/users/jamil-cloud/ "View Jamil's profile")  
Participant  
I will simply bookmark the local help URL within my browser to open manually.  
January 15, 2024 at 10:50 am [#29628](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
I couldn’t reproduce the issue. Before you bookmark the local help, how did you open the Help? Did you select **Search Help Topics** on the **Help** menu?  
January 15, 2024 at 11:20 am [#29629](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/05561bcf0e2ddd7cff592202c36eef4f?s=80&d=identicon&r=g)Jamil](https://www.emeditor.com/forums/users/jamil-cloud/ "View Jamil's profile")  
Participant  
Here is a screenshot of the issue and how I reproduced it:  
<https://www.dropbox.com/scl/fi/f6ta40lo064xq7ul3czmd/emeditor%5Fhelp%5Fissue.png?rlkey=j2y1z2rrr9izuzkf33upi9lgn&dl=0>  
January 15, 2024 at 9:20 pm [#29630](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/05561bcf0e2ddd7cff592202c36eef4f?s=80&d=identicon&r=g)Jamil](https://www.emeditor.com/forums/users/jamil-cloud/ "View Jamil's profile")  
Participant  
I installed emed64\_22.5.2.msi and emed\_help\_en\_22.1.0.msi to revert to chm help. Local help opens fine with this version.  
January 18, 2024 at 8:27 pm [#29634](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
I’ve just released v23.0.913, which sets the Use Web Browser within EmEditor to view Help if available option turned off by default. Hopefully, this will resolve the issue.  
January 19, 2024 at 10:59 pm [#29636](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/05561bcf0e2ddd7cff592202c36eef4f?s=80&d=identicon&r=g)Jamil](https://www.emeditor.com/forums/users/jamil-cloud/ "View Jamil's profile")  
Participant  
This version resolved the issue.  
Thank you.
* Author  
Posts

Viewing 12 posts - 1 through 12 (of 12 total)

* You must be logged in to reply to this topic.

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
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-blueprint-for-broadcasting-logging-roblox-games-via-your-mac-hardware/"><u>[New] 2024 Approved Blueprint for Broadcasting Logging Roblox Games via Your Mac Hardware</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-windows-best-facsimile-software-for-ps3-games-for-2024/"><u>[New] Windows' Best Facsimile Software for PS3 Games for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-time-your-shots-perfectly-tips-for-instagrams-slow-motion/"><u>[Updated] 2024 Approved Time Your Shots Perfectly Tips for Instagram’s Slow Motion</u></a></li>
<li><a href="https://win-special.techidaily.com/1-mastering-file-management-utilize-microsoft-365-mobile-app-efficiently/"><u>1. Mastering File Management: Utilize Microsoft 365 Mobile App Efficiently</u></a></li>
<li><a href="https://win-special.techidaily.com/affordable-microsoft-office-2019-deals-get-your-windowsmac-license-for-just-25-read-more-on-zdnet/"><u>Affordable Microsoft Office 2019 Deals: Get Your Windows/Mac License for Just $25 - Read More on ZDNet</u></a></li>
<li><a href="https://win-special.techidaily.com/critical-deadline-approaching-for-microsoft-to-fix-windows-11-issues-in-just-one-year-insights-from-zdnet/"><u>Critical Deadline Approaching for Microsoft to Fix Windows 11 Issues in Just One Year | Insights From ZDNet</u></a></li>
<li><a href="https://program-issues.techidaily.com/how-to-repair-corsair-icue-pairing-problems-in-windows-10-or-11-a-comprehensive-guide/"><u>How to Repair Corsair iCUE Pairing Problems in Windows 10 or 11 - A Comprehensive Guide</u></a></li>
<li><a href="https://win-dash.techidaily.com/step-by-step-guide-downloading-and-updating-amd-rx-480-graphics-drivers/"><u>Step-by-Step Guide: Downloading & Updating AMD RX 480 Graphics Drivers</u></a></li>
<li><a href="https://win-special.techidaily.com/transforming-update-strategies-critical-facts-about-microsofts-refreshed-windows-update-process-cyberwise-chronicles/"><u>Transforming Update Strategies: Critical Facts About Microsoft's Refreshed Windows Update Process | CyberWise Chronicles</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/unveiling-the-best-5-tools-for-youtube-video-url-shortening/"><u>Unveiling the Best 5 Tools for YouTube Video URL Shortening</u></a></li>
<li><a href="https://win-special.techidaily.com/unveiling-the-future-of-productivity-with-microsoft-surface-laptop-studio-a-first-look-that-will-make-you-want-more/"><u>Unveiling the Future of Productivity with Microsoft Surface Laptop Studio - A First Look That Will Make You Want More</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135404/19272" target="_top" id="2135404">
  <img src="//a.impactradius-go.com/display-ad/19272-2135404" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135404/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

