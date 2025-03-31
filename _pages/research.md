---
layout: single
title: "Research"
permalink: /research/
---
<div style="text-align: center; margin-bottom: 1em;">
  <span style="font-size: 0.9em; font-style: italic; color: #555;">
    Keywords: Boundary Layer, Surface Winds, Momentum Analysis, Air–Sea Interaction, High Resolution Climate Models, ORCESTRA
  </span>
</div>

<figure>
    <img src="/assets/images/Equatorial_Winds.png" alt="Equatorial Surface Wind Pattern">
    <figcaption style="background-color: #f2f2f2; padding: 5px;"> Wind patterns along the equator. Top: Equatorial region of interest. Bottom: Daily mean wind patterns, meridionally averaged between 2°S and 2°N (including land areas), based on a two-year ICON simulation. Meridional wind components are shown in green, zonal components in pink, with white indicating the transition between the two regimes. </figcaption>
</figure>
<section>
  <p>
    As part of my PhD research, I investigated the dynamics of surface winds over the equatorial oceans.
    The figure above illustrates two distinct wind patterns that prevail near the equator: the Zonal Wind Pattern, which flows parallel to the equator, and the Meridional Wind Pattern, which crosses it.
    Contrary to intuitive expectations, the winds cross the equator at nearly right angles in some regions.
    These areas are highlighted in green, representing the Meridional Wind Pattern.
  </p>

  <p>
    On their journey toward the equator—originating from the higher latitudes where the trade winds descend
    from the Hadley cell—the momentum balance governing these winds undergoes a shift.
    Farther from the equator, an Ekman balance between the Coriolis force, pressure gradient force, and surface
    friction dominates. Closer to the equator, however, the Coriolis force vanishes, and the balance is instead
    shaped by the pressure gradient force, surface friction, and both horizontal and vertical momentum transport.
  </p>

  <p>
    With the high resolution of the storm-resolving climate model ICON which operates at kilometer scale, we can capture
    these subtle contributions and quantify their role in shaping the equatorial surface wind momentum budget.
  </p>
</section>

<figure>
    <img src="/assets/images/overturning.png" alt="Small scale triggers overturning circulation">
    <figcaption style="background-color: #f2f2f2; padding: 5px;">Surface heat flux revives surface pressure: an illustrative example. Surface heat exchange (small curly arrows, lower left) triggers convection, shifting the vertical temperature profile (red) toward higher temperatures and lowering surface pressure ("L"). The free troposphere is assumed to rapidly equilibrate horizontal temperature differences by redistributing mass and energy. This adjustment modifies temperature profiles (blue) over non-convective regions and reinforces higher surface pressure ('H') over cooler areas. This process ultimately strengthens surface winds by enhancing the circulation pattern (blue circular arrows). Visualization: Yvonne Schrader. </figcaption>
</figure>
<section>
  <p>
    From the study at the top of this page, we learned how important the pressure gradient force is, which is largely shaped by the underlying sea surface temperature (SST).
  </p>

  <p>
    In an atmosphere-only ICON simulation, I found that, despite prescribing an ideal SST distribution, the equatorial surface winds were, on monthly average, only about half as strong as those in ERA5, which I used as a reference.
  </p>

  <p>
    This result was surprising at first, since in the earlier project I demonstrated that, following the approach of 
    <a href="https://journals.ametsoc.org/view/journals/atsc/44/17/1520-0469_1987_044_2418_otross_2_0_co_2.xml" target="_blank">Lindzen &amp; Nigam (1987)</a>,
    surface winds can be well approximated by the SST distribution alone.
  </p>

  <p>
    By comparing ICON to the standalone COARE algorithm, which is based on observational data from the <a href="https://journals.ametsoc.org/view/journals/bams/73/9/1520-0477_1992_073_1377_tctcor_2_0_co_2.xml" target="_blank">TOGA-COARE</a> field campaign in the early 1990s, we find that while ICON reasonably simulates the momentum exchange, it permits far too little heat exchange.
  </p>

  <p>
    Through a sensitivity study, I show how strongly free-tropospheric winds respond to changes in heat exchange at the air-sea interface. Even small changes in surface heat fluxes can lead to enhanced deep convection, which initiates an overturning circulation which ultimately drives the surface winds.
  </p>
</section>

<figure>
    <img src="/assets/images/BCO_Action.png" alt="BCO action">
    <figcaption style="background-color: #f2f2f2; padding: 5px;">Launching radiosondes during the ORCESTRA field campaign 2024 shown here during a BCO outreach event with local students (left, credit: Nina Robbins Blanch) at the <a href="https://barbados.mpimet.mpg.de/" target="_blank">Barbados Cloud Observatory</a> at Deebles Point (right). </figcaption>
</figure>

<section>
  <p>
    In 2024, I had the great opportunity to take part in the ORCESTRA field campaign. For four weeks,
    I led the radiosonde mission in Barbados, launching 141 sondes together with a team of 15 young scientists.
  </p>

  <p>
    It was my first time in the tropics, and it was eye-opening to witness just how dynamic cloud and weather
    formation can be. Like bubbles rising in a glass of carbonated water, water vapor ascends, clouds form like
    raised index fingers above the transition layer and just as quickly, they rain down and vanish again.
  </p>

  <p>
    Since returning to Germany, I’ve been post-processing the data from all radiosonde launches conducted at
    BCO (Barbados), INMG (Sal, Cape Verde), and the R/V Meteor. The dataset is already complete. After installing the 
    <a href="https://docs.ipfs.tech/install/ipfs-desktop/#windows" target="_blank">IPFS client</a>, 
    you can run these two lines to access the data:
  </p>

  <div class="code-box-wrapper">
    <button class="copy-btn" onclick="copyCode(this)">Copy</button>
    <div class="code-box">
  <span class="keyword">import</span> xarray <span class="keyword">as</span> xr

  ds = xr.open_dataset(<span class="string">"ipns://latest.orcestra-campaign.org/products/Radiosondes/RS_ORCESTRA_level2.zarr"</span>, engine=<span class="string">"zarr"</span>)
    </div>
  </div>

  <script>
  function copyCode(btn) {
    const code = btn.nextElementSibling;
    const text = code.innerText;
    navigator.clipboard.writeText(text).then(() => {
      btn.textContent = "Copied!";
      setTimeout(() => btn.textContent = "Copy", 1500);
    });
  }
  </script>

  <p>
    Currently I am writing the data paper, which should be published this year.
  </p>



</section>


