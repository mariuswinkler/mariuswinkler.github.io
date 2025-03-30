---
layout: single
title: "Research"
permalink: /research/
---
<div style="text-align: center; margin-bottom: 1em;">
  <span style="font-size: 0.9em; font-style: italic; color: #555;">
    Keywords: Atmospheric Physics, Momentum Analysis, Air–Sea Interaction, Surface Winds, Equatorial Cold Tongue
  </span>
</div>

<figure>
    <img src="/assets/images/Equatorial_Winds.png" alt="Equatorial Surface Wind Pattern">
    <figcaption style="background-color: #f2f2f2; padding: 5px;"> Wind Patterns along the Equator. At the top, region of interest. At the bottom, daily mean wind patterns averaged meridionally between -2° and 2° latitude, including land areas, based on a two-year ICON simulation. The Meridional Wind Pattern is shown in green, while the Zonal Wind Pattern is displayed in pink, with white indicating the transition between the two regimes. </figcaption>
</figure>

<section>
  <p>
    As part of my PhD research, I studied the dynamics of surface winds over the equatorial oceans.
    The figure above shows two distinct wind patterns that prevail near the equator.
    Contrary to intuitive expectations, the winds cross the equator at nearly right angles in some regions,
    as indicated by the green-shaded areas representing the meridional wind component.
  </p>

  <p>
    On their journey toward the equator—originating from the higher latitudes where the trade winds descend
    from the Hadley cell—the momentum balance governing these winds undergoes a shift.
    Farther from the equator, an Ekman balance between the Coriolis force, pressure gradient force, and surface
    friction dominates. Closer to the equator, however, the Coriolis force vanishes, and the balance is instead
    shaped by the pressure gradient force, surface friction, and both horizontal and vertical momentum transport.
  </p>

  <p>
    With the high resolution of the ICON storm-resolving climate model—operating at kilometer scale—we can capture
    these subtle contributions and quantify their role in shaping the equatorial surface wind momentum budget.
  </p>
</section>


<figure>
    <img src="/assets/images/overturning.png" alt="Small scale triggers overturning circulation">
    <figcaption style="background-color: #f2f2f2; padding: 5px;">Surface Heat Flux Revives the Surface Pressure: An Example. Surface heat exchange (small, curly arrows, lower left) triggers convection, shifting the vertical temperature profile (red) toward higher temperatures and lowering the surface pressure ("L"). Gravity waves (black, curly arrows) redistribute mass and energy across the free troposphere, altering temperature profiles (blue) over non-convective areas and reinforcing higher surface pressure ("H") over already cold regions. This process ultimately supports stronger surface winds by enhancing the circulation pattern (blue arrows circularly arranged). </figcaption>
</figure>

<section>
  <p>
    From the study at the top of this page, we learned how important the pressure gradient force is — a force largely shaped by the underlying sea surface temperature (SST).
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
    By comparing ICON to the standalone COARE algorithm, which is based on observational data from the TOGA-COARE field campaign in the early 1990s, we find that while ICON reasonably simulates the momentum exchange, it permits far too little heat exchange.
  </p>

  <p>
    Through a sensitivity study, I show how strongly free-tropospheric winds respond to changes in heat exchange at the air-sea interface. Even small changes in surface heat fluxes can lead to enhanced deep convection, which initiates an overturning circulation which ultimately drives the surface winds.
  </p>
</section>

<figure>
    <img src="/assets/images/BCO_Action.png" alt="BCO action">
    <figcaption style="background-color: #f2f2f2; padding: 5px;">Launching radiosondes during the ORCESTRA field campaign 2024 shown here during a BCO outreach event with local students (left) at the <a href="https://barbados.mpimet.mpg.de/" target="_blank">Barbados Cloud Observatory</a> at Deebles Point (right). </figcaption>
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
    BCO (Barbados), INMG (Sal, Cape Verde), and the R/V Meteor. The dataset is already complete — I’m currently
    writing the paper!
  </p>
</section>
