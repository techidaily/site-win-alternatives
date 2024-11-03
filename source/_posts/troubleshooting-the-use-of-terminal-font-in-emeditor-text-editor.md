---
title: Troubleshooting the Use of Terminal Font in EmEditor Text Editor
date: 2024-11-02T16:04:25.840Z
updated: 2024-11-03T21:56:52.729Z
tags:
  - product
categories:
  - emeditor
thumbnail: https://thmb.techidaily.com/77d3e1b90c90a1223bd94c398f31bb9940ba742ed134b8bf4a5fe9e955fed55f.jpg
---

## Troubleshooting the Use of Terminal Font in EmEditor Text Editor

Viewing 4 posts - 1 through 4 (of 4 total)

* Author  
Posts
* March 18, 2008 at 5:18 am [#5584](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/752c4f319bff640acf6a4d657924ad4d?s=80&d=identicon&r=g)Alekhe](https://www.emeditor.com/forums/users/Alekhe/ "View Alekhe's profile")  
Member  
I’ve got some problems using bitmap Terminus font (I’m using ter-c12n) in EmEditor 7 (tested on 7002 and 7003).  
 When I type dot “.” the whole line’s font changes to another one. Or maybe it’s just wrong letter-spacing:  
 Same text in EmEditor 6 is OK:  
 What could it be?  
March 18, 2008 at 6:03 am [#5585](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
> Alekhe wrote:  
> I’ve got some problems using bitmap Terminus font (I’m using ter-c12n) in EmEditor 7 (tested on 7002 and 7003).  
> When I type dot “.” the whole line’s font changes to another one. Or maybe it’s just wrong letter-spacing:  
>  
> Same text in EmEditor 6 is OK:  
>  
> What could it be?  
 I am not sure why this font has the issue, but can you please try this work around:  
 Run RegEdit.exe, and add “UseUniscribe” value as DWORD in the following key:  
 HKEY\_CURRENT\_USERSoftwareEmSoftEmEditor v3Common  
 and UseUniscribe = 0  
 Please let me know if this works.  
March 20, 2008 at 3:34 am [#5594](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/752c4f319bff640acf6a4d657924ad4d?s=80&d=identicon&r=g)Alekhe](https://www.emeditor.com/forums/users/Alekhe/ "View Alekhe's profile")  
Member  
It works perfect. Thanks a lot!  
 I added “UseUniscribe = 0” into eeCommon.ini for portable version.  
 What does this option affect on? Any unicode restrictions?  
 BWT, sorry for late answer. I haven’t received any notification by e-mail (I didn’t expect the default behavior is to notify by PM, not an e-mail).  
March 21, 2008 at 12:26 am [#5595](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
> Alekhe wrote:  
> It works perfect. Thanks a lot!  
>  
> I added “UseUniscribe = 0” into eeCommon.ini for portable version.  
>  
> What does this option affect on? Any unicode restrictions?  
>  
> BWT, sorry for late answer. I haven’t received any notification by e-mail (I didn’t expect the default behavior is to notify by PM, not an e-mail).  
 Well, that is related to text draw engine in Windows. You can google “Uniscribe” to find about it more.  
 For notifications, you can choose how you get notifications from your profile (Edit Account under User Menu).
* Author  
Posts

Viewing 4 posts - 1 through 4 (of 4 total)

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
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-the-ultimate-tutorial-iphoneipad-time-lapse-recording/"><u>[New] In 2024, The Ultimate Tutorial IPhone/iPad Time Lapse Recording</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/1-descubre-la-diferencia-entre-variantes-de-rescate-una-vision-general-comparativa-de-aomei-onekey/"><u>1. Descubre La Diferencia Entre Variantes De Rescate: Una Visión General Comparativa De AOMEI OneKey</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-phantom-gag-craftsman/"><u>2024 Approved Phantom Gag Craftsman</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-the-insiders-guide-to-recording-games-in-windows-11/"><u>2024 Approved The Insider's Guide to Recording Games in Windows 11</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/1728470152846-windows-11108/"><u>在Windows 11、10或8上進行外接硬碟備份與同步手段 - 多項解決方案導讀</u></a></li>
<li><a href="https://win-howtos.techidaily.com/bypassing-and-repairing-disk-write-errors-in-steam-with-simple-techniques/"><u>Bypassing and Repairing Disk Write Errors in Steam with Simple Techniques</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/discover-the-power-of-aomei-image-deploy-for-hassle-free-free-image-automation/"><u>Discover the Power of AOMEI Image Deploy for Hassle-Free Free Image Automation</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/ensuring-digital-safety-mastering-your-systems-backup-preferences-and-procedures/"><u>Ensuring Digital Safety: Mastering Your System's Backup Preferences and Procedures</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/expert-strategies-for-restoring-lost-data-following-a-fresh-windows-10-installation/"><u>Expert Strategies for Restoring Lost Data Following a Fresh Windows 10 Installation</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-infinix-hot-30-5g-phone-without-password-by-drfone-android/"><u>How To Unlock Infinix Hot 30 5G Phone Without Password?</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/movmp4-vlc/"><u>MOVからMP4への変換 – VLCユーザー向け最適化戦略</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/procedures-simples-pour-activer-la-sauvegarde-programmee-sur-le-serveur-windows/"><u>Procédures Simples Pour Activer La Sauvegarde Programmée Sur Le Serveur Windows</u></a></li>
<li><a href="https://tech-revival.techidaily.com/protecting-privacy-how-not-to-save-conversations-with-chatgpt/"><u>Protecting Privacy: How Not to Save Conversations with ChatGPT</u></a></li>
<li><a href="https://win-able.techidaily.com/smooth-gameplay-in-lost-ark-addressing-fps-fluctuations-and-ensuring-optimal-performance/"><u>Smooth Gameplay in Lost Ark: Addressing FPS Fluctuations & Ensuring Optimal Performance</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/step-by-step-guide-activating-hyper-v-remote-management-features/"><u>Step-by-Step Guide: Activating Hyper-V Remote Management Features</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/the-ultimate-guide-to-securely-erasing-images-from-your-ios-devices-memory/"><u>The Ultimate Guide to Securely Erasing Images From Your iOS Device's Memory</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/to-purchase-or-not-to-purchase-a-blu-ray-player-guide/"><u>To Purchase or Not to Purchase – A Blu-Ray Player Guide</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134494/18498" target="_top" id="2134494">
  <img src="//a.impactradius-go.com/display-ad/18498-2134494" border="0" alt="https://techidaily.com" width="721" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134494/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

