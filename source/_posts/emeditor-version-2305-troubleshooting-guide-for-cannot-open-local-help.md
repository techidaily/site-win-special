---
title: EmEditor Version 23.0.5 - Troubleshooting Guide for 'Cannot Open Local Help'
date: 2024-10-13T18:27:42.256Z
updated: 2024-10-14T20:26:56.568Z
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
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-professional-online-broadcast-capture-methods/"><u>[Updated] 2024 Approved Professional Online Broadcast Capture Methods</u></a></li>
<li><a href="https://win-special.techidaily.com/advanced-text-editing-with-emeditor-professional-702-rc1-powerful-word-processor/"><u>Advanced Text Editing with EmEditor Professional 7.02 RC1 - Powerful Word Processor</u></a></li>
<li><a href="https://change-location.techidaily.com/catch-or-beat-sleeping-snorlax-on-pokemon-go-for-vivo-y77t-drfone-by-drfone-virtual-android/"><u>Catch or Beat Sleeping Snorlax on Pokemon Go For Vivo Y77t | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/catchemall-celebrate-national-pokemon-day-with-virtual-location-on-xiaomi-redmi-note-12-5g-drfone-by-drfone-virtual-android/"><u>CatchEmAll Celebrate National Pokémon Day with Virtual Location On Xiaomi Redmi Note 12 5G | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/desktop-dots-best-notepad-alternatives-for-windows/"><u>Desktop Dots: Best Notepad Alternatives for Windows</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/easy-steps-record-audio-on-mac-using-audacity/"><u>Easy Steps Record Audio on Mac Using Audacity</u></a></li>
<li><a href="https://win-special.techidaily.com/emeditor-pro-advanced-text-replacement-feature-in-version-83-beta-powerful-editing-software/"><u>EmEditor Pro: Advanced Text Replacement Feature in Version 8.3 Beta – Powerful Editing Software</u></a></li>
<li><a href="https://win-special.techidaily.com/emeditors-efficient-sort-and-select-feature-a-comprehensive-guide/"><u>EmEditor's Efficient Sort-and-Select Feature: A Comprehensive Guide</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-detect-and-stop-mspy-from-spying-on-your-honor-play-40c-drfone-by-drfone-virtual-android/"><u>How to Detect and Stop mSpy from Spying on Your Honor Play 40C | Dr.fone</u></a></li>
<li><a href="https://win-special.techidaily.com/how-to-fix-control-plus-tab-issue-in-emeditor-version-9-is-this-a-known-bug/"><u>How to Fix Control + Tab Issue in EmEditor Version 9 - Is This a Known Bug?</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-text-messages-from-motorola-razr-40-ultra-to-new-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Text Messages from Motorola Razr 40 Ultra to New Phone | Dr.fone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-quickfirerecorder-firefox-plugin/"><u>In 2024, QuickFireRecorder Firefox Plugin</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-the-updated-method-to-bypass-tecno-frp-by-drfone-android/"><u>In 2024, The Updated Method to Bypass Tecno FRP</u></a></li>
<li><a href="https://win-special.techidaily.com/mastering-central-european-character-sets-using-emeditor-for-dos-compatible-cp852-encoding/"><u>Mastering Central European Character Sets: Using EmEditor for DOS-Compatible CP852 Encoding</u></a></li>
<li><a href="https://win-special.techidaily.com/simplify-your-experience-with-emeditors-easy-auto-update-and-uninstall-function-join-our-beta/"><u>Simplify Your Experience with EmEditor's Easy Auto-Update and Uninstall Function - Join Our Beta!</u></a></li>
<li><a href="https://win-special.techidaily.com/troubleshooting-overcoming-installation-lockup-in-version-906-of-emeditor-software/"><u>Troubleshooting: Overcoming Installation Lockup in Version 9.06 of EmEditor Software</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918679/19272" target="_top" id="1918679">
  <img src="//a.impactradius-go.com/display-ad/19272-1918679" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918679/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

