# Where to get the DATA?

When making an orienteering map, it is important to get most of the data. LIDAR data for understanding terrain and vegetation; parcel data for understanding boundaries; roads and other for quick imports.

# USA 
## Building footprints
Microsoft ran a machine learning process to find all [building footprints in USA and Canada](https://www.microsoft.com/en-us/maps/building-footprints). [USA data](https://github.com/Microsoft/USBuildingFootprints).
Importing is not a trivial process: the files a geo json that usually is handled slowly in software.

## Washington state
### LIDAR

* [LIDARPORTAL](https://lidarportal.dnr.wa.gov/) is the standard location for all new data and has replaced PSLC.
* [PSLC](https://pugetsoundlidar.ess.washington.edu/lidardata/restricted/index.html) - Puget sound lidar consortium - data got added there till 2017, but seems like that is gone.

### Various

It seems that each county creates its own data.
* King county [GIS](https://gis-kingcounty.opendata.arcgis.com/)
* Grant county [mapsifter](https://grantwa-mapsifter.publicaccessnow.com/Disclaimer.aspx?ReturnUrl=%2fdefault.aspx) for parcel viewing.

