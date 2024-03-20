Principle Investigator, Kaiser, Jennifer B.
Georgia Institute of Technology

Picarro G2307 Formaldehyde Measurements
01 Aug 2022 - 31 Jan 2023

Variables:
time_utc, Time of measurement in UTC timezone
hcho_ppb, Formaldehyde measurement reported by Picarro G2307. Averaged to 1 min from 1 Hz native time resolution. Calibrated using formaldehyde standard from Apel-Riemer on 8 Oct 2021 and Airgas standard on 13 Sep. 2022.

PI CONTACT INFO: Ford Environemntal Science & Technology Building, Rm 3324, Atlanta, GA 30332; jennifer.kaiser@ce.gatech.edu; 404-894-2644; https://eas.gatech.edu/people/kaiser
PLATFORM: Measured 5 m above ground, 8 m inlet line length (line is PTFE with 0.25 in OD), indoor portion of line heated to 115 deg F / 46 deg C, flow rate of 444.38 ccm with std of 0.20 ccm. From 28 July - 13 Sep. 2022, inlet line teed with Aeris Pico. Full setup description can be found in in Mouat et al. (2023) (accepted).
LOCATION: Environmental Protection Divison South Dekalb site: 2300-C Wildcat Road, Decatur GA 30034, Lat: 33.6878, Lon: -84.2905
INSTRUMENT INFO: Picarro G2307 Gas Concentration Analyzer; https://www.picarro.com/products/g2307_gas_concentration_analyzer
DATA INFO: All data in parts per billion (ppb), averaged to 1 min from 1 Hz. Processed using MATLAB R2023a.
UNCERTAINTY: Manufacturer reported measurement uncertainty for Picarro G2307 is +/- 10 %. Initial calibration (8 Oct. 2021) with Apel-Riemer standard has uncertainty of +/- 5 %, resulting measurement uncertainty is +/- 10 %. Second calibration (13 Sep 2022) conducted with Airgas standard with an uncertainty of +/- 10 %, resulting in 10 % uncertainty. Calibration slopes agree within 2.5 %. Instrument precision calculated using Allen-Werle curve and scrubbed air measurments. Data is reported here at 1 min time resolution with precision of 150 ppt.
DM CONTACT INFO: Asher P. Mouat; amouat3@gatech.edu
STIPULATIONS ON USE: Use of these data requires prior approval from the PI.
OTHER_COMMENTS: Missing periods result from spikes/drops in pressure or temperature, setup issues (e.g. H2O in inlet), exhaustion of HCHO scrubber used to determine instrument baseline, or other possible external influences tampering with data.
REVISION:
R0: Formaldehyde concentration time series measured at the Environmental Protection Division's South Dekalb site starting on 12 Oct. 2021. Initial version, processed on 12-12-2022 by A. P. Mouat (amouat3@gatech.edu)
R1: Humidity-correction applied to HCHO measurements via York regression. Resulting slope for >0.2 % H2O is -5.67 * (% H2O) and for <0.2 % H2O os -0.40*% H2O). Regressions determined from experimment conducted on 19 June 2023 with full description of setup and application of regressions provided in Mouat et al. (2023, submitted).
R1_b: Temporary dataset for a conference Jen is presenting at. Dataset is largely the same as R1 except that data between 17 - 29 June 2023 (normally calculated using DNPH) has been swapped out for values calculated using DR as the DNPH was dying during this period. Future releases will likely include both columns of data.
R2: Complete dataset used for Mouat et al. (2023). Measurements are averaged to 1 h with 5 min zeros taken hourly used to correct the baselines. The full time series is corrected using the June 2023 calibration. This regression is [HCHO]=(y+0.17)/0.93. Precision for these measurements is 90 ppt and uncertainty is 10%. Data switches at various points between being corrected with a zero determined using DR/DR+MS or DNPH. This was done to provide as full a time series as possible.
R3: Dataset averaged to 1 h time resolution per request of EPA.
R3_b: Dataset averaged to 1 min time resolution for public release.