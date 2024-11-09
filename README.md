# defraQGIS
New process to 3d print from DEFRA LIDAR data via QGIS

Import the LIDAR data into QGIS as a raster layer

Crop the layer to the extents needed

Export the layer using:
 => Raster | Conversion | Translate (Convert Format)
 => Choose to save as a temporary file

Easy (but large) format for export is XYZ, this is just an array of X, Y and Z points
