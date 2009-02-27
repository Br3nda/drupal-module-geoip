// $Id: README.txt,v 1.1 2009/02/27 15:42:59 rz Exp $

Installation
--------------------
Before using this module, you will need to download one of the GeoLite database
files. These files are provided by MaxMind as gzipped files.  You will need to
gunzip these data files before using them.

To be installed in this directory:

- GeoLite Country binary format database
  - Information: http://www.maxmind.com/app/geolitecountry
  - Download: http://geolite.maxmind.com/download/geoip/database/GeoLiteCountry/GeoIP.dat.gz

- OR -

- GeoLite City binary format database
  - Information: http://www.maxmind.com/app/geolitecity
  - Download: http://geolite.maxmind.com/download/geoip/database/GeoLiteCity.dat.gz

Updates
--------------------
Both of the Lite databases are updated monthly. The module will prompt
administrators to update if the timestamp on the data file is older than 1
month. Simply replace the database file(s) with the latest one from the MaxMind
site. 