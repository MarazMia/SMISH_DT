# SMISH_DT: A Smishing Dataset Collection

This repository, **SMISH_DT**, houses a comprehensive collection of smishing-related datasets, along with the code and refined versions used in our research.

---

## 📚 Repository Structure

* **`Dataset/`**: Contains the **original, raw datasets** as discussed in our paper. This directory also includes a valid list of **Top-Level Domains (TLDs)** used for URL extraction.

* **`Code/`**: Includes Jupyter notebooks for dataset handling and analysis:
    * `dataset_analysis.ipynb`: A notebook for comprehensive analysis of the collected datasets.
    * `website_analysis_example.ipynb`: An example notebook demonstrating how to perform website analysis (e.g., using the UCI dataset).

* **`Refined_Datasets/`**: Our processed versions of the datasets in `.csv` format. Each refined dataset includes the original data columns, augmented with **7 additional valuable features**:
    * `Extracted URL`
    * `Message Len`
    * `FQDN` (Fully Qualified Domain Name)
    * `Website Size in KB`
    * `Website Textual Content Length`
    * `Status Code`
    * `Parked`

* **`URL_Data/`**: This directory stores all the **URLs extracted from the messages** across the various datasets.
    * **Note:** While multiple URLs per message are counted, the direct index of the messages corresponding to each URL was not preserved during extraction. However, this trace can still be achieved through brute-force techniques if needed.

## 🗄️ Original Dataset Sources

* **`Enron Email Spam (2006)`**: https://www.kaggle.com/datasets/wcukierski/enron-email-dataset
* **`English SMS (2011)`**: https://mtaufiqnzz.wordpress.com/british-english-sms-corpora/
* **`UCI ML Repo (2011)`**: https://archive.ics.uci.edu/dataset/228/sms+spam+collection
* **`ExAIS SMS Spam (2015)`**: https://github.com/AbayomiAlli/SMS-Spam-Dataset
* **`Mendeley Smishing (2022)`**: https://data.mendeley.com/datasets/f45bkkt8pr/1
* **`Super Dataset (2024)`**: https://github.com/smspamresearch/spstudy
* **`Kor-Smishing (2024)`**: https://github.com/Ez-Sy01/KOR_phishing_Detect-Dataset
* **`NUS Corpus (2011)`**: https://www.kaggle.com/datasets/rtatman/the-national-university-of-singapore-sms-corpus/data
* **`Spam Hunter (2022)`**: https://github.com/opmusic/SpamHunter_dataset
* **`SMS Gateways (2023)`**: https://github.com/wspr-ncsu/sms-phishing
* **`Smishtank (2024)`**: https://smishtank.com/dataset