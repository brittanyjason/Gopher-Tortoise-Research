# Establishing Ideal Habitat Locations to Determine Potential Gopher Tortoise (*Gopherus polyphemus*) Protected Areas with LiDAR Data

![tortoise](GT1.jpg)

Source: http://tort-time.com/post/126830290707/animal-alphabet-t-is-for-tortoise-gopher

## Gopher Tortoise Habitat & Protection

Typically, gopher tortoises are found in upland habitats that consist of well-drained sandy soiled areas, you can find them in other habitats such as: scrub, xeric hammock, pine flatwoods, dry prairie, coastal grasslands and dunes, mixed hardwood-pine communities and other disturbed habitats (Auffenberg and Franz 1982; Kushlan and Mazzotti 1984; Diemer 1986, 1987, 1992b; Breininger et al. 1994; Ashton and Ashton 2008). 

A management plan for gopher tortoises was created in 2007 by the Florida Wildlife Commission (FWC) it was revised in 2012 for continued recovery of the Species of Special Concern and this management plan will be re-evaluated in 2022. It is our hope that we can define managed areas for gopher tortoises in the Wekiwa Springs State Park before 2022 when the plan is re-evaluated. 

![ideal habitat](sandhill.jpg)

Source:https://beetlesinthebush.files.wordpress.com/2009/12/img_1195_1200x800_enh.jpg

## How You Can Help!

