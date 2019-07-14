![IronHack Logo](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_d5c5793015fec3be28a63c4fa3dd4d55.png)

# Project: Data Cleaning and Manipulation with Pandas - MET Data

## Overview

The goal of this project is to apply the learned data wrangling, cleaning, and manipulation techniques with Pandas. For this project, I have chosen the following dataset: 

* [Met objects](https://github.com/metmuseum/openaccess/)

This is data that comes from the Metropolitan Museum of Art of New York City and contains information on ~500,000 art and archeological pieces from different departments of the museum.

---

## Cleaning Steps:
In the enclosed jupyter notebook file, I have applied the following steps for data cleaning:
1. Import Libraries and Dataset
2. Find and Remove Duplicates
3. Identify and Deal with Null Fields
4. Standardize and Clean Text Information
5. Check and Change Data Types
6. Examine Categorical Variables
7. Rename and Order Columns
8. Export CSV File

## Methods used:
During the work, I have used the following methods and functions:
- pd.read_csv()
- drop(), drop_duplicates()
- value_counts(), count()
- is_null()
- groupby()
- fillna()
- concat()
- rename()
- apply()
- str.replace()
- get_dummies()
- describe()
- cut()
- to_csv()

## Final Data Structure

After the cleaning, the dataset has the following variables:

Column Title | Type of Data | Description
___ | ___ | ___
'Object ID'| int | consecutive unique ID
'Object Name' | str | descriptive name of the object
'Title' | str | title of art piece
'Authorship' | str | individual or collective author
'Nationality' | str | origin of artist
'Artist Role' | str | type of contribution
'Artist Begin Date' | int | year of birth/foundation of artist or institution 
'Artist End Date' | int | year of death of artist or institution
'Object Begin Date' | int | estimate year of production (1st)
'Object End Date' | int | estimate year of production (range)
'How Old' | str | categorical, from Oldest to New
'Medium' | str | material of which the object is made
'Credit Line' | str | 
'Classification' | str |  classification
'Dimensions' | str | dimensions of the object inches and cm
'Is Highlight' | bool |
'PubDomain' | bool | True if in public domain; False if not in public domain
'Not In Public Domain' | bin | 1 if not in public domain 
'In Public Domain' | bin | 1 if in public domain
'Department' | str | categorical, department of the museum
'D: American Decorative Arts' | bin | 1 if in department
'D: Ancient Near Eastern Art' | bin | 1 if in department
'D: Arms and Armor' | bin | 1 if in department
'D: Arts of Africa Oceania and Americas' | bin | 1 if in department
'D: Asian Art' | bin | 1 if in department
'D: Costume Institute' | bin | 1 if in department
'D: Drawings and Prints' | bin | 1 if in department
'D: Egyptian Art' | bin | 1 if in department
'D: European Paintings' | bin | 1 if in department
'D: European Sculpture' | bin | 1 if in department
'D: Greek and Roman Art' | bin | 1 if in department
'D: Islamic Art' | bin | 1 if in department
'D: Medieval Art' | bin | 1 if in department
'D: Modern and Contemporary Art' | bin | 1 if in department 
'D: Musical Instruments' | bin | 1 if in department
'D: Photographs' | bin | 1 if in department
'D: Robert Lehman Collection' | bin | 1 if in department
'D: Cloisters' | bin | 1 if in department
'D: Libraries' | bin | 1 if in department
'Link Resource' | str | link for the object in the museum website
'Tags'| str | keywords related to the object


