# AnomaliesV2
Four codes to calculate anomalies. This calculates anomalies of precipitation, using input data contained on a google drive shared  data-PREC-1-year-day. The process takes 3 days in calculating the final result. The directories need to be changed if new variables are desired to be used. 
CODES:
anomalies1.m 
% This is first code to apply. This code takes data which is stored in
% original format year-day and accomodate it in format day_year
% This means, the output files contain a specific day but along 33 years


anomalies2.m 
% This is second code to apply. It generates the "anomalies"
% Tath is, it takes the data organized by day-year, computes the mean per
% day along 33 years and then subtract it to the day. As a result, the data
% is now from - sign values to + sign values



anomalies3_compute_percentile.m 



anomalies4_threshold_anomalies.m 

Functions:
mypercentile.m
