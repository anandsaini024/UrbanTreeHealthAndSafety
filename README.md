# UrbanTreeHealthAndSafety
Monitoring trees' health status by combining data from in-situ IoT devices and EO satellites


Challenge 8 and 11

Guidline


1.Data
We have two source that collect two type of data. The objectiv here is to match the sources.

Source 1:
In SITU DATA :
   a. AQP (air quality)
   b. HTP (helath trees)
   
Source2:
Satellite DATA :
  a. S2 (helath trees): eg geolocalized numbers
  b. S3 (surface temperature): don't know if it's better to work with images or 
  c. S5P (air quality)
  d. HR Optical (not yet)

2. Make the super resolution
3. Single analyse tree

Objectif:

=======
Steps to do:
- reproduce the super resolution algoritms to mak ethem work on sentinel 2, 3 and 5p
- assemble and make the Health Tree Platform (HTP) working
- acquire in situ data from AQP, HTP and Public in situ data about trees and air quality,
- perform an AI image recognition model to find and geolocalize trees in an image
- get tree information from HTP, Sentinel 2, Sentinel 3 and sentinel 5p and merge them in a single database 
- use a final AI algorithm to determine healt and stability of each trees in the AOI
  

