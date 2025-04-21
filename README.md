# public-analytics
This repository contains Waterly-published analyses of public water-related datasets. It is using jupyter notebooks that were executed in DataSpell, although they should be executable anywhere that jupyter notebooks can be used. 

It is recommended to use a unique python .venv for this project.

Users will have to manually create folders EPA_Data and BoundaryOutputData. EPA data will need to include: 
- NPDES_EFF_VIOLATIONS.csv,
- NPDES_NAICS.csv, and
- SDWA_VIOLATIONS_ENFORCEMENT.csv.

BoundaryOutputData will need to include: 
- EPA_CWS_V1.shp.

NPDES and SDWA Data can be found on the [EPA ECHO Data Download](https://echo.epa.gov/tools/data-downloads) website. 

The CWS shapfile can be found on the [ORD_SAB_Model Git Repo](https://github.com/USEPA/ORD_SAB_Model/tree/main) under output data. 

Dependencies that are required to execute the notebooks can be installed using the reuirements.txt file. Users can run the following code to install all dependencies:

- pip install -r requirements.txt
