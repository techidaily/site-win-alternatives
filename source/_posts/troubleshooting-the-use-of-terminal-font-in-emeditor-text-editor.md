---
title: Troubleshooting the Use of Terminal Font in EmEditor Text Editor
date: 2024-11-08T18:19:05.033Z
updated: 2024-11-13T00:43:45.347Z
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
<li><a href="https://youtube-tips.techidaily.com/024-approved-elevate-your-digital-presence-mastering-the-art-of-video-reacts/"><u>[New] 2024 Approved Elevate Your Digital Presence Mastering the Art of Video Reacts</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-a-novices-vision-on-vectors-categories-explored-and-apps-for-2024/"><u>[Updated] A Novice's Vision on Vectors Categories Explored and Apps for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-inside-polarr-the-powerhouse-photo-toolkit/"><u>[Updated] In 2024, Inside Polarr The Powerhouse Photo Toolkit</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-docu-script-writers-guide/"><u>2024 Approved The Docu-Script Writer's Guide</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/como-solucionar-problemas-al-acceder-al-dispositivo-de-arranque-de-windows-11-tras-la-clonacion-guia-detallada/"><u>Cómo Solucionar Problemas Al Acceder Al Dispositivo De Arranque De Windows 11 Tras La Clonación: Guía Detallada</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/how-to-restore-your-lost-windows-data-after-an-unintentional-partition-delete/"><u>How to Restore Your Lost Windows Data After an Unintentional Partition Delete</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/hp-simplesave-pour-windows-gratuits-solutions-de-sauvegarde-alternatives-gratuites/"><u>HP SimpleSave Pour Windows Gratuits: Solutions De Sauvegarde Alternatives Gratuites</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-prime-edition-best-video-editing-apps-unveiled/"><u>In 2024, Prime Edition Best Video Editing Apps Unveiled</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-unlock-your-honor-x50iplus-phone-with-ease-the-3-best-lock-screen-removal-tools-by-drfone-android/"><u>In 2024, Unlock Your Honor X50i+ Phone with Ease The 3 Best Lock Screen Removal Tools</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/passare-dalloutlook-a-gmail-in-un-clic-una-guida-completa-per-limportazione/"><u>Passare Dall'Outlook a Gmail in Un Clic: Una Guida Completa per L'importazione</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/pruebe-nuestra-facil-solucion-de-respaldo-y-copia-de-seguridad-para-volumenes-de-disco-dinamico-con-version-gratuita/"><u>Pruebe Nuestra Fácil Solución De Respaldo Y Copia De Seguridad Para Volúmenes De Disco Dinámico Con Versión Gratuita</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/solving-the-problem-of-png-files-wont-load-on-your-windows-11-pc/"><u>Solving the Problem of PNG Files Won't Load on Your Windows 11 PC</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/1125587-9781609251710-the-black-pullet/"><u>The Black Pullet | Free Book</u></a></li>
<li><a href="https://program-issues.techidaily.com/troubleshooting-tips-resolving-multiversus-pc-launch-issues/"><u>Troubleshooting Tips: Resolving MultiVersus PC Launch Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-the-full-potential-of-warhammer-40k-eliminate-pc-lag/"><u>Unlock the Full Potential of Warhammer 40K: Eliminate PC Lag</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/1728481310972-windows-1011-hdd/"><u>Windows 10/11 HDDのシステム移行と起動手順</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/1728486313924-windows-10/"><u>Windows 10における問題:システムの復元機能が使用不可</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1975821/19272" target="_top" id="1975821">
  <img src="//a.impactradius-go.com/display-ad/19272-1975821" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975821/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

