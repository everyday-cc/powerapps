---
title: "Neumorphism Generator"
excerpt: "This app helps in the design and implementation of HTML-based rectangular and circular neumorphic elements. It can produce four element types: a flat"
originalUrl: https://powerusers.microsoft.com/t5/Community-App-Samples/Neumorphism-Generator/td-p/539729
type: download
publishedDateTime: 2020-04-26T17:01:00Z
heat: 55

actions:
  - url: "https://powerusers.microsoft.com/jgvjg48436/attachments/jgvjg48436/AppFeedbackGallery/509/2/Neumorphism%20Generator.msapp"
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
    - name: wyotim

topics:
  - Power Apps

images:
  - url: https://powerusers.microsoft.com/t5/image/serverpage/image-id/180100i527A243A242BE7BB/image-size/large?v=1.0&px=999
    width: 400
    height: 225
    isCached: true

secured: "08bnWB30AMajDnnUpfHqui+/6zN2cIo/+Uooj8S3nfIWUva+t6oS5jmlr9XqzvaphlBDcNPF6UVnyjYsqPY1eFeOoaQVNPo8Oiw1nuhXtTfADT2Hy1ALT0RpZopdz7UJAyJ0dL3x/WdKz/cMNRP5X5Sv9cdrftF8D7op4Dmzu1GN14VPwMh2xIMjVo5cA87EwIIP/eVY9Bheo8wNnSbcBnw9epLpfoE9JJb25cEQ37EhN9Y24vYyzIi/O40ORvl1hgH7rvaZQPygU59nyjmDMaUGwdUv/aiVruh4unXl5UruS1gQgggpaNlOxTBBatzZZ5sB2Dbth8TCpKYquTB3PP6c9Zle3r+46bQxF2r6VXwXalzaexVS2BOOwOkbt6qeLkhqlpIv0J+TvH5dYsr/dAKfZILRrVNFqGjUCGAN2/qSBCpQ+E/FysZI94ybLzqs;A2Fa664B7fcc8WStKXO7DQ=="
---
<p>This app helps in the design and implementation of HTML-based rectangular and circular neumorphic elements.</p>
<p>&nbsp;</p>
<p>It can produce four element types: a flat shape, a concave shape, a convex shape, and a "pressed" shape that looks pushed into the surface. There are also four light directions: top left, top right, bottom left, and bottom right. The distance, intensity, and blur of the shadow elements can be set, as well as the size and corner radius. Also, it can take hex or RGB colors and has some error handling to help if an invalid value is entered.&nbsp;</p>
<p>&nbsp;</p>
<p>To read more about neumorphism, please see <a href="https://css-tricks.com/neumorphism-and-css/" target="_self" rel="nofollow noopener noreferrer">this article</a> or <a href="https://uxdesign.cc/neumorphism-in-user-interfaces-b47cef3bf3a6" target="_self" rel="nofollow noopener noreferrer">this article</a> and for a critique of some problems of this design, <a href="https://uxdesign.cc/neumorphism-the-zombie-trend-88cff23de46b" target="_self" rel="nofollow noopener noreferrer">this article</a>. This app was also based heavily on <a href="https://neumorphism.io/" target="_self" rel="nofollow noopener noreferrer">this online generator</a>. If you enjoy this app, please consider clicking the "buy me a coffee" link at the bottom to show the creator who inspired it,&nbsp;Adam Giebl (<a href="https://www.instagram.com/adamgiebl.io/" target="_self" rel="nofollow noopener noreferrer">Instagram</a> / <a href="https://twitter.com/adam_giebl" target="_self" rel="nofollow noopener noreferrer">Twitter</a>), some appreciation!</p>
<p>&nbsp;</p>
<p>There are two basic parts to this tool:</p>
<ol>
<li>The app itself, which is a designer and HTML generator</li>
<li>Three components that can be used to insert neumorphic rectangles and circles into a Power App</li>
</ol>
<p>The HTML generator has code that can be put into an HtmlText object along with some notes to aid in the setup of the shape. If using the code, there are comments to give the needed values to put in each respective property. Also, this only generates squares/circles up to 400px in width/height. The code can be manually altered with desired dimensions, which the comments also address.</p>
<p>&nbsp;</p>
<p>One very important note: all Padding properties must be set to 0! If not, scrollbars will appear, and no one wants that! There will be math involved in aligning other elements to the shape. Simply put, the shape exists within +/- one margin on the width and height, though the overall height of the HtmlText object is 1 pixel more than the height of the neumorphic shape and the margins on each side. For more on the dimensions and how to align objects, please see the "Getting Started" section of this <a href="https://powerusers.microsoft.com/t5/News-Announcements/Using-layered-html-box-shadows-to-create-a-sense-of-depth/ba-p/415661" target="_self">blog post</a>.</p>
<p>&nbsp;</p>
<p>To explain why there are three components, they are based around the color code used. One is for hex color codes, one is for RGB color codes, and the third is a transparent shape for those who may want to forgo the color aspect for whatever reason. This seemed easier and lighter than trying to have one component for all color types or forcing users to choose one.&nbsp;</p>
<p>&nbsp;</p>
<p>One note on these components and the shapes in general: because these are HTML objects with shadows, the boundaries of the object depend greatly on the distance and blur of the shadows. The shape casting the shadow is actually within the object and will have different height, width, and X and Y coordinates for the items that are overlaying the object. To try and make this easier, the components have Shape X, Shape Y, Shape Height, and Shape Width inputs. To easily align the HTML object, set the component X and Y properties as follows:</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<pre class="lia-code-sample language-csharp"><code>// X property
comNeumorphName.ShapeX - comNeumorphName.ShapeOffset

