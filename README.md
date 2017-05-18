# MOMENT-Study
This repository contains MOMENT data documentation. 

Four datasets are received as of May 18, 2017. 

**_20170505-screener_bl_fu_wlabel_fmt12oct16-no PII.dta_**

Screener, baseline, and follow up surveys for all 118 participants. _id_no_ is participants' unique identifier and can be used to merge with EMA and tracking data. All variables are documented in the codebook (_Moment Study Unified Codebook 030717_). 

**_20160920 - Moment Study - Screener - ok to recontact.xlsx_**

Complete screener with participants' name and email. Variables are documented in the codebook as well. The only issue is there's no identifier to link personal data to other available datasets. 

**_ema_self_random11jul16.dta_**

Random EMAs responded by participants. _ID_no_ is participants' unique identifier. Variables are documented in the codebook. Many responses have geolocations but the accuracy is low due to technical issues. 

**_Final_Geotracking_20170126.csv_**

Cleaned geotracking for participants. Data can be merged with screener and ema through _device_code_ after extracting numbers. 
