---
permalink: /video.html
---

<body>
    {% capture homeRow %}{% include homeRow.md %}{% endcapture %}
    {{ homeRow | markdownify }}
</body>

<figure class="video_container">
  <video controls="true" allowfullscreen="true" poster="path/to/poster_image.png">
    <source src="assets/videos/bruh.mp4" type="video/mp4">
  </video>
</figure>
