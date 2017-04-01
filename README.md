# GPService_Contour
An example of call an asynchronous GP Service that makes contour line

# GP Service definition
Service URL : https://<your gis server>/arcgis/rest/services/MyGPService/ca_ozone_gp/GPServer/mymodel

| param name  | type                  | description                                | comment        |
|-------------|-----------------------|--------------------------------------------|----------------|
|input        |GPFeatureRecordSetLayer| Input parameter, an array of point features|                |
|outline      |GPFeatureRecordSetLayer| Input parameter, an array of polygon       |                |
|output_clip  |GPFeatureRecordSetLayer| output parameter, ignore                   |                |
|Z_value_field|GPString               | Input parameter, the name of z value field |                |
