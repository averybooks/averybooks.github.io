---
layout: page
title: "Radio Astronomy"
permalink: /research/radio-astronomy/
header: no
---

### Abstract
This page contains 3 lab reports from the UC Berkeley Undergraduate Radio Lab course. Topics and goals include interferometry and radio frequency mapping. The primary objectives of these projects were to develop practical scientific experiemntal skills and developing the ability to produce conclusions that have sound reasoning such that we can be confident in our outcomes. Code can be found here https://github.com/averybooks/radiolab2026-Cal . For this lab, I wrote a python package called 'rafpy' that contains radio frequency analysis functions. Note that not all functions within the package are generally helpful, the package was designed with the course requirements and needs in mind. 

<hr>

#### Full Reports
<div class="row" style="margin-bottom: 50px; border-bottom: 1px solid #eee; padding-bottom: 40px;">
  <div class="medium-4 columns">
    <img src="{{ '/assets/img/nps_velocity_final.png' | relative_url }}" alt="Pulsar Timing" style="border-radius: 4px;">
  </div>
  <div class="medium-8 columns">
    <h3>The Kinematic, Mass, and Temperature Characterization of the North Polar Spur</h3>
    <p>We present a 21-cm neutral hydrogen survey of the North Polar Spur (NPS)
supershell conducted with the 4.5-m Leuschner radio telescope, covering Galac
tic longitudes ℓ = 210◦–20◦ and latitudes b = 0◦–90◦ across 1170 pointings col
lected over two observing sessions. Frequency switching and cross calibration
against the Leiden-Argentine-Bonn (LAB) HI Survey yield a system tempera
ture of Tsys = 43 ± 6 K. The calibrated brightness temperature map reveals a
prominent HI arc peaking at Tb ≈ 31.5 K near (ℓ,b) ≈ (350◦,30◦), consistent
with the known NPS ridge. LSR velocity centroids across the survey span −45.3
to +61.0 km s−1, with a systematic redshift to blueshift gradient consistent with
an expanding shell geometry. Applying the Berkhuijsen et al. (1971) geometric
shell boundary with a 2σ brightness threshold, we isolate 209 shell associated
pointings and derive a shell HI mass of Mshell = 9,124 ± 2,741 M⊙ at an as
sumed distance of 140 pc, consistent with prior estimates when distance and
shell-definition differences are accounted for.</p>
    <a href="{{ '/assets/pdfs/Astron_121_Lab_4_Report_Final_Avery_Books.pdf' | relative_url }}" target="_blank" class="button small secondary">View Report</a>
  </div>
</div>

<div class="row" style="margin-bottom: 50px; border-bottom: 1px solid #eee; padding-bottom: 40px;">
  <div class="medium-4 columns">
    <img src="{{ '/assets/img/baseline_chisq.png' | relative_url }}" alt="Pulsar Timing" style="border-radius: 4px;">
  </div>
  <div class="medium-8 columns">
    <h3>Solar Diameter Measurement with Interferometry</h3>
    <p>This paper details the calibration and application of a two-element X-band
(10.5 GHz) radio interferometer to measure the angular diameter of the Sun. By
tracking the solar transit over a 12-hour period, we extracted the characteristic broadband interference fringes and utilized a non-linear least-squares optimization to precisely calibrate the instrumental baseline (b_ew, b_ns) and cable delays.Applying a 1-D uniform disk approximation and Fourier bandpass filtering to the
visibility data, we isolated the fringe modulator to identify the spatial frequency
of the first zero-crossing. We derived a solar angular diameter of 31 arcminutes,
close to the accepted value of 32 arcminutes with a highly accurate 3.125% error.
Remaining discrepancies are analyzed in the context of solar limb darkening and bandwidth smearing. These results successfully validate both the robust hard-
ware calibration of the New Campbell Hall array and the foundational theoretical framework of aperture synthesis.</p>
    <a href="{{ '/assets/pdfs/Radio Astronomy (Astro 121) Lab Report 3.pdf' | relative_url }}" target="_blank" class="button small secondary">View Report</a>
  </div>
</div>

<div class="row" style="margin-bottom: 50px; border-bottom: 1px solid #eee; padding-bottom: 40px;">
  <div class="medium-4 columns">
    <img src="{{ '/assets/img/Power Spectra Cygnus X 2MHz w LSR Table.png' | relative_url }}" alt="Hydrogen Line" style="border-radius: 4px;">
  </div>
  <div class="medium-8 columns">
    <h3>Hydrogen 21cm Line Observation</h3>
    <p>The hyperfine transition of neutral hydrogen (HI line) is a primary tool for
looking through interstellar dust and characterizing galactic structures. It is
critical to determine information such as the thermal and kinematic properties
of the Interstellar Medium in the Milky Way Galaxy and the structures within.
The main objective of this paper is to characterize thermal and Doppler velocity
properties of Hydrogen in the Cygnus X and the line of sight local arm while
looking at Cygnus X. We utilized a radio telescope capable of detecting the
1420.4 MHz emission line to obtain power spectra data. With this data we
used gaussian fitting to decompose the multi-peak spectra and statistical analysis
to determine Doppler and temperature quantities. We were able to determine
the LSR corrected velocity of the main parcel of gas to be 12.75 km/s and to
determine the readings are made of 4 distinct parcels of gas each experiencing
different parameters. Our best constrained upper limit temperature measurement
is Tupper = 3984 ± 706 K, which still has an error of ≈ 17% which is poorly
constrained..  </p>
    <a href="{{ '/assets/pdfs/Radio Astronomy (Astro 121) Lab Report 2.pdf' | relative_url }}" target="_blank" class="button small secondary">View Report</a>
  </div>
</div>