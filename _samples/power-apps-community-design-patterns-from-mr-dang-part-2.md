---
title: "Design Patterns from Mr. Dang (Part 2)"
excerpt: "Formativ_ is an app I showcased during an Open House livestream I held a few months ago: https://www.youtube.com/watch?v=Qbl4MujHB9U During the"
originalUrl: https://powerusers.microsoft.com/t5/Community-App-Samples/Design-Patterns-from-Mr-Dang-Part-2/td-p/198929
type: download
publishedDateTime: 2019-01-01T17:50:00Z
heat: 61

actions:
  - url: "https://powerusers.microsoft.com/jgvjg48436/attachments/jgvjg48436/AppFeedbackGallery/70/2/formativ_.msapp"
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
    - name: Mr-Dang-MSFT

topics:
  - Power Apps

images:
  - url: https://powerusers.microsoft.com//jgvjg48436/attachments/jgvjg48436/AppFeedbackGallery/70/1/Screenshot%20(49).png
    width: 4500
    height: 3000
    isCached: true

secured: "Krdr62owyZJOyhxtt2dyM7NIXeItB7l4uMPTCeR4RWtOagKawmkuk48ZCcZubF93X3gWE0W02SzOBxoiwhZkcj01zk7A7PQnEvhqcNLSHNOdqAmv0KZcZgCsKaRSBvrVFFZ5fSPGFA18cYLyxKVdTf4vrrwGLKDYXPaTKBRWSaeDb6CHJQodp6Z8Vi47Fr/utYI6wPqK75umaqmDXUfgNY4F0eA9JElvLkGzSFaA/wA+7sNPBEbveMn2l4VM7uN3ptP1/eWfA7p4nfDzG9ZHEzu5mphFBjXmHLHmnUKh5ykye6TbVQ/buKe3RW1iIQvkBF32DFj79gofyvdXiwwlkp82oncVKuOVkUzby4Ke5gt5I4l2NaXiqyIWMm4YQKROiuJ26M8F+0J3XNBbsnr9104xfw+M/CLvoFzoOZCR77snKxBhyJIrvwpMke47wTYJ;WePqJBCXvqPL3rIt/iQ20A=="
---
<p>Formativ_ is an app I showcased during an Open House livestream I held a few months ago:</p>
<p><a href="https://www.youtube.com/watch?v=Qbl4MujHB9U" target="_blank" rel="nofollow noopener noreferrer">https://www.youtube.com/watch?v=Qbl4MujHB9U</a></p>
<p>&nbsp;</p>
<p>During the livestream, I showed some of the patterns I had in the app, but the app was not as complete for sharing yet.</p>
<p>&nbsp;</p>
<p>Most of the app functionality is complete now. I am sharing its current form so you can see some patterns&nbsp;inside.</p>
<p>&nbsp;</p>
<p>The big idea with the formativ_ app is to take existing&nbsp;questions&nbsp;I have in a spreadsheet and make it into a form, rather than repeating that content in another service. Previously, I would redo questions I wanted to ask one by one in another online service.&nbsp;This takes a lot of time and copy pasting.</p>
<p>&nbsp;</p>
<p>Creating an app would allow me to have a nice interface for users to respond to questions. And the neat thing about PowerApps is I can edit my questions from the spreadsheet or within the UI of the app. I work where I'm comfortable.</p>
<p><span style="font-family: inherit;"><span class="lia-inline-image-display-wrapper lia-image-align-center" image-alt="Screenshot (49).png" style="width: 999px;"><img src="https://powerusers.microsoft.com/t5/image/serverpage/image-id/46941i87CFCA880F8E0C8B/image-size/large?v=1.0&amp;px=999" title="Screenshot (49).png" alt="Screenshot (49).png" li-image-url="https://powerusers.microsoft.com/t5/image/serverpage/image-id/46941i87CFCA880F8E0C8B?v=1.0" li-image-display-id="'46941i87CFCA880F8E0C8B'" li-message-uid="'198929'" li-messages-message-image="true" li-bindable="" class="lia-media-image" tabindex="0" li-bypass-lightbox-when-linked="true" li-use-hover-links="false"></span></span></p>
<p>&nbsp;</p>
<p>Across the app, I use SVG images.&nbsp;This lets me add effects like drop shadow and gradients. The icons I use are consistent in style and minimal.</p>
<p><span style="font-family: inherit;"><span class="lia-inline-image-display-wrapper lia-image-align-center" image-alt="Screenshot (50).png" style="width: 999px;"><img src="https://powerusers.microsoft.com/t5/image/serverpage/image-id/46943iA36595C90B7FACD6/image-size/large?v=1.0&amp;px=999" title="Screenshot (50).png" alt="Screenshot (50).png" li-image-url="https://powerusers.microsoft.com/t5/image/serverpage/image-id/46943iA36595C90B7FACD6?v=1.0" li-image-display-id="'46943iA36595C90B7FACD6'" li-message-uid="'198929'" li-messages-message-image="true" li-bindable="" class="lia-media-image" tabindex="0" li-bypass-lightbox-when-linked="true" li-use-hover-links="false"></span></span></p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>The app has logic built in to autosave.&nbsp;As the user is creating or editing a form/quiz, their changes are saved immediately. As a user is responding to a form or quiz, their responses are saved immediately. This avoids situations where a browser is accidentally closed and progress is lost.</p>
<p><span class="lia-inline-image-display-wrapper lia-image-align-center" image-alt="Screenshot (54).png" style="width: 999px;"><img src="https://powerusers.microsoft.com/t5/image/serverpage/image-id/46939iCD6265AA680BFA6E/image-size/large?v=1.0&amp;px=999" title="Screenshot (54).png" alt="Screenshot (54).png" li-image-url="https://powerusers.microsoft.com/t5/image/serverpage/image-id/46939iCD6265AA680BFA6E?v=1.0" li-image-display-id="'46939iCD6265AA680BFA6E'" li-message-uid="'198929'" li-messages-message-image="true" li-bindable="" class="lia-media-image" tabindex="0" li-bypass-lightbox-when-linked="true" li-use-hover-links="false"></span></p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>While the purpose of the app is to use spreadsheets in harmony with PowerApps, I made a UI to make form/quiz creation to be easier in the app space itself.&nbsp;This interface includes a couple of features I want to call out:</p>
<ul>
<li>reordering records in a collection</li>
<li>duplicating a record in a collection</li>
<li>adapting the content in each row of a gallery depending on what type it is</li>
<li>copy-pasting a column of choices and having it split itself apart into different rows</li>
<li>jump to a question</li>
<li>apply autoheight to a text input box</li>
</ul>
<p><span class="lia-inline-image-display-wrapper lia-image-align-center" image-alt="Screenshot (55).png" style="width: 999px;"><img src="https://powerusers.microsoft.com/t5/image/serverpage/image-id/46944i4E366C0CF9A72984/image-size/large?v=1.0&amp;px=999" title="Screenshot (55).png" alt="Screenshot (55).png" li-image-url="https://powerusers.microsoft.com/t5/image/serverpage/image-id/46944i4E366C0CF9A72984?v=1.0" li-image-display-id="'46944i4E366C0CF9A72984'" li-message-uid="'198929'" li-messages-message-image="true" li-bindable="" class="lia-media-image" tabindex="0" li-bypass-lightbox-when-linked="true" li-use-hover-links="false"></span></p>
<p>&nbsp;&nbsp;&nbsp;</p>
<p>&nbsp;</p>
<p>Existing quizzes and forms can be searched and revised.</p>
<p><span style="font-family: inherit;"><span class="lia-inline-image-display-wrapper lia-image-align-center" image-alt="Screenshot (51).png" style="width: 999px;"><img src="https://powerusers.microsoft.com/t5/image/serverpage/image-id/46942i606E20DD1AE2A4CA/image-size/large?v=1.0&amp;px=999" title="Screenshot (51).png" alt="Screenshot (51).png" li-image-url="https://powerusers.microsoft.com/t5/image/serverpage/image-id/46942i606E20DD1AE2A4CA?v=1.0" li-image-display-id="'46942i606E20DD1AE2A4CA'" li-message-uid="'198929'" li-messages-message-image="true" li-bindable="" class="lia-media-image" tabindex="0" li-bypass-lightbox-when-linked="true" li-use-hover-links="false"></span></span></p>
<p>&nbsp;&nbsp;</p>
<p>&nbsp;</p>
<p>On the Play screen, you can see how I use an accordion to show each session the user has started for a given form.</p>
<p><span class="lia-inline-image-display-wrapper lia-image-align-center" image-alt="Screenshot (52).png" style="width: 999px;"><img src="https://powerusers.microsoft.com/t5/image/serverpage/image-id/46940i342AF462CBF4FAA8/image-size/large?v=1.0&amp;px=999" title="Screenshot (52).png" alt="Screenshot (52).png" li-image-url="https://powerusers.microsoft.com/t5/image/serverpage/image-id/46940i342AF462CBF4FAA8?v=1.0" li-image-display-id="'46940i342AF462CBF4FAA8'" li-message-uid="'198929'" li-messages-message-image="true" li-bindable="" class="lia-media-image" tabindex="0" li-bypass-lightbox-when-linked="true" li-use-hover-links="false"></span></p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>The app is used for both experiences of creating and responding to forms and quizzes. Unique to PowerApps is the ability to include an ink control. I did not put in logic to save the image back to OneDrive, as I leave that up to you to save image content to the service of your choice.&nbsp;<a href="/t5/user/viewprofilepage/user-id/6096">@timl</a>&nbsp;can help explain how to have images saved to your OneDrive from the same spreadsheet.</p>
<p><span style="font-family: inherit;"><span class="lia-inline-image-display-wrapper lia-image-align-center" image-alt="Screenshot (56).png" style="width: 999px;"><img src="https://powerusers.microsoft.com/t5/image/serverpage/image-id/46945i89FD2BD21E58B768/image-size/large?v=1.0&amp;px=999" title="Screenshot (56).png" alt="Screenshot (56).png" li-image-url="https://powerusers.microsoft.com/t5/image/serverpage/image-id/46945i89FD2BD21E58B768?v=1.0" li-image-display-id="'46945i89FD2BD21E58B768'" li-message-uid="'198929'" li-messages-message-image="true" li-bindable="" class="lia-media-image" tabindex="0" li-bypass-lightbox-when-linked="true" li-use-hover-links="false"></span></span></p>
<p>&nbsp;</p>
<p>And as a bonus, the app can be translated. You can see a method of gathering text across the app and translating it. You'll also find that I've worked in tabbing for accessibility.</p>
<p><span style="font-family: inherit;"><span class="lia-inline-image-display-wrapper lia-image-align-center" image-alt="Screenshot (53).png" style="width: 999px;"><img src="https://powerusers.microsoft.com/t5/image/serverpage/image-id/46938iF8E2D746B408218E/image-size/large?v=1.0&amp;px=999" title="Screenshot (53).png" alt="Screenshot (53).png" li-image-url="https://powerusers.microsoft.com/t5/image/serverpage/image-id/46938iF8E2D746B408218E?v=1.0" li-image-display-id="'46938iF8E2D746B408218E'" li-message-uid="'198929'" li-messages-message-image="true" li-bindable="" class="lia-media-image" tabindex="0" li-bypass-lightbox-when-linked="true" li-use-hover-links="false"></span></span></p>
<p>&nbsp;</p>
<p><span style="font-family: inherit;">I am sharing this app with you sooner rather than later. Much of it is complete, but there is a lot that is open for you to implement on your own.&nbsp;</span></p>
<p>&nbsp;</p>
<p><span style="font-family: inherit;">Here's some ideas to get you started:</span></p>
<ul>
<li><span style="font-family: inherit;">implement date, datetime, ratings, etc.&nbsp;</span></li>
<li>create a theme selector for high contrast modes and dark mode</li>
</ul>
<p>&nbsp;</p>
<p>Instructions</p>
<ol>
<li>Download the msapp file and this excel sheet:<br><a href="https://8bitblob.blob.core.windows.net/powerapps/formativ_.xlsx" target="_blank" rel="nofollow noopener noreferrer">https://8bitblob.blob.core.windows.net/powerapps/formativ_.xlsx</a></li>
<li>Move the Excel sheet to your OneDrive</li>
<li>Open create.powerapps.com</li>
<li>File &gt; Open &gt; Browse for the msapp file</li>
<li>View &gt; Datasources &gt; remove all tables from OneDrive so you can add your own.</li>
<li>Add all the tables from the Excel sheet in step 2 (using OneDrive or Dropbox)</li>
<li>Try it out.</li>
</ol>

