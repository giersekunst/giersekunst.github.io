---
layout: default
title: "Gallery"
author_profile: true
permalink: /
---

<div class="gallery-container">
  <!-- Sa Pa Market -->
  <a href="/images/Little_treat.jpeg" class="glightbox" data-title="Dong Ba Market – Little treat">
    <img src="/images/Little_treat.jpeg" alt="Little treat">
  </a>

  <!-- Sylhet Horse -->
  <a href="/images/Syllhet_horse.jpeg" class="glightbox" data-title="Sylhet Horse">
    <img src="/images/Syllhet_horse.jpeg" alt="Sylhet Horse">
  </a>
</div>

<style>
.gallery-container {
  display: flex;
  flex-wrap: wrap;
  gap: 15px;
}

.gallery-container img {
  width: 200px;
  height: 300px;
  object-fit: cover;
  cursor: pointer;
  border-radius: 6px;
  transition: transform 0.2s;
}

.gallery-container img:hover {
  transform: scale(1.05);
}

@media (max-width: 768px) {
  .gallery-container {
    justify-content: center;
  }
  .gallery-container img {
    width: 150px;
    height: 225px;
  }
}
</style>

<!-- Include GLightbox -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/glightbox/dist/css/glightbox.min.css" />
<script src="https://cdn.jsdelivr.net/npm/glightbox/dist/js/glightbox.min.js"></script>
<script>
document.addEventListener("DOMContentLoaded", function() {
  const lightbox = GLightbox({
    selector: '.glightbox',
    touchNavigation: true,
    loop: true
  });
});
</script>
