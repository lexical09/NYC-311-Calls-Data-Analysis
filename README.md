# NYC-311-Calls-Data-Analysis

This Project is an analysis of NYC 311 calls dataset with 18,774,870 entries since 2010 from the [NYC OpenData website](https://nycopendata.socrata.com/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9).   

### Data
311 complaints were downloaded in bulk from New York City's open data portal and are not included in this repository due to their size (10GB). The dataset includes all 311 complaints filed in New York City from 2010 to 2018, and includes the following headers relevant to the analysis:

* `Created Date` — The date the complaint was received.
* `Incident Address` — The address associated with the 311 complaint
* `Complaint Type` — The main category of complaint. E.g., Noise - Residential or Noise - Street/Sidewalk.
* `Descriptor` — The subtype of complaint the complaint. E.g., Loud Music/Party or Loud Music/Party.
* `Resolution Description` — A categorical variable describing how the complaint was resolved . E.g., The Police Department responded to the complaint and took action to fix the condition..
* `Latitude` — Latitude of location associated with complaint.
* `Longitude` — Longitude of location associated with complaint.


### This Project answers the following major questions:
 
* Find Patterns in Data
* Display City and Complaint Type Together
* Find the top 10 complaint types
* Plot graph of count vs. complaint types
* Visualize major complaint types and their count

