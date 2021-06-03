---
title: "App for taking photos and adding notes"
excerpt: "App was inspired by a comment with a question posted some time ago under my post about hand written signatures . Kevan asked, if this is possible to"
originalUrl: https://powerusers.microsoft.com/t5/Community-App-Samples/App-for-taking-photos-and-adding-notes/td-p/289368
type: download
publishedDateTime: 2019-05-25T15:36:00Z
heat: 54

actions:
  - url: "https://powerusers.microsoft.com/jgvjg48436/attachments/jgvjg48436/AppFeedbackGallery/186/2/AddNotesToImage.msapp"
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
    - name: TomaszPoszytek

topics:
  - Power Apps

images:
  - url: https://powerusers.microsoft.com//jgvjg48436/attachments/jgvjg48436/AppFeedbackGallery/186/1/2019-05-25_23h15_51.png
    width: 2874
    height: 1871
    isCached: true

secured: "FWglD8hcEz4yyY+Et743jFRv1Sp9kQEfOhNfvTpnn17qVCyeeHIVXtuDmq5oT2T3ns0U5iFnPUr9GUms3SnxCGFlrYfR9kSn/T2h6UK7PnU8l5oNveT7vCSDQDAn7KXcEInRvcm8KbqKPnWValoW2ofBiJzcl0mLTzgdv14+vrW2TGreSKpSXwiPzV4LMpR9kCvHZfqyYeHaVeES5kIqTZFqSP0qkWZ/JW0OXtlJCSfSLr/Agg2eSypf1WBOUDMMbzW5zDBp82ULcCpwdpQ92OriHio1Zib1NAppOTupHzqqVLz6p3w/1A7COAP15P8zYceM/OJqRksNJERJZdOKoGXK0ricLO5/S3vJfa2hCd9hZu5Z9ZyxOycGWvaH/175ZK4Bz76viL5rQ5UbscGsuieXQdac9z3/q20ePp5Q9VS7xL0UGLCsJBM4ALU4NUAh;ow6zjG7EmjQIfJ0xcOnaPw=="
---
<p><span>App was inspired by a comment with a question posted some time ago under my post about </span><a href="https://poszytek.eu/microsoft-en/office-365-en/flow-en/powerapps-hand-written-signature/" target="_blank" rel="noreferrer noopener nofollow noopener noreferrer">hand written signatures</a><span>. Kevan asked, if this is possible to take a photo, then sketch-note on it and finally save two images as a single one.</span></p><p>&nbsp;</p><p><span><!--   wp:paragraph   --></span></p><p>I thought that it should be fairly easy and to be honest it was, however I failed on the last step - merging the images. I must really admit it - I didn't make it on my own. Instead I decided to use free API called "<a href="https://www.convertapi.com/html-to-png" target="_blank" rel="noreferrer noopener nofollow noopener noreferrer">Convert API</a>". I wanted to make it using Azure Function, but I wasn't able to do it alone and help didn't come from anywhere too <img class="lia-deferred-image lia-image-emoji" src="/html/emoticons/1f642.png" alt=":slightly_smiling_face:" title=":slightly_smiling_face:"> But with that API it works too! User has 1.500 free monthly conversions <img class="lia-deferred-image lia-image-emoji" src="/html/emoticons/1f642.png" alt=":slightly_smiling_face:" title=":slightly_smiling_face:"></p><p>&nbsp;</p><p><strong>The solution</strong></p><p><span><!--   /wp:heading   --><!--   wp:paragraph   --></span></p><p>It is build from the following components:</p><p><span><!--   /wp:paragraph   --><!--   wp:list {&amp;quot;ordered&amp;quot;:true}   --></span></p><ol><li>PowerApps - is used for taking a photo and then overlaying notes on it;</li><li>Blob Storage - used for uploading image from a camera and second one - with sketch-notes, as well as for uploading the final, merged image;</li><li>Flow - receives all the information about transformations done to the images and overlays and creates HTML merging two images in a single canvas;</li><li>Convert API - used to perfectly convert HTML into a PNG file <img class="lia-deferred-image lia-image-emoji" src="/html/emoticons/1f642.png" alt=":slightly_smiling_face:" title=":slightly_smiling_face:"></li></ol><p>You can find detailed description of a solution here:&nbsp;<a href="https://poszytek.eu/microsoft-en/office-365-en/powerapps-en/sketch-noting-in-powerapps-and-merging-images/" target="_blank" rel="noopener nofollow noopener noreferrer">https://poszytek.eu/microsoft-en/office-365-en/powerapps-en/sketch-noting-in-powerapps-and-merging-i...</a></p><p>&nbsp;</p><p><span class="lia-inline-image-display-wrapper lia-image-align-inline" image-alt="2019-05-25_22h55_36.png" style="width: 400px;"><img src="https://powerusers.microsoft.com/t5/image/serverpage/image-id/67352i697F824D2082D774/image-size/medium?v=1.0&amp;px=400" title="2019-05-25_22h55_36.png" alt="2019-05-25_22h55_36.png" li-image-url="https://powerusers.microsoft.com/t5/image/serverpage/image-id/67352i697F824D2082D774?v=1.0" li-image-display-id="'67352i697F824D2082D774'" li-message-uid="'289368'" li-messages-message-image="true" li-bindable="" class="lia-media-image" tabindex="0" li-bypass-lightbox-when-linked="true" li-use-hover-links="false"></span><span class="lia-inline-image-display-wrapper lia-image-align-right" image-alt="2019-05-25_23h07_16.png" style="width: 400px;"><img src="https://powerusers.microsoft.com/t5/image/serverpage/image-id/67354i961436DDD7EFE41B/image-size/medium?v=1.0&amp;px=400" title="2019-05-25_23h07_16.png" alt="2019-05-25_23h07_16.png" li-image-url="https://powerusers.microsoft.com/t5/image/serverpage/image-id/67354i961436DDD7EFE41B?v=1.0" li-image-display-id="'67354i961436DDD7EFE41B'" li-message-uid="'289368'" li-messages-message-image="true" li-bindable="" class="lia-media-image" tabindex="0" li-bypass-lightbox-when-linked="true" li-use-hover-links="false"></span><span class="lia-inline-image-display-wrapper lia-image-align-left" image-alt="2019-05-25_23h10_22.png" style="width: 400px;"><img src="https://powerusers.microsoft.com/t5/image/serverpage/image-id/67351iB15825F61067B31C/image-size/medium?v=1.0&amp;px=400" title="2019-05-25_23h10_22.png" alt="2019-05-25_23h10_22.png" li-image-url="https://powerusers.microsoft.com/t5/image/serverpage/image-id/67351iB15825F61067B31C?v=1.0" li-image-display-id="'67351iB15825F61067B31C'" li-message-uid="'289368'" li-messages-message-image="true" li-bindable="" class="lia-media-image" tabindex="0" li-bypass-lightbox-when-linked="true" li-use-hover-links="false"></span><span class="lia-inline-image-display-wrapper lia-image-align-right" image-alt="2019-05-25_23h16_59.png" style="width: 400px;"><img src="https://powerusers.microsoft.com/t5/image/serverpage/image-id/67355i69B672121753F4BB/image-size/medium?v=1.0&amp;px=400" title="2019-05-25_23h16_59.png" alt="2019-05-25_23h16_59.png" li-image-url="https://powerusers.microsoft.com/t5/image/serverpage/image-id/67355i69B672121753F4BB?v=1.0" li-image-display-id="'67355i69B672121753F4BB'" li-message-uid="'289368'" li-messages-message-image="true" li-bindable="" class="lia-media-image" tabindex="0" li-bypass-lightbox-when-linked="true" li-use-hover-links="false"></span></p><p>&nbsp;</p><p><span><!--   /wp:list   --></span></p><p>&nbsp;</p><p>&nbsp;</p><p><span class="videoUrl">watch?v=3p9hQbWtwZI</span></p>

