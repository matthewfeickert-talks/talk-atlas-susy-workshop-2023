class: middle, center, title-slide
count: false

# LHC Reinterpretation Forum<br>2023 Summary
.large.blue[Matthew Feickert]<br>
.large[(University of Wisconsin-Madison)]
<br>
[matthew.feickert@cern.ch](mailto:matthew.feickert@cern.ch)
<br>

[ATLAS SUSY Workshop 2023](https://indico.cern.ch/event/1274064/timetable/#44-reinterpretation-forum-summ)

September 12th, 2023

---
# Talk notes

* ATLAS Summary of the 2023 (Re)interpretation of the LHC results for new physics
* Talk time: 20 minutes
   - talk: 15 minutes
   - questions: 5 minutes

---
# My motivations on this topic

.kol-1-2[
.large[
* Postdoc in high energy physics and data science at University of Wisconsin-Madison Data Science Institute
* Analysis Systems area lead for IRIS-HEP
* Member of ATLAS collaboration
   - Happy collaborator of TUM ATLAS group!
* Administrator of Scikit-HEP community organization
* Care about .bold[reusable] open science to be able to push physics forward at the .bold[community scale]
]
]
.kol-1-2[
.center.width-65[[![logo_IRIS-HEP](assets/logos/logo_institution.png)](https://datascience.wisc.edu/institute/)]

.center.width-30[[![logo_IRIS-HEP](assets/logos/logo_IRIS-HEP.png)](https://iris-hep.org/)]

.center.width-40[[![logo_ATLAS](assets/logos/logo_ATLAS.png)](https://atlas.cern/)]

.center.width-30[[![logo_ATLAS](figures/scikit-hep-logo.svg)](https://scikit-hep.org/)]
]

---
# Summary

.huge[
* Whirlwind tour of lifting analysis code from version control, to packages, distributed binaries, and the rest of the world
* Not a hopeless bog of technical debt, but community infrastructure built by people who you can collaborate with
* Reusable code can be a nucleation point for communities
]

.kol-1-4[
<p style="text-align:center;">
   <a href="https://github.com/">
      <img src="figures/github-mark.svg"; width=95%>
   </a>
</p>
]
.kol-1-4[
<p style="text-align:center;">
   <a href="https://pypi.org/">
      <img src="figures/pypi-logo.svg"; width=95%>
   </a>
</p>
]
.kol-1-4[
<br>
<p style="text-align:center;">
   <a href="https://conda-forge.org/">
      <img src="figures/conda-forge-anvil.png"; width=95%>
   </a>
</p>
]
.kol-1-4[
<p style="text-align:center;">
   <a href="https://paperswithcode.com/">
      <img src="figures/papers-with-code.png"; width=95%>
   </a>
</p>
]

---
# References

1. [Level Up Your Python](https://henryiii.github.io/level-up-your-python/), Henry Schreiner
2. [Python Packaging User Guide, Packaging Python Projects Tutorial](https://packaging.python.org/en/latest/tutorials/packaging-projects/), The PyPA
3. [Scientific Python Library Development Guide](https://learn.scientific-python.org/development/), Scientific Python (originally made by Scikit-HEP)
4. [`cookie`](https://github.com/scientific-python/cookie), Scientific Python (originally made by Scikit-HEP)
5. [INTERSECT's packaging tutorial](https://intersect-training.org/packaging/), INTERSECT

---
class: end-slide, center

Backup

---
# Zenodo: DOI minting made easy

- Everything on Zenodo has a DOI
   - Provides both a .bold[project] DOI (resolves to latest) and .bold[version specific] DOI
- Enable it to [automatically preserve work from GitHub](https://guides.github.com/activities/citable-code/) (can also directly upload, but lose out on automation)
   - Benefit from having a DOI for .bold[every version] regardless of software paper landscape state
- Once you have a DOI, put it .bold[everywhere] (again)
   - Recommend sharing the project DOI and letting users select a specific version if they want it

.center[
.width-80[[![Zenodo_DOI_guide](figures/Zenodo_DOI_guide.png)](https://zenodo.org/account/settings/github/)]
]

---
# Julia ecosystem for easier CUDA

.huge[
Julia's packaging system seems to be working, as using [CUDA libraries in Julia](https://juliagpu.org/) is rather simple.
]

---

class: end-slide, center
count: false

The end.
