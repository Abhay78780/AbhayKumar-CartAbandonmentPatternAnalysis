# Cart Abandonment Pattern Analysis

**Student:** Abhay Kumar  
**Program:** IBM SkillsBuild Data Analytics with AI Academic Internship Program  
**Conducted by:** BharatCares in association with AICTE

## Project description
A beginner-friendly Python data analytics project measuring cart abandonment, comparing device/customer/channel segments, visualizing cart value and reported reasons, and reviewing recovery emails.

## Dataset
- `Data/cart_abandonment_demo_dataset.csv`: 800-row synthetic demonstration dataset bundled so the notebook runs immediately. **It is not a Kaggle dataset**, and results must be described as illustrative.
- Kaggle source: [eCommerce behavior data from multi category store](https://www.kaggle.com/datasets/mkechinov/ecommerce-behavior-data-from-multi-category-store). The real dataset is event-level and may be very large; download from Kaggle after reviewing terms. It includes events such as `view`, `cart`, `remove_from_cart`, and `purchase`. Raw event data needs session aggregation before calculating abandonment.

## Technologies
Python, pandas, NumPy, Matplotlib, Jupyter Notebook / Google Colab.

## Files
- `AbhayKumar_CartAbandonmentPatternAnalysis.ipynb` — analysis notebook
- `requirements.txt` — dependencies
- `AbhayKumar_ProjectReport.docx` — report
- `README.md` — this guide
- `Data/cart_abandonment_demo_dataset.csv` — demo data

## Run in Google Colab
1. Upload the notebook to [Google Colab](https://colab.research.google.com/).
2. Run cells from top to bottom. When prompted, upload `cart_abandonment_demo_dataset.csv` from the `Data` folder.
3. Review the KPI table, charts, segment summaries, and recommendations.

## Run locally
1. Install Python 3.10+.
2. In a terminal opened in the project folder, run `pip install -r requirements.txt`.
3. Run `jupyter notebook`, open the notebook, and choose Run All.

## Important note
Do not present demo data results as findings from Kaggle or a real company. If using the Kaggle data, document the exact file/month used and preprocess event-level data into sessions first.
