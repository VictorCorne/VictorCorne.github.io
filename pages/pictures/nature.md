---
title: Pictures from the forest
layout: post
---

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Heverleebos Image Gallery</title>
    <style>
        .gallery {
            /* display: flex; */
            /* flex-wrap: wrap; */
            gap: 30px; /* Space between images */
        }

        .image-item {
            <!-- flex: 1 1 200px; /* Each item takes up at least 200px and can grow */ -->
            <!-- max-width: 200px; /* Maximum width for each image item */ -->
        }

        .image-item img {
            width: 100%; /* Images take up full width of their container */
            height: auto; /* Maintain aspect ratio */
            border-radius: 5px; /* Optional: add rounded corners */
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1); /* Optional: add a subtle shadow */
        }
    </style>
</head>


<div class="gallery">

  {% for i in (1..11) %}
    <div class="image-item">
      <img src="../../assets/pictures/nature/Heverleebos/bos_{{ i }}.jpg" alt="bos_{{ i }}">
    </div>
    <p></p>
  {% endfor %}

</div>