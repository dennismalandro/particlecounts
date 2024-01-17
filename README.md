##  Cleanroom Particle Count Analyzer

### Description

The script summarizes and plots particle concentrations over a user-specified date range and calculates alert and action levels for cleanrooms and areas within them

- JSL File: "Analyze Clean Room Particle Counts.jsl"

- Version: 0.2

- Author: Dennis Malandro

- Url: TBD

### Input files

The scripts requires the hree input files (examples of which are in the "testing" folder in the file's git repository at TBD)


- Particle-count data

    - The file name contains the string "Particle Count Data.xls"

    - The file name contains the cleanroom number, which musts start with "CLEAN" (_e.g._, "CLEANROOM-1", "CLEANBENCH-1001")
    
    - It has columns "Date Time", "Area", "Location Name", "Counts 2 Cumulate", "Counts 5 Cumulate", "Volume"
    
    - It's an Excel spreadsheet
  
- Production area type lookup table

    - It has columns "Area", "Location Name", "Room Number", "Producton Area Type"
    
- Alert and action levels lookup table

    - with columns "Area", "Room Number", "Producton Area Type", and historical alert and action levels 


