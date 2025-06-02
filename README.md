# Exploratory-Data-Analysis-EDA-

Hisplot:

There is a sharp spike at around age 29–30, with a significantly higher count (~240). This suggests a large number of entries with this specific age, possibly due to data entry defaulting, imputation, or a bulk update.

The overall distribution is skewed to the right (long tail to older ages), meaning there are more younger individuals, and fewer as age increases.

The ages span from 0 up to about 80 years.


Pairplot:

A strong spike at around age 29–30 appears again — possibly due to data imputation or defaulting

The distribution is right-skewed (common in economic data).

Majority of passengers are in 3rd class, followed by 1st and then 2nd.

Some high fares are paid by older passengers, possibly those in 1st class.

Heatmap:
Color intensity indicates value magnitude (darker = lower, lighter = higher).

Some rows are entirely black for Age, suggesting missing age values.

High-fare passengers are sparse and likely belong to 1st class.

Boxplot:

Consistent with earlier histograms: most ages are clustered around 20–40, and a suspicious spike may indicate default imputation (e.g., age 29–30).

These high fares likely correspond to passengers in 1st class.

The color bar confirms that Fare reaches above 500, which is rare but present.


Scatter plot:
Noticeable horizontal black lines represent missing Age values (likely NaN), confirming incomplete data in this feature.

Majority of Fares are in the low-to-mid range (darker colors).

Missing data is more prominent in Age than in Fare.





