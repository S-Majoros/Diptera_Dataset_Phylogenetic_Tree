This README.txt was last updated on April 5th, 2023, by Samantha Majoros
We request that researchers cite this paper when using this dataset: 
Majoros, S.E. & Adamowicz, S.J. (2023). CanFlyet: Habitat Zone and Diet Trait Dataset for Diptera Species of Canada and Greenland. bioRxiv. doi: 10.1101/2023.03.15.532812. 

#Title of Dataset: 

CanFlyet: Habitat Zone and Diet Trait Dataset for Diptera Species of Canada and Greenland

#Description of the Data and file structure

Description: This dataset contains habitat, larval diet, and adult diet for True Fly (Diptera) species in Canada. The fly species were chosen for inclusion in this dataset by first downloading data for Diptera from Canada and Greenland from BOLD directly into R using BOLD’s application programming interface (API) on June 24th, 2021. The records were filtered based on the requirements outlined in Majoros et al. (2023), and the remaining species were chosen for analysis and inclusion in this dataset. Additional species from Greenland were chosen based on occurrence records from GBIF (GBIF.org (June 24th, 2021), GBIF Occurrence Download (https://doi.org/10.15468/dl.mk52hp) and included in the dataset. The biological traits for each species were determined and assigned through literature searches conducted from April 2021 - January 2023. Through the Omni Academic search tool available through the University of Guelph and Google Scholar, traits were found using the following search terms: trait AND “Taxonomic name”, habitat AND “Taxonomic name”, diet AND “Taxonomic name”, and “Feeding mode” AND “Taxonomic name”. Traits were assigned to the lowest taxonomic level possible; however, not all traits could be assigned at the species level. For these species, traits were assigned using data from the next lowest level available, whether genus, subfamily or family. The full analysis this data was used for is outlined in Majoros et al. (2023) and the code is available at https://github.com/S-Majoros/Population_Genetic_Structure. The data was put into DarwinCore format using the R package traitdatafrom version 0.6.8 (Schneider et al., 2019) in the R programming language. 

Dataset Contents: 
Number of columns: 14
Number of rows: 1985
Column List:
id: The serial number for each record.
order: The order level taxonomic classification.
family: The family level taxonomic classification.
subfamily: The subfamily level taxonomic classification.
genus: The genus level taxonomic classification. 
specificEpithet: The species level taxonomic classification. 
scientificName: The scientific name of the species.
habitat: The habitat in which the taxon is found. Taxa can be assigned terrestrial (taxa that live primarily in land habitats), aquatic (taxa that live primarily in water bodies or associated habitats) or semi-aquatic (species that require both aquatic and terrestrial habitats).
traitName: The name of the biological trait. The traits included are adultDiet and larvalDiet.
traitValue: The trait category assigned to the species. Taxa can be assigned predaceous (taxa who prey on insects or other animals), phytophagous (taxa who feed on plant material), fungivores (those who feed on fungi), saprophagous (those who feed on decaying organic matter), omnivores (those who consume material of both plant and animal origin), nectivore (taxa that primarily feed on nectar), parasites (those who live and feed in or on an organism of another species) or parasitoid (organism whose young develop within a host, eventually resulting in host death). The taxa can also be assigned a combination of these categories. In this case, the categories are separated by “_and_”. For example, “nectivore_and_predaceous”.
traitAssignmentLevel: The taxonomic level mentioned in the publication from which the traits were obtained and assigned. 
basisOfRecord: Where the trait data was obtained from.
referenceNumber: The number of sources referenced when obtaining the trait information for each taxon. 
reference: The title and DOI of the references used for the trait assignment. Full references are included in the manuscript. 

File Structure:
File List: DipteraTraitDataset.csv, DipteraTraitDataset.xlsx, DipteraTraitDataset.tsv
File Descriptions: The dataset files contain the habitat and diet for Diptera species from Canada and Greenland. All files contain the same dataset, just with different file formats.

#Sharing/Acess Information:
This data is also available at https://github.com/S-Majoros/Diptera_Dataset_Phylogenetic_Tree 
Data was derived from the sources outlined in Appendix 1 of Majoros & Adamowicz (2023).

References: 
Majoros, S.E. & Adamowicz, S.J. (2023). CanFlyet: Habitat Zone and Diet Trait Dataset for Diptera Species of Canada and Greenland. bioRxiv. doi: 10.1101/2023.03.15.532812. 
Majoros, S.E., Adamowicz, S.J. & Cottenie, K. (2023). Novel pipeline for large-scale comparative population genetics. bioRxiv. doi: 10.1101/2023.01.23.524574
Schneider,  F.D., Jochum, M., Le Provost, G., Ostrowski, A., Penone, C., Fichtmüller, D., Güntsch, A., Gossner, M.M., König-Ries, B., Manning, P., Simons, N.K. (2019). Towards an Ecological Trait-data Standard. Methods in Ecology and Evolution, 10(12), 2006-2019. doi: 10.1111/2041-210X.13288

