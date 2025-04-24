# EDA on Gene Expression 🧬💻

This project explores GSE2034 gene expression dataset using python. You get the opportunity to put your skills into practice and possibly learn new ones.
We strongly encourage our fellow learners to:
- try to carry out each analysis before lookiing at the proposed solution;
- repeat the analyses with different datasets.

## 🧬 GSE2034
With the GSE2034 breast cancer dataset, it performs basic exploratory data analysis to uncover patterns in gene expression levels across samples.

### 📊 Dataset
- Source: [GEO - GSE2034](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE2034)
- insight: `data/raw/GSE2034.md` walks you through the download process of GSE2034

### 🎯 Goals
- Visualize expression distributions
- Check for missing or noisy data
- Perform PCA and correlation analysis

### ▶️ How to Run
1. Clone the repo
2. Download `GSE2034.csv` into `data/raw/`
3. Install dependencies: `pip install -r requirements.txt`
4. Open Jupyter: `jupyter lab`

#### 🔽 **Step-by-step: Download the Dataset from GEO**

1. **Go to this section on the page:**
   - Scroll to **"Series Matrix File(s)"**  
   - You’ll see a link like:
     ```
     GSE2034_series_matrix.txt.gz
     ```

2. **Download the file:**
   - Click the `GSE2034_series_matrix.txt.gz` link to download the matrix file (this contains the expression data + phenotype info).

3. **(Optional) Download platform annotation (gene mapping):**
   - Under **"Platforms"** section (GPL96), you might see:
     ```
     GPL96: [HG-U133A] Affymetrix Human Genome U133A Array
     ```
   - Click it, then click **"Download full table"** to get the gene annotation if you want to map probe IDs to gene symbols.

---

### 💡 After Downloading:
Uunzip `GSE2034_series_matrix.txt.gz` and move it to the `data/raw/` folder of your project.

---

## ✨ Extra Material

[Here](https://www.notion.so/EDA-on-Gene-Expression-e74f532089ce4941a09dd78de56e5348?pvs=4) you can find extra material with suggestions and or references for further analyses

## ⚠️ Disclaimer

This repository is intended **solely for educational purposes**. These notebooks are to serve as examples of real-life use cases. The approaches presented here reflect one possible way to explore gene expression data in a biomedical context, but they do **not cover all methodologies**, nor do they imply clinical or diagnostic validity.

**Omics Pilot** team is not responsible for any use, misuse, or interpretation of the code, results, or insights provided in this project.


## 📜 License
MIT


## 🫱🏼‍🫲🏾 Contribution
We welcome contributions to this project! If you have ideas, suggestions, or improvements, feel free to open an issue or submit a pull request.