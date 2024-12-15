---
title: Troubleshooting the Use of Terminal Font in EmEditor Text Editor
date: 2024-12-12T09:43:08.655Z
updated: 2024-12-14T21:51:30.202Z
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
<li><a href="https://youtube-tips.techidaily.com/fficiently-uploading-youtube-vids-to-insta-profile-for-2024/"><u>[New] Efficiently Uploading YouTube Vids to Insta Profile for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-elevate-your-recording-game-with-nvidias-tools/"><u>[New] In 2024, Elevate Your Recording Game with NVIDIA's Tools</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-elevate-your-content-top-rated-cameras-for-youtubers/"><u>[Updated] 2024 Approved Elevate Your Content Top-Rated Cameras for YouTubers</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/audi-a3-mk7-2019-ultimate-picture-showcase-with-crisp-hd-walls-images-and-visuals-yl-computings-premium-selection/"><u>Audi A3 (MK7) 2019 Ultimate Picture Showcase with Crisp HD Walls, Images & Visuals – YL Computing's Premium Selection</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/capture-lifes-moments-with-nokia-71-outstanding-display-superior-camera-and-wallet-friendly-price/"><u>Capture Life's Moments with Nokia 7.1 – Outstanding Display, Superior Camera, and Wallet-Friendly Price</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/diy-ipad-battery-swap-tutorial-for-extended-device-life/"><u>DIY iPad Battery Swap Tutorial for Extended Device Life</u></a></li>
<li><a href="https://extra-information.techidaily.com/gliding-heroes-the-2022-winter-games/"><u>Gliding Heroes The 2022 Winter Games</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/high-definition-devil-may-cry-hd-wallpaper-collection-stunning-visuals-and-graphics-from-yl-computings-exclusive-library/"><u>High-Definition Devil May Cry HD Wallpaper Collection: Stunning Visuals & Graphics From YL Computing's Exclusive Library</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/how-can-i-determine-if-my-sound-card-is-at-fault-expert-advice-from-yl-computing/"><u>How Can I Determine If My Sound Card Is at Fault? - Expert Advice From YL Computing</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/how-to-fix-computer-stalling-problems-linked-to-graphics-drivers-expert-advice-by-yl-software-solutions/"><u>How to Fix Computer Stalling Problems Linked to Graphics Drivers - Expert Advice by YL Software Solutions</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/identifying-key-hardware-checks-for-optimal-performance-with-yl-software-solutions/"><u>Identifying Key Hardware Checks for Optimal Performance with YL Software Solutions</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-getting-the-pokemon-go-gps-signal-not-found-11-error-in-oppo-reno-9a-drfone-by-drfone-virtual/"><u>In 2024, Getting the Pokemon Go GPS Signal Not Found 11 Error in Oppo Reno 9A | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-can-oneplus-nord-ce-3-5gmirror-share-to-pc-drfone-by-drfone-android/"><u>In 2024, How Can OnePlus Nord CE 3 5GMirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-top-picks-the-ultimate-android-mp3-downloader-collection/"><u>In 2024, Top Picks The Ultimate Android MP3 Downloader Collection</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/modifying-your-desktop-shortcuts-and-symbols-for-efficiency-insights-from-yl-software-experts/"><u>Modifying Your Desktop Shortcuts & Symbols for Efficiency: Insights From YL Software Experts</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/solve-your-pcs-network-connection-errors-with-ease-using-our-expert-tips-from-yl-software/"><u>Solve Your PC's Network Connection Errors with Ease Using Our Expert Tips From YL Software</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/step-by-step-guide-adding-files-to-zip-archives-on-windows-tips-from-yl-computing/"><u>Step-by-Step Guide: Adding Files to Zip Archives on Windows - Tips From YL Computing</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/step-by-step-guide-locating-files-on-your-pc-using-windows-insights-by-yl-computing/"><u>Step-by-Step Guide: Locating Files on Your PC Using Windows - Insights by YL Computing</u></a></li>
<li><a href="https://technical-tips.techidaily.com/transformar-videos-mod-directamente-a-wmv-por-internet-gratis-mediante-any-video-converter-limpieza-y-conversion-en-linea-completa/"><u>Transformar Videos MOD Directamente a WMV Por Internet Gratis Mediante Any Video Converter - Limpieza Y Conversión en Línea Completa</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xq2r4ZKM-Po?si=fA2DdEB1op-atCkz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

