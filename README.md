**NetCDF to Raster Conversion in ArcGIS Pro**

This script processes NetCDF (.nc) files and converts them into raster layers using ArcGIS Pro. The output raster files are stored in a specified directory, and the script dynamically handles time-based layers.
Features
Converts NetCDF data into raster layers
Automatically organizes raster layers by time
Allows user input for file paths (no hardcoded paths)
Ensures output directory exists
**Requirements**

ArcGIS Pro with arcpy module
Python 3.x
netCDF4 module
**Installation**
Make sure you have the required dependencies installed:
pip install netCDF4
ArcGIS Pro should be installed with arcpy available.
**Usage**

Run the script and provide the required file paths when prompted:
python netcdf_to_raster.py

**Example Input**

Enter the full path to your NetCDF file (.nc): C:\path\to\your\file.nc
Enter the output folder path for raster files: C:\path\to\output\folder

**Output**

The script generates raster layers as .tif files in the specified output folder, named according to their time step in the NetCDF file.

**Contributing**

Feel free to fork this repository and submit pull requests to improve functionality.

