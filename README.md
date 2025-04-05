# Amazon Listing Optimizer

This repository contains a prototype for an NLP-based Listing Optimization Engine designed to enhance Amazon product listings. It extracts high-performing keywords from ad campaign data and generates optimized titles and descriptions, as part of an assignment submission.

## Overview

The project processes a dataset with campaign performance metrics (e.g., clicks, conversions) and associated keywords. Using NLP techniques like lemmatization and optional Named Entity Recognition (NER), it ranks keywords and creates listings focused on a single product with a complementary description.

### Sample Output
- **Keyword + Lemmatization:**  
  - **Title:** Samsung Galaxy Watch  
  - **Description:** Enjoy seamless pairing with our premium Samsung wireless earbuds for top performance and style.  

- **NER-Enhanced:**  
  - **Title:** Samsung Galaxy Watch  
  - **Description:** Optimized for use with our premium Samsung wireless earbuds thanks to advanced recognition technology.

## Files
- `Amazon_Listing_Optimizer.ipynb`: Jupyter notebook with the full Python implementation, including data processing, keyword ranking, and listing generation.

## Usage
1. Open the `.ipynb` file in Jupyter Notebook or Google Colab.
2. Run the cells to see the keyword extraction and listing optimization in action.
3. The script outputs results to `optimized_listing.csv`.

## Notes
- Built with Python, using basic NLP operations (e.g., lemmatization) and a mock dataset.
- Research included exploring DistilBERT for keyword ranking (BERT viable with more resources) and NER for branded term enhancement.

For details, refer to the assignment report submitted alongside this repository.
