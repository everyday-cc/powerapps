---
title: "Revamping Power Apps controls based on Google's Material Design"
excerpt: "Power Apps controls, although powerful, provide limited branding and customization capabilities. With Google investing a lot in research to come up"
originalUrl: https://powerusers.microsoft.com/t5/Community-App-Samples/Revamping-Power-Apps-controls-based-on-Google-s-Material-Design/td-p/465416
type: download
publishedDateTime: 2020-02-10T00:04:00Z
heat: 64

actions:
  - url: "https://powerusers.microsoft.com/jgvjg48436/attachments/jgvjg48436/AppFeedbackGallery/427/2/The%20Power%20Addict%20-%20Google%20Material%20Design.msapp"
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
  - url: https://powerusers.microsoft.com//jgvjg48436/attachments/jgvjg48436/AppFeedbackGallery/427/4/PowerAppsMaterialDesign.PNG
    width: 1962
    height: 1106
    isCached: true

secured: "hYh4M8Rb/bfaADW9FiYfNcaI9OWl+JPIxm0fK+i+SdXOtztBLzrqZP9E3579zCnyOuLAmNdBdl3nTwD50tI+KL1ruL0NWYDOOiHA8R/4cXhE5GE6ZJPYxSkV5atiEnip9kL0kuzOq8t+0AayE726XU1PcI73QXQL1tlP++SFEACWOl6AHyNFdCPOh1/I6GzKXVuYyp4qfVv0gQcCrPkDhWbwgN7uHoMTlizEeUThFXaYzOczWaxrmteFIWzi4Ios+lmpZJmWUjHzrGZ5gzn2NWPIK9jACo9EQLgHpJ6OBnyDoB6TdeOjXE5qKUrBoFw27x+9kfWJTRokpNu3QYRbsxfxwqqP3g2KQO2rgsf8y0aNgICoQ5nC3GVH/E5RldDlVenD6ilyHlkLRqNpDitlnWCaCgoGS/4C5IVyEjU8DcMUPUHVLFEqjfJrvwKpmsaB;kVeMVqrQgz/vZWVVg4r21A=="
---
<p>Power Apps controls, although powerful, provide limited branding and customization capabilities. With Google investing a lot in research to come up with design standards (Material Design), I wanted to incorporate those standards into Power Apps controls using the standard out of the box controls. These revamped controls will help our apps look just like, if not better, than any app we see on our mobile phones!</p><p>&nbsp;</p><p>The 3 controls I have revamped so far are: text fields, tooltips, and buttons. The reasons for picking these controls are:&nbsp;</p><p>&nbsp;</p><ol><li>The standard out of the box (OOB) versions, while good, do not provide many customization capabilities</li><li>The design for these controls was very different, so there was a greater scope of improvement</li><li>These looked way better than their OOB counterparts, helping Power Apps look as pretty, if not prettier than any other app on our phones</li><li>Tooltips interested me the most because<ul><li>honestly, they were the easiest to implement!!!</li><li>on a serious note, the OOB tooltips don't show up on mobile as there is no way to "hover"</li></ul></li><li><span>One specific button type - floating action buttons (FAB) interested me the most among all the different types as they help save some real estate, especially for mobile apps.</span></li></ol><p>&nbsp;</p><p>The design specifications from Google are very detailed. I went through those documents (so you don't have to go through those documents!) and summarized the design for tooltips and buttons:&nbsp;</p><p>&nbsp;</p><ol><li>Tooltips<ul><li>They should become visible when a user taps onto a control, like a text input field</li><li>When visible, they should display a text label providing a description of the control</li><li>They should stay visible for 1.5 seconds or until the user changes focus to another control</li></ul></li><li>Buttons<ul><li>A FAB represents the primary action of a screen</li><li>When pressed, a FAB can display/emit 3 to 6 related actions in the form of a speed dial</li><li>The speed dial actions close when a user taps the FAB again or anywhere else on the screen</li></ul></li><li>Text Fields<ul><li>This article does a very good job of explaining the research and provides a summarized design as well:&nbsp;<a href="https://medium.com/google-design/the-evolution-of-material-designs-text-fields-603688b3fe03" target="_blank" rel="noopener nofollow noopener noreferrer">https://medium.com/google-design/the-evolution-of-material-designs-text-fields-603688b3fe03</a></li></ul></li></ol><p>&nbsp;</p><p>I have blog posts for each one of these controls:&nbsp;</p><p>&nbsp;</p><ol><li>Text Fields:&nbsp;<a href="https://thepoweraddict.com/implementing-googles-material-design-for-labels-using-power-apps/" target="_blank" rel="noopener nofollow noopener noreferrer">https://thepoweraddict.com/implementing-googles-material-design-for-labels-using-power-apps/</a></li><li>Tooltips:&nbsp;<a href="https://thepoweraddict.com/implementing-googles-material-design-for-tooltips-using-power-apps/" target="_blank" rel="noopener nofollow noopener noreferrer">https://thepoweraddict.com/implementing-googles-material-design-for-tooltips-using-power-apps/</a></li><li>Buttons:&nbsp;<a href="https://thepoweraddict.com/implementing-googles-material-design-for-buttons-using-power-apps/" target="_blank" rel="noopener nofollow noopener noreferrer">https://thepoweraddict.com/implementing-googles-material-design-for-buttons-using-power-apps/</a></li></ol><p>&nbsp;</p><p><span>Hopefully, my series of posts on Google's Material design along with the app I am sharing here will inspire you to achieve beautiful, more customizable controls using standard Power Apps controls!</span></p><p>&nbsp;</p><p><span>Would love to hear your feedback, comments, suggestions, and questions!&nbsp;</span></p><p>&nbsp;</p><p><span>Thank you!</span></p><p><span>Hardit Bhatia</span></p><p><span>The Power Addict</span></p><p><span><a href="https://thepoweraddict.com" target="_blank" rel="noopener nofollow noopener noreferrer">https://thepoweraddict.com</a></span></p><p>&nbsp;</p><p><span>Here is a demo of all 3 controls on one screen!</span></p><p>&nbsp;</p><p><span><span class="lia-inline-image-display-wrapper lia-image-align-inline" image-alt="GoogleMaterialDesign.gif" style="width: 564px;"><img src="https://powerusers.microsoft.com/t5/image/serverpage/image-id/116496i0F4F92B64266B644/image-size/large?v=1.0&amp;px=999" title="GoogleMaterialDesign.gif" alt="GoogleMaterialDesign.gif" li-image-url="https://powerusers.microsoft.com/t5/image/serverpage/image-id/116496i0F4F92B64266B644?v=1.0" li-image-display-id="'116496i0F4F92B64266B644'" li-message-uid="'465416'" li-messages-message-image="true" li-bindable="" class="lia-media-image" tabindex="0" li-bypass-lightbox-when-linked="true" li-use-hover-links="false"></span></span></p>

