---
layout: home
title: "Gallery"
author_profile: false
---
<div class="gallery">

  <div class="gallery-item">
    <a href="{{ '/blog/sa-pa-market/' | relative_url }}">
      <img src="{{ '/images/Sa_Pa_market_Little_treat.jpeg' | relative_url }}" alt="Sa Pa Market - Little Treat">
    </a>
    <p>Sa Pa Market – Little Treat</p>
  </div>

  <div class="gallery-item">
    <a href="{{ '/blog/syllhet-horse/' | relative_url }}">
      <img src="{{ '/images/Syllhet_horse.jpeg' | relative_url }}" alt="Syllhet Horse">
    </a>
    <p>Syllhet Horse</p>
  </div>

</div>

<style>
.gallery {
  display: flex;
  flex-wrap: wrap;
  gap: 15px;
}
.gallery-item {
  width: 250px;
  text-align: center;
}
.gallery-item img {
  width: 100%;
  border-radius: 6px;
}
</style>
