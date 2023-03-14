# Data 

---

## Source

1. [Bureau of Transportation Statistics Airline On-Time Performance Data](https://www.transtats.bts.gov/Fields.asp?gnoyr_VQ=FGJ)

2. [Bureau of Transportation Statistics Airline DOT ID Mappings](https://www.transtats.bts.gov/FieldInfo.asp?Svryq_Qr5p=N0%FDvqr06vsvpn6v10%FD07zor4%FDn55vt0rq%FDoB%FDhf%FDQbg%FD61%FDvqr06vsB%FDn%FD70v37r%FDnv4yv0r%FD%FLpn44vr4%FM.%FDN%FD70v37r%FDnv4yv0r%FD%FLpn44vr4%FM%FDv5%FDqrsv0rq%FDn5%FD10r%FDu1yqv0t%FDn0q%FD4r2146v0t%FD70qr4%FD6ur%FD5nzr%FDQbg%FDpr46vsvpn6r%FD4rtn4qyr55%FD1s%FDv65%FDP1qr%FP%FDanzr%FP%FD14%FDu1yqv0t%FDp1z2n0B/p14214n6v10.&Svryq_gB2r=a7z&Y11x72_gnoyr=Y_NVeYVaR_VQ&gnoyr_VQ=FGJ&flf_gnoyr_anzr=g_bagVZR_eRcbegVaT&fB5_Svryq_anzr=bc_PNeeVRe_NVeYVaR_VQ)

3. [Bureau of Transportation Statistics Airport DOT ID Mappings](https://www.transtats.bts.gov/FieldInfo.asp?Svryq_Qr5p=b4vtv0%FDNv42146%FP%FDNv42146%FDfr37r0pr%FDVQ.%FDN0%FDvqr06vsvpn6v10%FD07zor4%FDn55vt0rq%FDoB%FDhf%FDQbg%FD61%FDvqr06vsB%FDn%FD70v37r%FDnv42146%FDn6%FDn%FDtv8r0%FD21v06%FD1s%FD6vzr.%FD%FDNv42146%FDn664vo76r5%FP%FD57pu%FDn5%FDnv42146%FD0nzr%FD14%FDp114qv0n6r5%FP%FDznB%FDpun0tr%FD18r4%FD6vzr.&Svryq_gB2r=a7z&Y11x72_gnoyr=Y_NVecbeg_fRd_VQ&gnoyr_VQ=FGJ&flf_gnoyr_anzr=g_bagVZR_eRcbegVaT&fB5_Svryq_anzr=beVTVa_NVecbeg_fRd_VQ)

## Usage

1. Main data set containing airline on-time performance data (Nov. 2021 - Nov. 2022)

2. Model numerical subsitution for strings, thi table is ued to verify the values on table (1)

3. Model numerical subsitution for strings, thi table is ued to verify the values on table (1)

## Processed Data
These are the output of scripts

`ORD_11_21-11_22.csv (data_agg.ipynb)` - ORD subset of DOT data, not clean

`ORD_11_21-11-22_short.csv (eda.ipynb)` ORD subset of DOT data with no diversion information

`ORD_11_21-11-22_model.csv (model_prep.ipynb)` ORD subset of DOT data with model level cleaning applied, all non-number values are replaced with numerical mappings

## Custom Data
This data may be made by a script or by hand

`blk_mapping.csv` - contains mapping of time blocks mapped to integers, used in modeling
