---
title: Fixing EmEditor Collapse During Column Replace - Solutions and Tips for Text Editor Issues
date: 2024-10-06T12:18:09.844Z
updated: 2024-10-11T09:15:36.495Z
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
<li><a href="https://on-screen-recording.techidaily.com/updated-elevating-your-gaming-the-xbox-recorder-playbook/"><u>[Updated] Elevating Your Gaming The Xbox Recorder Playbook</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-premier-portable-gba-players-on-android/"><u>[Updated] In 2024, Premier Portable GBA Players on Android</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/advance-your-figma-skills-with-the-power-of-ai-experience-the-pro-version-of-horizon-boilerplates-innovation-from-creative-tim/"><u>Advance Your Figma Skills with the Power of AI: Experience the PRO Version of Horizon Boilerplates - Innovation From Creative Tim</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/advanced-argon-dashboard-pro-high-quality-angular-admin-theme-by-creative-tim/"><u>Advanced Argon Dashboard Pro: High-Quality Angular Admin Theme by Creative Tim</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/advanced-material-kit-professional-edition-for-flutter-developers-top-tier-templates-by-creative-tim/"><u>Advanced Material Kit Professional Edition for Flutter Developers | Top-Tier Templates by Creative Tim</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/angular-13-now-ui-dashboard-andamp-free-bootstrap-4-admin-theme-by-creative-tim/"><u>Angular 13 Now UI Dashboard &Amp; Free Bootstrap 4 Admin Theme by Creative Tim</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/creative-tims-vuetify-material-professional-ui-kit-ultimate-vuejs-dashboard-solution-for-web-developers/"><u>Creative Tim's Vuetify Material Professional UI Kit - Ultimate Vuejs Dashboard Solution for Web Developers</u></a></li>
<li><a href="https://techidaily.com/how-to-soft-reset-motorola-moto-g34-5g-phone-drfone-by-drfone-reset-android-reset-android/"><u>How to Soft Reset Motorola Moto G34 5G phone? | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-to-bypass-frp-from-lava-agni-2-5g-by-drfone-android/"><u>In 2024, How to Bypass FRP from Lava Agni 2 5G?</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-vivo-v29e-pin-codepattern-lockpassword-by-drfone-android/"><u>In 2024, How to Unlock Vivo V29e PIN Code/Pattern Lock/Password</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-melding-music-and-media-the-reel-rhythm-guide/"><u>In 2024, Melding Music and Media The Reel Rhythm Guide</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-imei-unlokers-for-your-realme-narzo-60x-5g-phone-by-drfone-android/"><u>In 2024, Top IMEI Unlokers for Your Realme Narzo 60x 5G Phone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/three-ways-to-sim-unlock-xiaomi-redmi-13c-5g-by-drfone-android/"><u>Three Ways to Sim Unlock Xiaomi Redmi 13C 5G</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/ultimate-step-by-step-tutorial-recording-gameplay-in-roblox-across-all-platforms/"><u>Ultimate Step-by-Step Tutorial: Recording Gameplay in Roblox Across All Platforms</u></a></li>
<li><a href="https://win-alternatives.techidaily.com/understanding-the-legalities-apowersofts-backdrop-eliminator-license-conditions/"><u>Understanding the Legalities: Apowersoft's Backdrop Eliminator License Conditions</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1982508">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982508.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982508">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982508.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982508%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982508/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

