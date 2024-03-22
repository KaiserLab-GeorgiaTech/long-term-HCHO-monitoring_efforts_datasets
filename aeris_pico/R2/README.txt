Principle Investigator, Kaiser, Jennifer B.
Georgia Institute of Technology

Aeris Pico Formaldehyde Measurements
01 Aug 2022 - 01 Jan 2023

Variables:
time_utc, Time of measurement in UTC timezone
hcho_ppb, Formaldehyde measurement reported by Aeris HCHO. Averaged to 1 min from 1 Hz native time resolution. The instrument was set to sample ambiently for 180 s and then sampled through a DNPH HCHO-scrubber for 30 s. Standard additions conducted using formaldehyde standards from Airgas during Oct 2022 and Sep 2023.

PI CONTACT INFO: Ford Environemntal Science & Technology Building, Rm 3324, Atlanta, GA 30332; jennifer.kaiser@ce.gatech.edu; 404-894-2644; https://eas.gatech.edu/people/kaiser
PLATFORM: Measured 5 m above ground, 8 m inlet line length (line is PTFE with 0.25 in OD), indoor portion of line insulated with fiberglass sleeve, average flow rate of 450 ccm with std of 0.20 ccm. From 28 July - 13 Sep. 2022, inlet line teed with Picarro G2307. Full setup description can be found in in Mouat et al. (2023).
LOCATION: Ford Environmental Science and Technology, 311 Ferst Dr NW, Atlanta, GA 30332, Lat: 33.778386047268725, Lon: -84.39623942837747
INSTRUMENT MIRA Pico Gas Analyzer; https://aerissensors.com/pico-series/
DATA INFO: All data in parts per billion (ppb), averaged to 1 min. Processed using MATLAB R2023a.
UNCERTAINTY: Shutter et al. (2019) (https://doi.org/10.5194/amt-12-6079-2019) determined an uncertainty of 10% + 0.3 ppb. Airgas HCHO standard has uncertainty of +/- 10 %, resulting measurement uncertainty is 14% + 0.3 ppb. Standard addition slopes agree within 10% of manufacturer calibration. Instrument precision calculated using Allen-Werle curve and scrubbed air measurments (Mouat et al., 2023). Data is reported here at 1 min time resolution with precision of 410-660 ppt.
DM CONTACT INFO: Asher P. Mouat; amouat3@gatech.edu
STIPULATIONS ON USE: Use of these data requires prior approval from the PI.
OTHER_COMMENTS: Missing periods result from spikes/drops in pressure or temperature, setup issues, exhaustion of HCHO scrubber used to determine instrument baseline, power outages, instrument issues with laser-locking, or other possible external influences tampering with data.
REVISION: R0
R0: Formaldehyde concentration time series measured at the Ford Environemntal Science & Technology Building site starting on 25 Jul. 2022. Initial version, processed on 24-7-2023 by A. P. Mouat (amouat3@gatech.edu). PLEASE NOTE: data in this particular iteration will likely be subject to a correction after further calibration and intercomparison between the Pico, the Ultra, and the Picarro is conducted, and is therefore not finalized.
R0_b: Temporary dataset being used for a conference Jen is presenting at in July 2023. A week of data in July 2023 is included that uses only 15-20 sec averages to generate points rather than the usual 3 min average.
R1: Complete ambient time series of the Aeris Pico at Ford ES&T. Data is integrated to 3 min after subtracting out a 30 s integrated zero (determined by sampling through DNPH-coated cartridges) and corrected using the 2023 Pico standard addition calibration described in Mouat et al. (2023). The regression is [HCHO]=(y-0.16)/0.97. Precision is determined to be 0.40 ppb per the 30 s zeros used to calculate the final concentrations.
R2: Ambient time series of the Aeris Pico presented in Mouat et al. (2024). From 1 Aug - 12 Sep 2022, the Pico is stationed at the SDK site. Afterwards, the Pico is stationed at the GT site. Data is integrated to 1 min after subtracting out a 30 s integrated zero (determined by sampling through DNPH-coated cartridges) and corrected using the 2023 Pico standard addition calibration described in Mouat et al. (2023). The regression is [HCHO]=(y-0.16)/0.97.