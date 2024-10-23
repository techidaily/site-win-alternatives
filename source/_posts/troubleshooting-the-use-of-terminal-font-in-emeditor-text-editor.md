---
title: Troubleshooting the Use of Terminal Font in EmEditor Text Editor
date: 2024-10-19T07:09:31.569Z
updated: 2024-10-22T20:22:34.894Z
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
<li><a href="https://youtube-blog.techidaily.com/024-approved-earning-by-critiquing-goodies-a-youtube-guide/"><u>[New] 2024 Approved Earning by Critiquing Goodies A YouTube Guide</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-amplify-your-fb-video-content-a-complete-music-integration-tutorial/"><u>[Updated] In 2024, Amplify Your FB Video Content A Complete Music Integration Tutorial</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/1728487514847-win11-lenovo/"><u>重建失效的 Win11 Lenovo分區設定- 深入指南</u></a></li>
<li><a href="https://tech-revival.techidaily.com/comprehensive-tutorial-on-bypassing-drm-protection-in-google-ebooks/"><u>Comprehensive Tutorial on Bypassing DRM Protection in Google eBooks</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/datensicherung-fur-programme-in-windows-11-keine-notwendigkeit-zur-erneuten-installation/"><u>Datensicherung Für Programme in Windows 11 – Keine Notwendigkeit Zur Erneuten Installation</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/guida-passo-passo-come-configurare-automaticamente-il-backup-su-windows-11-in-quattro-modalita-diverse/"><u>Guida Passo-Passo: Come Configurare Automaticamente Il Backup Su Windows 11 in Quattro Modalità Diverse</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-change-your-sim-pin-code-on-your-xiaomi-redmi-13c-phone-by-drfone-android/"><u>How To Change Your SIM PIN Code on Your Xiaomi Redmi 13C Phone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-text-messages-from-vivo-y17s-to-new-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Text Messages from Vivo Y17s to New Phone | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/overcoming-virtual-reality-discomfort-for-2024/"><u>Overcoming Virtual Reality Discomfort for 2024</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/quattro-migliori-modi-per-ritornare-da-windows-11-a-windows-10/"><u>Quattro Migliori Modi per Ritornare Da Windows 11 a Windows 10</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2141688/17094" target="_top" id="2141688">
  <img src="//a.impactradius-go.com/display-ad/17094-2141688" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://bluetties.sjv.io/i/5597632/2141688/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

