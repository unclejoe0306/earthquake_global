# Global Seismic Fractal Analysis War Room PRO

[![DOI](https://zenodo.org/badge/DOI/18284864.svg)](https://doi.org/10.5281/zenodo.18284864)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20Web-green)](https://github.com/)

**Version:** 4.2.5
**Author:** Yu-Ching Chou

## 🌍 Overview

**Global Seismic Fractal Analysis War Room PRO** is a real-time seismic monitoring system capable of detecting precursor anomalies using non-linear dynamics and statistical physics.

Unlike traditional magnitude-based alerts, this system utilizes a multi-parameter fractal analysis engine to monitor the entropy and clustering behaviors of seismic events across global tectonic zones.

### 🚀 Try it Live
[**Click here to launch the Web App**](https://unclejoe0306.github.io/earthquake_global/)

---

## ✨ Key Features (v4.2.5)

* **Real-time Visualization:** High-performance 3D globe rendering (WebGL) of USGS seismic data.
* **5-Parameter Fractal Engine:**
    * **b-value:** Gutenberg-Richter scaling.
    * **Dt:** Temporal Fractal Dimension.
    * **D₀:** Capacity Dimension (Spatial clustering).
    * **H:** Hurst Exponent (Time-series memory).
    * **Δα:** Multifractal Spectrum Width (Complexity).
* **🛡️ Sync Guard Mechanism (New in v4.2.5):** A novel algorithm that detects "Sync Lock" (pre-quake coherence) and "Sync Release" phases by analyzing the derivative trends of fractal parameters.
* **Z-Score Anomaly Detection:** Statistical alerts based on a 150-day floating baseline distribution.
* **Multi-Zone Monitoring:** Dedicated analysis for Global, Ryukyu/Taiwan, Japan/Kuril, Indo-Sunda, and Americas subduction zones.

## 📝 Changelog
## 🚀 What's New in v4.2.5
* **Algorithm:** Optimized the Sync Guard sensitivity.
* **UI:** Fixed layout issues on smaller Android devices.
* **Performance:** Improved WebGL rendering speed.

## 📱 Installation (Android)

You can download the latest Android APK from the **[Releases Page](../../releases)**.

1.  Download the `.apk` file.
2.  Allow installation from unknown sources in your Android settings.
3.  Launch the app (Internet connection required).

## 📊 Methodology

This software implements a sliding window approach (3-day & 7-day) to compute fractal dimensions. Anomalies are flagged when parameters deviate significantly ($|Z| > 1.5$) from the background noise level.

## ☕ Support 

This is an independent research project. If you find it useful, consider supporting its development.
1. BuyMeACoffee https://buymeacoffee.com/unclejoe038
2. USDT/ETH/BTC BNB Smart Chain (BEP-20) address: 0xf7c4806d5ea6d965f8eb3158416bce88f9d261d8

## ⚠️ Disclaimer 

This software is for scientific research and educational purposes only. It is not an official early warning system. Do not use it for life-safety decisions.

Copyright © 2026 Yu-Ching Chou. Licensed under the MIT License.

## 📖 Citation

If you use this software in your research, please cite it as follows:

**APA Format:**
> Chou, Y.-C. (2026). Global Seismic Fractal Analysis War Room PRO (Version 4.2.5) [Software]. Zenodo. https://doi.org/10.5281/zenodo.18284864

**BibTeX:**
```bibtex
@software{chou2026global,
  author       = {Chou, Yu-Ching},
  title        = {Global Seismic Fractal Analysis War Room PRO},
  version      = {4.2.5},
  year         = {2026},
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.18284864},
  url          = {[https://doi.org/10.5281/zenodo.18284864](https://doi.org/10.5281/zenodo.18284864)}
}

