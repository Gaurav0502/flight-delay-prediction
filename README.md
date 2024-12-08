# Multiclass classification of arrival delay of flights

## Aim

To explore tree-based models for the prediction of the arrival delay of aircrafts on US domestic routes by binning the arrival delay.

## Datasets

- The Airline Delay Dataset is available <a href="https://data.mendeley.com/datasets/j3z5bm7496/1">here</a>.

## Models Used

The following tree-based models are used from `sklearn`:

- Decision Tree
- Random Forest Classifier
- Gradient Boosting Classifier
- Histogram Gradient Boosting Classifier

## Directory structure

```bash
.
├── DelayData.csv
├── README.md
├── data-cleaning.ipynb
└── requirements.txt

1 directory, 4 files
```

## Instructions to execute the code

The `data-cleaning.ipynb` notebook can be used after completing the following steps:

- Download the dataset from the URL above.
- Ensure the dataset is named as `DelayData.csv` and in the location same as that of the notebook (refer the directory structure above).
- Install all the required modules from `requirements.txt`.

```bash
pip install -r requirements.txt
```
