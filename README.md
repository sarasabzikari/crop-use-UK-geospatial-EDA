# geospatial_data

## Crop land use within the UK

#### Reviewing annual changes to land coverage of crops can serve as a proxy for several important indicators of soil and plant health. If we know the neccessary conditions that a crop species needs in order to grow, we can extrapolate what the environmental conditions are in the regions where these crops dominate, and how these conditions may change as crop coverage changes too.

#### For example, we know legumious crops, such as beans, peanuts and soy, are efficient nitrogen fixers and flourish on nitrogen-deficient soils. 

#### Looking at one region in the UK, we have five files to use: 
#### 1. [Shapefile](https://environment.data.gov.uk/catchment-planning/WaterBody/GB109055037112) containing outline of the catchment area for the UK county Hereford
#### 2. [Shapefile](https://environment.data.gov.uk/catchment-planning/WaterBody/GB109055037112) containing outline of the river that runs through catchment area
#### 3. List of [land use codes](https://www.gov.uk/guidance/rural-payments-service-land-use-codes) with respective use and cover descriptions (crop name and plant category)
#### 4. 2020 Crop Map of England [(CROME)](https://www.data.gov.uk/dataset/be5d88c9-acfb-4052-bf6b-ee9a416cfe60/crop-map-of-england-crome-2020) polygon vector dataset mainly containing the crop types 
#### 5. As above, but for [2021](https://environment.data.gov.uk/dataset/f0f54bc1-b77a-42c8-b601-2f4aaf4dd851)

#### We will merge all these datasets together, filter for regions with an 80%  confidence interval of the named crop being grown, and visualise this data.
