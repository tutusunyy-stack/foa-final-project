# FOA Final Project – Air Quality & Health Outcomes

This repository contains all code, datasets, and documentation for our Foundations of Analytics final project.  
Our project investigates how **air quality** is associated with **chronic respiratory disease outcomes** across U.S. counties.

---

## 📌 Project Overview

We merge and analyze two independent public datasets:

### **1. EPA Annual AQI by County (2024)**
- **Source:** U.S. Environmental Protection Agency (EPA) – AirData  
- **Variables used:**
  - `Max AQI`
  - `Days PM2.5`
  - `Days Ozone`
  - `Good Days`, `Moderate Days`, `Unhealthy Days`, etc.

### **2. CDC PLACES – County Data 2024**
- **Source:** Centers for Disease Control and Prevention (CDC) – PLACES: Local Data for Better Health  
- **Measures used:**
  - `Chronic obstructive pulmonary disease among adults`
  - `Current asthma among adults`
  - `Current lack of health insurance among adults aged 18–64 years`
  - `Fair or poor self-rated health status among adults`

### **Goal of the Project**
To evaluate whether poor air quality is associated with higher rates of chronic respiratory conditions in U.S. counties.

---

## 📁 Repository Structure

```text
foa-final-project/
│
├─ data/
│  ├─ annual_aqi_by_county_2024.csv
│  └─ CDC_PLACES_County_Data_2024_CSV.csv
│
├─ notebooks/
│  └─ final.ipynb
│
├─ slides/
│  └─ ProjectPresentationTemplate.pptx
│
├─ requirements.txt
└─ README.md
```

- **data/** → contains all datasets needed to run the notebook  
- **notebooks/** → contains the complete analysis (`final.ipynb`)  
- **slides/** → final project presentation  

---

## 🚀 How to Run the Code

### **1. Clone the repository**

```bash
git clone <THIS_REPO_URL>
cd foa-final-project
```

> ⚠️ IMPORTANT: Replace `<THIS_REPO_URL>` with the actual GitHub link.

---

### **2. Create and activate a Python environment (recommended)**  
Using conda:

```bash
conda create -n foa_final python=3.11
conda activate foa_final
```

---

### **3. Install dependencies**

```bash
pip install -r requirements.txt
```

---

### **4. Run the notebook**

```bash
jupyter notebook notebooks/final.ipynb
```

Ensure the **data folder structure stays the same**, otherwise the notebook will not find the datasets.

---

## 🧪 Reproducibility Notes

- All code is written in **Python 3.11**.
- Required packages are listed in `requirements.txt`.
- The notebook will run without modification as long as:
  - datasets remain in `data/`
  - paths are unchanged
  - required libraries are installed

---



## 📬 Contact

If there are any issues running the notebook, please open a GitHub issue in this repository.

---