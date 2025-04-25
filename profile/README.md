# Evaluating the protection of diverse and representative coastal and marine habitats within California’s Marine Protected Area (MPA) network

This is a capstone project for the [Master of Environmental Data Science Program](https://bren.ucsb.edu/masters-programs/master-environmental-data-science) at [Bren School of Environmental Science and Management](https://bren.ucsb.edu), University of California, Santa Barbara

For the official project description on the Bren website, click [here](https://bren.ucsb.edu/projects/evaluating-protection-diverse-and-representative-coastal-and-marine-habitats-within).

## Abstract 
The Marine Life Protection Act of 1999 endeavors to protect the “natural diversity and abundance of marine life” along the California coastline and its nearshore environments, with the goal of promoting marine habitats, ecosystems, and marine natural heritage*. In pursuit of informing these goals, substantial advances in Marine Protected Area (MPA) habitat measuring have occurred since the initial MPA planning process, including the use of remote sensing data. However, there is still a need for statewide visual understanding and statistical analysis of the distribution of habitat types within MPAs. 
Our team will integrate existing spatial habitat datasets to generate map layers for defined habitat types, and use those layers to analyze the habitat makeup inside MPAs, compared to habitat type and variation outside of the network. We will analyse how these different habitat types are protected, and standardize the method of calculating the composition of habitat within each MPA. Our findings will culminate in a written report summarizing this process, and will include effective visualization of key insights through tables, figures, and maps. This report will be read and utilized by researchers involved in the decadal evaluation of California’s MPA network, state partners at the California Department of Fish and Wildlife, the California Ocean Protection Council, and ecologists. 

## Data Sources
| **Data**                                | **Data Type**                                                                 | **Source**                                                               |
|-----------------------------------------|------------------------------------------------------------------------------|--------------------------------------------------------------------------|
| California MPAs shapefiles              | .cpg, .dbf, .prg, .shp, .shx, .xml                                           | [CA Department of Fish and Wildlife](https://data.ca.gov/dataset/california-marine-protected-areas-ds582)                                       |
| Substrate (rock vs. sediment)           | .freelist, .gdbtable, .gbdtablx, .horizon, .atx, .gbindexes, .spx          | [PMEP Nearshore Substrate Component](https://www.pacificfishhabitat.org/data/nearshore-cmecs-substrate-habitat/)                                       |
| Nearshore biotic habitat                | .freelist, .gdbtable, .gbdtablx, .horizon, .atx, .gbindexes, .spx          | [PMEP Nearshore Biotic Component](https://www.pacificfishhabitat.org/data/nearshore-cmecs-biotic-habitat/)                                          |
| Bathymetry                              | .tif, .csv                                                                  | NOAA West Coast Deep Sea Coral Initiative, via client (Google Drive)     |
| Kelp forest canopy cover                | .csv                                                                        | [KelpWatch](https://kelpwatch.org/map?zoom=4.19667&center=-125.13024%2C32.82854)                                                                 |
| Biotic cover within estuaries           | .freelist, .gdbtable, .gbdtablx, .horizon, .atx, .gbindexes, .spx          | [PMEP Estuarine Biotic Component](https://www.pacificfishhabitat.org/data/estuarine-biotic-habitat)                                          |
| Eelgrass extent                         | .gdb                                                                        | [PMEP Eelgrass Habitat](https://www.pacificfishhabitat.org/data/west-coast-usa-eelgrass-habitat/)                                                    |

## Repositories
This organization is home to 5 different repositories.
- rds_creation: This repository's sole purpose is to document the creation of .RDS files used for MPA analysis
- Biota: This repository houses data cleaning and MPA analysis for the biotic layer.
- Substrate: This repository houses data cleaning and MPA analysis for the substrate layer.
- Bathymetry: This repository houses data cleaning and MPA analysis for depth zones.
- mbm_dashboard: This repository houses code for the R Shiny dashboard. This dashboard will host an interactive map with biota, substrate, and bathymetry layers, along with habitat composition percentages. Additionally, the final technical report and additional metadata will be available.

## Client, Advisor and Contributors
Cori Lopazanski, PhD Candidate, Bren School. Client

Dr. Joshua Smith, Ocean Conservation Research Scientist, Monterey Bay Aquarium. Client

Dr. Samantha Stevenson-Karl, Associate Professor, Bren School. Advisor

Dr. Carmen Galaz García, Assistant Teaching Professor, Bren School. Faculty Advisor


## MarineBioMaps Team
Madison Enda
Bailey Jørgensen
Michelle Yiv

## References 
*(1999). Marine Life Protection Act, California Department of Fish and Wildlife. https://wildlife.ca.gov/Conservation/Marine/MPAs/MLPA 




