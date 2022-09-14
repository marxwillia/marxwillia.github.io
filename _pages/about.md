---
permalink: /
title: "Understanding the Explosions of Massive Stars: Bridging Theory and Observation"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

My name is Marc Williamson, and I am a Future Investigator in NASA Earth & Space Science & Technology (FINESST) investigator
in the final year of my PhD at New York University studying stripped envelope supernovae. 
In my research, I strive to bridge the gap between theory (radiative transfer modeling to reconstruct stellar explosions)
and observations (leveraging large datasets to make statistical inferences and find unique supernovae). I am the lead 
developer of the [SESNPCA](insert url) code, which provides a physically interpretable, time dependent spectral classification
algorithm for stripped supernovae. In addition, I am a core developer on the open-source radiative transfer code [TARDIS](insert url).

Current Research Directions
======

My current focus is on trying to understand the progenitor stars of stripped supernovae. In particular, I want to know how
these stars lose their outer layers of Hydrogen and Helium, and which explosions are likely to require a binary companion
during pre-supernova evolution. Towards this end, I am actively working on the following projects:

A Potential Detection of Hydrogen in an SN Ic
------

I am leading a paper (Williamson et al 2022 in prep) to be submitted this Fall presenting a new dataset of SN Ic spectra
containing recently discovered supernovae and follow-up observations from the LCO network. This project will increase the
number of pre-maximum SN Ic spectra publicly available by 25%. In addition, I present a detailed analysis and models for 
SN2019ewu, where early spectra (2 weeks before peak) show a P-Cygni feature that can be explained with Hydrogen. 


Emulator-assisted Radiative Transfer Modeling
------

I have helped develop a neural network based emulator for the TARDIS radiative transfer code which speeds up the 
production of models by over 5 orders of magnitude. This massive speed-up allows millions of models to be quickly calculated,
unlocking Bayesian inference for automated model fitting to observed spectra. I am leading a project to apply this technique
to stripped supernovae in order to constrain Helium abundances for a statistical sample of objects.


MESA-->STELLA-->TARDIS: An End-to-End Simulation Pipeline
------

I am currently working on a pipeline so that models of realistic stellar progenitors evolved using MESA and exploded with 
STELLA can be ingested into TARDIS to produce synthetic spectra. I am leading a project to produce synthetic spectra for 
a stripped envelope stellar progenitor evolved as a single and binary system to understand the impact of environment on 
observed spectra.

Outreach
======

For the last 3 years, I have been a Google Summer of Code Mentor and Org Admin for the TARDIS group. As a mentor, I have
had the opportunity to help many students from a diverse background develop tools that are incorporated into the TARDIS
codebase. Many of these students have remained active in the TARDIS organization long after their internships end, some
even becoming mentors themselves for the next generation of interns. 

