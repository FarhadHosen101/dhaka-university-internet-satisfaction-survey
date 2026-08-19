# Internet Service Quality and User Satisfaction Survey Dataset - Dhaka University Students 2026

**Version:** 1.0  
**Date:** August 2026  
**Authors:** [Author Names]  
**Affiliation:** [University Name / Institution]  
**DOI:** [Pending / Add IEEE DataPort DOI here if uploaded]

---

## 1. Overview / Abstract

This dataset contains survey responses from **489 undergraduate students** across **33 public and private universities** in Dhaka, Bangladesh. The survey was conducted between **April and May 2026** to assess:

- Internet availability (Free Wi-Fi, 4G/5G, Home broadband, Lab/Library access)
- Technical problems (Peak-hour congestion, data cost, slow speed, power outages, login difficulty, ISP support)
- Overall user satisfaction with internet service quality
- Perceived academic impact of internet access
- Expectations and future usage intentions

The data supports the research paper:  
*"Internet Service Quality and User Satisfaction Among University Students in Dhaka: A Comparative Study of Public and Private Universities"* (under review, IEEE).

---

## 2. File Information

| Item | Description |
| :--- | :--- |
| **File Name** | `internet_satisfaction_survey_data.csv` |
| **Format** | CSV (Comma Separated Values) |
| **Rows** | 489 (valid responses) |
| **Columns** | 27 (including Timestamp) |
| **Encoding** | UTF-8 |
| **Software** | Compatible with Excel, Google Sheets, Python (pandas), R, SPSS, etc. |

---

## 3. Data Collection Methodology

- **Design:** Quantitative, cross-sectional survey.
- **Sampling:** Purposive sampling targeting undergraduate students in Dhaka.
- **Instrument:** Adapted from Ogunsola et al. (2013), 26-item structured questionnaire.
- **Distribution:** Online (Google Forms), shared via social media (Facebook, WhatsApp) and student groups.
- **Period:** April 21, 2026 – May 17, 2026.
- **Data Cleaning:**
  - Raw responses collected: 491
  - Removed: 1 troll response ("Test University"), 1 exact duplicate submission.
  - **Final valid responses: 489**
- **Balance:**
  - Public universities: 247 (50.5%)
  - Private universities: 242 (49.5%)
- **Institutions Covered:** 9 Public + 24 Private universities (including University of Dhaka, BUET, Jagannath University, BRAC University, North South University, etc.)

---

## 4. Data Dictionary (Codebook)

### A. Demographics (Section A)

| Column Name | Description | Values / Coding |
| :--- | :--- | :--- |
| `Timestamp` | Date and time of response submission | DD/MM/YYYY HH:MM:SS |
| `A1_Name` | Respondent's full name (anonymized in this dataset) | Text (removed for privacy) |
| `A2_Gender` | Gender of respondent | `Male`, `Female` |
| `A3_University_Name` | Name of the university | Text (normalized) |
| `A4_Academic_Year` | Current academic year | `1st year`, `2nd year`, `3rd year`, `4th year` |
| `A5_Accommodation` | Primary place of residence during semester | `University hall`, `Private hostel/mess`, `Family home` |
| `A6_Primary_Connection` | Primary internet connection used | `Home broadband/Fiber`, `Multiple types`, `University Wi-Fi`, `Mobile data only` |

### B. Internet Availability (Section B - Binary)
*1 = Yes, 0 = No*

| Column Name | Description |
| :--- | :--- |
| `B1_Campus_WiFi` | Free Wi-Fi or LAN available on campus |
| `B2_Lab_Library_Access` | Internet access in department lab or central library |
| `B3_Home_Broadband` | Broadband or fiber connection at home/mess |
| `B4_Mobile_Data` | 4G/5G mobile data plan regularly used |

### C. Technical Problems (Section C - Binary)
*1 = Yes (problem experienced), 0 = No (did not experience)*

| Column Name | Description |
| :--- | :--- |
| `C1_Slow_Speed` | Internet speed often too slow due to insufficient bandwidth |
| `C2_Power_Outage` | Frequent power outage (load shedding) interrupts internet use |
| `C3_Congestion` | Network congestion (slow speed during peak hours) |
| `C4_Login_Difficulty` | Difficulty logging into internet server or connecting to Wi-Fi |
| `C5_Data_Cost` | Cost of internet (BDT per GB) too expensive for budget |
| `C6_ISP_Support` | ISP or mobile operator's customer support ineffective |

### D. Satisfaction & Expectations (Section D - Binary)
*1 = Yes (Agree/Satisfied), 0 = No (Disagree/Not Satisfied)*

| Column Name | Description |
| :--- | :--- |
| `D1_Satisfied` | **(Primary Dependent Variable)** - Overall satisfied with current internet service quality |
| `D2_Admin_Improve` | University administration should improve internet facilities |
| `D3_Unstable_Disrupts` | Unstable internet disrupts online classes or study activities |

### E. Service Quality Expectations (Section E - Binary)
*1 = Yes, 0 = No*

| Column Name | Description |
| :--- | :--- |
| `E1_Quality_More_Satisfaction` | Agree that better internet quality will increase satisfaction |
| `E2_Use_More_Digital_Services` | Would use more digital services (online library, registration) if internet were reliable and fast |

### F. Likert Scale Items (Section F - 5-point scale)
*Scale: 1 = Strongly Disagree, 2 = Disagree, 3 = Neutral, 4 = Agree, 5 = Strongly Agree*

| Column Name | Description |
| :--- | :--- |
| `F1_Campus_Speed_Sufficient` | Campus internet speed is sufficient for online classes and video conferencing |
| `F2_Power_Backup` | Have alternative power backup (UPS/inverter/mobile hotspot) to continue internet during power cuts |
| `F3_Data_Price_Competitive` | Data pack prices among mobile operators are competitive |
| `F4_Network_Drops` | Frequently experience network drops or connection interruptions |
| `F5_Academic_Impact` | Overall, internet service quality has a positive impact on academic performance |

---

## 5. Anonymization & Ethics

- All personally identifiable information (names, email addresses, student IDs) have been **removed** or pseudonymized.
- The dataset is fully anonymized and cannot be traced back to individual respondents.
- The study was conducted in compliance with standard ethical guidelines for survey research in Bangladesh.

---

## 6. How to Cite This Dataset

If you use this dataset in your research, teaching, or analysis, please cite it as follows:

**IEEE Format:**
> [Author Surname], [Initials]. (2026). *Internet Service Quality and User Satisfaction Survey Dataset - Dhaka University Students 2026*. [Data File]. Available: [GitHub Repository URL or IEEE DataPort DOI]. [Accessed: Date].

**BibTeX:**
```bibtex
@misc{author2026internet,
  author = {Lastname, Firstname},
  title = {Internet Service Quality and User Satisfaction Survey Dataset - Dhaka University Students 2026},
  year = {2026},
  howpublished = {GitHub / IEEE DataPort},
  note = {DOI: [Insert DOI/URL here]}
}
