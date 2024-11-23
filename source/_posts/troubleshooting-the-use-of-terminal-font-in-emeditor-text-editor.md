---
title: Troubleshooting the Use of Terminal Font in EmEditor Text Editor
date: 2024-11-16T18:46:16.217Z
updated: 2024-11-22T23:54:46.479Z
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
<li><a href="https://extra-skills.techidaily.com/new-seamless-switch-to-virtual-reality-your-phones-next-step/"><u>[New] Seamless Switch to Virtual Reality Your Phone's Next Step</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-step-by-step-guide-to-protected-youtube-to-mp3-conversions/"><u>[New] Step-by-Step Guide to Protected YouTube-to-MP3 Conversions</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-the-definitive-list-of-cam-covers-for-secure-shopping/"><u>[New] The Definitive List of Cam Covers for Secure Shopping</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/1-successful-migration-strategies-transitioning-from-an-existing-esxi-server-to-a-new-machine/"><u>1. Successful Migration Strategies: Transitioning From an Existing ESXi Server to a New Machine</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-easy-ways-to-copy-contacts-from-motorola-moto-g73-5g-to-iphone-14-and-15-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Easy Ways to Copy Contacts from Motorola Moto G73 5G to iPhone 14 and 15 | Dr.fone</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/best-free-programs-for-recovering-deletedformatted-documents-downloading-and-using-iso-file-reconstruction-tools/"><u>Best Free Programs for Recovering Deleted/Formatted Documents: Downloading and Using ISO File Reconstruction Tools</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ors-uniting-for-marvels-digital-future/"><u>Creators Uniting for Marvel's Digital Future</u></a></li>
<li><a href="https://some-techniques.techidaily.com/impress-your-pals-as-a-fake-linux-guru-with-just-5-hilarious-bash-tricks/"><u>Impress Your Pals as a Fake Linux Guru with Just 5 Hilarious Bash Tricks</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-bass-bridges-and-high-beats-understanding-sound-mixing/"><u>In 2024, Bass Bridges & High Beats Understanding Sound Mixing</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-your-account-has-been-disabled-in-the-app-store-and-itunes-on-iphone-xs-max-by-drfone-ios/"><u>In 2024, Your Account Has Been Disabled in the App Store and iTunes On iPhone XS Max?</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/resolve-clonezilla-errors-caused-by-mbrgpt-format-inconsistencies-a-three-step-guide/"><u>Resolve Clonezilla Errors Caused by MBR/GPT Format Inconsistencies: A Three-Step Guide</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/titre-seo-probleme-de-sauvegarde-avec-windows-11-comment-resoudre-le-dysfonctionnement/"><u>Titre SEO: Problème De Sauvegarde Avec Windows 11 : Comment Résoudre Le Dysfonctionnement ?</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/top-ranking-windows-10-data-duplication-applications-your-ultimate-guide/"><u>Top-Ranking Windows 10 Data Duplication Applications: Your Ultimate Guide</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/ultimate-windows-1111-notebook-hdd-upgrade-tutorial-avoid-rebuilding-your-os-easily/"><u>Ultimate Windows 11/11 Notebook HDD Upgrade Tutorial: Avoid Rebuilding Your OS Easily!</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/unveiling-the-top-features-of-kensuns-travel-friendly-tire-pump-a-reliable-review/"><u>Unveiling the Top Features of Kensun's Travel-Friendly Tire Pump – A Reliable Review</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RhLjZsruC9M?si=-861oUSfrUde2Ykt&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

