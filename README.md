# damselfish_territoriality_exp
Contains data and code for experiment examining fertilizer impacts on damselfish behavior

# Data
The data folder contains four documents:

damselfish_territory_measurements.csv contains both territory sizes and information on the number/sizes of resident damselfishes from both timepoints included in the study (Pre- and 13d post- treatment). 

damselfish_video_data.csv contains information on territory size as well as the behaviors of all resident fish that were visible in the videos for at least 50% of the video's runtime. Fish ID is used to distinguish between behaviors of multiple fish within a given territory. Video time is in seconds. Time guarding refers to the amount of time a fish was visible (in seconds). Prop guarding refers to the proportion of time that fish was visible. Bites refers to the number of bites by the resident fish. Other fish bites refers to the number of bites by roving herbivores. Inter chases is the number of chases towards heterospecifics, whereas Intra chases is the number of chases towards conspecifics. 

damselfish_turf_biomass.csv contains information used for the turf biomass analyses, including the dimensions of each turf sample in cm, the dry weight in g, the ash free dry weight (AFDW), and the biomass calculated as the difference between the two. 

damselfish_turf_nitrogen.csv contains information used for the turf elemental analysis, included unused data on turf isotopic content. 

# Code

All code necessary to run the analyses are present in the file damselfish_territoriality_exp_code.rmd. This file requires the user to clone the github repository in RStudio as a version control R project. 
