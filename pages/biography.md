---
title: Biography
layout: page
permalink: /biography/

bio-img-left: 100px
---

<!--
bio-img-top: -40px
bio-img-top: 30px
bio-img-left: 20px
-->

<style>
  :root {
    --bio-img-top: {{ page.bio-img-top | default: "100%" }};
    --bio-img-left: {{ page.bio-img-left | default: "30px" }};
  }
</style>



<div class="container py-4">

  <div class="row">
    
      <!-- LEFT SIDE -->
<div class="col-md-4 bio-left">

  <div class="bio-header">

  <img class="bio-avatar"
       src="{{ '/assets/img/juanluna3.png' | relative_url }}"
       alt="Photo of Juan Luna">

</div>
     
  <div class="bio-side-text">
    <p><strong>Quick Info:</strong></p>
    <p>
      Born on October 25, 1857<br>
      (1857–1899)
    </p>
  </div>

</div>

<!-- RIGHT SIDE -->
<div class="col-md-8">

  <h2>Biography</h2>

  <p>
    Main biography text goes here. This sits to the right of the image.
  </p>

  <p>
    Add more paragraphs.
  </p>

</div>


</div>
