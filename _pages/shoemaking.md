---
title: ""
layout: single
permalink: /shoemaking/
---

# A Shoemaker's Path into Science

As a child, I spent long summers in my father's workshop, and something about that world, the smell of sawdust, the weight of a well-balanced tool, the quiet satisfaction of a joint that fits, stayed with me long after. When I graduated school, I stumbled across a book about bespoke shoemaking on my father's bookshelf and was immediately confronted with a humbling realisation: I knew almost nothing about leather, and I had no idea how a shoe was made. That gap was exactly the kind of problem I could not leave unsolved. Germany's "Duales Ausbildungssystem", the dual vocational training system, made it possible to pursue that curiosity seriously, and in 2012 I began an apprenticeship in Neumünster under Hans-Joachim Vauk, a Master Shoemaker trained at Bally in Switzerland, who had quietly run his workshop for over 40 years.

I always knew, even then, that I wanted to study at a university one day, as my friends were doing. Shoemaking was not a detour but a fire I needed to walk through first, an urge to work with my hands and understand a craft from its very foundations before sitting down at a desk. Every day at the bench, I listened to *Deutschlandfunk, Forschung aktuell* (Science Today), the German public radio science programme, arriving each afternoon in the middle of cutting and stitching and lasting. It helped me decide that when the time came, it would be physics.

I finished my "Gesellenstück", the journeyman's piece, in 2014 as best of my class, a pair of shoes completed within a single week (which usually takes up to four weeks) to demonstrate quality, speed, and economical working. During the first year of my PhD I recognised a closing window of opportunity: Germany's Master craftsman examination requires five certified Master Shoemakers as examiners, and as the craft quietly contracts, assembling such a panel becomes increasingly rare. For six months I spent every weekend travelling to Berlin to attend the Master's class, completing the technical examination and my "Meisterstück", the master's piece. The two remaining modules, on pedagogy and business management, I finished after my PhD in 2025, and both shaped how I think about supervising people and setting priorities.

Until today, two hearts beat in my chest: one for science, one for the craft. They are not in competition. They are in equilibrium. That equilibrium is what keeps both alive. The craft taught me that skill is not talent but accumulated practice made invisible by time, and it gave me patience, precision, and the humility of standing before something not yet understood. There is a particular satisfaction in holding something in your hands that did not exist before, a cleanly skived edge, a heel built up layer by layer, standing perfectly plumb, and I have come to realise it is the same satisfaction as closing a proof. After long weeks at the desk, I need the workbench to clear the mental disk space. After time in the workshop, I return to science ready to start again. The workshop will always be there. But the atmosphere is changing. And that is where I want to be.

<style>
.shoe-gallery {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin-top: 1.5em;
}
.shoe-gallery .thumb {
  width: 140px;
  height: 140px;
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
  background: rgba(0,0,0,0.85);
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
</style>

<div class="shoe-gallery">
  <div class="thumb" onclick="openBox(this)">
    <img src="/assets/images/shoe1.jpeg" data-caption="The Meisterstück.">
  </div>
  <div class="thumb" onclick="openBox(this)">
    <img src="/assets/images/shoe2.jpeg" data-caption="">
  </div>
  <div class="thumb" onclick="openBox(this)">
    <img src="/assets/images/shoe3.jpeg" data-caption="">
  </div>
  <div class="thumb" onclick="openBox(this)">
    <img src="/assets/images/shoe4.jpeg" data-caption="">
  </div>
</div>

<div id="lightbox" onclick="closeBox(event)">
  <span id="lightbox-close" onclick="closeBox()">&times;</span>
  <img id="lightbox-img" src="" alt="">
  <div id="lightbox-caption"></div>
</div>

<script>
function openBox(el) {
  var img = el.querySelector('img');
  document.getElementById('lightbox-img').src = img.src;
  document.getElementById('lightbox-caption').textContent = img.getAttribute('data-caption');
  document.getElementById('lightbox').classList.add('active');
}
function closeBox(e) {
  if (!e || e.target === document.getElementById('lightbox') || e.target.id === 'lightbox-close') {
    document.getElementById('lightbox').classList.remove('active');
  }
}
document.addEventListener('keydown', function(e) {
  if (e.key === 'Escape') closeBox();
});
</script>