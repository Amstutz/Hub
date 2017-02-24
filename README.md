ILIAS Hub-Plugin
===
An ILIAS-Plugin for middleware-synchronization of external systems to ILIAS. Several "Origins" can be added and configured to get data from external systems. Only small PHP-Classes have to be implemented (connect to the service, read the data and save the data in the middleware-tables).

### Installation

In order to access the HUB plugin through the Main Menu navbar, configure the HUB plugin appropriately. In the synchronisation
subsection add the role id's, that should be able to use the HUB plugin.

###Supported Objects
* Categories
* Courses
* Users
* Course-Memberships 

### Documentation
Download the full Documentation here: https://github.com/studer-raimann/Hub/blob/master/doc/Dokumentation.docx?raw=true

###Requirements
Nedd the latest version of ILIAS ActiveRecord (https://github.com/studer-raimann/ActiveRecord) and Router-Service (https://github.com/studer-raimann/RouterService)

###Contact
studer + raimann ag  
Waldeggstrasse 72  
3097 Liebefeld  
Switzerland 

info@studer-raimann.ch  
www.studer-raimann.ch  
