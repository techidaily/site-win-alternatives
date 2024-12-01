---
title: Troubleshooting the Use of Terminal Font in EmEditor Text Editor
date: 2024-11-25T17:54:08.216Z
updated: 2024-12-01T04:27:47.100Z
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
<li><a href="https://youtube-web.techidaily.com/rom-flv-to-youtube-stardom-top-10-video-conversion-tools-reviewed/"><u>[New] From FLV to YouTube Stardom Top 10 Video Conversion Tools Reviewed</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-scrutinizing-the-latest-in-screen-recording-tech-by-tunefab/"><u>[Updated] Scrutinizing the Latest in Screen Recording Tech by Tunefab</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/2024windowstop5/"><u>2024年度ご活躍！Windows専用クローンプログラムTOP5 - 無料版と有料版の違い</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/1728484204754-windows-server-2022/"><u>工場出荷時の復元方法として最高のWindows Server ‣2022リセット手順を解明する：上位二つの技術</u></a></li>
<li><a href="https://win-data.techidaily.com/mybook/"><u>恢复碎片区的详解 - MyBook学习方法</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/1728490923506-windows-11/"><u>簡單操作的方法:Windows 11 轉移至新電腦的過程及其相關許可</u></a></li>
<li><a href="https://win-howtos.techidaily.com/expert-tips-to-fix-crashing-videos-with-dxgkrnl-errors-on-your-pc/"><u>Expert Tips to Fix Crashing Videos with Dxgkrnl Errors on Your PC</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-snaps-in-a-flash-directly-upload-images-from-camera-roll/"><u>In 2024, Snaps in a Flash Directly Upload Images From Camera Roll</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/mkvtoolnix-for-mac-the-easiest-way-to-edit-videos-for-2024/"><u>MKVtoolnix for Mac The Easiest Way to Edit Videos for 2024</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-2024-approved-final-cut-pro-x-for-filmmakers-creating-visually-stunning-videos/"><u>New 2024 Approved Final Cut Pro X for Filmmakers Creating Visually Stunning Videos</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-best-free-video-splitters-for-mkv-files-updated-2023/"><u>New In 2024, Best Free Video Splitters for MKV Files (Updated 2023)</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/resetting-files-after-clean-install-on-windows-10-and-11-comprehensive-guide/"><u>Resetting Files After Clean Install on Windows 10 and 11 - Comprehensive Guide</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/resolving-issues-why-your-itunes-cant-add-items-to-windows-devices-and-how-to-overcome-it/"><u>Resolving Issues: Why Your iTunes Can't Add Items to Windows Devices and How to Overcome It</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/step-by-step-guide-transforming-a-physical-pc-into-a-vmware-virtual-machine/"><u>Step-by-Step Guide: Transforming a Physical PC Into a VMware Virtual Machine</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/ultimate-tutorial-step-by-step-process-for-successfully-downloading-and-setting-up-rsat-on-windows-11/"><u>Ultimate Tutorial: Step-by-Step Process for Successfully Downloading & Setting Up RSAT on Windows 11</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-in-2024-find-a-solution-for-effortless-sky-replacement-photoshop-in-this-comprehensive-guide-also-use-the-easiest-video-editing-tool-to-make-your-me/"><u>Updated In 2024, Find a Solution for Effortless Sky Replacement Photoshop in This Comprehensive Guide. Also, Use the Easiest Video Editing Tool to Make Your Media Stunning</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/diskgenius/"><u>データ管理上手：DiskGeniusの代用となる無料ストレージソフトウェアをご紹介</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLO5dwmJAVs?si=1OYH8rv8aPaMsCiU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

