# Milwaukee County District Attorney Data

This repository contains aggregate data that populates the [Milwaukee County District Attorney Dashboard](https://data.mkedao.com/). Data are updated at monthly intervals with a month lag. For example, on December 1st, data will be current up until the end of October. This is due to a processing delay in the data.

Content on this repo will change as data and documentation are updated.

Data is organized into five directories: key indicators, referrals, charging, disposition, and sentencing. Each directory contains a table that corresponds to a chart on the dashboard.

## Data Sources

The administrative data sources that populate the dashboard draw from two sources: PROTECT and WCCA Rest Interface, commonly known as CCAP.

### PROTECT

Protect stands for Prosecutor Technology for Case Tracking and is Wisconsin's DA Case Management system. It interfaces with law enforcement and other criminal justice agencies including the Wisconsin Circuit Court. This system captures the outcome of each charge at each stage: referral, filed charge, convicted charge, and disposition (e.g. Guilty Due to Guilty Plea, Deferred Prosecution). It also captures data related to demographic information, individuals charged with crime, and data related to law enforcement that refer cases.

### WCCA Rest Interface

This WCCA REST Interface provides access to certain bulk access to public records of the Wisconsin circuit courts. The Milwaukee DA Dashboard populates metrics on disposition and sentencing from this interface.

### WCCA Disclaimer

This dashboard uses Wisconsin Court data made available through the WCCA REST Interface

The data or information provided is not the official records of the court. Data provided from WCCA Information may not reflect the most current disposition activity. Users should verify the data and information by consulting the official court record maintained by the court in question. The official custodian of all official circuit court records in Wisconsin is the clerk of circuit court or register in probate.
