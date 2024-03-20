Principle Investigator, Kaiser, Jennifer B.
Georgia Institute of Technology

Aeris Ultra Formaldehyde Measurements
01 Aug. 2022 - 31 Jan. 2023

Variables:
time_utc, Time of measurement in UTC timezone
hcho_ppb, Formaldehyde measurement reported by Aeris HCHO. Averaged to 1 min from 1 Hz time resolution. The instrument was set to sample ambiently for 180 s and then sampled through a DNPH HCHO-scrubber for 30 s. Standard additions were conducted using formaldehyde standards from Apel_Riemer in Oct 2022 and Airgas in Sep. 2023.

PI CONTACT INFO: Ford Environemntal Science & Technology Building, Rm 3324, Atlanta, GA 30332; jennifer.kaiser@ce.gatech.edu; 404-894-2644; https://eas.gatech.edu/people/kaiser
PLATFORM: Measured 3 m above rooftop ground, 5 m inlet line length (line is PTFE with 0.25 in OD), indoor portion of line insulated with fiberglass sleeve, flow rate of 756.73 ccm with std of 1.77 ccm. Full setup description can be found in in Mouat et al. (2023) (accepted).
LOCATION: Ford Environmental Science and Technology, 311 Ferst Dr NW, Atlanta, GA 30332, Lat: 33.778386047268725, Lon: -84.39623942837747
INSTRUMENT MIRA Ultra Gas Analyzer; https://aerissensors.com/ultra-series/
DATA INFO: All data in parts per billion (ppb), averaged to 1 min. Processed using MATLAB R2023a.
UNCERTAINTY: Shutter et al. (2019) (https://doi.org/10.5194/amt-12-6079-2019) determined an uncertainty of 10% + 0.3 ppb. Airgas HCHO standard has uncertainty of +/- 10 %, resulting measurement uncertainty is 14% + 0.3 ppb. Standard addition slopes agree within 10% of manufacturer calibration. Instrument precision calculated using Allen-Werle curve and scrubbed air measurments (Mouat et al. 2024). Data is reported here at 1 min time resolution with precision of 0.24 ppb.
DM CONTACT INFO: Asher P. Mouat; amouat3@gatech.edu
STIPULATIONS ON USE: Use of these data requires prior approval from the PI.
OTHER_COMMENTS: Missing periods result from spikes/drops in pressure or temperature, setup issues, exhaustion of HCHO scrubber used to determine instrument baseline, power outages, instrument issues with laser-locking, or other possible external influences tampering with data.
REVISION:
R0: Formaldehyde concentration time series measured at the Ford Environemntal Science & Technology Building site starting on 25 Jul. 2022. Initial version, processed on 6-9-2023 by A. P. Mouat (amouat3@gatech.edu). PLEASE NOTE: data in this particular iteration will likely be subject to a correction after further calibration and intercomparison between the Pico, the Ultra, and the Picarro is conducted, and is therefore not finalized.
R0_b: Formaldehyde concentration time series measured at the Ford Environemntal Science & Technology Building site starting on 25 Jul. 2022. The Pico v Ultra time series regression is used to correct the 3 min average, differential HCHO data reported by the Ultra i.e. y=1.27*[HCHO_Ultra]+0.24. This is not a final correction to this data.
R1: Formaldehyde concentration time series measured at the Ford Environemntal Science & Technology Building site starting on 25 Jul. 2022. The 2023 standard addition calibration conducted for the Ultra is used to correct the 3 min integrated, differential HCHO data. The regression applied is [HCHO]=(y-0.28)/0.77.
R2: Data averaged to 1 h resolution per the request of the EPA.
R2_b: Data averaged to 1 minute resolution for public release.