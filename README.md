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