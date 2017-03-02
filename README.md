# mudrod_ontologies

This project contains all ontology resources generated through the Mining and Utilizing Dataset Relevancy from Oceanographic Datasets to Improve Data Discovery and Access (MUDROD) project funded by NASA AIST (NNX15AM85G).

<img src="http://geant4.slac.stanford.edu/Space06/NASAJPLlogo.jpg" align="right" width="300" />
<img src="http://www.iucrc.org/sites/default/files/centerLogo.png" align="right" width="170" />

# Introduction
MUDROD ontologies stem from a number of sources
 * **NASA Global Change Master Directory Directory Interchange Format** (GCMD-DIF) - defined appropriately [here](http://gcmd.gsfc.nasa.gov/DocumentBuilder/defaultDif10/guide/whatisadif.html), GCMD-DIF exists primarily as an [XSD](http://gcmd.gsfc.nasa.gov/Aboutus/xml/dif/dif_v10.2.xsd) however through MUDROD we have created an OWL manifestation which can be found at [dif_v10.2.owl](https://raw.githubusercontent.com/mudrod/mudrod_ontologies/master/podaacDatasets.owl).
 * **podaacDatasets.owl** - a PO.DAAC-specific extension of the [SWEET reprDataProduct.owl#Dataset](http://sweet.jpl.nasa.gov/2.3/reprDataProduct.owl) concept with the Data property assertions based off of the GCMD-DIF data model provided above. Each PODAACDataset instance (individual) represents a PO.DAAC dataset with the data values being derived from the [PO.DAAC WebServices](https://podaac.jpl.nasa.gov/ws).

# Team members:

 * Chaowei (Phil) Yang - [NSF Spatiotemporal Innovation Center](http://stcenter.net/), George Mason University
 * [Yongyao Jiang](https://www.linkedin.com/in/yongyao-jiang-42516164) - [NSF Spatiotemporal Innovation Center](http://stcenter.net/), George Mason University
 * Yun Li - [NSF Spatiotemporal Innovation Center](http://stcenter.net/), George Mason University
 * Edward M Armstrong - [Jet Propulsion Laboratory](http://www.jpl.nasa.gov/), [NASA](http://www.nasa.gov)
 * Thomas Huang - [Jet Propulsion Laboratory](http://www.jpl.nasa.gov/), [NASA](http://www.nasa.gov)
 * David Moroni - [Jet Propulsion Laboratory](http://www.jpl.nasa.gov/), [NASA](http://www.nasa.gov)
 * Chris Finch - [Jet Propulsion Laboratory](http://www.jpl.nasa.gov/), [NASA](http://www.nasa.gov)
 * [Lewis John Mcgibbney](https://www.linkedin.com/in/lmcgibbney) - [Jet Propulsion Laboratory](http://www.jpl.nasa.gov/), [NASA](http://www.nasa.gov)

# License
All MUDROD ontologies are licensed permissively under the [Apache License v2.0](https://www.apache.org/licenses/LICENSE-2.0) a copy of which ships with this code.
