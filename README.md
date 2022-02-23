# Smartby
Smartbyprosjekt for studassstilling


## Node-RED avhengigheter
Importer flowene fra RaspberryPi/flows.json inn i Node-RED

Disse må installeres for å få kjørt Node-RED flowene:

* Worldmap
* Dashboard

## Database
### ER-diagram
![alt text](doc/db/er_diagram.PNG)

### Oppsett
* Installer MariaDB server
* Databasen (smartby.sql) kan importeres inn i MariaDB med kommandoen:
"mysql -u root -p smartby < smartby.sql"

