---
title: "Drivers License PDF417 Barcode Data Extraction"
excerpt: "This app shows you how to extract data from a drivers license barcode. There is an incredible amount of data in every drivers license; being able to"
originalUrl: https://powerusers.microsoft.com/t5/Community-App-Samples/Drivers-License-PDF417-Barcode-Data-Extraction/td-p/463649
type: download
publishedDateTime: 2020-02-06T17:41:00Z
heat: 59

actions:
  - url: "https://powerusers.microsoft.com/jgvjg48436/attachments/jgvjg48436/AppFeedbackGallery/423/3/License%20Scanner.msapp"
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
    - name: EricLott

topics:
  - Power Apps

images:
  - url: https://powerusers.microsoft.com//jgvjg48436/attachments/jgvjg48436/AppFeedbackGallery/423/1/Main.jpg
    width: 1566
    height: 879
    isCached: true

secured: "uZrZj5oYh3B9NMA73c/wruHQZn/ubYkakwrhof/Df7mBI2HWxEC1mwr0fuZvBDOSXpicNZhdcKvpKDZl/89SBQSb3oU44Ka+rv5ZH2yxUbe4tEBv68LKqCdLTpnDyPLdhiYCNVtcRVHo/VfJ0gFki+2mkOMq/oUY9Ke4Oc75iKFhHHBTSZm4M5Uxkp2Iyo8RPkNslrpBNPsFXm5CR5dIYbcbKCybFOY7VJqWbEzttLCNDPjrjP2L8LktuekFWvu4Ww9P5k4eED6PBt71Z7Gk10liU3VDVS7ln2DxcDL5y8lwJr4ULoFOOf8z6rjJKdsIeQ7eJY6+MGnDl7uh3V3JZnlpEQ0O8zYUVAeGcKDDjb7RLPK0eyypKvBgxsT/Ik3i9xJgsnqnuRjzrmjQvj6Z62b/5BN8HzaSYR3tsCNxaovTEn8fmQPBOQ0VRjvGDVQQ;OWl1fXRBcsU4SgqtnPQN/Q=="
---
<p><span class="lia-inline-image-display-wrapper lia-image-align-center" image-alt="bc.png" style="width: 400px;"><img src="https://powerusers.microsoft.com/t5/image/serverpage/image-id/116001i96B977DD00C497DF/image-size/medium?v=1.0&amp;px=400" title="bc.png" alt="bc.png" li-image-url="https://powerusers.microsoft.com/t5/image/serverpage/image-id/116001i96B977DD00C497DF?v=1.0" li-image-display-id="'116001i96B977DD00C497DF'" li-message-uid="'463649'" li-messages-message-image="true" li-bindable="" class="lia-media-image" tabindex="0" li-bypass-lightbox-when-linked="true" li-use-hover-links="false"></span></p><p><span>&nbsp; &nbsp; &nbsp;This app shows you how to extract data from a drivers license barcode. There is an incredible amount of data in every drivers license; being able to collect it has many purposes. From HR on-boarding to event registration and check in, the possibilities are nearly endless.</span></p><p>&nbsp; &nbsp; &nbsp;There isn't a lot to this app. Each value has it's own Match() function to build the data collection. In the example below you can see that the abbreviation "DAA" matches the "Full Name" value, so I use a regular expression to find that value and add it to the collection.</p><p>&nbsp;</p><pre class="lia-code-sample language-c"><code>{Value: First(Match(LicenseData,"\n" &amp; "DAA" &amp; "(.+)\n",MatchOptions.Contains).SubMatches), Description: "Full Name" },</code></pre><p>&nbsp;</p><p>Special thanks to this post that had the abbreviations for all the data explained.</p><p><a href="https://blog.dynamsoft.com/imaging/extract-data-pdf417-driver-licenses/" target="_blank" rel="noopener nofollow noopener noreferrer">https://blog.dynamsoft.com/imaging/extract-data-pdf417-driver-licenses/</a></p><p>&nbsp;</p><p>Download the app, scan your license (or the sample license barcode attached) and let me know some use cases you can think of!</p><p>Thank you!</p><p>Eric</p>

