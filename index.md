---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

<figure>
    <div style="display: flex; justify-content: center;">
        <video id="myVideo" style="width: 60%; height: auto; object-fit: cover;" controls autoplay loop>
            <source src="inputs/Spherical_Windvideo_16_fps_transparent.webm" type="video/webm">
            Your browser does not support the video tag.
        </video>
    </div>
    <figcaption style="background-color: #f2f2f2; padding: 5px; max-width: 100%; margin: 0 auto;">
        Surface winds (gray shading) interact dynamically with the Earth's surface—over land, they reveal orographic features, while over the ocean, they actively shape ocean dynamics. Sea surface temperature (color-coded) reaches a local minimum in the equatorial cold tongue regions, a signature of air-sea interaction. Shown is output from an ICON simulation at 5 km resolution. Credit: MPI-M, DKRZ.
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

I am Marius, an atmospheric physicist and currently engaged as a Postdoc at the Max Planck Institute for Meteorology.

My research centers on equatorial dynamics. As a kitesurfer and sailor, I’m particularly interested in surface winds and the processes within the atmospheric boundary layer over the oceans.
The equator is one of the warmest regions on Earth on an annual average. At the same time, wind-driven ocean currents bring cold water masses to the surface, where they interact with the warm boundary layer. This interaction creates temperature gradients that lead to pressure gradients and drive boundary layer winds.
Yet, the warm boundary layer also interacts with the overlying free troposphere and thus serves as an active, mediating layer that connects Earth’s surface with the higher atmosphere. <br>Exciting, isn't it ?
