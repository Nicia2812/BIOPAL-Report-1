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
| eGFR | Derived from LBXSCR, RIDAGEYR, RIAGENDR | Estimated kidney filtration rate |
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

- Matsushita, K. et al., 2010. Association of estimated glomerular filtration rate and albuminuria with all-cause and cardiovascular mortality. *Lancet*, 375(9731), pp.2073–2081. https://doi.org/10.1016/S0140-6736(10)60674-5  
- Inker, L.A. et al., 2023. Change in albuminuria and GFR as end points for clinical trials in early stages of CKD. *American Journal of Kidney Diseases*, 81(3), pp.293–305. https://doi.org/10.1053/j.ajkd.2022.09.006  
- National Kidney Foundation, 2023. Kidney failure risk factor: urine albumin-creatinine ratio (uACR). https://www.kidney.org/kidney-failure-risk-factor-urine-albumin-creatinine-ratio-uacr
- Scialla, J.J. & Anderson, C.A.M., 2020. Diet and Chronic Kidney Disease: A Focus on Plant-Based Diets: A Scientific Statement From the American Heart Association. Circulation, 141(6), pp.e33–e43. https://doi.org/10.1161/CIR.0000000000000740
- Rysz, J., Gluba-Brzózka, A., Franczyk, B., Jabłonowski, Z. & Ciałkowska-Rysz, A., 2022. Novel Biomarkers in the Diagnosis of Chronic Kidney Disease and the Prediction of Its Outcome. International Journal of Molecular Sciences, 23(1), p.13. https://doi.org/10.3390/ijms23010013
- Singh, R., Vohra, R. & Dewan, R., 2023. Chronic Kidney Disease. In: StatPearls [Internet]. Treasure Island (FL): StatPearls Publishing. Available at: https://www.ncbi.nlm.nih.gov/books/NBK507821/ [Accessed 18 Jun. 2025].
- Vassalotti, J.A., Centor, R., Turner, B.J., Greer, R.C., Choi, M. & Sequist, T.D., 2014. Practical Approach to Detection and Management of Chronic Kidney Disease for the Primary Care Clinician. The American Journal of Medicine, 127(6), pp.542–549. https://doi.org/10.1016/j.amjmed.2013.11.027
- Levey, A.S., Stevens, L.A., Schmid, C.H., Zhang, Y.L., Castro, A.F., Feldman, H.I., Kusek, J.W., Eggers, P., Van Lente, F., Greene, T. & Coresh, J., 2009. A New Equation to Estimate Glomerular Filtration Rate. Annals of Internal Medicine, 150(9), pp.604–612. https://doi.org/10.7326/0003-4819-150-9-200905050-00006
- Liu, P., Liang, Y., Cui, S., Hu, K., Lin, L., Shao, X. & Lei, M., 2023. Association of uric acid with the decline in estimated glomerular filtration rate in middle‑aged and elderly populations: evidence based on the China Health and Retirement Longitudinal Study. BMJ Open, 13(5), e071771. https://doi.org/10.1136/bmjopen-2023-071771
- Kramer, H.J., Nguyen, Q.D., Curhan, G., Hsu, C.-Y., Kestenbaum, B., Lora, C.M., Ricardo, A.C., Ravel, J., Saran, R., Saydah, S., Schelling, J.R. & Vassalotti, J.A., 2017. US Renal Data System 2016 Annual Data Report: Epidemiology of Kidney Disease in the United States. American Journal of Kidney Diseases, 69(3 Suppl 1), pp.A7–A8. https://doi.org/10.1053/j.ajkd.2016.12.004

---

*This repository contributes to the growing body of research on the social determinants of chronic kidney disease and supports preventive public health strategies based on biomarker screening.*
