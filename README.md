# LLM-Based Cybersecurity Consultation – Public Dataset & Instruments

This repository provides **public-ready datasets and analysis artifacts** supporting the study:

> *Integrating an LLM-Based Consultation Service into a National Cybersecurity Awareness Survey*

The data are released in a **privacy-preserving form** to support transparency and reproducibility while protecting participants, including minors.

---

## 📂 Repository Structure

data/
├─ output_data_public.csv
├─ output_data_public_correlations.csv
├─ output_data_public_engagement_summary.csv
├─ output_data_public_table_gender.csv
├─ output_data_public_table_age_group.csv
├─ output_data_public_table_education.csv
├─ output_data_public_table_knowledge.csv
├─ output_data_public_table_internet_usage.csv
└─ output_data_public_table_incident_any.csv
instruments/
 ├─ SeBIS_Indonesian_Adapted.pdf
 ├─ UX_Questionnaire.pdf
 └─ Expert_Evaluation_Rubric.pdf



---

## 📋 Research Instruments

This repository also provides the research instruments used in the study,
including (i) an adapted Indonesian version of the SeBIS questionnaire,
(ii) a post-interaction UX questionnaire, and (iii) an expert evaluation
rubric for assessing LLM-generated cybersecurity recommendations.
All instruments are provided for transparency and academic reuse.


## 📊 Dataset Description

### 1) `output_data_public.csv`
**Unit:** individual participant (N = 104)  
**Content:** minimized microdata containing only **composite scores**:
- SeBIS total and subscale scores (pre, post, and Δ)
- UX construct means (Usefulness, Ease of Understanding, Personal Relevance, Trust & Adoption, Overall UX)

**Excluded intentionally:**
- Item-level questionnaire responses  
- Demographic variables  
- Engagement logs (e.g., session duration, follow-up turns)  
- Any identifiers or timestamps  

This minimization reduces re-identification risk while preserving the ability to reproduce core statistical analyses.

---

### 2) `output_data_public_correlations.csv`
Spearman correlation coefficients between ΔSeBIS and UX/engagement indicators, corresponding to **Results Section F** and **Figure 3**.

---

### 3) `output_data_public_engagement_summary.csv`
Aggregated engagement statistics (mean, SD) for session duration and number of follow-up turns, corresponding to **Results Section D**.

---

### 4) `output_data_public_table_*.csv`
Aggregated participant characteristics supporting **Table 2**, including:
- Gender
- Age group
- Education level
- Self-rated cybersecurity knowledge
- Daily internet usage
- Incident experience (binary/aggregated)

Percentages may exceed 100% for incident experience due to multiple selections.

---

## 🔒 Privacy and Ethics

- No names, contact information, IDs, or message content are included.
- Chat message content was **not stored persistently** and is **not part of this dataset**.
- Individual-level demographic combinations were removed to mitigate re-identification risk, particularly for participants aged 15–17.
- The released data comply with data minimization principles and ethical requirements for human-subject research.

---

## 📜 License

This dataset is released for **academic and non-commercial research purposes**.  
Please cite the associated paper when using the data.

---

## 📬 Contact

For access to additional materials or questions regarding the dataset, please contact the corresponding author.
