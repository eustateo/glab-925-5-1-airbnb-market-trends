# GLAB 925.5.1 — Exploring Airbnb Market Trends Using AI Assistance

**Author:** Oscar Eustate

This Python notebook analyzes the supplied 2019 NYC Airbnb data, focusing on private rooms. It covers validated joins, data cleaning, missingness, pricing distributions, room-type inventory, price bands, IQR outliers, location comparisons, review recency, and exploratory correlations.

## Run in Google Colab

1. Upload `Oscar_Eustate_GLAB_925_5_1.ipynb` to [Google Colab](https://colab.research.google.com/).
2. Select **Runtime → Run all**.
3. The notebook attempts to download the three assignment files. If prompted, upload the original `airbnb_price.csv`, `airbnb_room_type.xlsx`, and `airbnb_last_review.tsv` files.
4. Review the generated tables, charts, and interpretations. Save the executed notebook before submitting it in Canvas.

## Run locally

Install Python dependencies with `python -m pip install -r requirements.txt`. Open the notebook in Jupyter or VS Code and run its cells. If downloads fail, place the three original source files in the notebook directory.

## Status and interpretation

The notebook is unexecuted against the original data because source downloads were unavailable in the authoring environment. Its calculation cells passed checks using synthetic fixtures; those fixtures are not included as lab results. Results and interpretations are generated from the real files when the notebook runs.

The dataset is a historical snapshot. Counts of each listing's latest review do not measure all reviews, bookings, seasonality, or changes in demand. Advertised prices do not establish realized revenue or profitability. AI assistance and verification steps are documented in the notebook.

## Assignment data sources

- [Prices — CSV](https://drive.google.com/file/d/1r9D6ElQHM4jL9ai7c-hjFpEqDwv0eHCr/view)
- [Room types — Excel](https://docs.google.com/spreadsheets/d/1wzpjNQiCtCsYZST4O7lNUB6KWe6AO01H/edit)
- [Latest reviews — TSV](https://drive.google.com/file/d/13D-XY_lY57XZaHirdlCb-dhOphQN9TWj/view)

Raw datasets are not included in this repository.
