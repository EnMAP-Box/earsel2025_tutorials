# Prerequisites


The tutorial requires the following software:

* QGIS 3.40 or higher, with scikit-learn
* EnMAP-Box
* tbd.

You can install all using conda:

1. Create an `enmap` conda environment with QGIS and all python dependencies:
````bash
conda env create -n enmap --file=https://raw.githubusercontent.com/EnMAP-Box/earsel2025_tutorials/refs/heads/main/enmap.yml 
````
2. Activate the `enmap` environment and start QGIS

````bash
conda activate enmap
qgis
````


3. Install the EnMAP-Box QGIS Plugin

* open the QGIS Plugin Installer
* search for EnMAP-Box
* click on the install button

![Installation of EnMAP-Box using the QGIS Plugin Installer](img/installation_enmapbox.png "Installation EnMAP-Box")

