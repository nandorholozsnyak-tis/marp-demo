<!-- 
paginate: true
backgroundColor: #1F2F3B
color: #f7941d
html: true
header: Presentation header
footer: Presentation footer
-->
---
# TIS Presentation
We can use the typical Markdown syntax and every time we would like to create a new slide we just have to insert the 3 dashed **'`---`'** at the end of our slide.
In the header comment section we are able to configure global and local directives which can control:
 - pagination
 - background color
 - text color
 - enable HTML tags in our presentation
 - header and footer content

---
<!-- _paginate: false -->
<!-- _header: Pagination turned off for this slide -->
<!-- _backgroundImage: "linear-gradient(to bottom, #1F2F3B, #1f1f1f)" -->
<!-- _footer: Custom background only for this slide -->
# Second slide
We can customize slides individually from the global scope, we can use local scope directives, to use the local scope just start the property name with a '_', for example:
  - pagination can be turned off on slides (_paginate: false)
  - header and footer content can be changed (_header and _footer)
  - background related color or image
  - font color
  - custom directives written in Javascript
---
# CSS support
Marp has a wide variety of CSS support which can be found [here](https://marpit.marp.app/theme-css)

---
# Presenter note
During the presentation we can make some presenter note for ourselves, which will only be shown to the presenter. To make it we just have to place the note into a comment tag like this:
<!-- We can make comments during our presentation which will be shown in the presenter tool -->

---
<!-- _backgroundImage: url(https://justyy.com/wp-content/uploads/2016/01/markdown-syntax-language.png) -->
<!-- _color: red -->
<p style="position:absolute; top: 100px">Background image support</p>
<p style="position:absolute; top: 400px">We all love Markdown</p>

---
<!-- _backgroundColor: white -->
<!-- _color: white -->
<!-- _header: '' -->
<!-- _footer: '' -->
<p style="position:absolute; top: 100px">Multiple backgrounds with splitting</p>

![bg](https://fakeimg.pl/800x600/0288d1/fff/?text=A)
![bg](https://fakeimg.pl/800x600/02669d/fff/?text=B)
![bg](https://fakeimg.pl/800x600/67b8e3/fff/?text=C)

---
# And many more
Check out the [Marp](https://marpit.marp.app/) website to know more.