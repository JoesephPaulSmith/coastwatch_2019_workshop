# coastwatch_2019_workshop
Jupyter Notebook for CoastWatch 2019 Workshop

This is intended to be ran on the desktop. Additional work required to do a cloud setup

To get the files in the analysis:

- Goto https://coastwatch.glerl.noaa.gov/erddap/info/

- Click on the data links for the following:

Color Producing Agent (CPA) Chlorophyll, VIIRS, Lake Erie (2018-present) 

Color Producing Agent (CPA) Colored Dissolved Organic Matter, VIIRS, Lake Erie (2008-present)

Color Producing Agent (CPA) Dissolved Organic Carbon, VIIRS, Lake Erie (2018-present)

Color Producing Agent (CPA) Suspended Minerals, VIIRS, Lake Erie (2018-present)

--- Select a time range for the data. In my case, I did End of April 2019 through roughly present for each data set
--- Select .nc for the file type
--- Click submit. The file should download, cut and paste it into the folder you want to work from

Then ensure os.chdir at the top of the notebook points to the folder you wish to work from

Have fun, and good luck

-Joe
