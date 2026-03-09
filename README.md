# Palmer Penguins: Exploratory Data Analysis  
**By Cory Shockley**  
Python • Pandas • Seaborn • Matplotlib • SciPy

---

## 📌 Project Overview
This project explores the Palmer Penguins dataset using a complete, professional exploratory data analysis (EDA) workflow. The goal is to understand species‑level differences, relationships between biological measurements, and how factors like island and sex relate to physical traits.

This project demonstrates:
- clean data inspection  
- missingness evaluation  
- univariate, bivariate and multivariate exploration  
- correlation analysis  
- statistical testing  
- clear narrative and interpretation  

---

## 🐧 Dataset Description
The Palmer Penguins dataset contains physical measurements for three penguin species observed on islands in the Palmer Archipelago, Antarctica.

**Variables include:**
- `species` — Adelie, Chinstrap, Gentoo  
- `island` — Biscoe, Dream, Torgersen  
- `bill_length_mm`  
- `bill_depth_mm`  
- `flipper_length_mm`  
- `body_mass_g`  
- `sex`  
- `year`  

---

## 🧠 Key Questions Explored
- How do species differ in physical characteristics?  
- How are species distributed across islands?  
- What relationships exist between numeric variables?  
- Are male penguins significantly heavier than females?  
- How do island and sex relate to body size?  

---

## 📊 Highlights & Findings
- Clear species‑level differences in body size  
- Strong correlations among flipper length, bill length, and body mass  
- Distinct island distributions for each species  
- Statistically significant difference in body mass between males and females (t‑test, p ≈ 0)  
- Visualizations reveal meaningful biological patterns  

---

## 🧰 Tools & Libraries
- **Python**  
- **Pandas** — data manipulation  
- **NumPy** — numerical operations  
- **Seaborn** — statistical visualization  
- **Matplotlib** — plotting  
- **SciPy** — statistical testing  

---

## 📁 Project Structure
palmer-penguins-eda/ 
├── data/ 
└── penguins.csv  
├── notebooks/ 
└── penguins_eda.ipynb 
├── README.md 
└── requirements.txt


---

## ▶️ How to Run This Notebook
1. Clone the repository  
2. Install dependencies:  pip install -r requirements.txt
3. Open the notebook in Jupyter, VS Code, or DataSpell  
4. Run cells from top to bottom  

---

## 🧪 Statistical Test
A two‑sample t‑test was performed to compare male and female body mass.

**Result:**  
Male penguins are significantly heavier than females (p-value near zero), confirming a meaningful biological difference.

---

## 🚀 Possible Future Improvements
- Add species classification model  
- Build interactive visualizations (Plotly)  
- Add data cleaning pipeline  
- Expand statistical testing  
- Create a dashboard version of the analysis  

---

## 📎 Notebook
The full analysis is available in:  
`notebooks/penguins_eda.ipynb`

---

## 📬 Contact
If you’d like to discuss this project or my workflow, feel free to reach out.
