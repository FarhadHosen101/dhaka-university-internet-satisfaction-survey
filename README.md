# Internet Service Quality and User Satisfaction Survey Dataset - Dhaka University Students 2026

**DOI:** [Pending / Link to IEEE DataPort if uploaded]  
**Version:** 1.0  
**Date:** August 2026  
**Authors:** [Author Names]  
**Affiliation:** [University Name / Institution]

---

## 1. Overview / Abstract
This dataset contains survey responses from **489 undergraduate students** across **33 public and private universities** in Dhaka, Bangladesh. The survey was conducted between April and May 2026 to assess:

- Internet availability (Free Wi-Fi, 4G/5G, Home broadband)
- Technical problems (Peak-hour congestion, cost, slow speed, power outages)
- Overall user satisfaction with internet service quality
- Perceived academic impact of internet access

The data supports the research paper: *"Internet Service Quality and User Satisfaction Among University Students in Dhaka: A Comparative Study of Public and Private Universities"*, currently under review (IEEE).

---

## 2. File List
- **`internet_satisfaction_survey_data.csv`**: Main dataset (489 rows, ~25 columns).
- **`codebook.txt`** (or see Section 3 below): Description of each variable.

---

## 3. Data Dictionary (Codebook)

### A. Demographics (Section A)
| Column Name | Description | Values / Coding |
| :--- | :--- | :--- |
| `id` | Unique respondent identifier | 1 to 489 |
| `gender` | Gender of respondent | `Male` / `Female` |
| `university_type` | Type of university | `Public` / `Private` |
| `academic_year` | Current academic year | `1st year`, `2nd year`, `3rd year`, `4th year` |
| `accommodation` | Primary place of residence | `University hall`, `Private hostel/mess`, `Family home` |
| `primary_connection` | Primary internet connection used | `Home broadband/Fiber`, `Multiple types`, `University Wi-Fi`, `Mobile data only` |

### B. Internet Availability (Section B - Binary)
*1 = Yes (Available), 0 = No (Not Available)*

| Column Name | Description |
| :--- | :--- |
| `avail_campus_wifi` | Free Wi-Fi / LAN available on campus |
| `avail_lab_library` | Departmental lab or library internet access |
| `avail_home_broadband` | Home broadband or fiber connection |
| `avail_mobile_data` | 4G / 5G mobile data plan available |

### C. Technical Problems (Section C - Binary)
*1 = Yes (Problem experienced), 0 = No (Did not experience)*

| Column Name | Description |
| :--- | :--- |
| `prob_slow_speed` | Slow bandwidth / internet speed |
| `prob_power_outage` | Power outage interrupts internet use |
| `prob_congestion` | Peak-hour network congestion |
| `prob_login_difficulty` | Difficulty logging in to Wi-Fi / networks |
| `prob_data_cost` | Data cost is too expensive |
| `prob_isp_support` | ISP customer support is ineffective |

### D. Satisfaction & Expectations (Section D - Binary)
*1 = Yes (Agree/Satisfied), 0 = No (Disagree/Not Satisfied)*

| Column Name | Description |
| :--- | :--- |
| `sat_current_quality` | Satisfied with the current internet service quality (Primary Dependent Variable) |
| `admin_should_improve` | University administration should improve internet facilities |
| `unstable_disrupts_study` | Unstable internet disrupts academic study |
| `quality_more_satisfaction` | Better internet quality would lead to more satisfaction |
| `would_use_more_digital` | Would use more digital services if quality improves |

### E. Likert Scale Items (Section F - 5-point scale)
*Scale: 1 = Strongly Disagree, 2 = Disagree, 3 = Neutral, 4 = Agree, 5 = Strongly Agree*

| Column Name | Description |
| :--- | :--- |
| `likert_campus_speed` (F1) | Campus internet speed is sufficient for academic needs |
| `likert_power_backup` (F2) | Adequate power backup is available for internet access |
| `likert_data_price` (F3) | Data prices are competitive and affordable |
| `likert_network_drops` (F4) | Internet disconnects frequently (network drops) |
| `likert_academic_impact` (F5) | Internet access has a positive impact on academic performance |

---

## 4. Methodology & Data Collection

- **Design:** Cross-sectional quantitative survey.
- **Sampling:** Purposive sampling targeting undergraduate students.
- **Instrument:** Adapted from Ogunsola et al. (2013), 26-item questionnaire.
- **Distribution:** Google Forms, distributed via social media and student groups (WhatsApp/Messenger).
- **Cleaning:** 
  - Raw responses: 491
  - Removed: 1 troll response (non-existent university), 1 exact duplicate submission.
  - **Final valid responses:** 489
- **Balance:** Public universities = 247 (50.5%), Private universities = 242 (49.5%).

---

## 5. Anonymization & Ethics

- All personally identifiable information (Names, Email addresses, Student IDs) have been **removed** from this dataset.
- The data is fully anonymized and aggregates responses for statistical analysis only.
- No ethical concerns regarding privacy remain.

---

## 6. Citation (How to Credit this Dataset)

If you use this dataset for your research, teaching, or analysis, please cite it as follows (IEEE format):

> [Author Surname], [Initials]. (2026). *Internet Service Quality and User Satisfaction Survey Dataset - Dhaka University Students 2026*. [Data File]. Available: GitHub Repository URL or IEEE DataPort DOI. [Accessed: Date].

**BibTex:**
```bibtex
@misc{author2026internet,
  author = {Lastname, Firstname},
  title = {Internet Service Quality and User Satisfaction Survey Dataset - Dhaka University Students 2026},
  year = {2026},
  howpublished = {GitHub / IEEE DataPort},
  note = {DOI: [Insert DOI/URL here]}
}
