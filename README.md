Common Data Model v5.2
=================

See full CDM specification file on our github [wiki](https://github.com/OHDSI/CommonDataModel/wiki) or in the [CDM V5.2 PDF](**link needed**)


Release Notes for v5.2.0
=============
This version is based on the CDM working group proposals:
* [#71](https://github.com/OHDSI/CommonDataModel/issues/71) 
  * Adds the field VERBATIM_END_DATE to DRUG_EXPOSURE and makes DRUG_EXPOSURE_END_DATE a required field

and is **backwards compatibile with v5.0.1**. The proposed and accepted changes include adding a datetime field to every table that had a date column and adding field DENOMINATOR_VALUE to the DRUG_STRENGTH table. These were the new columns added:


---------
  
This repo contains the definition of the OMOP Common Data Model. It supports the 4 SQL technologies: Impala, Oracle, Postgres and SQL Server. For each, the DDL, constraints and indexes (if appropriate) are defined. 

Versions are defined using tagging and versioning. Full versions (V6, 7 etc.) are released each year (1-Jan) and are not backwards compatible. Minor versions (V5.1, 5.2 etc.) are released each quarter (1-Apr, 1-Jul and 1-Sep) and are not guaranteed to be backwards compatible though an effort is made to make sure that current queries will not break. Micro versions (V5.1.1, V5.1.2 etc.) are released irregularly and often, and contain small hot fixes or backward compatible changes to the last minor version.
