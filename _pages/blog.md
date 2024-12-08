---
layout: archive
title: "Blog"
permalink: /blog/
author_profile: true
---

<div class="gallery">
  <!-- Add your photos here -->
  <div class="gallery-item">
    <img src="/images/neu_4f178x09j.jpeg" alt="Performing solar simulator experiments">
    <p>Performing solar simulator experiments</p>
  </div>
  <div class="gallery-item">
    <img src="/images/boston_urban_forum_ravi_ramamurti.webp" alt="Speaking as a panelist on sustainability at the Boston Urban Forum">
    <p>Speaking as a panelist on sustainability at the Boston Urban Forum</p>
  </div>
  <div class="gallery-item">
    <img src="/images/IMG_0855.png" alt="A successful thesis defense!">
    <p>A successful thesis defense!</p>
  </div>
  <div class="gallery-item">
    <img src="/images/EPD_7280.jpg" alt="Cleantech & Sustainability Finalists in the Eddies program">
    <p>Cleantech & Sustainability Finalists in the Eddies program</p>
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
  flex: 1 1 calc(50% - 16px); /* Ensures 2 items per row */
  text-align: center;
  display: flex;
  flex-direction: column;
  align-items: center;
  box-sizing: border-box;
}

.gallery-item img {
  width: 100%; /* Makes the image fill the item's width */
  max-width: 400px; /* Adjust this value as needed */
  height: 225px; /* Ensures consistent image height */
  object-fit: cover; /* Crops the image to fit the specified dimensions */
  border-radius: 8px; /* Optional: Adds rounded corners */
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); /* Optional: Adds a shadow effect */
}

.gallery-item p {
  margin-top: 8px;
  font-size: 14px;
  color: #555;
  min-height: 40px; /* Ensures consistent height for the text container */
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
}
</style>
