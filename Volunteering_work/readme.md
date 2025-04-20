# TUFT Dataset Documentation and Analysis

This repository contains documentation and analytical resources related to the **TUFT (Task-based fNIRS Understanding and Functional Testing)** dataset. The dataset was developed by Tufts University's Human-Computer Interaction Lab and includes synchronized **fNIRS brain signals** and **task performance data** collected during n-back cognitive tasks.

---

## Contents of This Repository

### Documentation Files
- **`Introduction to fNIRS and TUFT Dataset Acquisition Details.docx`**  
  Overview of the TUFT dataset, background on fNIRS, study purpose, task methodology, data collected, and ethical considerations.

- **`TUFT_Dataset_DetailedReport.docx`**  
  Detailed explanation of the structure and purpose of each file in the dataset (e.g., `fnirs_train.csv`, `task_result_train_*.txt`, etc.).

---

## Dataset Access

**Full dataset (148MB)** is hosted on OneDrive:  
[Click here to access the dataset](https://aseblr-my.sharepoint.com/:f:/g/personal/bl_en_u4aie23115_bl_students_amrita_edu/Eoa2KGWuXVhFqOZuJCapc0QBtGEfn9mZ5pUPHGQd7RF_Zg?e=daLyTU)  
---

## Dataset Overview

The TUFT dataset includes:

- fNIRS recordings collected using non-invasive sensors, measuring changes in oxygenated and deoxygenated hemoglobin.
- Task data from n-back tests (0-back to 3-back), used to vary cognitive workload levels.
- Subject responses with accuracy and keypress sequences.

These files are suitable for studies in:
- Cognitive workload modeling  
- Brain-computer interface (BCI) development  
- Machine learning applications in neuroscience  
- Neuroadaptive systems and intelligent user interfaces

---

## Dataset Structure

Each subject folder in the dataset contains:
- `fnirs_init.csv` – Baseline resting-state brain activity
- `fnirs_train.csv`, `fnirs_train.mat` – fNIRS data during training tasks
- `fnirs_test.csv`, `fnirs_test.mat` – fNIRS data during test tasks
- `task_result_train_*.txt`, `task_result_test_*.txt` – Annotated behavioral data including stimuli, responses, and accuracy

Each task result file is uniquely identified by session ID (e.g., `1_1_1`, `1_2_1`) and aligns with the corresponding brain signal file for synchronized analysis.

---


