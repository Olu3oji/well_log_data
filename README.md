# Well Log Data Analysis

This project focuses on exploratory data analysis (EDA) of well log data. The well log data was initially saved as a LAS file and converted to a Pandas DataFrame using the `lasio` library. The dataset consists of various columns representing different log measurements.

## Dataset Description

The dataset contains the following columns:

- `CABLE TENSION`
- `ANALOG SPONTANEOUS POTENTIAL`
- `NATURAL GAMMA`
- `NEUTRON POROSITY`
- `DSN NEAR COUNTS`
- `DSN FAR COUNTS`
- `DSN (NDSN/FDS) RATIO`
- `HRI DEEP RESISTIVITY`
- `HRI MEDIUM RESISTIVITY`
- `HI DEEP CONDUCTIVITY`
- `DIGITALLY FOCUSED LATEROLOG`
- `BULK DENSITY`
- `DENSITY CORRECTION`
- `PHOTO-ELECTRIC FACTOR`
- `FAR QUALITY`
- `NEAR QUALITY`
- `DENSITY POROSITY`
- `CALIPER`

## EDA

The provided code performs EDA on the dataset. 
The main objectives of this EDA are as follows:

1. Gain a better understanding of the distribution and characteristics of each log measurement in the dataset.
2. Identify any outliers, missing values, or data quality issues that may require further investigation and preprocessing.
3. Explore relationships and correlations among different log measurements to uncover potential dependencies or patterns.
4. Determine if any log measurements exhibit significant variations or trends with respect to depth or other factors.
5. Provide preliminary insights and visualizations that can guide subsequent analysis and decision-making.

To run the EDA code, make sure you have the following dependencies installed:

- Python 3
- pandas
- matplotlib

You can modify the code by replacing `'path_to_your_csv_file.csv'` with the actual file path of your well log data in CSV format.

## Conclusion

The EDA results provide insights into  each log measurement in the dataset. These findings can serve as a foundation for further analysis and modeling tasks.


