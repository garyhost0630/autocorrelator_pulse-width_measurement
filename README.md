# Interferometric Autocorrelator Pulse Width Measurement

This repository provides scripts for processing data obtained from an **interferometric autocorrelator** to estimate the **pulse duration** of ultrafast laser pulses.

The workflow reads the **background measurement** and the **interference autocorrelation data**, processes the signals, and calculates the **pulse width at the corresponding wavelength**.

---

## Overview

An interferometric autocorrelator measures the temporal characteristics of ultrafast laser pulses by recording the interference signal between two delayed replicas of the pulse.

This project provides a simple pipeline to:

1. Load background data  
2. Load interference autocorrelation data  
3. Subtract background  
4. Merge and process the signal  
5. Extract the **pulse width (FWHM)**

---
