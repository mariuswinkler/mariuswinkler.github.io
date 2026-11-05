---
title: "A Shoemaker's Path into Science"
layout: single
permalink: /shoemaking/
---
<figure style="max-width: 300px; margin: 1em auto;">
  <img src="/assets/images/shoemaking/shoe1.jpeg" style="width: 100%; height: auto; object-fit: cover;">
  <figcaption style="font-style: italic; color: #666; margin-top: 0.0em; font-size: 0.9em; width: 100%; display: block; text-align: center;">Meisterstück</figcaption>
</figure>

As a kid, I spent long summers in my father's workshop. The smell of sawdust and the quiet joy of a joint that fits stayed with me. After school, I found a book on bespoke shoemaking on his shelf and realized I had no idea how a shoe is made. I couldn't leave that alone. Thanks to Germany's dual vocational training system, the "Duales Ausbildungssystem", I started an apprenticeship in Neumünster in 2012. My teacher was Hans-Joachim Vauk, a master shoemaker trained at Bally in Switzerland, who had run his workshop for over 40 years.

In 2014, I finished my "Gesellenstück", the journeyman's piece, at the top of my class. It's a pair of shoes made in a single week, a job that usually takes up to four. During the first year of my PhD, I saw a window closing. The master's exam needs five certified master shoemakers as examiners, and as the craft shrinks, such panels get rare. So for six months I spent every weekend at the master's class in Berlin and finished the technical exam and my "Meisterstück", the master's piece at the top of this page. I completed the last two modules, pedagogy and business management, after my PhD.

I always knew I wanted to go to university one day. The choice of physics came at the workbench, listening every afternoon to "Forschung aktuell" on Deutschlandfunk while cutting and stitching leather, and reading the *Physik Journal*. Years later, I got to [write one of its cover stories](/research/#physik-journal) myself. The craft taught me that skill is practice piled up until you no longer see it. Holding something that didn't exist before, a cleanly skived edge or a heel built up layer by layer, feels just like closing a proof or giving a good talk.

Two hearts still beat in my chest, one for science and one for the craft. They keep each other in balance. After long weeks at the desk, the workbench clears my head. After time in the workshop, I'm ready for science again. The only difference is that the workshop can wait. The atmosphere can't.


<style>
.shoe-gallery {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 10px;
  max-width: 600px;
  margin-top: 1.5em;
}
@media (max-width: 600px) {
  .shoe-gallery { grid-template-columns: repeat(2, 1fr); }
}
.shoe-gallery .thumb {
  aspect-ratio: 1 / 1;
  overflow: hidden;
  cursor: pointer;
  border: 2px solid #ddd;
  border-radius: 4px;
  transition: border-color 0.2s;
}
.shoe-gallery .thumb:hover {
  border-color: #888;
}
.shoe-gallery .thumb img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  display: block;
}
#lightbox {
  display: none;
  position: fixed;
  top: 0; left: 0;
  width: 100%; height: 100%;
  background: rgba(0,0,0,0.88);
  z-index: 9999;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  padding: 2em;
  box-sizing: border-box;
}
#lightbox.active {
  display: flex;
}
#lightbox img {
  max-width: 80%;
  max-height: 70vh;
  border-radius: 4px;
  box-shadow: 0 4px 30px rgba(0,0,0,0.5);
}
#lightbox-caption {
  color: #fff;
  font-style: italic;
  margin-top: 1em;
  font-size: 0.95em;
  text-align: center;
  max-width: 600px;
}
#lightbox-close {
  position: absolute;
  top: 1em; right: 1.5em;
  color: white;
  font-size: 2em;
  cursor: pointer;
  line-height: 1;
}
#lightbox-prev, #lightbox-next {
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  color: white;
  font-size: 2.5em;
  cursor: pointer;
  user-select: none;
  padding: 0.2em 0.4em;
  background: rgba(255,255,255,0.1);
  border-radius: 4px;
  transition: background 0.2s;
}
#lightbox-prev:hover, #lightbox-next:hover {
  background: rgba(255,255,255,0.25);
}
#lightbox-prev { left: 1em; }
#lightbox-next { right: 1em; }
#lightbox-counter {
  position: absolute;
  bottom: 1em;
  color: rgba(255,255,255,0.5);
  font-size: 0.85em;
}
</style>

