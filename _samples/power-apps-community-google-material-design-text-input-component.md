---
title: "Google Material Design - Text Input Component"
excerpt: "A few months ago, I had shared (on my blog) and here in the community, a revamped text input control inspired by Google's Material Design. I"
originalUrl: https://powerusers.microsoft.com/t5/Community-App-Samples/Google-Material-Design-Text-Input-Component/td-p/530161
type: download
publishedDateTime: 2020-04-17T13:03:00Z
heat: 50

actions:
  - url: "https://powerusers.microsoft.com/jgvjg48436/attachments/jgvjg48436/AppFeedbackGallery/503/2/GoogleMaterialDesignTextInput.msapp"
    type: "download"
    title: "Download Source Code"
    attribution: "Power Apps Community"

provider:
  name: Power Apps Community
  domain: microsoft.com
  images:
    - url: /assets/images/organizations/microsoft.com-50x50.jpg
      width: 50
      height: 50
  authors:
    - name: PowerAddict

topics:
  - Power Apps

images:
  - url: https://powerusers.microsoft.com//jgvjg48436/attachments/jgvjg48436/AppFeedbackGallery/503/1/Google%20Materiel%20Design%20Text%20Input%20Component.JPG
    width: 2262
    height: 1288
    isCached: true

secured: "ubbb7vuaTZmw7ouSnLqA8W5Bdl8d6fOwobLWvEkgdESgjQBUAbuCS98NTJugU95L3xNG3rmfy3fQ2F2EywMBCuXmcPuswjW1aSO9/WQN9hNofW9vOZWhGqi4qauM8XFsn70tSl3oZDt0gPiApFfhh4vCcmTQRP/SvzKfJNpp0gZghnX5w1e+I+IJJg3pWGSWtU39Elz8JOEPDcc3yyKRfswNiHxck1Q+Kt2g6LjxYG/qNAZeu8R1RFrUDz7m0KoGQOOg/K20826MEM6t803LaHl0BEseFCm5zVIGOkmNpiop4o4ZsCTkBko3yvjeMr5mRw1tkTbZglyBa2f9OPXohuM19y9OuXjK/16/QH1o3fnwZ/TgphQzYe+v34gGQTOZGnuck/tjnsFyjllx6FFHz8KZ8x0E4i3JVTC3kwC59RcXBROrLwDmdH4plE0GWqbe;VPXOkC6kmjyHCsQDyHvumQ=="
---
<p>A few months ago, I had <a href="https://thepoweraddict.com/implementing-googles-material-design-for-labels-using-power-apps/" target="_blank" rel="noopener nofollow noopener noreferrer">shared</a>&nbsp;(on my blog) and <a href="https://powerusers.microsoft.com/t5/Community-App-Samples/Revamping-Power-Apps-controls-based-on-Google-s-Material-Design/td-p/465416" target="_self">here</a> in the community, a revamped text input control inspired by Google's Material Design. I presented this, for the first time, to an audience on April's session (recording can be found <a href="https://www.powerplatformug.com/viewdocument/session-recording-4?CommunityKey=f12bf679-9f8a-47d8-bdfd-b9468d85fa52&amp;tab=librarydocuments" target="_blank" rel="noopener nofollow noopener noreferrer">here</a>) for the <a href="https://www.powerplatformug.com/communities/community-home?CommunityKey=f12bf679-9f8a-47d8-bdfd-b9468d85fa52" target="_blank" rel="noopener nofollow noopener noreferrer">Houston Power Apps and Power Automate User Group</a>. The three controls I presented during the session were - text input, tooltip, and floating action button.</p>
<p>One of the feedback I got was to convert each of these control into a component to make them reusable. The first one I picked up (it just so happened to be in the order in which I had started off with revamping these controls!) was the text input control. I have started to love components (the first one was the <a href="https://thepoweraddict.com/revamping-the-date-picker-control-v2/" target="_blank" rel="noopener nofollow noopener noreferrer">date picker component</a> - also v3 coming out soon!)</p>
<p>I wanted to provide all the properties an out-of-the-box text input control has. So here is a list of all the properties available:</p>
<ol>
<li>PrimartTextAlign</li>
<li>PrimaryTextDisplayMode</li>
<li>PrimaryFontColor</li>
<li>PrimaryFontType</li>
<li>PrimaryTextFontWeight</li>
<li>PrimaryTextFormat</li>
<li>PrimaryTextItalic</li>
<li>PrimaryTextMode</li>
<li>PrimaryTextInFocusTopPadding</li>
<li>PrimaryTextOutFocusTopPadding</li>
<li>PrimaryTextSize</li>
<li>PrimaryTextStrikethrough</li>
<li>PrimaryTextUnderline</li>
<li>SecondaryTextAlign</li>
<li>SecondaryFontColor</li>
<li>SecondaryFontType</li>
<li>SecondaryTextFontWeight</li>
<li>SecondaryTextHeight</li>
<li>SecondryTextItalic</li>
<li>SecondaryTextSize</li>
<li>SecondaryTextStrikethrough</li>
<li>SecondaryTextUnderline</li>
<li>EnableSpellCheck</li>
<li>HintText</li>
<li>LineHeight</li>
<li>Reset</li>
<li>TextFillColor</li>
<li>ToolTip</li>
<li>VirtualKeyboardMode</li>
<li>FocusBarInFocusColor</li>
<li>FocusBarOutFocusColor</li>
<li>FocusBarHeight</li>
<li>GoogleStandardVisiblity</li>
</ol>
<p>All of them are pretty self explanatory except for the last one. That variable controls the visibility of a text input control that displays Google Material Design standards for some of these properties. It also provides suggestions for the other properties. Start off with a component size that is big enough to display this text input control and then once you have gone through all the properties, set the Width and Height of the component based on the suggestion. Once you are done with the suggestions, set the GoogleStandardVisibility to false and the instructions will go away.</p>
<p>This is how the suggestions are structured:</p>
<p>Google Design Standards:<br>-----------------------------<br>Height = 90<br>Width = 560<br>PrimaryTextInFocusTopPadding = 10<br>PrimaryTextOutFocusTopPadding = 5<br>PrimaryTextSize = 20<br>SecondaryFontColor = RGBA(56, 96, 178, 1)<br>SecondaryTextFontWeight = Semibold<br>SecondaryTextHeight = 32<br>SecondaryTextSize = 15<br>TextFillColor = RGBA(230, 230, 230, 1)<br>FocusBarInFocusColor = RGBA(56, 96, 178, 1)<br>FocusBarOutFocusColor = ColorFade(Gray, 0.5)<br>FocusBarHeight = 5</p>
<p>Other Defaults<br>-----------------<br>PrimartTextAlign = Align.Left<br>PrimaryTextDisplayMode = DisplayMode.Edit<br>PrimaryFontColor = Black<br>PrimartFontType = desired font type<br>PrimaryTextFontWeight = FontWeight.Normal<br>PrimartTextFormat = TextFormat.Text<br>PrimaryTextItalic = false<br>PrimaryTextMode = TextMode.SingleLine<br>PrimaryTextStrikethrough = false<br>PrimaryTextUnderline = false<br>SecondaryTextAlign = Align.Left<br>SecondaryFontType = desired font type<br>SecondryTextItalic = false<br>SecondaryTextStrikethrough = false<br>SecondaryTextUnderline = false<br>EnableSpellCheck = false<br>HintText = desired hint text<br>LineHeight = 1.2<br>Reset = false<br>Tooltip = desired tooltip<br>VirtualKeyboardMode = VirtualKeyboardMode.Text<br>GoogleStandardVisiblity = true to read these instructions</p>
<p>One other step is needed to make this component work as desired is to add a piece of code wherever you want the user to click to be able to hide the secondary text if there is no text in the primary text input control. In my example, I have added a label and pushed it to the back so its behind all other controls. I have them set it's OnSelect property to the following code:</p>
<pre><code>Reset(Component_GoogleTextInput)</code></pre>
<p>I have added 2 components and set them up with different font properties. With the rest of the settings configured as listed above, the component behaves as shown below:</p>
<p><span class="lia-inline-image-display-wrapper lia-image-align-inline" image-alt="GoogleMaterialDesignTextInputComponent.gif" style="width: 226px;"><img src="https://powerusers.microsoft.com/t5/image/serverpage/image-id/134521i0EC00FBADA2E664D/image-size/medium?v=1.0&amp;px=400" title="GoogleMaterialDesignTextInputComponent.gif" alt="GoogleMaterialDesignTextInputComponent.gif" li-image-url="https://powerusers.microsoft.com/t5/image/serverpage/image-id/134521i0EC00FBADA2E664D?v=1.0" li-image-display-id="'134521i0EC00FBADA2E664D'" li-message-uid="'530161'" li-messages-message-image="true" li-bindable="" class="lia-media-image" tabindex="0" li-bypass-lightbox-when-linked="true" li-use-hover-links="false"></span></p>
<p>I have attached the component here. Download it and enjoy a text input control inspired by Google Material Design in your apps!</p>
<p>&nbsp;</p>
<p>Thanks!</p>
<p><strong>Hardit Bhatia</strong></p>
<p><a href="https://thepoweraddict.com" target="_self" rel="nofollow noopener noreferrer"><strong>Blog</strong></a><strong>&nbsp;| </strong><a href="https://twitter.com/thepoweraddict" target="_self" rel="nofollow noopener noreferrer"><strong>Twitter</strong></a><strong> | </strong><a href="https://www.linkedin.com/in/harditbhatia/" target="_self" rel="nofollow noopener noreferrer"><strong>LinkedIn</strong></a><strong> | </strong><a href="https://www.facebook.com/thepoweraddict/" target="_self" rel="nofollow noopener noreferrer"><strong>Facebook</strong></a><strong> | </strong><a href="https://www.youtube.com/channel/UC01IDHuH1X3ZhUYMTj-ZyTg?view_as=subscriber" target="_self" rel="nofollow noopener noreferrer"><strong>YouTube</strong></a><strong>&nbsp; |&nbsp;&nbsp;</strong><a href="mailto:hardit.bhatia@thepoweraddict.com" target="_self" rel="nofollow noopener noreferrer"><strong>Email</strong></a></p>

