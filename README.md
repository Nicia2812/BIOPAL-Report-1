# Investigating Psychosocial and Socioeconomic Factors Effect On Kidney Dysfunction Using NHANES Data (2017–2018)

This project explores how **age**, **gender**, **race**, **BMI**, **physical activity**, **financial stress**, **food insecurity**, and other socioeconomic factors affect kidney function in U.S. adults aged 20 and above. Using data from NHANES 2017–2018, we analyze key biomarkers — **urine albumin-to-creatinine ratio (uACR)**, **uric acid**, and **eGFR** — to identify early signs of kidney dysfunction.

## 📁 Project Context
This study was conducted as part of the **Diploma in Biomedical Science – Biopharmaceutical Analysis Group Project**. The objective is to investigate how psychosocial and socioeconomic factors intersect with clinical outcomes, using nationally representative data.

## 🔍 Research Question

> In U.S. adults aged 20 and above using NHANES 2017–2018 data, how are age, gender, race, BMI, physical activity, perceived financial stress, and food insecurity associated with:
> - Albumin-to-Creatinine Ratio (ACR)
> - Uric Acid levels
> - eGFR (via serum creatinine)

## 📊 Methodology

- **Data Source**: NHANES 2017–2018  
- **Sample Size**: n = 5,533 U.S. adults aged 20+  
- **Analysis Tools**: Python (pandas, matplotlib, seaborn), Google Colab  
- **Statistical Tests**:  
  - Non-parametric (Kruskal-Wallis, Mann-Whitney U)  
  - Log-transformation for skewed variables  
  - Shapiro-Wilk for normality  
- **Visuals**: Boxplots, histograms, Q-Q plots

## 🔬 Key Variables

| Variable | Code | Description |
|----------|------|-------------|
| uACR | URXUMA / URXUCR | Biomarker for early kidney damage |
| Uric Acid | URXUAC | Biomarker linked to inflammation and filtration |
| BUN | LBDSBUSI | Biomarker linked to effectiveness of kidney filtration |
| Age | RIDAGEYR | Years |
| Gender | RIAGENDR | Male / Female |
| Race | RIDRETH3 | Ethnicity |
| BMI | BMXBMI | Body Mass Index |
| Physical Activity | PAQ650 | Weekly activity levels |
| Financial Stress | INDFMIN2 | Income-to-poverty ratio |
| Food Insecurity | FSDHH | Binary variable for food access |

## 📈 Summary of Findings

- **Log-uACR** (Shapiro-Wilk p )
- **Financial stress levels affect uACR** (Kruskal-Wallis p < )
- **Food insecurity impact on uACR** (Mann-Whitney p >)
- **Moderate stress group had more outliers**, suggesting greater risk variability

## 📌 How to View or Run the Notebook

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicia2812/BIOPAL-Report-1/blob/main/REPORT_1_BIOPAL.ipynb)

## 🧑‍🤝‍🧑 Contributors

- Nicia Chng Chyi Tong (S10268009J)  
- Haley Cheang Kai Le (S10267992C)  
- Tan Sze Zhuard (S10267097J)  
Class: 2P01 Group 2

## 📚 References
- Ammirati, A.L., 2020. Chronic kidney disease. Revista da Associação Médica Brasileira, 66(Suppl 1), pp.s03–s09. doi:10.1590/1806-9282.66.S1.3.
- Naber, T. and Purohit, S., 2021. Chronic kidney disease: Role of diet for a reduction in the severity of the disease. Nutrients, 13(9), p.3277. doi:10.3390/nu13093277.
- National Kidney Foundation, 2022. Urine albumin-to-creatinine ratio (UACR): A key marker for kidney disease. [online] Available at: https://www.kidney.org/kidney-failure-risk-factor-urine-albumin-creatinine-ratio-uacr [Accessed 25 Jun 2025].
- Weiner, I.D., Mitch, W.E. and Sands, J.M., 2015. Urea and ammonia metabolism and the control of renal nitrogen excretion. Clinical Journal of the American Society of Nephrology, 10(8), pp.1444–1458. doi:10.2215/CJN.10311013.
- Kanbay, M., Yilmaz, M.I., Sonmez, A., Turgut, F., Saglam, M., Cakir, E., Yenicesu, M., Covic, A., Jalal, D. and Johnson, R.J., 2011. Serum uric acid level and endothelial dysfunction in patients with nondiabetic chronic kidney disease. American Journal of Nephrology, 33(4), pp.298–304. doi:10.1159/000324847.
- Liu, P., Liang, Y., Cui, S., Hu, K., Lin, L., Shao, X. and Lei, M., 2023. Association of uric acid with the decline in estimated glomerular filtration rate in middle-aged and elderly populations: Evidence based on the China Health and Retirement Longitudinal Study. BMJ Open, 13(5), e071771. doi:10.1136/bmjopen-2023-071771.
- Tsai, C.W., Lin, S.Y., Kuo, C.C. and Huang, C.C., 2017. Serum uric acid and progression of kidney disease: A longitudinal analysis and mini-review. PLOS ONE, 12(1), e0170393. doi:10.1371/journal.pone.0170393.

---

*This repository contributes to the growing body of research on the social determinants of chronic kidney disease and supports preventive public health strategies based on biomarker screening.*
