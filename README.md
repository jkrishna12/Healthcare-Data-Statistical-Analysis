# Healthcare-Data-Statistical-Analysis
The healthcare dataset is the result of a Pharmaceutical companies randomised drug trial. This project performs three hypothesis tests on the dataset. The first one aims to see whether the proportions of the adverse effects in the drug and placebo groups are different. The second determines whether the drug and placebo groups are indpenedent of the number of effects. Finally, the third checks whether the distribution of the age variable for the two groups are different. The dataset is explained in the table below:

| Column | Description |
|--------|-------------|
|`sex` | The gender of the individual |
|`age` | The age of the individual |
|`week` | The week of the drug testing |
|`trx` | The treatment (Drug) and control (Placebo) groups | 
|`wbc` | The count of white blood cells |
|`rbc` | The count of red blood cells |
|`adverse_effects` | The presence of at least a single adverse effect |
|`num_effects` | The number of adverse effects experienced by a single individual |

# Techniques
- Created visualisations using seaborn to support findings from hypothesis test
- Used statsmodels to implement a two sample proportional z test
- Leveraged Pingouin library to perform chi2 independence and normality test
- Conducted Wilcoxon Mann Whitney test to compare distributions
