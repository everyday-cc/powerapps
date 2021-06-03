---
title: "Posting Adaptive Card to Teams/User from Power Apps"
excerpt: "This app allow you to send Adaptive Card to Teams channel or User directly from Power Apps. Overview So far, sending Adaptive Cards from Power"
originalUrl: https://powerusers.microsoft.com/t5/Community-App-Samples/Posting-Adaptive-Card-to-Teams-User-from-Power-Apps/td-p/571127
type: download
publishedDateTime: 2020-05-25T00:33:00Z
heat: 59

actions:
  - url: "https://powerusers.microsoft.com/jgvjg48436/attachments/jgvjg48436/AppFeedbackGallery/534/2/Send%20Adaptive%20Cards.msapp"
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
    - name: h-nagao

topics:
  - Power Apps

images:
  - url: https://powerusers.microsoft.com//jgvjg48436/attachments/jgvjg48436/AppFeedbackGallery/534/1/TitlePage.png
    width: 1568
    height: 709
    isCached: true

secured: "MznhwCEBOEYxlB2P5lBSEXqI+b+pKwEqLbxtSKPQPNM+GLQwOZmXcpQ/R3X5PsobffoxL26CZ8UsarGnokH1efPpjgooKEvrfhNFATM0FpFD+VRYCRg7cL6qKquzDkn0ZubIW7rhJiJ8iLimtn8ZjPx17LuI5HDjOPhyCAZAjsO9xDIKqblWG+bpqO66X0z+Tbe+0yfGtSL5+x1gzt08wThw+3IckUBDuT5gZL2HwXzqW1bb0ASylkSWeXbt3xajA9UEReA1v09aZFwvtDP4+6jRnKOsDMGJeRwKHL+kV6Unu4iObIMBUs6Vp1WSjwkY3EGQ7oLn1ORiWaURAjn4nygR8G5Q7sogg/Zf5go7+xDxZwbPiAvRws4O7p7YkPMSa04ChI6vOxOqS6G3AUOISD9yJzNsx7oJhJkQNF7sPpiERyhYXv/qfDvZzaXXYMDc;hnGFxovW7RVx4sfwQKUFaA=="
---
<p><font size="5">This app allow you to send Adaptive Card to Teams channel or User directly from Power Apps.</font></p><p>&nbsp;</p><p><strong><font size="5">Overview</font></strong></p><p>So far, sending Adaptive Cards from Power Automate have been well known, and used for a survey.</p><p>To collect response data from Team members, we need a workaround using "Apply to each", since Post Adaptive Card action in flow is finished when a team member submit their response - not allowed&nbsp; submit multiple response from one AC.</p><p>&nbsp;</p><p>Using the technique, direct post from Power Apps, you can <strong>set an arbitrary URL to send response data,</strong> so it makes available to submit data from one AC in Teams channel.</p><p>&nbsp;</p><p>In this sample app, Adaptive Card like survey form with single-line answers will be posted.</p><p>&nbsp;</p><p>&nbsp;<span class="lia-inline-image-display-wrapper lia-image-align-inline" image-alt="survey.png" style="width: 400px;"><img src="https://powerusers.microsoft.com/t5/image/serverpage/image-id/145618iEBC79943A844C382/image-size/medium?v=1.0&amp;px=400" title="survey.png" alt="survey.png" li-image-url="https://powerusers.microsoft.com/t5/image/serverpage/image-id/145618iEBC79943A844C382?v=1.0" li-image-display-id="'145618iEBC79943A844C382'" li-message-uid="'571127'" li-messages-message-image="true" li-bindable="" class="lia-media-image" tabindex="0" li-bypass-lightbox-when-linked="true" li-use-hover-links="false"></span></p><p><font size="5"><strong>Note</strong></font></p><p>To collect response data, it is required to build a flow with HTTP trigger, which URL will be used to receive response from AC.</p><p><span class="lia-inline-image-display-wrapper lia-image-align-inline" image-alt="automate.png" style="width: 400px;"><img src="https://powerusers.microsoft.com/t5/image/serverpage/image-id/145608i9552DE38AB4A7EDA/image-size/medium?v=1.0&amp;px=400" title="automate.png" alt="automate.png" li-image-url="https://powerusers.microsoft.com/t5/image/serverpage/image-id/145608i9552DE38AB4A7EDA?v=1.0" li-image-display-id="'145608i9552DE38AB4A7EDA'" li-message-uid="'571127'" li-messages-message-image="true" li-bindable="" class="lia-media-image" tabindex="0" li-bypass-lightbox-when-linked="true" li-use-hover-links="false"></span></p><p>&nbsp;</p><p><font size="5"><strong>How-to use</strong></font></p><ol><li>Go to Power Apps Studio, and Open (Ctrl+O) &gt; Browse Files &gt; select Send Adaptive Cards.msapp, which you downloaded from this page.</li><li>Allow to use your connection</li><li>Navigate "Config" screen, and set your flow url to Label text : flowURL</li><li>Test it!</li></ol><p><font size="5"><strong>Demo</strong></font></p><p>&nbsp;</p><p><div class="video-embed-center video-embed"><iframe class="embedly-embed" src="//cdn.embedly.com/widgets/media.html?src=https%3A%2F%2Fwww.youtube.com%2Fembed%2F-giwGM5w4wM%3Ffeature%3Doembed&amp;display_name=YouTube&amp;url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3D-giwGM5w4wM&amp;image=https%3A%2F%2Fi.ytimg.com%2Fvi%2F-giwGM5w4wM%2Fhqdefault.jpg&amp;key=fad07bfa4bd747d3bdea27e17b533c0e&amp;type=text%2Fhtml&amp;schema=youtube" width="400" height="225" scrolling="no" title="YouTube embed" frameborder="0" allow="autoplay; fullscreen" allowfullscreen="true"></iframe></div><p>&nbsp;</p><p>Any feedback will be appreciated <img class="lia-deferred-image lia-image-emoji" src="/html/emoticons/1f642.png" alt=":slightly_smiling_face:" title=":slightly_smiling_face:"></p><p>&nbsp;</p><p>Thank you!</p><p>&nbsp;</p><p>Hiro</p><p>&nbsp;</p>