Help Us! Be a citizen scientist! [FWC](https://mangomap.com/fwcwebmaster/maps/52930/Gopher-Tortoise-Sightings#) has an easy-to-use website that you can upload images of gopher tortoises that you have spotted with the location and they will map it for everyone to view. There have been very few citizen scientists in our study area and we would love your help! If you are enjoying the Wekiwa Springs State Park please feel free to take photos of gopher tortoises and their burrows, but remember, you are in their home and please do not disturb this protected species. Please take only pictures and leave only footprints!

![tortoisesign](GT4.jpg)

Source: http://www.ncflindependent.com/2016/02/27/amelia-island-earth-keepers-mobilize-to-protect-gopher-tortoises-from-development/

![tortoisesign3](GT6.JPG)

Source: http://www.pearassoc.org/Gopher%20Tortoise.htm

## Our Study Area

This LiDAR dataset is a 17 km2 subset from a 49 km2 total area from Wekiwa Springs State Park obtained from [OpenTopography](http://opentopo.sdsc.edu/lidarDataset?opentopoID=OTLAS.062012.26917.1). There are 112700100 points in the subset. The area is comprised of sandhill and flatwood habitats with some ephemeral swamps. Prescribed fires are often conducted which will clear out excess fuel loads, and provide open ground for new vegetation to propagate. This new vegetation provides palatable forage for many herbivores. The west and south sides are bordering residential areas.
 
Points were classified into low vegetation (points below 0.5 meters but above the ground), medium vegetation (points from 0.5 – 2 meters above the ground), and high vegetation (points between 2-10 meters above the ground). These three classes were then individual isolated into three separate digital elevation models (DEMs), which map the density of these classes. 

![subset area](subsetarea.png)

Images created in ArcGIS10.4 with their basemap.

![study area](StudyArea.PNG)

Images created in ArcGIS10.4 with their basemap.
## What is LiDAR?

Light detection and ranging (LiDAR) is a remote sensing surveying method which measures the distance from an aerial sensor to the surface of the landscape. Each time an object is registered a point is generated. Each LiDAR dataset may contain millions of points to map the landscape. The landscape is represented by all natural and artificial object and structures, so LiDAR maps the surface of the ground, trees, buildings, etc. Utilizing algorithms, software analyzes the points to classify various terrain types such as the ground surface, low vegetation, medium vegetation, and high vegetation. These different types are represented in a point map as different colors.

![lidar explanation](lidar.jpg)
Source:https://www.flickr.com/photos/128087132@N06/15407288840 

## Digital Elevation Models (DEMs)

DEM of all three vegetation classes (low, medium and high vegeation) 

![DEM of all vegetation classes](DEMclass3_4_5.PNG)

DEM of Low Vegetation- Red is where there is a high amount of low vegetation, whereas blue is where there is a small amount of low vegetation 

![DEM of low vegetation](DEMclass3.PNG)

DEM of Medium Vegetation- Red is where there is a high amount of medium vegetation, whereas blue is where there is a small amount of medium vegetation 

![DEM of mid vegetation](DEMclass4.PNG)

DEM of High Vegetation- Red is where there is a high amount of high vegation, whereas blue is where there is a small amount of high vegeation. 

![DEM of high vegetation](DEMclass5.PNG)

## Return Points Per Cell from LiDAR at 5m

These images of our study area depict the amount of points per 5m area throughout our dataset. The white areas are areas with no/unclassified data. The red areas show where we have the most data and blue is the least.

Low Vegetation

![class 3 vegetation points per cell 5m size](only3_5m_ptspercell.PNG)
Legend ![legendclass3 5m](legend_5m_3only.PNG)

Medium Vegetation

![class 4 vegetation points per cell 5m size](only4_5m_ptspercell.PNG)
Legend ![legend class 4 5m](legend_5m_4only.PNG)

High Vegetation

![class 5 vegetation points per cell 5m size](only5_5m_ptspercell.PNG)
Legend ![class5 5m](legend_5m_5only.PNG)

All Three Classes (low, medium, high) Together

![all vegetation classes points per cell 5m size](all345_5m_ptspercell.PNG)
Legend ![all3 5m](legend_5m_345all.PNG)

## Return Points Per Cell from LiDAR at 10m 

These images of study area depict the amount of points per 10m area throughout our dataset. The white areas are areas with no/unclassified data. The red areas show where we have the most data and blue is the least.

Low Vegetation

![class 3 vegetation points per cell 10m size](only3_10m_ptspercell.PNG)
Legend ![low 10m legend](legend_10m_3only.PNG)

Medium Vegetation
![class 4 vegetation points per cell 10m size](only4_10m_ptspercell.PNG)
Legend ![med 10mlegend](legend_10m_4only.PNG)

High Vegetation
![class 5 vegetation points per cell 10m size](only5_10m_ptspercell.PNG)
Legend ![legend high 10m](legend_10m_5only.PNG)

All Three Classes (low,medium, high) Together
![all vegetation classes points per cell 10m size](all345_10m_ptspercell.PNG)
Legend ![all3 10m](legend_10m_345all.PNG)

## Implications of Our Research

This work has implications due to the fact that gopher tortoises have a wide range of habitat options. They enjoy sand and scrub but have been found in forested areas and in the dunes near beaches. Low vegetation was important to us in this study, they may prefer areas that have lower scrub as they will be foraging on the ground only. 

## Our Recommendation For Gopher Tortoise Protected Areas
Below we have boxed areas that we have found to be some of the best habitat for gopher tortoises that we would like to protect in the future.

![areashighlighted](tortiareas.png)

## Acknowledgements

This material is based on [data, processing] services provided by the OpenTopography Facility with support from the National Science Foundation under NSF Award Numbers 1226353 & 1225810

Data Provider Acknowledgment
OpenTopography hosts datasets that have been collected by many research, governmental, and non-profit organizations funded by a variety of sources. The data user bears sole responsibility for recognizing the role of the data provider through co-authorship, citation, sponsor acknowledgement, and/or attribution, as appropriate and consistent with professional standards and sponsor requirements.
OpenTopography provides dataset acknowledgement language specific to each hosted dataset. This language is composed by the data provider can be found on the dataset access page and through the dataset’s metadata. OpenTopography also provides a Digital Object Identifier (DOI) for each hosted dataset as a means to facilitate data citation. Inclusion of the dataset’s DOI in your data citation or acknowledgement ensures that the dataset can be accessed and reused, data impact can be tracked, and that data producers and collectors are recognized.

## References

Auffenberg, W., and R. Franz. 1982. The status and distribution of the gopher tortoise (Gopherus polyphemus). Pages 95–126 in R. B. Bury, editor. North American tortoises: Conservation and ecology. U.S. Fish and Wildlife Service, Wildlife Research Report 12.

Ashton, R. E., and P. S. Ashton. 2008. The Natural History and Management of the Gopher Tortoise Gopherus polyphemus (Daudin). Krieger Press, Malabar, Florida, USA. 

Breininger, D. R., P. A. Schmalzer, and C. R. Hinkle. 1994. Gopher tortoise (Gopherus polyphemus) densities in coastal scrub and slash pine flatwoods in Florida. Journal of Herpetology 28:60–65.

Diemer, J. E. 1986. The ecology and management of the gopher tortoise in the southeastern United States. Herpetologica 42:125–133.

Diemer, J. E. 1987. The status of the gopher tortoise in Florida. Pages 72-83 in R. Odom, K. Riddleberger, and J. Osier, editors. Proceedings of the Third Southeastern Nongame and Endangered Wildlife Symposium. Georgia Department of Natural Resources, Game and Fish Division, Atlanta, USA.

Diemer, J. E. 1992b. Home range and movements of the tortoise Gopherus polyphemus in northern Florida. Journal of Herpetology 26:158–162.

Kushlan, J. A., and F. J. Mazzotti. 1984. Environmental effects on a coastal population of gopher tortoises. Journal of Herpetology 18:231–239.

![tortoise2](GT2.jpg)

Source: http://www.americaslongleaf.org/news/news-articles/range-wide-conservation-strategy-for-the-gopher-tortoise-now-available/

This webpage was created on the 18th of February 2017 by Jason Richardson and Brittany Capra at the University of South Florida in Tampa, FL.
