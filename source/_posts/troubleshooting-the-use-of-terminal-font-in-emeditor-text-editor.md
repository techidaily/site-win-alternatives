---
title: Troubleshooting the Use of Terminal Font in EmEditor Text Editor
date: 2024-10-04T09:47:47.914Z
updated: 2024-10-11T10:43:26.491Z
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
<li><a href="https://youtube-web.techidaily.com/voiding-illegal-content-youtube-to-mp4-transfer-safely/"><u>[New] Avoiding Illegal Content YouTube to MP4 Transfer Safely</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-offline-watching-made-simple-youtube-videos-for-ios-users/"><u>[New] Offline Watching Made Simple YouTube Videos for iOS Users</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-the-art-of-choosing-video-aspect-ratios/"><u>[New] The Art of Choosing Video Aspect Ratios</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-voice-modification-gear-top-picks-for-creators/"><u>2024 Approved Voice Modification Gear Top Picks for Creators</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/comprehensive-tutorial-on-using-windows-telnet-utility/"><u>Comprehensive Tutorial on Using Windows Telnet Utility</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/maintaining-proportions-across-representations-ensures-accuracy-in-depicting-real-world-relationships-at-different-scales/"><u>Maintaining Proportions Across Representations Ensures Accuracy in Depicting Real-World Relationships at Different Scales.</u></a></li>
<li><a href="https://screen-recording.techidaily.com/mastering-screen-recordings-the-recmeister-way-for-2024/"><u>Mastering Screen Recordings The Recmeister Way for 2024</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/premium-black-themed-react-admin-layout-using-bootstrap-n4-and-reactstrap-cost-free-template-by-creative-tim/"><u>Premium Black Themed React Admin Layout Using Bootstrap N4 & Reactstrap - Cost-Free Template by Creative Tim</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/pro-grade-purify-ui-control-center-built-on-chakra-tech-exclusive-design-from-creative-team/"><u>Pro-Grade Purify UI Control Center Built on Chakra Tech - Exclusive Design From Creative Team</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/-method-converting-images-into-desktop-thumbnails-for-youtube-for-2024/"><u>Rapid Method Converting Images Into Desktop Thumbnails for YouTube for 2024</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/top-3-free-nodejs-website-designs-from-creative-tim-premium-alternatives-included/"><u>Top 3 Free Node.js Website Designs From Creative Tim: Premium Alternatives Included</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136617/26400" target="_top" id="2136617">
  <img src="//a.impactradius-go.com/display-ad/26400-2136617" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136617/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

