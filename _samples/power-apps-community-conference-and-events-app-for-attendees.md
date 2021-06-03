---
title: "Conference and Events App for Attendees"
excerpt: "Hello, inspired by a video by Audrie Gordon ( https://www.youtube.com/watch?v=1rsyyYiI4sU ) and by a few conversations with Martin Lee and a few"
originalUrl: https://powerusers.microsoft.com/t5/Community-App-Samples/Conference-and-Events-App-for-Attendees/td-p/199250
type: download
publishedDateTime: 2019-01-02T10:19:00Z
heat: 55

actions:
  - url: "https://powerusers.microsoft.com/jgvjg48436/attachments/jgvjg48436/AppFeedbackGallery/71/2/Conference%20App%20Template.msapp"
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
  - url: https://powerusers.microsoft.com//jgvjg48436/attachments/jgvjg48436/AppFeedbackGallery/71/1/eventapp.JPG
    width: 321
    height: 571
    isCached: true

secured: "bwIY8yZk1II23P4sMN4tbH1zteStRf1eEweRPCRH3HrROsrb46nHf95IqtqAcJALFVT2OfjMlltCa8wqA1kUtieyyAlgYJwiXpt1SCt1JOMf0YwYFmE6Vxni2me+ys+fsniMD45cvAQc7eV7EJTq3Ji9DGBbGc5ot6V2UYOarz4YsWWOal5HcUEm8NNVFa1tDwUdpkoK04cx37YIh1307iLPyLl0S09lccYAllE7W2alBCkUwjegIlbzl1weEAe/RzIoO48y9HQQaucWObZkJdEUCM2fCdEBOvXzegdQvlaiSFFSf0YVlcRnvbSpulTozj8TiRwxvffmqjKmjv7RDkrjeVi/Y1aoQi5ZHIWtFFnBPKMBWWNt0v6+5XVQJ7aDRYIYA1yQpT0lhxa4pU7JRrSy1OPgclCd3TKpHzAnXsUltlLh1l1SRd+XNiLL7oC/;5gtjMRD+MG4kw+aAOD6r6Q=="
---
<p>Hello,<br><br>inspired by a video by Audrie Gordon (<a href="https://www.youtube.com/watch?v=1rsyyYiI4sU" target="_blank" rel="noopener nofollow noopener noreferrer">https://www.youtube.com/watch?v=1rsyyYiI4sU</a>) and by a few conversations with Martin Lee and a few people in my organization, I decided to develop a PowerApps template for attendees of a conference.<br>The template covers two use cases:<br><br>1. On the day of the event, for attendees to view the agenda, speakers, refreshment and transport options, provide feedback on sessions etc<br>2. If you're a member of a network at work, the second app would allow you to view events upcoming for that group/network, learn about opportunities etc. This could be enhanced to volunteer to speak, or suggest events.</p>
<p><br>All data in the template, including the navigation options, is coming from collections set in the OnVisible event of the first screens. The company colors are also set in the OnVisible event of the first screen.<br><br>Here are some screenshots of the app:</p>
<p><span class="lia-inline-image-display-wrapper lia-image-align-inline" image-alt="Network Events List and Registration" style="width: 503px;"><img src="https://powerusers.microsoft.com/t5/image/serverpage/image-id/47153i635ECE4EE6153F8D/image-size/large?v=1.0&amp;px=999" title="event3.JPG" alt="Network Events List and Registration" li-image-url="https://powerusers.microsoft.com/t5/image/serverpage/image-id/47153i635ECE4EE6153F8D?v=1.0" li-image-display-id="'47153i635ECE4EE6153F8D'" li-message-uid="'199250'" li-messages-message-image="true" li-bindable="" class="lia-media-image" tabindex="0" li-bypass-lightbox-when-linked="true" li-use-hover-links="false"><span class="lia-inline-image-caption" onclick="event.preventDefault();">Network Events List and Registration</span></span><span class="lia-inline-image-display-wrapper lia-image-align-inline" image-alt="Network Events Home Screen" style="width: 502px;"><img src="https://powerusers.microsoft.com/t5/image/serverpage/image-id/47152i823EE37D1231AD50/image-size/large?v=1.0&amp;px=999" title="event2.JPG" alt="Network Events Home Screen" li-image-url="https://powerusers.microsoft.com/t5/image/serverpage/image-id/47152i823EE37D1231AD50?v=1.0" li-image-display-id="'47152i823EE37D1231AD50'" li-message-uid="'199250'" li-messages-message-image="true" li-bindable="" class="lia-media-image" tabindex="0" li-bypass-lightbox-when-linked="true" li-use-hover-links="false"><span class="lia-inline-image-caption" onclick="event.preventDefault();">Network Events Home Screen</span></span><span class="lia-inline-image-display-wrapper lia-image-align-inline" image-alt="Speakers List" style="width: 506px;"><img src="https://powerusers.microsoft.com/t5/image/serverpage/image-id/47155iA665A159453313CF/image-size/large?v=1.0&amp;px=999" title="eventpeople.JPG" alt="Speakers List" li-image-url="https://powerusers.microsoft.com/t5/image/serverpage/image-id/47155iA665A159453313CF?v=1.0" li-image-display-id="'47155iA665A159453313CF'" li-message-uid="'199250'" li-messages-message-image="true" li-bindable="" class="lia-media-image" tabindex="0" li-bypass-lightbox-when-linked="true" li-use-hover-links="false"><span class="lia-inline-image-caption" onclick="event.preventDefault();">Speakers List</span></span><span class="lia-inline-image-display-wrapper lia-image-align-inline" image-alt="Agenda" style="width: 504px;"><img src="https://powerusers.microsoft.com/t5/image/serverpage/image-id/47154i84572E1E08FAE419/image-size/large?v=1.0&amp;px=999" title="eventagenda.JPG" alt="Agenda" li-image-url="https://powerusers.microsoft.com/t5/image/serverpage/image-id/47154i84572E1E08FAE419?v=1.0" li-image-display-id="'47154i84572E1E08FAE419'" li-message-uid="'199250'" li-messages-message-image="true" li-bindable="" class="lia-media-image" tabindex="0" li-bypass-lightbox-when-linked="true" li-use-hover-links="false"><span class="lia-inline-image-caption" onclick="event.preventDefault();">Agenda</span></span><span class="lia-inline-image-display-wrapper lia-image-align-inline" image-alt="Managers Conference Home Screen" style="width: 321px;"><img src="https://powerusers.microsoft.com/t5/image/serverpage/image-id/47156i6656F3BAA6B5B0D8/image-size/large?v=1.0&amp;px=999" title="eventapp.JPG" alt="Managers Conference Home Screen" li-image-url="https://powerusers.microsoft.com/t5/image/serverpage/image-id/47156i6656F3BAA6B5B0D8?v=1.0" li-image-display-id="'47156i6656F3BAA6B5B0D8'" li-message-uid="'199250'" li-messages-message-image="true" li-bindable="" class="lia-media-image" tabindex="0" li-bypass-lightbox-when-linked="true" li-use-hover-links="false"><span class="lia-inline-image-caption" onclick="event.preventDefault();">Managers Conference Home Screen</span></span></p>

