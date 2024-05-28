This README.txt was last updated on April 29th, 2024, by Samantha Majoros
#Updates: Based on feedback from peer reviewers, the trait assignments and categories have been updated. Additional search terms were added, and an additional extensive literature search was conducted resulting in over 400 new references. Trait categories were redefined. “Phytophagous” and "Omnivore" were removed as categories, and “Leaf/Root/Stem Feeding”, “Nectar/Pollen/Honeydew Feeding”, “Detritus and Algae Feeding”, “Kleptoparasitic” and “Ployphagous” were added. “Fungivore” has been renamed to “Mycophagous”. The “Unclear” category has been added for taxa where there is not enough information to make a trait assignment. Taxa may now also have two trait categories separated by “or”. In this case, it was unclear which was the most common trait category. Due to the new literature search and updated trait categories, assigned traits have been updated for over 700 species. The traitAssignmentLevel column has been split into three columns, one for habitat, adult diet and larval diet. This makes it clear which taxonomic level each individual trait assignment came from. A notes column was also added to provide some additional information and details about the diet and habitat of the taxa. 

We request that researchers cite this paper when using this dataset: 
Majoros, S.E. & Adamowicz, S.J. (2023). CanFlyet: Habitat Zone and Diet Trait Dataset for Diptera Species of Canada and Greenland. bioRxiv. doi: 10.1101/2023.03.15.532812. 

#Title of Dataset: 

CanFlyet: Habitat Zone and Diet Trait Dataset for Diptera Species of Canada and Greenland

#Description of the Data and file structure

Description: This dataset contains habitat, larval diet, and adult diet for True Fly (Diptera) species in Canada. The fly species were chosen for inclusion in this dataset by first downloading data for Diptera from Canada and Greenland from BOLD directly into R using BOLD’s application programming interface (API) on June 24th, 2021. The records were filtered based on the requirements outlined in Majoros et al. (2023), and the remaining species were chosen for analysis and inclusion in this dataset. Additional species from Greenland were chosen based on occurrence records from GBIF (GBIF.org (June 24th, 2021), GBIF Occurrence Download (https://doi.org/10.15468/dl.mk52hp) and included in the dataset. The biological traits for each species were determined and assigned through literature searches conducted from April 2021 - April 2024. Through the Omni Academic search tool available through the University of Guelph and Google Scholar, traits were found using the following search terms: trait AND “Taxonomic name”, habitat AND “Taxonomic name”, diet AND “Taxonomic name”, “Feeding mode” AND “Taxonomic name”, biology AND “Taxonomic name”, “Natural history” AND “Taxonomic name”, “Life history” AND “Taxonomic name”, taxonomy AND “Taxonomic name”, catalogue AND “Taxonomic name”, and “Field guide” AND “Taxonomic name”. Traits were assigned to the lowest taxonomic level possible; however, not all traits could be assigned at the species level. For these species, traits were assigned using data from the next lowest level available, whether genus, subfamily or family. The full analysis this data was used for is outlined in Majoros et al. (2023) and the code is available at https://github.com/S-Majoros/Population_Genetic_Structure. 

Dataset Contents: 
Number of columns: 17
Number of rows: 1982
Column List:
id: The serial number for each record.
order: The order level taxonomic classification.
family: The family level taxonomic classification.
subfamily: The subfamily level taxonomic classification.
genus: The genus level taxonomic classification. 
specificEpithet: The species level taxonomic classification. 
scientificName: The scientific name of the species.
habitat: The habitat in which the taxon is found. Taxa can be assigned terrestrial (taxa that live primarily in land habitats), aquatic (taxa that live primarily in water bodies or associated habitats) or semi-aquatic (taxa that primarily live in wet habitats and require high levels of moisture and some elements of both terrestrial and aquatic habitats).
traitName: The name of the biological trait. The traits included are adultDiet and larvalDiet.
traitValue: The trait category assigned to the species. Taxa can be assigned Predaceous (taxa who prey on insects or other animals), Mycophagous (those who feed on fungi), Saprophagous (those who feed on decaying organic matter), Nectar/Pollen/Honeydew Feeding (taxa that primarily feed on nectar, pollen and/or honeydew), Parasitic (those who live and feed in or on an organism of another species), Parasitoid (organism whose young develop within a host, eventually resulting in host death), Leaf/Root/Stem Feeding (those who feed on the leaves, roots and/or stems of plants), Detritus and Algae Feeding (those who feed on small particles of algae and detritus), Kleptoparasitic (those who take food and resources from another species), Polyphagous (those who engage in more than three of the other feeding modes), NonFeeding (those who do not feed at the specified life stage), and Unclear (taxa for which there is not enough information to make a trait assignment). The taxa can also be assigned a combination of these categories. In this case, the categories are separated by “and”. For example, “Saprophagous and Predaceous”. For cases where it is unclear which diet is more common, the categories are separated by “or”. For example, “Saprophagous or Predaceous”.
traitAssignmentLevelHabitat: The taxonomic level from which the habitat assignment was obtained and assigned. 
traitAssignmentLevelAdultDiet: The taxonomic level from which the adult diet assignment was obtained and assigned. 
traitAssignmentLevelLarvalDiet: The taxonomic level from which the larval diet assignment was obtained and assigned. 
notes: Additional information on the habitat and diet of the taxa. Information is provided for the lowest taxonomic level used for the trait assignments if available. 
basisOfRecord: Where the trait data was obtained from.
referenceNumber: The number of sources referenced when obtaining the trait information for each taxon. 
reference: The title and DOI of the references used for the trait assignment. Full references are included in the manuscript. 

File Structure:
File List: DipteraTraitDataset.csv, DipteraTraitDataset.xlsx, DipteraTraitDataset.tsv
File Descriptions: The dataset files contain the habitat and diet for Diptera species from Canada and Greenland. All files contain the same dataset, just with different file formats.

#Sharing/Access Information:
This data is also available at https://github.com/S-Majoros/Diptera_Dataset_Phylogenetic_Tree 
Data was derived from the sources outlined in Appendix 1 of Majoros & Adamowicz (2023).

References: 
Majoros, S.E. & Adamowicz, S.J. (2023). CanFlyet: Habitat Zone and Diet Trait Dataset for Diptera Species of Canada and Greenland. bioRxiv. doi: 10.1101/2023.03.15.532812. 
Majoros, S.E., Adamowicz, S.J. & Cottenie, K. (2023). Novel pipeline for large-scale comparative population genetics. bioRxiv. doi: 10.1101/2023.01.23.524574