<div class="shoe-gallery">
  <!-- Finished shoes: black and dark -->
  <div class="thumb"><img src="/assets/images/shoemaking/shoe2.jpeg"  data-caption=""></div>
  <div class="thumb"><img src="/assets/images/shoemaking/shoe3.jpeg"  data-caption=""></div>
  <div class="thumb"><img src="/assets/images/shoemaking/shoe4.jpeg"  data-caption=""></div>
  <div class="thumb"><img src="/assets/images/shoemaking/shoe13.jpeg" data-caption=""></div>
  <!-- Golden background, dark to light -->
  <div class="thumb"><img src="/assets/images/shoemaking/shoe17.jpeg" data-caption=""></div>
  <div class="thumb"><img src="/assets/images/shoemaking/shoe16.jpeg" data-caption=""></div>
  <div class="thumb"><img src="/assets/images/shoemaking/shoe15.jpeg" data-caption=""></div>
  <div class="thumb"><img src="/assets/images/shoemaking/shoe14.jpeg" data-caption=""></div>
  <!-- Light brown wingtip series -->
  <div class="thumb"><img src="/assets/images/shoemaking/shoe5.jpeg"  data-caption=""></div>
  <div class="thumb"><img src="/assets/images/shoemaking/shoe6.jpeg"  data-caption=""></div>
  <div class="thumb"><img src="/assets/images/shoemaking/shoe7.jpeg"  data-caption=""></div>
  <div class="thumb"><img src="/assets/images/shoemaking/shoe8.jpeg"  data-caption=""></div>
  <!-- Boots -->
  <div class="thumb"><img src="/assets/images/shoemaking/shoe9.jpeg"  data-caption=""></div>
  <div class="thumb"><img src="/assets/images/shoemaking/shoe10.jpeg" data-caption=""></div>
  <div class="thumb"><img src="/assets/images/shoemaking/shoe11.jpeg" data-caption=""></div>
  <div class="thumb"><img src="/assets/images/shoemaking/shoe12.jpeg" data-caption=""></div>
  <!-- Workshop in black and white -->
  <div class="thumb"><img src="/assets/images/shoemaking/shoe32.jpeg" data-caption=""></div>
  <div class="thumb"><img src="/assets/images/shoemaking/shoe34.jpeg" data-caption=""></div>
  <div class="thumb"><img src="/assets/images/shoemaking/shoe21.jpeg" data-caption=""></div>
  <div class="thumb"><img src="/assets/images/shoemaking/shoe22.jpeg" data-caption=""></div>
  <!-- From foot to last -->
  <div class="thumb"><img src="/assets/images/shoemaking/shoe19.jpeg" data-caption=""></div>
  <div class="thumb"><img src="/assets/images/shoemaking/shoe20.jpeg" data-caption=""></div>
  <div class="thumb"><img src="/assets/images/shoemaking/shoe23.jpeg" data-caption=""></div>
  <div class="thumb"><img src="/assets/images/shoemaking/shoe24.jpeg" data-caption=""></div>
  <!-- Lasts and materials -->
  <div class="thumb"><img src="/assets/images/shoemaking/shoe25.jpeg" data-caption=""></div>
  <div class="thumb"><img src="/assets/images/shoemaking/shoe26.jpeg" data-caption=""></div>
  <div class="thumb"><img src="/assets/images/shoemaking/shoe33.jpeg" data-caption=""></div>
  <div class="thumb"><img src="/assets/images/shoemaking/shoe35.jpeg" data-caption=""></div>
  <!-- Machines -->
  <div class="thumb"><img src="/assets/images/shoemaking/shoe27.jpeg" data-caption=""></div>
  <div class="thumb"><img src="/assets/images/shoemaking/shoe28.jpeg" data-caption=""></div>
  <div class="thumb"><img src="/assets/images/shoemaking/shoe29.jpeg" data-caption=""></div>
  <div class="thumb"><img src="/assets/images/shoemaking/shoe30.jpeg" data-caption=""></div>
  <!-- Making the shoe -->
  <div class="thumb"><img src="/assets/images/shoemaking/shoe31.jpeg" data-caption=""></div>
  <div class="thumb"><img src="/assets/images/shoemaking/shoe36.jpeg" data-caption=""></div>
  <div class="thumb"><img src="/assets/images/shoemaking/shoe37.jpeg" data-caption=""></div>
  <div class="thumb"><img src="/assets/images/shoemaking/shoe38.jpeg" data-caption=""></div>
  <!-- The finish -->
  <div class="thumb"><img src="/assets/images/shoemaking/shoe39.jpeg" data-caption=""></div>
  <div class="thumb"><img src="/assets/images/shoemaking/shoe40.jpeg" data-caption=""></div>
  <div class="thumb"><img src="/assets/images/shoemaking/shoe18.jpeg" data-caption=""></div>
  <div class="thumb"><img src="/assets/images/shoemaking/shoe41.jpeg" data-caption=""></div>
</div>

<div id="lightbox" onclick="closeBox(event)">
  <span id="lightbox-close" onclick="closeBox()">&times;</span>
  <span id="lightbox-prev" onclick="navigate(event, -1)">&#8592;</span>
  <img id="lightbox-img" src="" alt="">
  <span id="lightbox-next" onclick="navigate(event, 1)">&#8594;</span>
  <div id="lightbox-caption"></div>
  <div id="lightbox-counter"></div>
</div>

<script>
var currentIndex = 0;
var thumbs = document.querySelectorAll('.shoe-gallery .thumb img');
var total = thumbs.length;

document.querySelectorAll('.shoe-gallery .thumb').forEach(function(el, i) {
  el.addEventListener('click', function() { openBox(i); });
});

function openBox(index) {
  currentIndex = index;
  showImage();
  document.getElementById('lightbox').classList.add('active');
}

function showImage() {
  var img = thumbs[currentIndex];
  document.getElementById('lightbox-img').src = img.src;
  document.getElementById('lightbox-caption').textContent = img.getAttribute('data-caption');
  document.getElementById('lightbox-counter').textContent = (currentIndex + 1) + ' / ' + total;
}

function navigate(e, dir) {
  e.stopPropagation();
  currentIndex = (currentIndex + dir + total) % total;
  showImage();
}

function closeBox(e) {
  if (!e || e.target === document.getElementById('lightbox') || e.target.id === 'lightbox-close') {
    document.getElementById('lightbox').classList.remove('active');
  }
}

document.addEventListener('keydown', function(e) {
  if (!document.getElementById('lightbox').classList.contains('active')) return;
  if (e.key === 'Escape') closeBox();
  if (e.key === 'ArrowRight') navigate(e, 1);
  if (e.key === 'ArrowLeft')  navigate(e, -1);
});
</script>