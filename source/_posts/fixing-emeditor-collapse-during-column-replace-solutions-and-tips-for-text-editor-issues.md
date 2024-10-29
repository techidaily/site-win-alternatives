---
title: Fixing EmEditor Collapse During Column Replace - Solutions and Tips for Text Editor Issues
date: 2024-10-23T20:20:25.261Z
updated: 2024-10-28T18:05:36.318Z
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
<li><a href="https://youtube-web.techidaily.com/choes-of-amusement-comical-tune-transformations-for-2024/"><u>[New] Echoes of Amusement Comical Tune Transformations for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-unveiling-lgs-monitor-magic-a-comprehensible-review-of-4k-tech/"><u>[New] Unveiling LG's Monitor Magic A Comprehensible Review of 4K Tech</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/guida-passo-passo-per-creare-un-backup-di-windows-server-2022-su-disco-fisso-nouveau/"><u>Guida Passo-Passo per Creare Un Backup Di Windows Server 2022 Su Disco Fisso Nouveau</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/how-to-duplicate-the-recovery-partition-on-an-ssd-in-windows-operating-systems/"><u>How to Duplicate the Recovery Partition on an SSD in Windows Operating Systems</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-old-music-from-your-lava-yuva-2-by-fonelab-android-recover-music/"><u>How to recover old music from your Lava Yuva 2</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/instant-start-seamless-auto-backup-of-your-outlook-inbox-explained/"><u>Instant Start: Seamless Auto-Backup of Your Outlook Inbox Explained</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/mastering-information-purging-ideas-and-essays-from-stellars-experts/"><u>Mastering Information Purging - Ideas & Essays From Stellar's Experts</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/quick-and-easy-upgrading-your-pc-with-windows-11-on-ssd-by-bypassing-reinstallation-learn-two-techniques/"><u>Quick and Easy: Upgrading Your PC with Windows 11 on SSD by Bypassing Reinstallation - Learn Two Techniques</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/sd-2022/"><u>SD卡数据恢复的三种简便技巧 - 2022年最新方法</u></a></li>
<li><a href="https://games-able.techidaily.com/step-into-anothers-shoes-playing-in-different-switch-areas/"><u>Step Into Another's Shoes: Playing in Different Switch Areas</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/top-3-tactics-transforming-pin-videos-into-mp3-sounds-for-2024/"><u>Top 3 Tactics Transforming Pin Videos Into MP3 Sounds for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ling-the-art-of-youtube-split-screens-for-2024/"><u>Unveiling the Art of YouTube Split-Screens for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/zero-cost-instant-message-services-available-for-apple-products-download-now/"><u>Zero Cost Instant Message Services Available for Apple Products – Download Now</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137378/7443" target="_top" id="2137378">
  <img src="//a.impactradius-go.com/display-ad/7443-2137378" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137378/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

