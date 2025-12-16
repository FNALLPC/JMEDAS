# Jet CMSDAS Exercise Repository — DAS January 2026
This repository contains code used for several years of the CMS Data Analysis School (CMSDAS). Each CMSDAS school corresponds to a dedicated branch that reflects the tools, 
workflows, and best practices used in that particular year. ---
## For students
If you want to follow the **CMSDAS short jet exercise for January 2026**, please refer to the official CMSDAS jet exercise website and the instructions provided during the school: 
http://cms-jet.github.io/JMEDAS/ The **January 2026** version of the school uses the branch: ``` DASJan2026 ``` You can clone the repository with: ``` git clone 
git@github.com:cms-jet/JMEDAS.git -b DASJan2026 ``` This branch contains all the material needed to run the jet exercises as presented during CMSDAS January 2026. ---
## For contributors
The `master` branch contains code accumulated over many CMSDAS schools across multiple years. As a result, parts of the code may be obsolete or rely on tools and workflows that are 
no longer recommended by CMS. When contributing, please make sure to target the appropriate DAS-specific branch (e.g. `DASJan2026`) rather than `master`, unless you are performing 
broad maintenance or archival updates. ---
### To update the website
The CMSDAS Jet Exercise website is built using the [Carpentries software](https://github.com/carpentries/styles/). To update the website content: - Use the `gh-pages` branch - Follow 
the Carpentries style guidelines and contribution recommendations ---
### To update the exercises
The **January 2026 exercises** are based on modern CMS analysis tools, including: - **NanoAOD** - **Jupyter notebooks** - **Python-based workflows** - **coffea** The latest exercises 
for DAS January 2026 are located under: ``` notebooks/master/ ``` Older or deprecated notebooks from previous CMSDAS schools are archived under: ``` notebooks/obsolete/ ``` The 
directories: - `interface/` - `plugins/` - `scripts/` - `src/` contain legacy CMSSW-based code (typically using miniAOD). These components are **no longer used** in the January 2026 
exercises and are kept only for documentation and historical reference. ---
## CMSDAS Jet Short Exercise — January 2026
### Introduction
This tutorial is intended to provide the foundational knowledge required to work with jets in a CMS physics analysis. Topics covered include: - What jets are and how they are defined 
- Jet reconstruction algorithms - Jet energy corrections and uncertainties - Practical jet analysis using NanoAOD and coffea The tutorial is designed to be run on CMS computing 
resources (such as cmslpc) and followed alongside the instructional slides and documentation linked on the **JMEDAS 2026 website**. Participants are encouraged to work through the 
notebooks interactively and use the provided examples as a starting point for their own analyses.
