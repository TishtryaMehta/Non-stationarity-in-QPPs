# Non-stationarity-in-QPPs
Data and code associated with non-stationarity in Quasi-periodic pulsations (QPPs) study.

The .csv file in this repository called "period_drifts_in_M_X_class_QPPs_MNRAS.csv" contains 21 columns, and 98 rows (not inc. header) 
It details the 98 flares assessed for QPP non stationarity in Mehta et al., 2022b, (Submitted to MNRAS). All flares are M- or X- class and are from solar cycle 24, of which some are associated with coronal mass ejections. 

The table contains the following:

#ID number: Unique ID number for each flare from 1-98 inclusive. (Integer)

Date: The date on which the flare began. Given in YYYY-MM-DD format. (String)

t_start: The time at which the flare began. Given in HH:MM:SS. (String)

t_end: The time at which the flare ends. Given in HH:MM:SS. Flares that continued until the following day are followed by ***. (String)

t_peak: The time at which the flare reached its maximal flare energy as seen in the 1--8 Angstrom channel. Given in HH:MM:SS. (String)

duration: The duration of the flare in seconds (rounded to the nearest second). (Integer)

goes_class: The goes class of the flare. (String)

CME: Flag to indicate whether a CME is associated with the flare. 1= CME, 0 = No CME. (Integer)

period_average: The average period obtained by taking the mean of the impulsive phase period and decay phase period, given in seconds. (Float)

period_average_plus_error: The plus error associated with period_average, given in seconds. (Float)

period_average_neg_error: The minus error associated with period_average, given in seconds. (Float)*

impulsive_period: The period detected for the impulsive phase of the flare, given in seconds. (Float)

impulsive_plus_error: The plus error associated with impulsive_period, given in seconds. (Float)

impulsive_neg_error: The minus error associated with impulsive_average, given in seconds. (Float)*

decay_period: The period detected for the decay phase of the flare, given in seconds. (Float)

decay_plus_error: The plus error associated with decay_period, given in seconds. (Float)

decay_neg_error: The minus error associated with decay_average, given in seconds. (Float)*

period_drift: Calculated as (decay_period – impulsive_period), given in seconds. (Float)

period_drift_plus_error: The plus error associated with period_drift, given in seconds. (Float)

period_drift_neg_error: The minus error associated with period_drift, given in seconds. (Float)*

pd_non_sig_flag: Flag indicating whether the period drift is not statistically significant (less than 4.09 seconds). 1= Not statistically significant, 0= Statistically significant. (Integer)

* Note that all the negative errors already have the associated minus sign.

Please cite (Mehta et al., 2022b) if you make use of this database. 
