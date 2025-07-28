# clinical-sas-end-to-end-sdtm-adam

# Clinical SAS Project: SDTM & ADaM Mapping for a Phase II Clinical Trial

## 📌 Project Overview
This project demonstrates an **end-to-end process of converting raw clinical trial data into CDISC-compliant SDTM and ADaM datasets using SAS**.  
The study is based on a **Phase II randomized, double-blinded, placebo-controlled trial** to evaluate the **safety and effectiveness of Autologous Human Mesenchymal Stem Cells in patients with chronic heart conditions undergoing bypass surgery**.

---

## 🧾 Study Highlights
- **Phase:** II  
- **Design:** Randomized, double-blind, placebo-controlled  
- **Objective:** Evaluate safety (Adverse Events) and efficacy (treatment outcomes)  
- **Population:** Patients with chronic heart conditions undergoing bypass surgery  
- **Treatment Arms:**  
  - **Active:** Autologous Human Mesenchymal Stem Cells  
  - **Placebo:** Standard treatment  

---

## 📂 Project Structure
clinical-sas-sdtm-adam-project/
│
├── rawdata_sas/ # Raw SAS datasets (demo, adverse, ex, vital, etc.)
├── programs/
│ ├── sdtm/ # SAS programs for SDTM domains (DM, AE, EX, VS)
│ └── adam/ # SAS programs for ADaM datasets (ADSL, ADAE)
├── sdtm_datasets/ # Generated SDTM datasets
├── adam_datasets/ # Generated ADaM datasets
├── metadata/ # Mapping specs (SDTM & ADaM)
├── validation/ # Pinnacle 21 outputs (define.xml, validation reports)
└── README.md # Project documentation



## ✅ Steps Covered in This Project
1. **Raw Data Preparation**  
   - Source: Synthetic SAS datasets (training data)
   - Datasets: `demo` → DM, `adverse` → AE, `ex` → EX, `vital` → VS  

2. **SDTM Mapping**
   - Created SDTM domains:
     - **DM**: Demographics
     - **AE**: Adverse Events
     - **EX**: Exposure
     - **VS**: Vital Signs
   - Mapping as per **SDTM IG 3.3**

3. **ADaM Mapping**
   - Created:
     - **ADSL** (Subject-Level Analysis Dataset)
     - **ADAE** (Adverse Events Analysis Dataset)
   - Based on **ADaM IG standards**

4. **Validation**
   - Converted SDTM datasets to `.xpt`
   - Validated using **Pinnacle 21 Community Edition**
   - Generated **define.xml**

## 🛠 Tools & Technologies
- **SAS 9.4 / SAS Studio** – Data manipulation, SDTM & ADaM programming
- **Pinnacle 21** – SDTM validation & define.xml generation
- **GitHub** – Version control & project portfolio

---

## 📜 Disclaimer
This project uses **synthetic/sample data for learning and demonstration purposes only**. No real patient data is included.

---

Author
[Mogili Udayasri]
Clinical SAS Programmer | CDISC SDTM & ADaM Implementation |BSC STATISTICS
📧 Email: your-email@example.com
