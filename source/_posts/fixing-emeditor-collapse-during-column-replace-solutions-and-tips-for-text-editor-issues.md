---
title: Fixing EmEditor Collapse During Column Replace - Solutions and Tips for Text Editor Issues
date: 2024-11-17T23:28:00.275Z
updated: 2024-11-22T20:56:53.096Z
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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-hack-your-channels-identity-with-these-11-budget-tools/"><u>[New] 2024 Approved Hack Your Channel's Identity with These 11 Budget Tools</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-ultimate-gear-guide-for-fresh-powder-adventures-for-2024/"><u>[Updated] Ultimate Gear Guide for Fresh Powder Adventures for 2024</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/4-alsfa-rulen-voor-herstelven-van-geheemde-begeethken-fragmenten-op-windows-7/"><u>4 ALSFA RULEN VOOR HERSTELVEN VAN GEHEEMDE BEGEETHĈKEN FRAGMENTEN Op Windows 7</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/7s-file-history-feature/"><u>7'S File History Feature</u></a></li>
<li><a href="https://media-tips.techidaily.com/effortless-video-transfer-tips-for-ipods-without-using-itunes/"><u>Effortless Video Transfer Tips for iPods Without Using iTunes</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/full-tutorial-how-to-effectively-retrieve-lost-data-from-a-maxtor-hdd/"><u>Full Tutorial: How to Effectively Retrieve Lost Data From a Maxtor HDD</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/identifiez-et-corrigez-les-problemes-courants-avec-lexecution-automatique-sous-windows-11/"><u>Identifiez Et Corrigez : Les Problèmes Courants Avec L'exécution Automatique Sous Windows 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-circle-everything-you-need-to-know-on-tecno-pop-8-drfone-by-drfone-virtual-android/"><u>Life360 Circle Everything You Need to Know On Tecno Pop 8 | Dr.fone</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/notification-online-content-missing-your-request-cannot-be-fulfilled-due-to-a-non-existent-page/"><u>Notification: Online Content Missing – Your Request Cannot Be Fulfilled Due To A Non-Existent Page</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/overview-of-the-best-zte-axon-40-lite-screen-mirroring-app-drfone-by-drfone-android/"><u>Overview of the Best ZTE Axon 40 Lite Screen Mirroring App | Dr.fone</u></a></li>
<li><a href="https://win-answers.techidaily.com/plex-versus-kodi-showdown-which-is-the-superior-media-streaming-platform/"><u>Plex Versus Kodi Showdown: Which Is the Superior Media Streaming Platform?</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-ultimate-rankings-top-10-free-ios-and-android-live-streamers/"><u>The Ultimate Rankings Top 10 Free iOS and Android Live Streamers</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/bXmwwSmYqq4?si=Bb-eJfLnlpeeClyt&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

