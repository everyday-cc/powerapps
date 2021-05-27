---
title: "#Challenge: PowerApps with two Data Sources"
excerpt: "This app showcases the use of 2 data sources within the same application, connecting to a Microsoft Dynamics GP on-premises company database in SQL"
originalUrl: https://powerusers.microsoft.com/t5/Community-App-Samples/Challenge-PowerApps-with-two-Data-Sources/td-p/234981
type: download
publishedDateTime: 2019-02-10T16:43:00Z
heat: 50

actions:
  - url: "https://powerusers.microsoft.com/jgvjg48436/attachments/jgvjg48436/AppFeedbackGallery/99/2/Sales%20Contact%20-%20Two%20Sources.msapp"
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
    - name: SanAndresMan1

topics:
  - Power Apps

images:
  - url: https://powerusers.microsoft.com//jgvjg48436/attachments/jgvjg48436/AppFeedbackGallery/99/1/SalesContact2Sources.png
    width: 1913
    height: 884
    isCached: true

secured: "MZQS99HmB8ZSlPHmisM7W89Tq6EZ2/r+RITZa3CcK5qk5MohSAhwofzIPnS+8+2WA11ncv4XPm7BY6Z+kFhi2C7wOPpCg3gv7XRbhczCnNMrp2uAForCAZcPXH4gljQsxmQa0mK8zw4e2EY07TyVEe4/Jn+uymZYd5s9MBzo02fEu4v/wDtCOAfusAFPZzJbXY4dm6bhdsNfGnXONBNgzk0eiHAISFpjVfb1PmFejbx53QqcUFl9uJ+S0fCGyqgdZjwmX7xMP5GdMLdCkclMNrMQB0eZ/4ngxIpoPR5NBds3YOd/19QuUebZWe7nLEtn1JeAdSBbid4oEUBiUhm7zAMNgSR1WYM1Iljw6Vuof7BCnQKApJZ8oL463mtA63mhfPQIa6hNummsgTUajEKkIUSNNpaWQECu/YMl+LNWI+p0fYA+z2s9hTDZlGtptyar;FIAH5Npi+NdE1k4g+svYvQ=="
---
<p>This app showcases the use of 2 data sources within the same application, connecting to a Microsoft Dynamics GP on-premises company database in SQL Server and a Dynamics 365 for Sales cloud instance.&nbsp;</p><p>In this case, we will display a customer list from Microsoft Dynamics GP and find the corresponding contacts in the Contacts entity in Dynamics 365 for Sales.&nbsp;</p><p>&nbsp;</p><p><span class="lia-inline-image-display-wrapper lia-image-align-inline" image-alt="SalesContact2Sources.png" style="width: 999px;"><img src="https://powerusers.microsoft.com/t5/image/serverpage/image-id/51787i2027DDE428ACACB4/image-size/large?v=1.0&amp;px=999" title="SalesContact2Sources.png" alt="SalesContact2Sources.png" li-image-url="https://powerusers.microsoft.com/t5/image/serverpage/image-id/51787i2027DDE428ACACB4?v=1.0" li-image-display-id="'51787i2027DDE428ACACB4'" li-message-uid="'234981'" li-messages-message-image="true" li-bindable="" class="lia-media-image" tabindex="0" li-bypass-lightbox-when-linked="true" li-use-hover-links="false"></span></p><p>If a customer is selected from the list, summary information is presented from Microsoft Dynamics GP, but contact information is retrieved from Dynamics 365 for Sales as shown below. The map is achieved by passing in the customer address to Google Maps.&nbsp;</p><p><span class="lia-inline-image-display-wrapper lia-image-align-inline" image-alt="SalesContact2Sources2.png" style="width: 999px;"><img src="https://powerusers.microsoft.com/t5/image/serverpage/image-id/51788iF3512A95215CCD37/image-size/large?v=1.0&amp;px=999" title="SalesContact2Sources2.png" alt="SalesContact2Sources2.png" li-image-url="https://powerusers.microsoft.com/t5/image/serverpage/image-id/51788iF3512A95215CCD37?v=1.0" li-image-display-id="'51788iF3512A95215CCD37'" li-message-uid="'234981'" li-messages-message-image="true" li-bindable="" class="lia-media-image" tabindex="0" li-bypass-lightbox-when-linked="true" li-use-hover-links="false"></span></p><p>In order to display the contact list from Dynamics 365 for Sales, a gallery has been added which simply displays the contact name and whether or not they would like to be contacted by email. A filter is applied to only display the correspoding contact for a specific customer record.</p><p>&nbsp;</p><p><span class="lia-inline-image-display-wrapper lia-image-align-inline" image-alt="SalesContact2Sources3.png" style="width: 999px;"><img src="https://powerusers.microsoft.com/t5/image/serverpage/image-id/51790i70CAC072086FC872/image-size/large?v=1.0&amp;px=999" title="SalesContact2Sources3.png" alt="SalesContact2Sources3.png" li-image-url="https://powerusers.microsoft.com/t5/image/serverpage/image-id/51790i70CAC072086FC872?v=1.0" li-image-display-id="'51790i70CAC072086FC872'" li-message-uid="'234981'" li-messages-message-image="true" li-bindable="" class="lia-media-image" tabindex="0" li-bypass-lightbox-when-linked="true" li-use-hover-links="false"></span></p>

