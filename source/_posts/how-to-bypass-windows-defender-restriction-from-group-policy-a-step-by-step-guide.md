---
title: "How to Bypass Windows Defender Restriction From Group Policy: A Step-by-Step Guide"
date: 2024-11-21T18:37:00.817Z
updated: 2024-11-26T17:35:25.388Z
tags:
  - product
  - antivirus
  - utilities
categories:
  - malwarefox
thumbnail: https://thmb.techidaily.com/f567a9fec699d773d0b269b2abfaf091f129a875a6f111520a97150e50266041.jpg
---

## How to Bypass Windows Defender Restriction From Group Policy: A Step-by-Step Guide

With the growing cyber threats, a good security solution is the need of the hour. Windows users have the luxury of a robust security program, **Windows Defender**, which is now known as **Microsoft Defender**. It comes in-built into the latest Windows 10 devices. 

![TotalAv Logo](https://www.malwarefox.com/wp-content/uploads/2024/02/totalav-svg.webp "totalav-svg")

**Stay malware-free with reliable antivirus**

Don't compromise your Data and Privacy. TotalAV is a top-notch antivirus program that handles various viruses, trojans, and other malware that may target your devices. It will safeguard your devices and enhance your system performance.

**4.9**/5

⭐ **Editor's Choice**

✔️ Excellent Malware Detection  
✔️ Multiple set of Features  
✔️ 30 Day Money-Back

[](https://tools.techidaily.com/malwarefox/products/) Get TotalAV > 

Taking lessons from the backlashes it receives after its initial release, Microsoft made some necessary security changes. Today, Microsoft Defender is one of the [top antivirus solutions](https://tools.techidaily.com/malwarefox/products/) in the cybersecurity field and used by millions of users.

However, this extensive security program can malfunction and stop working because of a few errors caused intentionally to stop it; one of those errors is “**Windows Defender blocked by Group Policy**.” 

In this guide, we would list out the possible fixes for this error.

[Is Windows Defender Enough?](https://tools.techidaily.com/malwarefox/products/)

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Why “Windows Defender blocked by Group Policy” Error Occurs?

There could be a number of reasons for this error to happen. Here are the most common ones.

* Another [third-party antivirus](https://tools.techidaily.com/malwarefox/products/) or antimalware is clashing with the Windows Defender program.
* Cybercriminals might have used infiltrate Group Policy using [malware](https://tools.techidaily.com/malwarefox/products/) to disable the security of the Windows system.
* Some unauthorized changes in the Group Policies can also lead to the error. The changes can be made by mistake or intentionally too.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/slm2NjVPNtk?si=9ow6g1ucmf0TnT4T&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to fix “Windows Defender is Turned off by Group Policy”?

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LI9nKlbhnw8?si=uUXFVbuEqXtFHHv0&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### **Using Group Policy Editor**

**_Note_**_: The Group Policy Editor is not available on the Windows 10 Home version_

1. Search for the **Group Policy Editor** in the windows search bar and launch it.![Open Group Policy Editor](https://www.malwarefox.com/wp-content/uploads/2020/06/Group-Policy-Editor.png)
2. In the editor, navigate to: **Computer Configuration** \-> **Administrative Templates** \-> **Windows Components** \-> **Microsoft Defender Antivirus**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/poI1NQxHfjc?si=ZLG0wziYcTKIKwL5&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3. Locate “**Turn off Microsoft Defender Antivirus**” and double click on it to open it.![Turn Off Microsoft Defender Antivirus](https://www.malwarefox.com/wp-content/uploads/2020/10/Turn-Off-Microsoft-Defender-Antivirus.png)
4. In order to enable the Microsoft Defender, click on the **Disabled** bullet.![Enable-MS-Defender](https://www.malwarefox.com/wp-content/uploads/2020/10/Enable-MS-Defender.png)

5. Click **Apply** and **OK** to finish the configuration.
6. Restart the system to enable the settings.

---

### **Using Registry Editor**

1. Search for “**Registry Editor**” in the windows search box and launch it.![launch registry editor](https://www.malwarefox.com/wp-content/uploads/2020/10/launch-registry-editor.png)
2. Navigate to or copy & paste this path to reach the Windows Defender folder: **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Policies\\Microsoft\\Windows Defender**

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PUDdKOsEN74?si=tkZf-KVinjuwmgx9&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3. Right-click on the **DisableRealTimeMonitoring** key and Delete it.![Delete DisableRealtimeMonitoring key](https://www.malwarefox.com/wp-content/uploads/2020/10/Delete-DisableRealtimeMonitoring-key.png)
4. Exit from the Registry Editor and reboot your system to apply the changes.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/8U3ooyFiAB4?si=yXPQrDhMBEJwN2EZ&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

---

---

### **Using the PowerShell Command**

1. Search for the **Windows Powershell** in the Windows search box and select **Run as Administrator.**![PowerShell Run as Admin](https://www.malwarefox.com/wp-content/uploads/2020/10/PowerShell-Run-as-Admin.jpg)
2. Type or copy & paste this command and hit the enter key: **_Set-MpPreference -DisableRealtimeMonitoring 0_**![Enable MS defender with Powershell](https://www.malwarefox.com/wp-content/uploads/2020/10/Enable-MS-defender-with-Powershell.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wNhKhWc0wLc?si=1XLYV0sXV52Xc0lu&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/it8VkxDUdAc?si=ef6VZWR7kW4P9ikh&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

---

### **Using Windows Settings**

1. Right-click on the windows start icon and choose Settings from the list.![Settings](https://www.malwarefox.com/wp-content/uploads/2020/10/Settings.png)
2. Select **Update & Security** settings.![Update and Security](https://www.malwarefox.com/wp-content/uploads/2020/10/Update-and-Security.png)

3. From the left-pane choose **Windows Security**![launch windows security](https://www.malwarefox.com/wp-content/uploads/2020/10/launch-windows-security.png)

4. Next, click on **Virus & threat protection**.![Choose virus & threat protection](https://www.malwarefox.com/wp-content/uploads/2020/10/Choose-virus-threat-protection.png)

5. Navigate to Virus & threat protection settings and click on **Manage settings**.![manage V&T settings](https://www.malwarefox.com/wp-content/uploads/2020/10/manage-VT-settings.png)

6. Toggle the switch to turn on the Microsoft Defender **real-time protection**.![turn On the Real Time protection](https://www.malwarefox.com/wp-content/uploads/2020/10/turn-On-the-RT-protection.png)

---

### **Disable the Third-Party Security App**

The “Windows Defender blocked by Group Policy” error can also be caused if any third-party application has conflicts with the Defender. So, if you really require Windows Defender to run, try disabling the third-party antimalware or antivirus application and then launch the Defender app.

[How to Choose Best Antivirus for Windows 10](https://tools.techidaily.com/malwarefox/products/)

---

## Final Words

These are the top working solutions to fix the Windows Defender blocked by Group Policy error. If you apply the steps correctly, you would be able to run the Defender application eventually. However, if the problem persists even after trying the above methods, you can get the robust security solutions like **[Malwarefox](https://tools.techidaily.com/malwarefox/products/)**, that can provide better protection than the Microsoft Defender.

**Why my Windows Defender is turned off?** 

Windows Defender on your system can be turned off because of the various reasons like any third-party security app is conflicting with it, or a malware attack has infiltrated and modified the settings to disable it.

**Where is Windows Defender in group policy?** 

To edit the Windows Defender settings in the group policy editor, you can follow this path: **Local Computer Policy > Administrative Templates > Windows Components > Windows Defender Antivirus.** In the latest Windows version, the name of the Windows Defender is changed to **Microsoft Defender.** On those systems, the path to be followed is: **Local Computer Policy > Administrative Templates > Windows Components > Microsoft Defender Antivirus**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0pSRlspzW-A?si=A82G3Yxwj_31cKDq&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Leave a Comment [Cancel reply](https://tools.techidaily.com/malwarefox/products/)

Comment

Name Email 

Save my name, email, and website in this browser for the next time I comment.

Δ

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
<li><a href="https://youtube-video-recordings.techidaily.com/new-enhance-your-online-skills-a-guide-to-youtube-editing-via-sony-vegas/"><u>[New] Enhance Your Online Skills A Guide to YouTube Editing via Sony Vegas</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-explore-the-best-ways-to-record-sound-in-your-latest-windows-11-pc/"><u>[Updated] Explore the Best Ways to Record Sound in Your Latest Windows 11 PC</u></a></li>
<li><a href="https://win-special.techidaily.com/2windows-server-201-query-what-are-the-different-types-of-clouds-and-how-do-they-form/"><u>2層入門：Windows Server 201 # Query: What Are the Different Types of Clouds and How Do They Form?</u></a></li>
<li><a href="https://extra-tips.techidaily.com/detailed-synopsis-gopro-silver-hero4-model-review/"><u>Detailed Synopsis GoPro Silver Hero4 Model Review</u></a></li>
<li><a href="https://win-dash.techidaily.com/easy-to-use-sm-bus-controller-driver-available-now-ideal-for-windows-11-10-8-and-7-users/"><u>Easy-to-Use SM Bus Controller Driver Available Now: Ideal for Windows 11, 10, 8 & 7 Users</u></a></li>
<li><a href="https://win-special.techidaily.com/effortlessly-achieve-complete-xcopy-mirror-file-replication-with-these-essential-steps/"><u>Effortlessly Achieve Complete Xcopy Mirror File Replication with These Essential Steps</u></a></li>
<li><a href="https://win-special.techidaily.com/explore-the-different-shades-of-hacker-skillsets-from-white-hat-pioneers-to-black-hat-villains-and-everything-in-between/"><u>Explore the Different Shades of Hacker Skillsets: From White Hat Pioneers to Black Hat Villains and Everything in Between</u></a></li>
<li><a href="https://article-helps.techidaily.com/in-2024-essential-strategies-for-finding-fabulous-and-free-images-on-pexels/"><u>In 2024, Essential Strategies for Finding Fabulous and Free Images on Pexels</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-everything-you-need-to-know-about-lock-screen-settings-on-your-oppo-a2-by-drfone-android/"><u>In 2024, Everything You Need to Know about Lock Screen Settings on your Oppo A2</u></a></li>
<li><a href="https://win-special.techidaily.com/simple-steps-make-your-own-bootable-usb-stick-to-restore-windows-server-2t99/"><u>Simple Steps: Make Your Own Bootable USB Stick to Restore Windows Server 2T99</u></a></li>
<li><a href="https://howto.techidaily.com/stuck-at-android-system-recovery-of-oneplus-open-fix-it-easily-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Stuck at Android System Recovery Of OnePlus Open ? Fix It Easily | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-ultimate-zoom-video-enhancement-playbook-for-2024/"><u>The Ultimate Zoom Video Enhancement Playbook for 2024</u></a></li>
<li><a href="https://win-special.techidaily.com/top-ranking-free-sandisk-cruzer-blade-file-retrieval-tools/"><u>Top Ranking Free Sandisk Cruzer Blade File Retrieval Tools</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/when-order-falls-premium-lineup-of-best-zombie-games/"><u>When Order Falls Premium Lineup of Best Zombie Games</u></a></li>
<li><a href="https://win-special.techidaily.com/windows-7-8-or-10hddssd/"><u>Windows 7, 8, or 10のHDDをSSDへシンプルなクローニング手順</u></a></li>
<li><a href="https://win-special.techidaily.com/1728500268518-windows-server/"><u>Windows Serverでスケジュールされた自動バックアップを中断する手順</u></a></li>
<li><a href="https://win-special.techidaily.com/windowswbadmin/"><u>WindowsのWbadminツールを用いて特定リソースのバックアップ作りガイド: 詳細な手引きと効果的戦略</u></a></li>
</ul></div>

