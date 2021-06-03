---
title: "App Creator Portal (Version 1)"
excerpt: "I have been working on an app using the App Maker connector that would bring governance and support documentation closer to the app creator. The app"
originalUrl: https://powerusers.microsoft.com/t5/Community-App-Samples/App-Creator-Portal-Version-1/td-p/246245
type: download
publishedDateTime: 2019-03-05T06:29:00Z
heat: 64

actions:
  - url: "https://powerusers.microsoft.com/jgvjg48436/attachments/jgvjg48436/AppFeedbackGallery/122/2/App%20Creator%20Portal%20(3).msapp"
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
    - name: Anonymous

topics:
  - Power Apps

images:
  - url: https://powerusers.microsoft.com//jgvjg48436/attachments/jgvjg48436/AppFeedbackGallery/122/1/appcreator1.JPG
    width: 981
    height: 566
    isCached: true

secured: "2S33Eh8d6zj2bO9qSjFtxKRt/1FMQi2z62o7pEc4yzv/dLR0EWe9q3ONitbCStlo4U0bYZbo1t8/N75ypsMD64rlpRRuWD1RKoKhWTrclxGdNuTcnQlZWPgpnuZNZWuFDAW48msIM1IkWqVGVNGo4oZXv43+2/za4prjQ3B7kRoSlb0l296E3lM+6G7NdLOX7Dgm+tyIq+aDKGpr32+BBGqMi1FY1bgi5JuGmpT5Yw5wrDW5hGCalt6LpQdmGbnFTJo6+NuLM78CFEAxdlHwl5Q5UQqVewe+hxY8P2Zi/UAM71APe2aDoG0CpTP/kBWiI7Ya0hwFRdkuQ8fnAcd+A6SyNuqz5Bsa43hW08lZUKZnGxidod0T+ELwr5EFETxcoyhCDHFn4NYtuv15GI/qSGFvQ7luFW5Io/Cb7RBsYyXCEVd50rJvdccXJXI2nyzU;jFWK0+l2AsYMb3r1kuu+mw=="
---
<p>I have been working on an app using the App Maker connector that would bring governance and support documentation closer to the app creator.</p>
<p>The app will show users their apps, and allow them to check compliance status and submit a support form.&nbsp;</p>
<p>The support form is what IT would typically require as a Support Procedure Manual for new apps.&nbsp;</p>
<p>&nbsp;</p>
<p>The <strong>front page</strong> shows all apps that a user has, and an indicator of compliance status which is based on if the app has been published in the last 60 days, if the app description is filled out and if the support form has been completed.</p>
<p><br><span class="lia-inline-image-display-wrapper lia-image-align-inline" image-alt="appcreator1.JPG" style="width: 981px;"><img src="https://powerusers.microsoft.com/t5/image/serverpage/image-id/54999i1B04CC2436C758F6/image-size/large?v=1.0&amp;px=999" title="appcreator1.JPG" alt="appcreator1.JPG" li-image-url="https://powerusers.microsoft.com/t5/image/serverpage/image-id/54999i1B04CC2436C758F6?v=1.0" li-image-display-id="'54999i1B04CC2436C758F6'" li-message-uid="'246245'" li-messages-message-image="true" li-bindable="" class="lia-media-image" tabindex="0" li-bypass-lightbox-when-linked="true" li-use-hover-links="false"></span></p>
<p>&nbsp;</p>
<p>The <strong>App Detail</strong> screen provides further details, a breakdown of the compliance status, the ability to submit the support form, an overview of users/roles of the app and the ability to email all users and re-publish the app.</p>
<p>&nbsp;</p>
<p><span class="lia-inline-image-display-wrapper lia-image-align-inline" image-alt="appcreator2.JPG" style="width: 999px;"><img src="https://powerusers.microsoft.com/t5/image/serverpage/image-id/55001i5086484D08BF5EE5/image-size/large?v=1.0&amp;px=999" title="appcreator2.JPG" alt="appcreator2.JPG" li-image-url="https://powerusers.microsoft.com/t5/image/serverpage/image-id/55001i5086484D08BF5EE5?v=1.0" li-image-display-id="'55001i5086484D08BF5EE5'" li-message-uid="'246245'" li-messages-message-image="true" li-bindable="" class="lia-media-image" tabindex="0" li-bypass-lightbox-when-linked="true" li-use-hover-links="false"></span></p>
<p>&nbsp;</p>
<p>The <strong>eMail app</strong> users opens a pop-up where you can select users to email - this could be useful to communicate version updates / changes. At the moment this doesn't support sending attachments.&nbsp;</p>
<p><span class="lia-inline-image-display-wrapper lia-image-align-inline" image-alt="appcreator4.JPG" style="width: 999px;"><img src="https://powerusers.microsoft.com/t5/image/serverpage/image-id/55000i46260CF6C0488F5F/image-size/large?v=1.0&amp;px=999" title="appcreator4.JPG" alt="appcreator4.JPG" li-image-url="https://powerusers.microsoft.com/t5/image/serverpage/image-id/55000i46260CF6C0488F5F?v=1.0" li-image-display-id="'55000i46260CF6C0488F5F'" li-message-uid="'246245'" li-messages-message-image="true" li-bindable="" class="lia-media-image" tabindex="0" li-bypass-lightbox-when-linked="true" li-use-hover-links="false"></span></p>
<p>&nbsp;</p>
<p>In the background, the Support Form is stored in a SharePoint list. <strong>Note</strong>: I have a Flow using the Admin Connectors set up that writes all apps and details (creator, ID) to the SharePoint list. This allows Service Managers to check who has and hasn't provided further details on the app. If you don't have this pre-populated, the Support Form in the app would need to be extended to write app name, creator etc back to this list.</p>
<p>&nbsp;</p>
<p><span class="lia-inline-image-display-wrapper lia-image-align-inline" image-alt="appcreator3.JPG" style="width: 999px;"><img src="https://powerusers.microsoft.com/t5/image/serverpage/image-id/55002i3FA85197FA85D1F1/image-size/large?v=1.0&amp;px=999" title="appcreator3.JPG" alt="appcreator3.JPG" li-image-url="https://powerusers.microsoft.com/t5/image/serverpage/image-id/55002i3FA85197FA85D1F1?v=1.0" li-image-display-id="'55002i3FA85197FA85D1F1'" li-message-uid="'246245'" li-messages-message-image="true" li-bindable="" class="lia-media-image" tabindex="0" li-bypass-lightbox-when-linked="true" li-use-hover-links="false"></span></p>
<p>&nbsp;</p>
<p>This is Version 1 of the app, allowing app users to get a better overview of their apps and documentation.</p>
<p>&nbsp;</p>
<p>I'm working on Version 2, that will include an approval process to get sign-off for an app and bring it into production / IT support or transition it to L2 IT support.&nbsp;</p>
<p>&nbsp;</p>
<p>Any ideas you have for this, please let me know!</p>

