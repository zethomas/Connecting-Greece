# Connecting-Greece

This is the GitHub repository for the Digital Humanities project "Connecting Greece" or CoG done by Susan Crane 
and Zoé Elise Thomas.

# CoG-map-code
This is our mapping code, designed to run through R Studio Cloud. It relies on two .csv files, inscription_database_Rcompat.csv and latlongcoords.csv.
BOTH FILES ARE REQUIRED FOR THE CODE TO WORK. You can download both .csv files from this GitHub repository.

# inscription_database_Rcompat.csv
This is a sampler of our collected data for the proof of concept.

# latlongcoords.csv
This is a secondary data set based on inscription_database_Rcompat.csv which allows for the drawing of 
segmented lines within RStudio Cloud using leaflet, instead of leaflet's default continuous line. It uses the same
IDs assigned to the inscription_database_Rcompat.csv file (one ID per inscription) to keep the two files linked
together.

# Screenshots
These are screenshots of the map when the CoG-map-code is run through RStudio Cloud. FULL-MAP is a representation of 
all data points from inscription_database_Rcompat.csv and latlongcoords.csv. GORTYN and RHODES are both examples
of the markers and their formatting. The hyperlinks within the marker (Rhodes or Gortyn) lead to the stable
location URI in Pleiades.
