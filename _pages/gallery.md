---
layout: archive
title: "Gallery"
permalink: /gallery/
author_profile: true
---

<div class="gallery">
  <!-- Add your photos here -->
  <div class="gallery-item">
    <img src="images/neu_4f178x09j.jpeg" alt="Performing solar simulator experiments">
    <p>Performing solar simulator experiments</p>
  </div>
  <div class="gallery-item">
    <img src="images/boston_urban_forum_ravi_ramamurti.webp" alt="Speaking as a panelist on sustainability at the Boston Urban Forum">
    <p>Speaking as a panelist on sustainability at the Boston Urban Forum</p>
  </div>
  <!-- Repeat the above block for more images -->
</div>

<style>
.gallery {
  display: flex;
  flex-wrap: wrap;
  gap: 16px;
  justify-content: center;
}

.gallery-item {
  flex: 1 1 calc(33.333% - 16px);
  box-sizing: border-box;
  text-align: center;
}

.gallery-item img {
  max-width: 100%;
  height: auto;
  border-radius: 8px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.gallery-item p {
  margin-top: 8px;
  font-size: 14px;
  color: #555;
}
</style>
