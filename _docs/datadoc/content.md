---
title: Product Library
permalink: /docs/content/
---

Civic Mapper curated data and developed ArcGIS Online products for Carnegie Science Center use. Data curation included formatting all documents to be compatible with ArcGIS, simplifying spreadsheets, and filling in data gaps. This webpage outlines the resultant mapping products and their data sources.

# ArcGIS Online Maps

## STEMSTARSMapper

**Layers**
* STEMSTARS Student Count Jan-April
* STEMSTARS Student Count Oct-Dec
* STEMSTARS School Location Jan-April
* STEMSTARS School Location Oct-Dec
* STEMSTARS Student Participant Density
* STEMSTARS Student Participant Density
* US Public School Districts

**Description**

This map displays data pertaining to the STEM STARS program. Layers include school locations, rings with radius indicating number of student participants, and zip code polygons with color indicating total number of participating students per zip code. The year's data is split into two halves, and show which schools or zip codes grew participation or experienced diminished participation. A public school district layer is included as background information.

**Source Spreadsheets**
* 2016-2017 STEM Stars Attendance Tracker Jan-April-FINAL.xlsx
* 2016-2017 STEM Stars Attendance Tracker Oct-Dec-Final.xlsx

**Necessary Edits**
* Look up school locations
* Create school summary spreadsheet
* Create student summary spreadsheet
* Standardize school names

## FCC Team and School Data Map

**Layers**
* FCC Team Roster Data
* School Data 2017 - Locations
* School Data 2017 - PRSEF Count
* FCC Team Sum Student Count by Zip Code
* SchoolDataMapper - Zip Code Boundary
* SchoolDataMapper - U.S. Public School District Boundary

**Description**

This map displays FCC and PRSEF progam data at the school level and summarizes student participation by zip code. FCC Team roster data is symbolized by orange dots, while blue rings symbolize quantity of PRSEF program participants. Zip codes are shaded by number of total FCC Team participants.

**Source Spreadsheets**
* FCC Team Roster
* School Data - 2017
* School Data

**Necessary Edits**
* FCC Team Roster was joined to School Data by school name to geocode
* FCC Team Roster data was edited to contain one record per school with fields containing pertinent data
* School location data was verified

## CSC_TYF_FL_TEA_Map

**Layers**
* Fab Lab and TEA by Zip
* TYF by Zip

**Description**

This map displays Fab Land and TEA participant count per zip code and TYF participant count by zip code. 

**Source Spreadsheets**
* 16 Sept - 17 June CSC STEM Programs Summary - SiriusWare

**Necessary Edits**
* Delete  empty  rows  or  rows  without  ZIP  data
* Make  sure  ZIP  codes  are  stored  as  number 

## CSC STEM Program Map

**Layers**
* Median Household Income (Living Atlas Public)
* CSC STEM - Fab Lab and TEA by Zip
* CSC STEM - TYF by Zip
* FY18_FNS_CACFP_SFSP_Eligibility (USDA)
* School District Boundaries (PennDOT)
* School District Boundaries (Allegheny County)
* Municipal Boundaries(Allegheny County)
* 2017 USA Education Spending (Living Atlas Premium)

**Description**

This map overlays CSC Fab Lab and TEA by Zip and TYF by Zip layers on relevant background layers, allowing the user to develop an idea about participant school socioeconomic conditions.

**Source Spreadsheets**
* 16 Sept - 17 June CSC STEM Programs Summary - SiriusWare

## CSC_CRCC_Map

**Layers**
* CSC_CRCC_Geocode
* CSC_CRCC_ByZip

**Description**

This map displays CRCC participants by school location and zip code. Rings show location of participating schools, with radius indicating number of participants. Zip codes are shaded according to total number of student participants.

**Source Spreadsheets**
* 2016-17 CRCC School Data

**Necessary Edits**
* Simplify  Field  Names  by  removing  punctuation  and  spaces  and  shortening  
* Store  Zipcodes  as  Number  
* Verify  addresses  are  correct 

## CRCC_WebMap

**Layers**
* 2016 - 2017 CRCC School Locations
* Number of Students participating in CRCC per Zip Code
* Zip Code Area

**Description**

This map displays CRCC program participation by school location and zip code.

**Source Spreadsheets**
* 2016-17 CRCC School Data

## CSCProgramsByZip

**Layers**
* CRCC Schools Student Numbers
* FCC Teams Student Numbers
* SOR Surveys
* TYF Locations
* FabLab and TEA Locations
* STEMSTARS Locations (OCT - DEC)
* STEMSTARS Locations (JAN - APR)
* Program Zipcode Totals
* CRCC Zip Sum
* FCC Zip Sum
* SOR Zip Sum
* TYF Zip Sum
* FL and TEA Zip Sum
* STEMSTARS Zip Sum
* Program Zipcode Totals
* Zipcodes

**Description**

This map displays the locations of all CSC programs. These include:
* CRCC Schools
* FCC Teams
* SOR Surveys
* FabLab and TEA Locations
* STEMSTARS Locations

The map also contains layers displaying the sum of participants for each program individually by zip code, as well as an overall zip code summary layer comprising all programs. The overall zip code summary layer is displayed in two different ways, by size of orange circle, and by color of polygon. Click on a zip code to see its statistics.

**Source Spreadsheets**
* 16 Sept - 17 June CSC STEM Programs Summary - SiriusWare
* 2016-17 CRCC School Data
* 2016-2017 STEM Stars Attendance Tracker Jan-April-FINAL
* 2016-2017 STEM Stars Attendance Tracker Oct-Dec-Final
* FCC Team Roster
* pathway_report_200917
* School Data - 2017
* School Data

**Necessary Edits**
* All data simplified to contain participant number and zip code
