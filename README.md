# Arabic-Span-Extraction-based-Reading-Comprehension-ASER-Benchmark-
## ASER Dataset

**ASER** is a manually created dataset for **Arabic Machine Reading Comprehension (MRC)**, comprising **10,000 records** of triples divided into **training** and **testing** sets (90:10).

This repository contains:
- The **training set**, which includes **9,000 records**.  
- The **testing set**, which includes **1,000 records**.  
- An additional **100 records** sampled from the test set to evaluate human results.

Each record in the dataset consists of **seven columns**:
1. **Semester number** – Indicates the semester in which the record was created (within two semesters).  
2. **Article ID** – The unique identifier for the article.  
3. **Question** – The question associated with the article.  
4. **Answer** – The answer to the question.  
5. **Paragraph** – The paragraph from which the answer is extracted.  
6. **Answer index** – The index of the first character of the answer in the paragraph.  
7. **Domain category** – The category or domain of the article.

---

**📌 Note:**  
If you use this dataset in your research or development, please cite both of the following papers:

- Biltawi, M. M., Awajan, A., & Tedmori, S. (2023). *Arabic Span Extraction‑based Reading Comprehension Benchmark (ASER) and Neural Baseline Models.* ACM Transactions on Asian and Low‑Resource Language Information Processing, 22(5), 127:1‑127:29.  
- Biltawi, M. M., Awajan, A., & Tedmori, S. (2025). *Improved bidirectional attention flow (BIDAF) model for Arabic machine reading comprehension.* Natural Language Processing, 31(3), 771‑799. DOI: [10.1017/nlp.2024.46](https://doi.org/10.1017/nlp.2024.46)

Thank you for using the ASER dataset!
