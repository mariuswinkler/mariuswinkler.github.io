---
layout: single
title: "Research"
permalink: /research/
---
**Keywords:** Atmospheric Physics, Momentum Analysis, Air-Sea Interaction, Surface Winds, Equatorial Cold Tongue

<figure>
    <img src="/assets/images/Equatorial_Winds.png" alt="Equatorial Surface Wind Pattern">
    <figcaption style="background-color: #f2f2f2; padding: 5px;">Launching radiosondes from BCO on Barbados during the ORECSTRA field campaign 2024. </figcaption>
</figure>

As part of my PhD research, I studied the dynamics of surface winds over the equatorial oceans. The figure above shows zeigt zwei verschiedene Windmuster, die am Äquator vorherschen. Anders, als man intuitiv annehmen würde, überqueren die Winde sehr wohl den Äquator sogar fast rechtwinklig in manchen Bereichen dargestellt durch die grünen eingefärbten Bereiche, die das Meridional Wind Pattern repräsentieren. Auf ihrem Weg zum Äquator, von den höheren Latituden, wo die Passatwinde aus dem absteigenden Ast der Hadley celle entspringen, verändert sich die momentum balance und das, was die oberflächenwinde antreibt: während weiter entfernt vom Äquator noch eine Ekman Balance zwischen Corioliskraft, Druckgradientenkraft und surface friction das momentum budget dominiert, sind es am Äquator die Druckgradientenkraft, surface friction aber auch horizontaler und vertikaler Momentumtransport. Dank der hohen Auflösung des sturmauflösenden Klimamodels at kilometer scale ICON, können wir die kleinen Beiträge auflösen und ihren Beitrag zum äquatorialen Wind momentum balance aufdecken.

<figure>
    <img src="/assets/images/overturning.png" alt="Small scale triggers overturning circulation">
    <figcaption style="background-color: #f2f2f2; padding: 5px;">Launching radiosondes from BCO on Barbados during the ORECSTRA field campaign 2024. </figcaption>
</figure>

From the study at the top of this page haben wir gelernt, wie wichtig die Druckgradientenkraft ist, die maßgeblich durch die underlying sea surface temperature geformt wird. In einer atmosphere-only ICON Simulation habe ich festgestellt, dass trotz idealer sea surface temperature verteilung, die äquatorialen oberflächenwinde im monatsmittel etwa halb so stark sind wie zum Beispiel in ERA5, was ich als Referenz herangezogen habe. Das ist erst einmal überraschend, da ich im obigen Projekt unter anderem gezeigt habe, dass man à la [Lindzen&Nigam, 1987](https://journals.ametsoc.org/view/journals/atsc/44/17/1520-0469_1987_044_2418_otross_2_0_co_2.xml) sehr gut, die oberflächenwinde von lediglich der sea surface temperature annähern kann. Durch den Vergleich von ICON mit dem stand alone COARE algorithm, der auf den Beobachtungsdaten der TOGA-COARE field campaign der early 90's beruht, lernen wir, dass währned ICON den momentum exchange einigermaßen gut simuliert, es viel zu wenig heat exchange zulässt. Durch eine Sensitivitätsstudie zeige ich, wie sensible die freien troposphären winde auf eine änderung des heat exchanges an der air-sea interface reagiert. Kleine Änderungen im heat exchange an der Oberfläche, resultiert in einer more enhanced deep convection, die eine overtruning circulation in gang setzt, die wiederum die öberflächenwinde antreibt. 

<figure>
    <img src="/assets/images/BCO_Action.png" alt="BCO action">
    <figcaption style="background-color: #f2f2f2; padding: 5px;">Launching radiosondes from BCO on Barbados during the ORECSTRA field campaign 2024. </figcaption>
</figure>



The factors contributing to the formation and persistence of surface winds are as varied as they are complex. By employing a momentum analysis, I uncovered the driving forces that maintain these winds. This approach provided me with insights into the essential components of the "wind recipe". I am not doing this just for one specific ocean; rather, I am considering all equatorial ocean basins, each subject to fundamentally different dynamics. We learn that the pressure gradient force is crucial for surface winds. Other significant drivers are surface friction, horizontal advection, and vertical momentum transport, which interact in a balanced manner.

At the equator over the ocean, there is another intriguing phenomenon triggered by the east-west winds, known as "equatorial upwelling". The cause of this equatorial upwelling is rooted in the Coriolis force, which has different signs in the northern and southern hemispheres. Equatorial upwelling is characterized by the uplift of cold water masses from the ocean depths to the surface, where they interact with the overlying warm atmosphere. This leads to substantial temperature differences, generating pressure gradients that, in turn, drive winds.

We now understand that surface pressure gradients are key for surface winds. However, what determines surface pressure gradients ? As early as the late 1980s, scientists successfully tackled this question (see [Lindzen&Nigam, 1987](https://journals.ametsoc.org/view/journals/atsc/44/17/1520-0469_1987_044_2418_otross_2_0_co_2.xml)) and linked surface pressure to sea surface temperature. The transition from surface pressure to surface wind, however, is considerably more difficult, and the lack of resolving the small scale processes has so far prevented us from shedding complete light on that matter.

Here at the Max Planck Institute in Hamburg, in collaboration with numerous partners such as the [Deutschen Klimarechenzentrum](https://www.dkrz.de/de/dkrz-partner-der-klimaforschung), we are developing a high-resolution climate model called "ICON" (see [NextGEMS](https://nextgems-h2020.eu/)). This is precisely what we need: a high-resolution, atmosphere-ocean coupled climate model.

With the output generated by ICON, I am directing my focus toward equatorial surface winds, striving to contribute to the understanding of atmosphere-ocean interaction.

**Supervisors:** [Prof. Dr. Bjorn Stevens](https://mpimet.mpg.de/institut/mitarbeiterinnen/mitarbeiterdetail?tx_mitarbeiterverwaltung_mitarbeiterliste%5Baction%5D=show&tx_mitarbeiterverwaltung_mitarbeiterliste%5Bcontroller%5D=Mitarbeiter&tx_mitarbeiterverwaltung_mitarbeiterliste%5Bmitarbeiter%5D=11&cHash=6b76dcfaee5961642aba4f38def0c875) (MPI-M), [Prof. Dr. Juan Pedro Mellado González](https://jpmellado.github.io/) (UHH)
