---
layout: video
---

<div class="index-video">
    <video autoplay muted loop playsinline id="bg-video">
        <source src="{{ '/assets/videos/background.mp4' | relative_url }}" type="video/mp4">
    </video>
    <style>
    #bg-video {
        position: relative;
        top: 0;
        left: 0;
        width: 100%;
        height: 76vh;
        object-fit: cover;
        z-index: -1;
    }
    </style>
</div>