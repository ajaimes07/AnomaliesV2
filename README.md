# AnomaliesV2
Four codes to calculate anomalies. Calculate anomalies of precipitation. 
INPUT. Data contained on a google drive folder named: data-PREC-1-year-day
Source: https://drive.google.com/drive/folders/0B3jfvAFKA3QEaUVhc1BUdHlDTG8?usp=sharing
Note: The process takes 3 days in calculating the final result. The directories need to be changed if new variables are desired to be used. 
CODE Description:
anomalies1.m 
% Source code. Reformats timestamp from year-day to format day_year
% This means, the output files contain a specific day but along 33 years

anomalies2.m 
Calculates "anomalies"
% It takes the data organized by day-year, computes the mean per
% day along 33 years and then subtract the observed daily value.

anomalies3_compute_percentile.m 
% This is third code to apply. Computes percentiles and store a
% 568x668 matrix with the values (color) of percentile.
% This code is very slow, it may take up to 24 hours to run

anomalies4_threshold_anomalies.m 
% This is fourth code to apply. It counts the # of events that are above or below the mean.
% display figures of anomalies


Functions:
mypercentile.m
