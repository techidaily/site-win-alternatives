---
title: Troubleshooting the Use of Terminal Font in EmEditor Text Editor
date: 2024-10-12T16:05:26.326Z
updated: 2024-10-17T16:05:12.802Z
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
<li><a href="https://extra-skills.techidaily.com/new-top-8-photo-grid-online-makers-to-polish-your-pictures/"><u>[New] Top 8 Photo Grid Online Makers to Polish Your Pictures</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-top-5-budget-friendly-methods-for-live-feed-recordings/"><u>[Updated] 2024 Approved Top 5 Budget-Friendly Methods for Live Feed Recordings</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-from-conference-call-to-online-showcase-google-meet-on-youtube-for-2024/"><u>[Updated] From Conference Call to Online Showcase Google Meet on YouTube for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-the-ultimate-resource-for-instagram-livestreams-via-obs-software/"><u>[Updated] In 2024, The Ultimate Resource for Instagram Livestreams via OBS Software</u></a></li>
<li><a href="https://win-marvelous.techidaily.com/after-effects-unsaved-aep/"><u>After Effects: 破棄前のunsaved AEPファイルを回復するステップ</u></a></li>
<li><a href="https://unlock-android.techidaily.com/best-xiaomi-redmi-note-12r-pattern-lock-removal-tools-remove-android-pattern-lock-without-losing-data-by-drfone-android/"><u>Best Xiaomi Redmi Note 12R Pattern Lock Removal Tools Remove Android Pattern Lock Without Losing Data</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/choisissez-entre-hdd-et-ssd-decouvrez-les-principaux-avantages-et-inconvenients-pour-optimiser-votre-stockage-numerique/"><u>Choisissez Entre HDD Et SSD - Découvrez Les Principaux Avantages Et Inconvénients Pour Optimiser Votre Stockage Numérique</u></a></li>
<li><a href="https://win-amazing.techidaily.com/easy-access-to-logitech-windows-drivers-quick-download-guide/"><u>Easy Access to Logitech Windows Drivers – Quick Download Guide</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/les-3-meilleurs-choix-de-sauvegarde-des-donnees-en-2024-avantages-et-defis-compares-a-backblaze/"><u>Les 3 Meilleurs Choix De Sauvegarde Des Données en 2024: Avantages Et Défis Comparés À Backblaze</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/missing-content-alert-unable-to-locate-your-request-error-similar-problem/"><u>Missing Content Alert: Unable to Locate Your Request (Error # Similar Problem)</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/move-your-iphone-data-directly-to-another-iphone-bypassing-icloud/"><u>Move Your iPhone Data Directly to Another iPhone, Bypassing iCloud</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-the-best-of-the-best-4k-video-editing-software-for-professionals/"><u>New The Best of the Best 4K Video Editing Software for Professionals</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/recovering-lost-webp-images-a-step-by-step-guide/"><u>Recovering Lost WebP Images: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/tecnicas-seguros-para-clonacion-e-instalacion-de-un-sistema-operativo-en-diferentes-plataformas-de-hardware/"><u>Técnicas Seguros Para Clonación E Instalación De Un Sistema Operativo en Diferentes Plataformas De Hardware</u></a></li>
<li><a href="https://discover-guides.techidaily.com/transformation-gratuite-de-fichiers-pcx-en-images-jpeg-sur-internet-mouvavi/"><u>Transformation Gratuite De Fichiers PCX en Images JPEG Sur Internet - Mouvavi</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/unlocking-the-differences-comparative-analysis-of-stability-in-windows-11-vs-windows-10/"><u>Unlocking the Differences: Comparative Analysis of Stability in Windows 11 Vs. Windows 10</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1975807/19272" target="_top" id="1975807">
  <img src="//a.impactradius-go.com/display-ad/19272-1975807" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975807/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

