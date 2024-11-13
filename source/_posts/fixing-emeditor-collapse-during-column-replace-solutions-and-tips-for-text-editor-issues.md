---
title: Fixing EmEditor Collapse During Column Replace - Solutions and Tips for Text Editor Issues
date: 2024-11-07T23:23:22.824Z
updated: 2024-11-12T23:13:12.758Z
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
<li><a href="https://win-able.techidaily.com/fixed-steam-not-detecting-controller-on-windows/"><u>[Fixed] Steam Not Detecting Controller on Windows</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-become-a-communication-connoisseur-with-google-meet/"><u>[New] In 2024, Become a Communication Connoisseur with Google Meet</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-in-2024-the-complete-resource-for-high-quality-videos-in-gopro-studio/"><u>[New] In 2024, The Complete Resource for High-Quality Videos in GoPro Studio</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-master-your-headlines-with-our-guide/"><u>[Updated] Master Your Headlines with Our Guide</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/comment-faciliter-le-transfert-automatique-des-donnees-entre-les-appareils-avec-windows-10/"><u>Comment Faciliter Le Transfert Automatique Des Données Entre Les Appareils Avec Windows ˈ10</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/comprehensive-full-system-backup-tutorial-for-various-windows-versions/"><u>Comprehensive Full System Backup Tutorial for Various Windows Versions</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/211435708-9788412856354-die-wahl-der-seele-teil-2/"><u>Die Wahl der Seele. Teil 2 | Free Book</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/einfache-losungen-fur-das-bereinigen-von-systemspeicherplatz-unter-windows-11-entfernung-der-leeren-partitionen/"><u>Einfache Lösungen Für Das Bereinigen Von Systemspeicherplatz Unter Windows 11 - Entfernung Der Leeren Partitionen</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/expanding-your-data-with-ease-adding-columns-to-tsv-files-via-the-emeditor-text-editor/"><u>Expanding Your Data with Ease: Adding Columns to TSV Files via the EmEditor Text Editor</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-apps-from-xiaomi-redmi-13c-5g-to-another-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Apps from Xiaomi Redmi 13C 5G to Another | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-15-pro-to-other-iphone-15-pro-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From iPhone 15 Pro to other iPhone 15 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-prank-your-friends-easy-ways-to-fake-and-share-google-maps-location-on-apple-iphone-13-drfone-by-drfone-virtual-ios/"><u>In 2024, Prank Your Friends! Easy Ways to Fake and Share Google Maps Location On Apple iPhone 13 | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/instantaneously-assemble-aesthetic-fb-collage-posts/"><u>Instantaneously Assemble Aesthetic FB Collage Posts</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/simple-steps-moving-your-images-from-a-dell-pc-to-an-iphone-no-itunes-needed/"><u>Simple Steps: Moving Your Images From a Dell PC to an iPhone - No iTunes Needed</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/solution-wie-entfernen-sie-nicht-angezeigte-startprogramme-in-windows-11/"><u>Solution: Wie Entfernen Sie Nicht Angezeigte Startprogramme in Windows 11</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/wie-sie-die-maximale-festplattenkapazitat-bei-windows-7-erhohen-konnen/"><u>Wie Sie Die Maximale Festplattenkapazität Bei Windows 7 Erhöhen Können</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/1728496610617-windows-1011/"><u>Windows 10/11資源回收桶數據重生關鍵技巧</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135410/19272" target="_top" id="2135410">
  <img src="//a.impactradius-go.com/display-ad/19272-2135410" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135410/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

