DB 0.08 November 15, 2019
(1) updated QC so SCFA measurements with n < 2 were not included in mean and median calculations.
(2) Cleaned up comments so student notes no longer appear in final version of files 
(3) retained comments that would be of interested to researchers, found under individual descriptive columns
(4) no longer dropping pH measurements that were self-reported by students as urine contaminated 

DB 0.07 November 7, 2019
(1) fixed inconsistencies for frequency for Fall2016 across various files
(2) add columns to indicate fasting or non-fasting breath measurement
(3) add minimum number of samples for pH and Bristol (>1 per week)
(4) Changed QC for breath: CO2 < 2 excluded; combinations of CO2+Corr for range of CO2 values from 2-7.9 
(5) sorted final files by participant IDs (U100 - U799) 
(6) update methanogenic classifications; missing data no longer causes mean calculation to result in NaN, now indicated by NA

DB 0.06 October 25, 2019: 
(1) updated frequency information for Fall 2016 semester (BRMPS = 2x). 
(2) removed filtering for compliance. 
(3) fixed errors when filtering for individuals with too few measurements. (4) fixed error with SCFA joins - was dropping participants who had an "NA" for one SCFA measurement. 
(5) updated plates maps for U054, U076, U079, U750.
(6) updated adjusted methane calculation (substract 2ppm from all).

DB 0.05 August 28, 2019: 
updated frequency information for Fall16 semester

DB 0.04 August 2, 2019: 
updated SCFA data

DB 0.03 July 31, 2019: 
updated SCFA data as follows: 
(1) verified standards drifted in expected direction, no sample areas could fall outside the range of standards 
(2) identified extreme outliers and removed them from mean/median calculations of participants
(3) Participants must have at least 2 samples per week to be included in weekly mean/median calculations 

DB 0.02 July 24, 2019: 
updated SCFA data

DB 0.01 July 21, 2019:
Initial version of MMP undergraduate database
