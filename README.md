# 🧠 Arabic Span Extraction-based Reading Comprehension (ASER) Benchmark

![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-blue.svg)
![Language: Arabic](https://img.shields.io/badge/Language-Arabic-green)
![Dataset Size](https://img.shields.io/badge/Records-10,000-lightgrey)
![Category](https://img.shields.io/badge/Type-Reading%20Comprehension-orange)
![Version](https://img.shields.io/badge/Version-1.0-brightgreen)

---

## 📘 Overview

The **ASER** dataset is a **manually created benchmark for Arabic Machine Reading Comprehension (MRC)**.  
It consists of **10,000 question–answer triples**, divided into **training** and **testing** sets with a **90:10 split**.

ASER provides a reliable resource for evaluating Arabic MRC models on span-extraction tasks and contributes to advancing research in **Arabic NLP**.

---

## 📦 Dataset Contents

This repository includes:

- **Training set:** 9,000 records  
- **Testing set:** 1,000 records  
- **Human evaluation subset:** 100 records sampled from the test set for assessing human performance

---

## 📊 Data Format

Each record in the dataset contains seven fields:

| Column | Description |
|:-------|:-------------|
| **Semester number** | Indicates the semester in which the record was created (within two semesters). |
| **Article ID** | Unique identifier for the article. |
| **Question** | The question associated with the article. |
| **Answer** | The extracted answer to the question. |
| **Paragraph** | The paragraph from which the answer is derived. |
| **Answer index** | The index of the first character of the answer in the paragraph. |
| **Domain category** | The thematic domain or category of the article. |

---

## 📚 Citation

If you use this dataset in your research or development, please cite the following papers:

1. **Biltawi, M. M., Awajan, A., & Tedmori, S.** (2023).  
   *Arabic Span Extraction-based Reading Comprehension Benchmark (ASER) and Neural Baseline Models.*  
   *ACM Transactions on Asian and Low-Resource Language Information Processing, 22*(5), 127:1-127:29.  

2. **Biltawi, M. M., Awajan, A., & Tedmori, S.** (2025).  
   *Improved Bidirectional Attention Flow (BIDAF) Model for Arabic Machine Reading Comprehension.*  
   *Natural Language Processing, 31*(3), 771-799. [DOI: 10.1017/nlp.2024.46](https://doi.org/10.1017/nlp.2024.46)

---

## ⚖️ License

This dataset is released under the **[Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)** license.  
You are free to **share** and **adapt** this dataset for any purpose, provided that **appropriate credit** is given and the above papers are cited.

---

## 🙏 Acknowledgment

Thank you for using the **ASER Dataset**!  
Your work contributes to the growth of **Arabic NLP** and **Machine Reading Comprehension** research. 🌍📖

---

## 🏷️ Tags
