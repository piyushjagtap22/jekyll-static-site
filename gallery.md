---
title: Gallery
layout: page
permalink: /gallery/
textcolor: black
projectcolor: pink  
location: bhopal
primaryimage: photo.png
projectdate: 2017
gallery: 
 - image1.jpg
 - image2.jpg
 - image3.jpg
 - image4.jpg
 - image5.jpg
 
---
gallery

<div class="projectimages">
<img src="../images/hara%20hara.png" width="100%" height="auto" />
<div class="imagegrid">
<ol>
    {%- for item in page.gallery -%}
<li>
        <img src="../images/{{item}}" alt="image"/>
</li>
    {%- endfor -%}
</ol>
</div>
</div>

     