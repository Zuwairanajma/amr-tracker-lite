# amr-tracker-lite
Simulated Genomic Surveillance Dashboard for AMR in Africa
---

![Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

---

## 🚀 How to Run
1. Clone the repo  
   `git clone https://github.com/Zuwairanajma/amr-tracker-lite.git`
2. Navigate into the project folder  
   `cd amr-tracker-lite`
3. Create & activate a virtual environment  
   `python -m venv env`  
   `source env/Scripts/activate` *(Windows)*  
4. Install dependencies  
   `pip install -r requirements.txt`
5. Launch the notebook  
   `jupyter notebook amr_dashboard.ipynb`

---

## 📂 Sample Data Fields

The `simulated_amr_data.csv` file includes:

- `Country`: Nigeria, Kenya, South Africa  
- `Pathogen`: e.g., *E. coli*, *S. aureus*, *K. pneumoniae*  
- `AMR_Gene`: e.g., blaCTX-M, mecA  
- `Date_Reported`: Simulated weekly dates  
- `Sample_Type`: Blood, Urine, Sputum  

---

## 📈 Visual Preview

> #### 🌍 Country-Wise Resistance Overview
![Dashboard View 1](dashboard_preview1.png)

#### 🧪 Resistance Trends Over Time
![Dashboard View 2](dashboard_preview2.png)

#### 🧬 Pathogen Breakdown by Drug Class
![Dashboard View 3](dashboard_preview3.png)


---

🔗 **[👉 View Full Interactive Notebook on NBViewer](https://nbviewer.org/github/Zuwairanajma/amr-tracker-lite/blob/master/amr_dashboard.ipynb)**

## 💡 Inspiration

This project was built as a fast prototype under mentorship guidance, to support a larger research proposal on **AI-Driven Genomic Surveillance of Drug-Resistant Pathogens in Africa**.


It draws inspiration from:  
- [Prof. Tulio de Oliveira](https://www.krisp.org.za/tulio.asp) and his groundbreaking genomic work at [CERI](https://www.krisp.org.za/ceri.asp)  

- WHO’s [GLASS](https://www.who.int/initiatives/glass) AMR surveillance strategy  

- Real-world gaps in cross-border bioinformatics capability in Africa

---

## 🧪 Future Plans

- Integration with real genomic datasets (GISAID/SRA)
- Streamlit-based live dashboard deployment
- Expansion to more African regions

---

## 👩🏽‍💻 Author

**Zuwaira Sadiq**  
Tech-Empowered Economist | Aspiring Bioinformatician  
🔗 [GitHub](https://github.com/Zuwairanajma) | ✉️ juwairiyyasadiq@gmail.com

---

## 📜 License

This project is licensed under the MIT License.  
Feel free to fork, adapt, and build upon it.

---
