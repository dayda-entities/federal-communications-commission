---
title: Geography Lookup Table
created: '2020-11-12T13:20:28.988412'
modified: '2021-04-21T20:05:57.487365'
state: active
type: dataset
tags:
  - Broadband
  - Fixed
  - Form 477
  - Map
groups: []
csv_url: 'https://opendata.fcc.gov/api/views/v5vt-e7vw/rows.csv?accessType=DOWNLOAD'
json_url: 'https://opendata.fcc.gov/api/views/v5vt-e7vw/rows.json?accessType=DOWNLOAD'
layout: post

---
Summary data of fixed broadband coverage by geographic area. License and Attribution: Broadband data from FCC Form 477, and data from the U.S. Census Bureau that are presented on this site are offered free and not subject to copyright restriction. Data and content created by government employees within the scope of their employment are not subject to domestic copyright protection under 17 U.S.C. § 105. See, e.g., U.S. Government Works.
 
While not required, when using content, data, documentation, code and related materials from fcc.gov or broadbandmap.fcc.gov in your own work, we ask that proper credit be given. Examples include:
• Source data: FCC Form 477
• Map layer based on FCC Form 477
• Code data based on broadbandmap.fcc.gov

The geography look ups are created from the US census shapefiles, which are in Global Coordinate System North American Datum of 1983 (GCS NAD83).  The coordinates do not get reprojected during processing. The "centroid_lng", "centroid_lat" columns in the lookup table are the exact values from the US census shapefile (INTPTLON, INTPTLAT).  The "bbox_arr" column is calculated from the bounding box/extent of the original geometry in the shapefile; no reprojection or transformations are done to the geometry.
