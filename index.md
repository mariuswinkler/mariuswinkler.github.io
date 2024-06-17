---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

<figure>
    <video id="myVideo" style="width: 100%; height: auto; object-fit: cover;" controls autoplay>
        <source src="inputs/SST_video.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
    <figcaption style="background-color: #f2f2f2; padding: 5px;">
        Shown are daily means of sea surface temperature in the equatorial Pacific Ocean from the ICON-Sapphire output.
        The darker, blue shades represent the formation of the equatorial cold tongue. This forms as part of the Bjerknes feedback cycle due to wind-driven upwelling at the equator.
        Also look for the Tropical Instability Waves, these tentacle-like and important structures north and south of the cold tongue.
    </figcaption>
</figure>

<script>
    document.getElementById('myVideo').addEventListener('loadedmetadata', function() {
        this.currentTime = 7; // Set the starting point to 18 seconds
    });
</script>

<div style="text-align: right;">
    <div style="width: 175px; height: 175px; overflow: hidden; border-radius: 50%; float: right;">
        <img src="inputs/MW.jpeg" alt="Marius Winkler" style="width: 100%; height: 100%; object-fit: cover;">
    </div>
</div>

Salut !

I am Marius, an atmospheric physicist and currently engaged as a PhD student within the IMPRS at the Max Planck Institute for Meteorology.

My research centers around equatorial dynamics. As a kitesurfer and sailor, I am particularly interested in surface winds and processes within the atmospheric boundary layer over the oceans.
The equator is one of the warmest areas on our planet on an annual average. At the same time, there are wind-driven currents in the ocean that transport cold water masses to the surface where they interact with the warm atmosphere. We get a region with strong temperature gradients, which is a perfect startpoint for pressure gradients and resulting winds. <br>Exciting, isn't it ?
