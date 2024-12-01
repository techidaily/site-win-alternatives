---
title: Fixing EmEditor Collapse During Column Replace - Solutions and Tips for Text Editor Issues
date: 2024-11-30T03:38:45.448Z
updated: 2024-11-30T17:33:52.011Z
tags:
  - product
categories:
  - emeditor
thumbnail: https://thmb.techidaily.com/6ea4b6540cbc9defac45234e6794ae14daad67ae8e54d2f0a08f445fb5dafc81.jpg
---

## Fixing EmEditor Collapse During Column Replace - Solutions and Tips for Text Editor Issues

Viewing 10 posts - 1 through 10 (of 10 total)

* Author  
Posts
* April 17, 2009 at 10:12 am [#7147](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/e617b7b1a7b5e8dffacd54fb3d09812a?s=80&d=identicon&r=g)PigletEE](https://www.emeditor.com/forums/users/PigletEE/ "View PigletEE's profile")  
Member  
Hi!  
 EmEditor crashes when Find&Replace for column selection.  
 To reproduce:  
 1\. Enable Virtual Space;  
 2\. Make a column selection “with virtual space” on some lines;  
 3\. Call Find&Replace dialog;  
 4\. Find ” ” and replace any character;  
 5\. Press Replace All…  
April 17, 2009 at 4:11 pm [#7148](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
> PigletEE wrote:  
> Hi!  
> EmEditor crashes when Find&Replace for column selection.  
> To reproduce:  
> 1\. Enable Virtual Space;  
> 2\. Make a column selection “with virtual space” on some lines;  
> 3\. Call Find&Replace dialog;  
> 4\. Find ” ” and replace any character;  
> 5\. Press Replace All…  
 I couldn’t reproduce your issue. Which version of EmEditor are you using? Which OS do you use? Any other options such as regular expressions, escape sequences, Case Match, Word Only, etc.?  
April 20, 2009 at 2:23 am [#7157](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/e617b7b1a7b5e8dffacd54fb3d09812a?s=80&d=identicon&r=g)PigletEE](https://www.emeditor.com/forums/users/PigletEE/ "View PigletEE's profile")  
Member  
I am sorry. I have  
 Windows XP sp3 32bit, EmEditor 8.04\. Only Use Regular Expression and In the selection Only are checked. SQL configuration with Enable Virtual Space, Show Ruler and Show Line Number are checked.  
April 20, 2009 at 6:37 pm [#7158](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
> PigletEE wrote:  
> I am sorry. I have  
> Windows XP sp3 32bit, EmEditor 8.04\. Only Use Regular Expression and In the selection Only are checked. SQL configuration with Enable Virtual Space, Show Ruler and Show Line Number are checked.  
 I reproduced this issue. I will release v8.05 RC 1 shortly, so please try it and see the bug is fixed. Thank you!  
April 21, 2009 at 4:14 am [#7168](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/e617b7b1a7b5e8dffacd54fb3d09812a?s=80&d=identicon&r=g)PigletEE](https://www.emeditor.com/forums/users/PigletEE/ "View PigletEE's profile")  
Member  
Yes. Now It works.  
 Thank you.  
April 21, 2009 at 11:22 am [#7171](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/e617b7b1a7b5e8dffacd54fb3d09812a?s=80&d=identicon&r=g)PigletEE](https://www.emeditor.com/forums/users/PigletEE/ "View PigletEE's profile")  
Member  
Ooops. Another one.  
 Find&Replace works but … The right margin of selection moves to the end of the last line in the column selection after find&replace operation.  
April 21, 2009 at 9:16 pm [#7175](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
> PigletEE wrote:  
> Ooops. Another one.  
> Find&Replace works but … The right margin of selection moves to the end of the last line in the column selection after find&replace operation.  
 I fixed and built for you:  
[http://www.emeditor.com/pub/emed805rc3epx.msi](https://tools.techidaily.com/emeditor/products/)  
 Can you please try and see it is fixed?  
 Thank you!  
April 22, 2009 at 3:24 am [#7178](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/e617b7b1a7b5e8dffacd54fb3d09812a?s=80&d=identicon&r=g)PigletEE](https://www.emeditor.com/forums/users/PigletEE/ "View PigletEE's profile")  
Member  
Ok.  
 It works but the problem still here with some cases.  
 If the low left corner of the selection is on the text and the low right corner on “virtual space” and Find&Replace operation MUST find and replace at least one time. You may see that the selection is changed.  
April 22, 2009 at 5:31 am [#7180](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/a0a6377144ed3636f985d87303f65ed2?s=80&d=identicon&r=g)Yutaka Emura](https://www.emeditor.com/forums/users/yemura/ "View Yutaka Emura's profile")  
Keymaster  
> PigletEE wrote:  
> Ok.  
> It works but the problem still here with some cases.  
> If the low left corner of the selection is on the text and the low right corner on “virtual space” and Find&Replace operation MUST find and replace at least one time. You may see that the selection is changed.  
 I cannot reproduce this case. Can you email me at [tech@emurasoft.com](https://tools.techidaily.com/emeditor/products/) a screenshot or a sample file to explain the details? Thanks!  
April 22, 2009 at 10:26 am [#7181](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/e617b7b1a7b5e8dffacd54fb3d09812a?s=80&d=identicon&r=g)PigletEE](https://www.emeditor.com/forums/users/PigletEE/ "View PigletEE's profile")  
Member  
check your mail.
* Author  
Posts

Viewing 10 posts - 1 through 10 (of 10 total)

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
<li><a href="https://vp-tips.techidaily.com/new-in-2024-charting-the-evolutionary-trajectory-of-mixed-reality/"><u>[New] In 2024, Charting the Evolutionary Trajectory of Mixed Reality</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-unmatched-access-the-finest-5-browser-tools-for-fb-videos/"><u>[New] Unmatched Access The Finest 5 Browser Tools for FB Videos</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-getting-acquainted-with-quantum-hdr-techniques-for-2024/"><u>[Updated] Getting Acquainted with Quantum HDR Techniques for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-in-2024-captivating-book-video-tours/"><u>[Updated] In 2024, Captivating Book Video Tours</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-maximize-youtube-views-a-comprehensible-guide-to-collaborative-videos/"><u>[Updated] Maximize YouTube Views A Comprehensible Guide to Collaborative Videos</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-simplifying-cinematics-in-filmora-answering-the-core-questions/"><u>[Updated] Simplifying Cinematics in Filmora Answering the Core Questions</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/1728476953985-windowsmac/"><u>如何在Windows和Mac电脑上恢复失去的文件？</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/dropboxssd/"><u>Dropboxと外部SSDを結び付けるシンプルな手順</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/effizientes-kopieren-von-windows-10-systemen-keine-neukonfiguration-erforderlich/"><u>Effizientes Kopieren Von Windows 10-Systemen - Keine Neukonfiguration Erforderlich</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/effortless-techniques-for-saving-youtube-videos/"><u>Effortless Techniques for Saving YouTube Videos</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/festplattensicherheit-mit-r-drive-erfahren-sie-uber-effektive-alternativmethoden-fur-ihr-datenabbildungsszenario/"><u>Festplattensicherheit Mit R-Drive - Erfahren Sie Über Effektive Alternativmethoden Für Ihr Datenabbildungsszenario!</u></a></li>
<li><a href="https://techidaily.com/how-to-update-or-downgrade-apple-iphone-se-2022-without-losing-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Update or Downgrade Apple iPhone SE (2022) Without Losing Data? | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-a-lost-oppo-reno-10-proplus-5g-for-free-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track a Lost Oppo Reno 10 Pro+ 5G for Free? | Dr.fone</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/navigating-windows-11-uncovering-synonyms-for-sync-center-and-detailed-tutorial/"><u>Navigating Windows 11: Uncovering Synonyms for Sync Center and Detailed Tutorial</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/restore-your-lost-adt-video-footage-with-these-3-easy-no-cost-methods/"><u>Restore Your Lost ADT Video Footage with These 3 Easy, No-Cost Methods</u></a></li>
<li><a href="https://discover-exceptional.techidaily.com/tutorial-pemulihan-daftar-kontak-yang-hapus-pada-iphone-percocahan-bebas-lainnya/"><u>Tutorial Pemulihan Daftar Kontak Yang Hapus Pada iPhone: Percocahan Bebas Lainnya</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/1728504361789-wbadmin/"><u>WBAdminを使用したバックアップデータの消去方法：ウィンドウズサーバー</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/1728468956836-windows-11-windows-10/"><u>Windows 11 から Windows 10への変更不可能性について</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/xcopy-vs-robocopy-features-and-differences-compared-alternative-methods-available/"><u>Xcopy vs Robocopy: Features and Differences Compared - Alternative Methods Available</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6KXVWj6Ar1M?si=Cd_jktmoN3e9OzH3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

