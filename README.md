DataAW transfers data from a vector file to a Grid vector file, using the area-weighted data method.
Results are better when data is homogeneous within the same polygon.
Mandatory CRS in meters (Project Properties and Files).

Data open file: Vectorial file with the data that will be transferred to the grid according to the area-weighted data method
Data select field: data field
Grid open file: A Grid vectorial file. If you don't have a Grid file you can create one using the Qgis Vector tool : Research - Create Grid. 
Grid select field id : Id field is a field of unique records (primary key), if your Grid file does not have one, use the field calculator's id function.
The result will be a file with the fields:
IdG: Grid Id field
DataAW: Field Data processed according to area-weighted data method
