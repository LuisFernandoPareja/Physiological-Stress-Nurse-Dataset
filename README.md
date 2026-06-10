# Physiological Nurse Stress Dataset

A cleaned, annotated and ready to use dataset with 16,813 observations. The dataset includes physiological and contextual variables such as heart rate (HR), body temperature (BT), shift code, class label, day of measurement, and nurse identifier.

##  Overview

**Physiological Nurse Stress Dataset** The Multimodal Physiological Dataset for Nurse Stress Detection is designed to support research on occupational stress
monitoring using physiological and work related data collected in real clinical environments. The dataset combines heart HR, BT, shift data, temporal variables, and nurse IDs with stress labels derived from questionnaire responses and expert validated scoring equation. The dataset can be used in a variety of tasks including:
* Binary & multiclass stress classification
* Personlaized stress detection
* Feature importance analysis
* Analysis of how physiological signals change during work shifts

## Dataset Details

* **Total Rows:** 16813
* **Classes:**

| Variable | Description |
|----------|-------------|
| `start` | Timestamp of the observation/event |
| `hr` | Heart rate measurement |
| `temp` | Body temperature |
| `day` | Calendar day |
| `ID` | Nurse identifier |
| `label` | Stress label |
| `shift_code` | Categorical code for work shift |
| `start_datetime` | Start of shift |
| `end_datetime` | End of shift |

## Directory Structure

Physiological-Stress-Nurse-Dataset/
├── binary_classification.ipynb
├── final_dataset.csv
```

## Scientific Relevance

This dataset supports research in:

* Stress Detection in the Workplace
* Plant Disease Diagnosis
* Computer Vision for Agriculture
* Deep Learning model benchmarking

It is suitable for models such as:

* Boosting models
* Transfer Learning frameworks
* Explainable AI methods

---

## Citation

If you use this dataset, please cite:

```
[Soon to be added]
```

---

##  Disclaimer

This dataset is intended for research and educational purposes only. It should not be used as a sole diagnostic tool in real world medicine decision-making without expert validation.

---

## Author
Pareja Bernal Luis Fernando, Bieri Jannic Stefan, Souissi Souhir Ben, Golz Christoph (2026)

---

