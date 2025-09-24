**Wavelet Power and Coherence in R**

This repository contains R code for analyzing wavelet power spectra and wavelet coherence in time series data. The scripts are designed for research applications where both within-subject (power) and between-subject (coherence) analyses are of interest.

**Features:**
+ **Wavelet Power Analysis**
  + Computes the wavelet power spectrum for each subject.
  + Generates and saves plots of power spectra.
  + Example power spectrum:
<img width="360" height="360" alt="example_wavelet" src="https://github.com/user-attachments/assets/faabde43-f941-412d-95ad-e132252a8311" />

+ **Wavelet Coherence (WTC)**
  + Calculates wavelet coherence across a range of frequencies for dyads.
  + Includes both:
  + True pairings (actual dyads).
  + Random pairings (control comparisons across participants).
  + Supports extraction of mean coherence values across specified frequency bands.
+ **Cluster-Based Approach**
  + Implements a cluster-based statistical method to identify significant regions of coherence.
  + Provides a way to control for multiple comparisons across time–frequency space.
+ **Time Series Coherence Extraction**
  + Extracts coherence and phase lag as a function of time within frequency bands of interest.
  + Enables time series analysis of coherence (e.g., trajectory plotting, synchrony dynamics).
