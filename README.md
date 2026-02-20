# Osteoporosis Risk Prediction (Unified Repository)

This repository combines two source projects into one place:

1. `app/`:
   Streamlit osteoporosis prediction application (UI + trained model).
2. `analysis/`:
   NHANES data analysis and model development notebooks/utilities.

## Source Repositories

- App project: https://github.com/eeliuqin/osteoporosis-prediction-app
- Analysis project: https://github.com/eeliuqin/Osteoporosis-Analysis-and-Prediction-on-NHANES-Data

## Structure

```text
.
├── app/
│   ├── app.py
│   ├── model/
│   ├── utils/
│   ├── data/
│   ├── css/
│   └── requirements.txt
├── analysis/
│   ├── predict-osteoporosis.ipynb
│   ├── data/
│   ├── images/
│   └── *_utils.py
└── README.md
```

## Run the App

```bash
cd app
pip install -r requirements.txt
streamlit run app.py
```

## Notes

- The two projects are preserved in separate folders to avoid filename collisions.
- Exact duplicate files were checked during merge.
