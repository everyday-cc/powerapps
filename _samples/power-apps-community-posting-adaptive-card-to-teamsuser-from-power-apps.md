---
title: "Posting Adaptive Card to Teams/User from Power Apps"
excerpt: "This app allow you to send Adaptive Card to Teams channel or User directly from Power Apps. Overview So far, sending Adaptive Cards from Power"
originalUrl: https://powerusers.microsoft.com/t5/Community-App-Samples/Posting-Adaptive-Card-to-Teams-User-from-Power-Apps/td-p/571127
type: download
publishedDateTime: 2020-05-25T00:33:00Z
heat: 60

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

secured: "XxPyWKpNLKGl8nfuT7buveg91feerSWkpOURFDuWF5jtObfLjOoO8kdKQvCTBIqkWqVPWn84Tkg8C2qo4jTepK82zdnof3iMnuWg8uYBpV90H2gmq92zeYUbbDYkS5AHRi4EKCtKxpoHbwyb6xrZKINhF+o9S47iEcoztkYADl8JNN+r0z8kH8COYjnmBFE8Tc7CF95hC7PMZbvuifE+V5trDLIZ6FtuXBYomOdBaJSXoM7C+JRbDANl0eJIaYQN26/XUFvfrtDlQZ2z3cn9YAi2aV8v8gMCypDNGjMu4NMBNit/VQ0Dcix05nX04gwPpsdl8x6ALioVAntOchnSOc3u69SljlY5d1Kwk7EbuC4NYJxXIAhL7YT1uXgwhMiySBCB1E0TxGBPTnVcik9IaC4F87b68bHSvqD9kp1UXMnAtv2Ghx1EGxAj1xvVyAfl;V2mXEWoRvXaXBU9CURxL5Q=="
---
<p><font size="5">This app allow you to send Adaptive Card to Teams channel or User directly from Power Apps.</font></p><p>&nbsp;</p><p><strong><font size="5">Overview</font></strong></p><p>So far, sending Adaptive Cards from Power Automate have been well known, and used for a survey.</p><p>To collect response data from Team members, we need a workaround using "Apply to each", since Post Adaptive Card action in flow is finished when a team member submit their response - not allowed&nbsp; submit multiple response from one AC.</p><p>&nbsp;</p><p>Using the technique, direct post from Power Apps, you can <strong>set an arbitrary URL to send response data,</strong> so it makes available to submit data from one AC in Teams channel.</p><p>&nbsp;</p><p>In this sample app, Adaptive Card like survey form with single-line answers will be posted.</p><p>&nbsp;</p><p>&nbsp;<span class="lia-inline-image-display-wrapper lia-image-align-inline" image-alt="survey.png" style="width: 400px;"><img src="https://powerusers.microsoft.com/t5/image/serverpage/image-id/145618iEBC79943A844C382/image-size/medium?v=1.0&amp;px=400" title="survey.png" alt="survey.png" li-image-url="https://powerusers.microsoft.com/t5/image/serverpage/image-id/145618iEBC79943A844C382?v=1.0" li-image-display-id="'145618iEBC79943A844C382'" li-message-uid="'571127'" li-messages-message-image="true" li-bindable="" class="lia-media-image" tabindex="0" li-bypass-lightbox-when-linked="true" li-use-hover-links="false"></span></p><p><font size="5"><strong>Note</strong></font></p><p>To collect response data, it is required to build a flow with HTTP trigger, which URL will be used to receive response from AC.</p><p><span class="lia-inline-image-display-wrapper lia-image-align-inline" image-alt="automate.png" style="width: 400px;"><img src="https://powerusers.microsoft.com/t5/image/serverpage/image-id/145608i9552DE38AB4A7EDA/image-size/medium?v=1.0&amp;px=400" title="automate.png" alt="automate.png" li-image-url="https://powerusers.microsoft.com/t5/image/serverpage/image-id/145608i9552DE38AB4A7EDA?v=1.0" li-image-display-id="'145608i9552DE38AB4A7EDA'" li-message-uid="'571127'" li-messages-message-image="true" li-bindable="" class="lia-media-image" tabindex="0" li-bypass-lightbox-when-linked="true" li-use-hover-links="false"></span></p><p>&nbsp;</p><p><font size="5"><strong>How-to use</strong></font></p><ol><li>Go to Power Apps Studio, and Open (Ctrl+O) &gt; Browse Files &gt; select Send Adaptive Cards.msapp, which you downloaded from this page.</li><li>Allow to use your connection</li><li>Navigate "Config" screen, and set your flow url to Label text : flowURL</li><li>Test it!</li></ol><p><font size="5"><strong>Demo</strong></font></p><p>&nbsp;</p><p><div class="video-embed-center video-embed"><iframe class="embedly-embed" src="//cdn.embedly.com/widgets/media.html?src=https%3A%2F%2Fwww.youtube.com%2Fembed%2F-giwGM5w4wM%3Ffeature%3Doembed&amp;display_name=YouTube&amp;url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3D-giwGM5w4wM&amp;image=https%3A%2F%2Fi.ytimg.com%2Fvi%2F-giwGM5w4wM%2Fhqdefault.jpg&amp;key=fad07bfa4bd747d3bdea27e17b533c0e&amp;type=text%2Fhtml&amp;schema=youtube" width="400" height="225" scrolling="no" title="YouTube embed" frameborder="0" allow="autoplay; fullscreen" allowfullscreen="true"></iframe></div><p>&nbsp;</p><p>Any feedback will be appreciated <img class="lia-deferred-image lia-image-emoji" src="/html/emoticons/1f642.png" alt=":slightly_smiling_face:" title=":slightly_smiling_face:"></p><p>&nbsp;</p><p>Thank you!</p><p>&nbsp;</p><p>Hiro</p><p>&nbsp;</p>

