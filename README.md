# X-ray Data Analysis Workshop at Tuebingen

This repository contains the source files for the "X-ray Data Analysis Workshop at Tuebingen" training material. The content is rendered as a Jupyter Book so participants and interested researchers can work through tutorials, scripts, and references online.

## Visit the Website

The final website will be available shortly at https://tuoyl.github.io/data-analysis-at-Tuebingen/. Once published, all workshop material—including agendas, tutorials, and walkthrough notebooks—can be accessed there from any browser.

If you want to preview the site locally before it goes live:

1. Install the dependencies from `requirements.txt`
   ```bash
   pip install -r requirements.txt
   ```
2. Build the Jupyter Book
   ```bash
   jupyter-book build .
   ```
3. Open `_build/html/index.html` in your browser to explore the rendered site.

## Workshop Introduction

### Welcome to the X-ray data analysis workshop at Tuebingen
*By Menglei Zhou and Honghui Liu*

In November 2025, the Institute for Astronomy and Astrophysics at Eberhard Karls University of Tübingen launched the X-ray Data Analysis Workshop. The workshop is designed to provide hands-on training in the reduction and analysis of X-ray data from major space missions, while fostering collaboration and knowledge exchange among students and researchers in high-energy astrophysics.

### What?

The goal of this workshop is to provide instruction on data reduction and analysis for data from X-ray missions, including NuSTAR, NICER, IXPE, Insight-HXMT, XMM-Newton, Chandra, XRISM. It will also contain lectures about X-ray spectral fitting, timing techniques and polarimetry. No prior experience is required. The workshop will start from the ground level and is relevant for anyone interested in skills of X-ray data reduction and analysis. 

### When & Where?

The workshop will usually be held **weekly** in the afternoon of **Wednesday from 16:00 to 18:00 at A210**, Sand 1, 72076, Tuebingen, Germany. The agenda is below and will be kept updated.

### Agenda

- 05.11.2025: Walkthrough of NuSTAR data analysis + Basic concepts of spectral fitting (Part I)
    - Lecturers: Menglei Zhou & Honghui Liu
    - Setting up HEASOFT, calibration data base, dealing with NuSTAR data (spectra and lightcurve), data fitting in XSPEC.
- 12.11.2025: Walkthrough of NICER data analysis + Basic concepts of spectral fitting (Part II)
- 19.11.2025: Timing analysis — from light curves to power spectra
- 26.11.2025: Polarization analysis — handling IXPE data

- Next: Pulsar timing
- Next: Introduction to reflection modeling — the relxill family
- Next: Walkthrough of XMM-Newton data analysis
- Next: Walkthrough of Insight-HXMT data analysis
- Next: Bayesian analysis
*Updated on 30 Oct 2025.*

### Contact
Dr. Honghui Liu: honghui.liu@uni-tuebingen.de
Dr. Menglei Zhou: menglei.zhou@astro.uni-tuebingen.de

