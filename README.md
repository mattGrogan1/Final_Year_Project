# Final_Year_Project #
## Predicting Fire Brigade Call Outs For Dublin City ##

The following describes each of the four csv files used within this project.  The four csv files are located within the Files Folder.

### Datasets ###
#### FireBrigadeCallOuts ####
This file consists of: 38,555 rows of data with 13 columns.  It is used to predict Fire Brigade call outs on specific dates.

#### FireBrigadeCallOuts_TypeOfFire ####
This file consists of: 38,555 rows of data with 13 columns.  It is used to predict Fire Brigade call outs relating to specific types of fires.

#### FireBrigadeCallOuts_StationArea ####
This file consists of: 38,555 rows of data with 13 columns.  It is used to predict Fire Brigade call outs at a local level.

#### AmbulanceCallOuts ####
This file consists of: 145,426 rows of data with 13 columns.  It is used to predict Ambulance call outs on specific dates.

### Forward Stepwise Regression Implementation ###

When implementing this stage of the project, open RStudio using one of the files below.  Note: Open the correct file to ensure no errors occur.

#### Forward Stepwise Regression - FireBrigadeCallOuts #### 
Use When required to run Forward Stepwise Regression for Fire Brigade call outs on specific dates.  Select FireBrigadeCallOuts csv file.

#### Forward Stepwise Regression - FireBrigadeCallOuts_TypeOfFire #### 
Use When required to run Forward Stepwise Regression for Fire Brigade call outs relating to specific types of fires.  Select FireBrigadeCallOuts_TypeOfFire csv file.

#### Forward Stepwise Regression - FireBrigadeCallOuts_StationArea #### 
Use When required to run Forward Stepwise Regression for Fire Brigade call outs at a local level. Select FireBrigadeCallOuts_StationArea csv file.

#### Forward Stepwise Regression - AmbulanceCallOuts #### 
Use When required to run Forward Stepwise Regression for Ambulance call outs on specific dates.  Select AmbulanceCallOuts csv file.

### Jupyter Notebook Implementation ###

#### FireBrigadeCallOuts.ipynb ####
Use this python file to predict Fire Brigade call outs on specific dates.

#### FireBrigadeCallOuts_TypeOfFire.ipynb ####
Use this python file to predict Fire Brigade call outs relating to specific types of fires.

#### FireBrigadeCallOuts_StationArea.ipynb ####
Use this python file to predict Fire Brigade call outs at a local level.

#### AmbulanceCallOuts.ipynb ####
Use this python file to predict Ambulance call outs on specific dates.

When running the code on Juypter Notebook, an error may occur if there is not enough storage on your device to run the csv files.  This may occur when attempting to run the AmublanceCallOuts csv files.  If this happens, follow the steps provided below.

* Press the Windows key.
* Type in SystemPropertiesAdvanced.
* Select Run as administrator.
* Click settings.
* Choose the Advanced tab.
* Select Change.
* Uncheck Automatically managing paging file size for all drives.
* Select Custom size and choose an appropriate size.
* Press Set, then Ok.
* Exit.
* Restart the computer.
