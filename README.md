# GEOS_505_Research_Computing_In_Earth_Science
This repo contains important notebooks, data and other files for GEOS 505- Research Computing In the Earth and Environmental Sciences that I am taking this fall 2022.

## Goal
To acquire knowledge and skills of using computing platforms, programming languages, and practises common in contemporary research to conduct data and computing-enabled research in the Earth and Environmental Sciences.
Skills to acquire include linux computing environment, version control using git and python programming. 

## Instructor
This course is taught by proffesor [Alejandro Flores](https://www.boisestate.edu/earth/staff-members/alejandro-n-flores/) of the Dept. of Geoscience, Boise State University.

Email: [lejoflores@boisestate.edu](mailto:lejoflores@boisestate.edu)

## Course Structure
The class is divided into two units. The first unit is approximately 5 weeks in duration and the second unit is about 10 weeks in duration. 

Unit 1 is for skill building. The goal of this unit is to build and/or refine some basic competencies and proficiencies in the python programming language, applied to the analysis of environmental science data, that will be the foundation to the rest of the semester.

Unit 2 will focus on class climate dashboard project. The goal of this unit is to develop a minimum viable product (MVP) for a climate dashboard for Idaho. 

## Learning Outcomes
- Setup, expand, maintain and repair a computing environment for scientific programming
- Use a programming language to carry out a tasks including data I/O, data reduction/wrangling, data analysis, and automation
- Demonstrate how to add, remove and edit shared software using a version control platform
- Describe key properties of and create effective visualizations to convey data and communicate scientific findings
- Describe effective practices of identifying needs of key stakeholders of a scientific software platform
- Design a piece of scientific software that addresses key stakeholders need
- List and describe important steps and practices of an agile scientific software development approach

## Overview Of My Research

### Research Problem, Hypothesis and Objective

Monitoring snow depth is important for climate modeling, water resource management and predicting hazards such as avalanches and flooding. Despite this significance, the current radar techniques for measuring snow depth still fall short of operational requirements. The commonly used backscatter method is highly uncertain while the accuracy of Interferometry Synthetic Aperture Radar (InSAR) techniques still does not meet operational requirements. 
My research will improve InSAR-based algorithms for estimating snow properties. I hypothesize that the better coherence and penetration in snowpack of low frequency radar (L-band; 1-2 GHz) data will improve retrieval accuracy. To test this hypothesis, I will process and analyze data collected by NASA’s UAVSAR in varying landscapes and conditions over Idaho. The result will be compared with snow depth retrievals from Sentinel 1 and validated using field and lidar data.

### Scope of Work

Data acquisition: The major data for this research include UAVSAR data, airborne Lidar data, Sentinel-1 and field measurement data. UAVSAR is an active airborne radar that carries L-band frequency which has a wavelength of 24cm and with approximate resolution of 5m. Lidar data are collected annually during snow-on period to validate the UAVSAR derived snow depth. Sentinel 1 data are freely available for public use. It is important to note that the field data for validating low frequency (UAVSAR) data algorithm had already been acquired during the SNOWEX expedition. The field data that will be acquired during this grant period is for validating high frequency data algorithm using the contemporary sentinel-1 data. This data will be acquired at the four snotel sites that fall within UAVSAR coverage of Boise River as shown in the figure below. The sites include Banner, Bogus Basin, Mores Creek and Jackson Peak.
![](https://snowex-hackweek.github.io/website/_images/SnowEx2020.png)
Fig 1: Map of the UAVSAR flight locations for NASA SnowEx. Source: Chris Hiemstra

Data Processing and InSAR modelling: NASA JPL has performed some preprocessing, but the data are still not ready for immediate analysis. The UAVSAR data is in binary format and would be converted to tiff. Further data cleaning such as removal of NAN, coordinate transformation will be done. Creating interferograms from Sentinel-1 data will require more preprocessing including creating single look complex, phase unwrapping etc. Snow depth estimation depends on accurate measurement of incidence angle. Some studies have discovered that the incidence angle provided by NASA JPL is not very accurate for InSAR models. So, I will first derive local incidence angles from lidar. Then further exploration involves finding the best model that relates the incidence angle, phase change and wavelength of the sensor to the snow depth. This will be performed at varying topography and environmental conditions to identify the most suitable method. 

## My Personal Goal

By taking this class, I intend to:
1. Improve my python programming skills
2. Create a dashboad that display, process and analyze earth data in realtime using API and others tools.
3. Learn to work with geospatial packages like geopandas, rioxarray, GDAL, PDAL etc.
4. Adquire basic knowlede of software development cycle

Achieving the goals above will be useful for my research and the next endeavour after PhD.  
