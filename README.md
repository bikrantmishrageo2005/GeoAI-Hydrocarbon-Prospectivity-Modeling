# GeoAI-Hydrocarbon-Prospectivity-Modeling


📌 Overview

This project presents an AI-assisted hydrocarbon prospectivity modeling workflow that integrates seismic attributes with machine learning. The aim is to demonstrate how GeoAI techniques can support risk-based interpretation in petroleum exploration, rather than claiming direct hydrocarbon discovery.
The work is designed as an academic and research-oriented mini project, suitable for graduate-level applications and GeoAI portfolios.


🎯 Motivation

Hydrocarbon exploration involves significant uncertainty due to complex subsurface geology and limited direct observations. Seismic data provides indirect information related to lithology and fluid effects, which can be further analyzed using data-driven methods.

This project explores how:

🧠 Seismic attributes act as proxies for subsurface properties

🤖 Machine learning assists in prospect ranking

🪨 Geological reasoning is preserved alongside AI


🗂 Dataset

The workflow is real-data ready and supports:

📡 SEG-Y seismic volumes (e.g., F3 Netherlands Offshore or similar open datasets)

🧪 Physics-inspired synthetic seismic attributes when real data are unavailable

This reflects realistic research scenarios where data availability may be staged.


🔬 Methodology

The modeling pipeline follows standard geophysical practice:

📥 Loading and validating seismic data

👁️ Visualizing seismic sections for quality control

📊 Extracting RMS amplitude as a key seismic attribute

🧩 Preparing feature matrices for machine learning

🌲 Applying a Random Forest classifier with class-imbalance handling

🔁 Using stratified cross-validation for robustness

🔍 Interpreting results using feature importance


🌍 Geological Interpretation

Seismic amplitude-based attributes, such as RMS amplitude, are widely used in petroleum geophysics to highlight contrasts in acoustic impedance. These contrasts may be associated with lithological changes, porosity variations, or fluid effects.
The model identifies anomalous attribute patterns that are commonly evaluated during hydrocarbon exploration. Final validation of such zones would always require integration with well data, rock physics analysis, and drilling.

🛢️ This project does not attempt direct hydrocarbon detection.

It focuses on prospectivity assessment and interpretation support.

📊 Results

✅ Stable model performance under cross-validation

✅ Identification of key seismic attributes influencing prospectivity

✅ Clear separation of prospective vs non-prospective zones in attribute space

✅ Workflow ready for extension to real interpreted seismic datasets


⚠️ Limitations

No direct well-log or production data
Proxy-based labels instead of confirmed hydrocarbon occurrences
Structural interpretation (faults, horizons) not explicitly included
Results therefore represent exploratory prospectivity, not proven reserves.


🚀 Scope for Future Work

➕ Multi-attribute integration (frequency, envelope, sweetness)

🧬 Rock-physics-based features (Vp/Vs, Poisson’s ratio, LMR)

🧠 Explainable AI techniques (e.g., SHAP)

🛰️ Deep learning models for 2D/3D seismic volumes

🧪 Well-to-seismic tie and calibration


🛠 Tools & Technologies

Python • NumPy • Pandas • Matplotlib • Scikit-learn • segyio


🎓 Academic Note

This repository represents a GeoAI mini-project for research and academic demonstration.
It emphasizes workflow design, geological reasoning, and responsible use of AI in petroleum geoscience.


👤 Author

Bikrant Kumar Mishra
Background: Geology
Interests: GeoAI, Petroleum Geophysics, Seismic Interpretation, Earth System Modeling
