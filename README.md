# Cohort Halo-Plot™

Cohort Halo-Plot™ is a Python-based visualization tool for longitudinal population health data, designed to map age, sex, and mortality distributions across large-scale cohorts.

It provides an intuitive halo-style circular representation of demographic structure over time, enabling rapid visual assessment of cohort evolution and mortality dynamics across multiple years.

---

## ✨ Key Features

- Age group distribution visualization
- Sex-based stratification (Male/Female comparison)
- Mortality proportion mapping
- Longitudinal cohort tracking
- Publication-ready graphical output

---

## 🎯 Intended Use

Cohort Halo-Plot™ is designed for large-scale longitudinal datasets such as healthcare or population cohort studies.  

It allows researchers and data scientists to summarize demographic structure across years within a single integrated visualization framework.

---

## 📂 Repository Contents

- `cohort-halomap.ipynb` — Main implementation notebook for generating the Halo-Plot visualization
- `README.md` — Project documentation
- `LICENSE` — MIT License

---

## 🔧 Requirements

Python 3.x

Libraries used:

- numpy
- pandas
- matplotlib
- IPython

Install required packages:


---

## 📊 Expected Dataset Structure

The notebook assumes the dataset contains the following columns:

- `patient_id` — Unique patient identifier  
- `sex` — Sex indicator (e.g., Male/Female)  
- `age` — Age or derived age value  
- `death_flag` — Indicator for mortality status  
- `year` — Observation year  

Column names can be adapted as needed for external datasets.

---

## 🔐 Data Availability

This repository contains code only.

The original data used for development were accessed via the SAIL Databank and cannot be shared publicly.  

Users can apply this visualization tool to their own longitudinal cohort datasets structured with the required demographic fields.

---

## 👩‍💻 Author

Aswathy

---

## 📄 License

MIT License
