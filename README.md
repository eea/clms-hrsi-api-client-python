# Python client for accessing the Copernicus Land Monitoring Service - High resolution Snow & Ice HTTP API

Python client for accessing the Copernicus Land Monitoring Service HTTP API by means of REST calls. Currently supported (on server side) are only Data from the [High Resolution Snow and Ice Monitoring (HR-S&I) ](https://land.copernicus.eu/pan-european/biophysical-parameters/high-resolution-snow-and-ice-monitoring).

The Pan-European ARLIE ice products by the CLMS are reachable through the Python client https://github.com/eea/clms-hrsi-api-client-python-arlie 

## Registration:
Before downloading any data you need to register [here](https://cryo.land.copernicus.eu/finder).  

## Other Data access possibilities:
Web frontend for search and download: https://cryo.land.copernicus.eu/finder  
Users should notice that using this interactive web interface also generates the corresponding REST query, that can be ingested directly by the Python script.

WMS services:  
**Snow products**
+	https://cryo.land.copernicus.eu/wms/FSC/  
+	https://cryo.land.copernicus.eu/wms/PSA/  
+	https://cryo.land.copernicus.eu/wms/SWS/
+	https://cryo.land.copernicus.eu/wms/WDS/
+	https://cryo.land.copernicus.eu/wms/GFSC/ 

**Ice products**
+ https://cryo.land.copernicus.eu/wms/RLIE/  

## API Url: 
https://cryo.land.copernicus.eu/resto/api/collections/HRSI/search.json
## API reference: 
https://cryo.land.copernicus.eu/resto/api/collections/HRSI/describe.xml

## Installation:
Download the script and run (use correct path):
```S
>python CLMS_downloader.py --help
```

## Legal notice about Copernicus Data:
Access to data is based on a principle of full, open and free access as established by the Copernicus data and information policy Regulation (EU) No 1159/2013 of 12 July 2013. This regulation establishes registration and licensing conditions for GMES/Copernicus users and can be found here: http://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A32013R1159.  

Free, full and open access to this data set is made on the conditions that:  
1. When distributing or communicating Copernicus dedicated data and Copernicus service information to the public, users shall inform the public of the source of that data and information.  
2. Users shall make sure not to convey the impression to the public that the user's activities are officially endorsed by the Union.  
3. Where that data or information has been adapted or modified, the user shall clearly state this.  
4. The data remain the sole property of the European Union. Any information and data produced in the framework of the action shall be the sole property of the European Union. Any communication and publication by the beneficiary shall acknowledge that the data were produced “with funding by the European Union”.  
