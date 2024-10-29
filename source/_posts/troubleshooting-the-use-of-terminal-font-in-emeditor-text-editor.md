---
title: Troubleshooting the Use of Terminal Font in EmEditor Text Editor
date: 2024-10-28T05:27:24.947Z
updated: 2024-10-28T19:50:47.629Z
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
<li><a href="https://win-alternatives.techidaily.com/windows-1087-11/"><u>無償恢復 Windows 10、8、7 與 11 中被磁碟分割的隔空</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/difficultes-de-clonage-du-systeme-avec-transcend-ssd-le-defi-des-fonctions-non-operationnelles/"><u>Difficultés De Clonage Du Système Avec Transcend SSD : Le Défi Des Fonctions Non Opérationnelles</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-breaking-down-the-free-fcp-puzzle/"><u>In 2024, Breaking Down The Free FCP Puzzle</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-comparing-micro-video-formats-the-battle-of-tiktok-and-youtube-shorts/"><u>In 2024, Comparing Micro-Video Formats The Battle of TikTok and YouTube Shorts</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-leveraging-hashtags-for-a-huge-impact-on-your-youtube-views/"><u>In 2024, Leveraging #Hashtags for a Huge Impact on Your YouTube Views</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-unlocking-optimal-flight-the-lipo-selection-saga/"><u>In 2024, Unlocking Optimal Flight The LiPo Selection Saga</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/paso-a-paso-como-convertir-tu-computadora-fisica-en-una-maquina-virtual-con-windows-11-8-o-7/"><u>Paso a Paso: Cómo Convertir Tu Computadora Física en Una Máquina Virtual Con Windows 11, 8 O 7</u></a></li>
<li><a href="https://data-wizards.techidaily.com/reclaiming-lost-parts-of-an-mp4-file/"><u>Reclaiming Lost Parts of an MP4 File</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolved-semaphore-timeout-error-code-0x80070079-now-fixed/"><u>Resolved: 'Semaphore Timeout Error Code 0X80070079' Now Fixed</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/step-by-step-tutorial-for-cloning-vms-on-vmware-esxi-including-methods-both-with-and-without-vcenter-support/"><u>Step-by-Step Tutorial for Cloning VMs on VMware ESXi - Including Methods Both with and without vCenter Support</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/strategies-for-restoring-accidentally-erased-or-corrupted-autodesk-autocad-documents/"><u>Strategies for Restoring Accidentally Erased or Corrupted Autodesk AutoCAD Documents</u></a></li>
<li><a href="https://win-outstanding.techidaily.com/switching-layouts-in-your-e-book-creation-a-step-by-step-guide-with-flipbuilder/"><u>Switching Layouts in Your E-Book Creation: A Step-by-Step Guide with FlipBuilder</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/top-5-best-ps1-emulators-for-pc/"><u>Top 5 Best Ps1 Emulators for PC</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/ultimate-guide-to-the-best-hard-drive-copying-software-compatible-with-windows-systems/"><u>Ultimate Guide to the Best Hard Drive Copying Software Compatible with Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-not-just-linux-no-more-windows-subsystem/"><u>Why Not Just Linux? No More Windows Subsystem</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151884/7443" target="_top" id="2151884">
  <img src="//a.impactradius-go.com/display-ad/7443-2151884" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151884/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

