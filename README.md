# Study_on_Malaria_dynamics

Repository for storing files and notebooks to be used in the elaboration of the article based on the Final Course Work for the Undergraduate Degree in Applied Mathematics at FGV-EMAp.

Supervising Professor: [Flávio Codeço Coelho](https://emap.fgv.br/professores/flavio-codeco-coelho-0)

Contents:

+ Folders:
  - elsarticle-ecrc: Contains necessary files for development of the article (One column format)
  - elsarticle-double-columns: Contains necessary files for development of the article (Two column format)
  - temperature_data: Contains .tif files of temperature data (Outdated)
  - transmission_dynamics_modeling: Contains .ipynb files developed for transmission modeling
  - qgis_data: Contains necessary files for mapping data in QGIS
    - Manaus shapefile obtained from [IBGE](https://www.ibge.gov.br/geociencias/organizacao-do-territorio/malhas-territoriais/15774-malhas.html)
    - Deforestation data obtained from [TerraBrasilis](https://terrabrasilis.dpi.inpe.br/app/map/deforestation?hl=pt-br) plug-in for QGIS
  - mapbiomas_data: Contains .csv and .ipynb files used for extraction and treatment of MapBiomas data
  - pysus_data: Contains .parquet, .csv and .ipynb files used for extraction and treatment of Pysus (SINAN) data
  - sivep_data: Contains .parquet, .csv and .ipynb files used for extraction and treatment of SIVEP data
+ Files:
  - mosqlimate_api.ipynb: Extraction of temperature data from the [Mosqlimate API](https://api.mosqlimate.org/datastore/)
  - API_Data_Modeling.ipynb: Development of SIR/SEI modeling using Mosqlimate data
  - temperature_tif_jupyter.ipynb: Extraction of temperature data from the [WorldClim database](https://www.worldclim.org/data/monthlywth.html) (Outdated)

Original repository for the Final Course Work: [https://github.com/RaphaLevy/Undergraduate_Dissertation/tree/main](https://github.com/RaphaLevy/Undergraduate_Dissertation/tree/main)
