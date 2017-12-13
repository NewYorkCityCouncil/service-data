# service-data
Snapshot of data from City Council District Offices 
<br>
Dataset updated daily - https://data.cityofnewyork.us/City-Government/NYC-Council-Constituent-Services/b9km-gdpy

## DATA SET
From Woodlawn to Coney Island, each New York City neighborhood is part of a Council district. New York City has 51 of these districts, and each is represented by an elected Council Member. 

In addition to its city-wide functions (legislative, financial, and land use), the City Council is also your advocate regarding local City matters. District Offices in all 51 districts help residents with a wide range of issues, from food stamps and affordable housing, to potholes and pedestrian safety.  Council Member District Office staff work with residents to resolve tough issues, and gather resident input. 

City Council offices have access to software that tracks their constituent case load (the issues they are helping residents with). This dataset aggregates the information that individual staff have input. However, district staffs handle a wide range of complex issues.  


## FIELDS

### Case #	
Case # is the case number of the constituent casework. This is unique to Account, but not unique over all Accounts.
For instance, NYCC01 may have case # "123456" and NYCC36 may also have case # "123456", but they are different cases, unique to each Account.
This is generated automatically.

### Account	
Account is the Council District that created the casework, this may or not be the district that the constituent lives in. 
This is generated automatically.

### General Issue	
General Issue is the broader category designated by staff for the constituent casework.

### Specific Complaint	
Specific Complaint is the more specific category designated by staff for the constituent casework.

### Open Date	
Open Date is the date the casework is created by staff.

### Close Date	
Close Date is the date the casework was closed.  A casework could be closed because the issue is resolved or because nothing else could be done for constituent. 

### Zip	
Zip code of the constituent

### Borough	
Borough of the constituent

### City	
City of the constituent

### Council Dist.	
Council District of the constituent

### Comm. Bd.
Community Board of the constituent