// Y property
comNeumorphName.ShapeY - comNeumorphName.ShapeOffset
</code></pre>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>Doing this, and setting the Shape X, Shape Y, Shape Height, and Shape Width inputs to the desired values for the shape itself, will result in a nicely aligned shape and a math-free design experience.&nbsp;<img class="lia-deferred-image lia-image-emoji" src="/html/emoticons/1f601.png" alt=":beaming_face_with_smiling_eyes:" title=":beaming_face_with_smiling_eyes:"></p>
<p>&nbsp;</p>
<p>There are some fun aspects in this app that have nothing to do with neumorphism, namely the dynamically calculated black/white text based on the chosen color and complementary color (with its own black/white text). Feel free to pick this apart and give me any feedback you have by messaging me here or on Twitter (@ShortForTim).&nbsp;</p>
<p>&nbsp;</p>
<p><span class="lia-inline-image-display-wrapper lia-image-align-inline" image-alt="NeumorphAppHex.png" style="width: 400px;"><img src="https://powerusers.microsoft.com/t5/image/serverpage/image-id/137126i1BCC034D58F472BC/image-size/medium?v=1.0&amp;px=400" title="NeumorphAppHex.png" alt="Hex color" li-image-url="https://powerusers.microsoft.com/t5/image/serverpage/image-id/137126i1BCC034D58F472BC?v=1.0" li-image-display-id="'137126i1BCC034D58F472BC'" li-message-uid="'539729'" li-messages-message-image="true" li-bindable="" class="lia-media-image" tabindex="0" li-bypass-lightbox-when-linked="true" li-use-hover-links="false"><span class="lia-inline-image-caption" onclick="event.preventDefault();">Hex color</span></span><span class="lia-inline-image-display-wrapper lia-image-align-inline" image-alt="NeumorphAppRGB.png" style="width: 400px;"><img src="https://powerusers.microsoft.com/t5/image/serverpage/image-id/137127i45E2A4C484C49611/image-size/medium?v=1.0&amp;px=400" title="NeumorphAppRGB.png" alt="RGB color" li-image-url="https://powerusers.microsoft.com/t5/image/serverpage/image-id/137127i45E2A4C484C49611?v=1.0" li-image-display-id="'137127i45E2A4C484C49611'" li-message-uid="'539729'" li-messages-message-image="true" li-bindable="" class="lia-media-image" tabindex="0" li-bypass-lightbox-when-linked="true" li-use-hover-links="false"><span class="lia-inline-image-caption" onclick="event.preventDefault();">RGB color</span></span><span class="lia-inline-image-display-wrapper lia-image-align-inline" image-alt="NeumorphAppColors.png" style="width: 400px;"><img src="https://powerusers.microsoft.com/t5/image/serverpage/image-id/137128i764A720193DF359D/image-size/medium?v=1.0&amp;px=400" title="NeumorphAppColors.png" alt="Enumerated colors" li-image-url="https://powerusers.microsoft.com/t5/image/serverpage/image-id/137128i764A720193DF359D?v=1.0" li-image-display-id="'137128i764A720193DF359D'" li-message-uid="'539729'" li-messages-message-image="true" li-bindable="" class="lia-media-image" tabindex="0" li-bypass-lightbox-when-linked="true" li-use-hover-links="false"><span class="lia-inline-image-caption" onclick="event.preventDefault();">Enumerated colors</span></span><span class="lia-inline-image-display-wrapper lia-image-align-inline" image-alt="NeumorphAppRGBError.png" style="width: 400px;"><img src="https://powerusers.microsoft.com/t5/image/serverpage/image-id/137129iB321F0D43227A11F/image-size/medium?v=1.0&amp;px=400" title="NeumorphAppRGBError.png" alt="RGB error" li-image-url="https://powerusers.microsoft.com/t5/image/serverpage/image-id/137129iB321F0D43227A11F?v=1.0" li-image-display-id="'137129iB321F0D43227A11F'" li-message-uid="'539729'" li-messages-message-image="true" li-bindable="" class="lia-media-image" tabindex="0" li-bypass-lightbox-when-linked="true" li-use-hover-links="false"><span class="lia-inline-image-caption" onclick="event.preventDefault();">RGB error</span></span></p>

