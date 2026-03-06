<p align="center">

# 🛢️ GeoAI Hydrocarbon Prospectivity Modeling

### Machine Learning • Petroleum Geophysics • Seismic Interpretation • GeoAI

</p>

---

## 📌 Project Overview

Hydrocarbon exploration is one of the most complex challenges in geoscience because the subsurface cannot be observed directly. Instead, geoscientists rely on indirect indicators derived from seismic data and geological interpretation.

This project demonstrates how **GeoAI techniques can support hydrocarbon prospectivity analysis** by combining seismic attributes with machine learning models.

Rather than claiming hydrocarbon discovery, the workflow focuses on **prospectivity assessment and interpretation support**, similar to early-stage petroleum exploration workflows used in academia and industry.

The project is designed as a **research-oriented GeoAI mini project**, suitable for academic portfolios, graduate applications, and geoscience data science demonstrations.

---

## 🎯 Motivation

Hydrocarbon exploration involves significant uncertainty due to complex subsurface geology and limited direct observations.

Seismic surveys provide indirect information related to:

• rock properties  
• structural traps  
• fluid indicators  

Machine learning can assist geoscientists by identifying patterns within these attributes.

This project explores how:

🧠 **Seismic attributes act as proxies for subsurface properties**

🤖 **Machine learning assists exploration risk evaluation**

🪨 **Geological reasoning remains central to interpretation**

The aim is to demonstrate how **AI can enhance geological workflows rather than replace them**.

---

## 🗂 Dataset

The workflow is designed to be flexible and adaptable to different research scenarios.

The model supports two types of datasets:

📡 **SEG-Y seismic volumes**

Example datasets include publicly available seismic datasets such as the **F3 Netherlands Offshore dataset**, commonly used in academic geophysics research.

🧪 **Physics-inspired synthetic seismic attributes**

When real seismic data are unavailable, synthetic attributes are generated based on realistic geophysical relationships between impedance, amplitude, and frequency.

This approach ensures the project remains **reproducible and demonstration-ready**.

---

## 🔬 Methodology

The modeling pipeline follows a simplified version of a **standard seismic interpretation workflow** used in petroleum geophysics.

Key steps include:

📥 Loading and validating seismic data

👁️ Visualizing seismic sections for quality control

📊 Extracting seismic attributes such as **RMS amplitude**

🧩 Preparing feature matrices for machine learning

🌲 Training a **Random Forest classifier**

🔁 Applying **Stratified Cross Validation** for robust model evaluation

🔍 Interpreting model behavior using **feature importance analysis**

This workflow combines **geophysical reasoning with data-driven modeling**.

---

## 🌍 Geological Interpretation

Seismic attributes such as **RMS amplitude** are widely used in petroleum geophysics to highlight contrasts in **acoustic impedance**.

These contrasts may indicate:

• lithological variations  
• porosity changes  
• fluid effects  

Machine learning models can help highlight **anomalous attribute patterns** that may correspond to zones of geological interest.

However, true hydrocarbon confirmation would require integration with:

• well logs  
• rock physics analysis  
• structural interpretation  
• drilling verification

🛢️ **This project does not attempt direct hydrocarbon detection.**

Instead, it demonstrates **prospectivity modeling as a decision-support workflow**.

---

## 📊 Results

The modeling workflow demonstrates several encouraging outcomes:

✅ Stable performance under cross-validation

✅ Identification of key seismic attributes influencing prospectivity

✅ Clear separation between prospective and non-prospective zones in attribute space

✅ A modeling workflow that can be extended to real interpreted seismic datasets

These results illustrate how **GeoAI can support exploration geoscientists during early-stage prospect evaluation**.

---

## ⚠️ Limitations

As an academic demonstration project, some limitations exist:

• No well-log calibration data included

• Labels are generated using **proxy geological rules**

• Structural interpretation (faults and horizons) is not explicitly modeled

Therefore, the results represent **exploration indicators rather than confirmed hydrocarbon reserves**.

---

## 🚀 Future Scope

This project can be expanded with more advanced exploration techniques:

➕ Multi-attribute integration  
(frequency, envelope, sweetness)

🧬 Rock physics derived attributes  
(Vp/Vs ratio, Poisson's ratio, Lambda-Mu-Rho)

🧠 Explainable AI techniques  
(SHAP, feature attribution)

🛰️ Deep learning models for **2D and 3D seismic volumes**

🧪 Integration with **well logs and seismic-to-well calibration**

---

## 🛠 Tools & Technologies

Python  
NumPy  
Pandas  
Matplotlib  
Scikit-learn  
segyio  

These tools enable the development of **GeoAI workflows for seismic interpretation and exploration analytics**.

---

## 📚 References

1. Taner, M. T., & Sheriff, R. E. (1977). *Seismic Attributes*. Geophysical Prospecting.

2. Chopra, S., & Marfurt, K. J. (2007). *Seismic Attributes for Prospect Identification and Reservoir Characterization*. SEG.

3. Goodfellow, I., Bengio, Y., & Courville, A. (2016). *Deep Learning*. MIT Press.

4. Hall, M. (2016). *Machine Learning Methods for Petroleum Exploration*. SEG.

5. Netherlands Offshore F3 Seismic Dataset – Open Seismic Repository.

---

## 👤 Author

**Bikrant Kumar Mishra**

Background: Geology

Research Interests:

• GeoAI  
• Petroleum Geophysics  
• Seismic Interpretation  
• Earth System Modeling

---

⭐ If you found this project interesting, feel free to explore the repository and the accompanying GeoAI portfolio.
