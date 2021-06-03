---
title: "Responsive Design Template"
excerpt: "In the following post, I explain the three attached companion apps/components. I use the two components to design a fully responsive app, the Sample"
originalUrl: https://powerusers.microsoft.com/t5/Community-App-Samples/Responsive-Design-Template/td-p/417884
type: download
publishedDateTime: 2019-12-03T06:59:00Z
heat: 53

actions:
  - url: "https://powerusers.microsoft.com/jgvjg48436/attachments/jgvjg48436/AppFeedbackGallery/339/4/screenSimulator.msapp"
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
    - name: KickingApps

topics:
  - Power Apps

images:
  - url: https://powerusers.microsoft.com//jgvjg48436/attachments/jgvjg48436/AppFeedbackGallery/339/6/Screen%20Shot%202020-05-06%20at%208.08.02%20PM.png
    width: 543
    height: 41
    isCached: true

secured: "/zjqgOYv+x9Q4U36mPztptV5c2aVSFXnPk/hWWTN7IyBmkNkGmOQC7s504GoRy2B8G8Up5bGWoQ0F/y3l5hGjj3xCuBR87XgcloFlC+JrN9eHFO7TsEiVwdy5crs8pvwBeiwFvT9F199xkLGmXGkhJTU/X1P790VjZEy+aicK3Z1d53OzX8l34UPtsWeQgCEi4PnxfjfKsJPZnPGnLXgfFfXhazDXI0Y1zpzjgg6FkJR3EXEecA2dVOxD+2QG91NaX53hqi1/qYdf1NNe1aMniKkdYcDl2Q25Bm4YoDud6CQu4iYIgzdqNQYukwqLgSIlnd8Ia0mQBjOnGD2HeZ1DMmvEnPYrnv1VMLIytF847qIHGPyusQfD9F0Vtowk6zdxMLRXOgdzyek3TAlKsEKOOLlBc6Gash++ShY48H5QdmBIg7B/yDLFwHuegVdwCmN;F7u0uqYy4UK29e40skc2wQ=="
---
<p class="p1">In the following post, I explain the three attached companion apps/components.&nbsp; I use the two components to design a fully responsive app, the Sample app is simply a reference tool.</p><p class="p1"><br>When responsive design was announced as a feature in PowerApps, I could hardly wait to dig in and start creating. When I did, however, I found the process quite challenging. Without a visual reference, the need to continually&nbsp;<i>Save and Publish</i> the app in order to view and test the layout was a pain. With that in mind, I created the the scrnSimulator (component). The idea is to visually see how things will look for a preselected screen layout. Additionally, while researching responsive design, I stumbled upon responsive, fluid grids and thought it would be a great companion to the screen simulator. Below I do my best to describe each.</p><ul><li><font color="#800000"><u><strong>Screen Simulator Component</strong></u>&nbsp;</font>- Mimic the various screen sizes I am designing for - primarily used as a visual reference and guide for determining dynamic height values of controls and Y positioning.&nbsp;</li></ul><p class="p1">I have found the most effective method for utilizing this template is to have the template open in one window and the actual app I am creating open in another. I use the template to create my&nbsp;<strong>layout</strong>. Once I am satisfied with the layout of controls, I:</p><p class="p1">1)'code' the&nbsp;property&nbsp;values into my actual app (for the selected screen size)</p><p class="p1">2) change the size of my template</p><p class="p1">3) re-order the controls so they fit the new screen size</p><p class="p1">4) update the code in my app, and repeat....</p><p class="p1">&nbsp;</p><p class="p1"><u><strong>Y Property</strong></u></p><p class="p1">To determine the Y property based on the layout, refer to lblY_Reference in the template&nbsp;</p><p class="p1">The result of this calculation is I what I use to set the Y properties of the controls.</p><p class="p1">&nbsp;</p><p class="p1"><u><strong>Height Property</strong></u></p><p class="p1">Similar to the Y Property reference, I have a<strong>&nbsp;height reference label</strong>&nbsp;to determine and calculate the dynamic height of each control. Set the value of the control in the app to the result of the height reference control in the template * App.Height.&nbsp;</p><p class="p1">** When switching layouts, this can be finicky, particularly transitioning to a large layout. I have found the best way to reset the view is to navigate from the component to Screen 1 and back to component. When back in the component, select the double arrow icon (zoom) and it should reset the view.</p><p class="p1">&nbsp;</p><ul><li><u><font color="#800000"><strong>Fluid Grid Component -</strong></font></u><font color="#000000"><strong> The&nbsp;</strong></font>Fluid&nbsp;Grid Component is comprised of&nbsp;<i>gutters</i><span>&nbsp;and&nbsp;</span><i>columns;&nbsp;</i>the values of the gutters and columns are what I use to set the 'X' property of my controls.&nbsp;<span>The width of the gutters and columns dynamically calculate as the screen size changes. The grid is meant as another design reference. I DO add this to the actual app I am creating, toggle the grid on when I need a visual reference, and remove it from the app once it is completed and moved into production (optional).&nbsp;</span></li></ul><p><span>The 'X' property of each control is determined from the output of the collection results (calculated in the 'OnChange' of the slider control). Because the slider is on the screen, not in the component, the values will 'hold' if the component is removed.</span></p><p>&nbsp;</p><ul><li><u><font color="#800000"><strong>Sample App -</strong></font></u><font color="#000000"><strong>&nbsp;<font color="#000000">This is simply a reference for the fluid grid component. The app has 3 text inputs that default to 'C4', and '3*1'. If you toggle the grid on, you will see that, with the above values, the&nbsp;<em>Button</em>'s X value will be at column 4 and width&nbsp;<em>Button</em> = 3 columns + 1 gutter. Change the values, and you will see the button change.&nbsp; Additionally, minimize the screen and you will see the width of the columns/gutters re-calculating on the fly.</font></strong></font></li><li><font color="#000000"><strong><font color="#000000">Finally, I have been experimenting with fluid/responsive text. I left the text boxes I am experimenting with in the app. </font></strong></font></li></ul><p class="p1">** Note - this is attached in reply below due to 3 attachment limit.&nbsp;</p><p class="p1">&nbsp;</p><p class="p1">Not too long ago, the #PowerAddicts interviewed&nbsp;@Foyinb and she said "Just do the thing". While I can "make the thing", "explaining the thing" isn't so easy :). So, with that, i<strong>f you have questions related to this template, please feel free to reach out via Twitter&nbsp; -&nbsp;</strong><a href="https://powerusers.microsoft.com/t5/user/viewprofilepage/user-id/16287" target="_blank" rel="noopener"><span class="s2"><strong>@tianaranjo</strong></span></a><strong>&nbsp;(a.k.a. kickingapps) or tianaranjo@kickingapps.onmicrosoft.com<br><br><br></strong></p>

