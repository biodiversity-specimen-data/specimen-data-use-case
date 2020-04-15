
**Table 1.** Overview of a subset of biodiversity occurrence record aggregators. If a collection is stored or available in Darwin Core (DwC) format, a checkmark is indicated. Checkmarks also indicate that an Application Programming Interface (API) is available, R packages, or Python libraries are available, which streamlines access to data and standardizes formatting.
  
  
| Aggregators                              | Focus         | DwC | Web portal                                          | API | R packages   | Python    |
|------------------------------------------|---------------|-----|-----------------------------------------------------|-----|--------------|-----------|
| ALA                                      | P, A          | ✓   | [ala.org.au](ala.org.au.e)                                        | ✓   | ALA4R^(1)[#1]       |           |
| Berkeley Ecoengine                       | P, A          | ✓   |                                                     | ✓   | Ecoengine^(2)[#2]   |           |
| CNABH                                    | Br            | ✓   | [bryophyteportal.org](bryophyteportal.org)                                 |     |              |           |
| eBird                                    | Bi            | ✓   | [ebird.org](ebird.org)                                         | ✓   | Auk^3         | ebird-api |
| FishNet2                                 | F             | ✓   | [fishnet2.net](fishnet2.net)                                        | ✓   |              | fishnet   |
| GBIF                                     | B             | ✓   | [gbif.org](gbif.org)                                           | ✓   | Rgbif^4      | pygbif    |
| iDigBio                                  | B             | ✓   | [idigbio.org](idigbio.org)                                      | ✓   | Ridigbio^5    | idigbio   |
| iNaturalist                              | P, A          | ✓   | [inaturalist.org](inaturalist.org)                                     | ✓   | Rinat^6       |           |
| InvertEBase                              | I             | ✓   | [invertebase.org](invertebase.org)                                     |     |              |           |
| LepNet                                   | Lep           | ✓   | [symbiota4.acis.ufl.edu/scan/lepnet/portal/index.php](symbiota4.acis.ufl.edu/scan/lepnet/portal/index.php) |     |              |           |
| Lichen Portal                            | Li            | ✓   | [lichenportal.org](lichenportal.org)                                    |     |              |           |
| Macaulay Library                         | Bi, F, Ap, Mm |     | [macaulaylibrary.org](macaulaylibrary.org)                                 |     | WarbleR^7     |           |
| Macroalgal Herbarium Consortium Portal​  | Ma            | ✓   | [macroalgae.org](macroalgae.org)                                  |     |              |           |
| Mid-AtlanticHerbaria Consortium          | P             | ✓   | [midatlanticherbaria.org](midatlanticherbaria.org)                             |     |              |           |
| MyCoPortal                               | Fu            | ✓   | [mycoportal.org](mycoportal.org)                                      |     | RMyCoPortal^8 |           |
| OBIS                                     | Pm, Am        | ✓   | [obis.org](obis.org)                                            | ✓   | Robis^9       |           |
| SEINet North American plant network      | P             | ✓   | [swbiodiversity.org/seinet/](swbiodiversity.org/seinet/)                         |     |              |           |
| SERNEC                                   | P             | ✓   | [sernecportal.org](sernecportal.org)                                    |     |              |           |
| SCAN                                     | At            | ✓   | [symbiota4.acis.ufl.edu/scan/portal/](symbiota4.acis.ufl.edu/scan/portal/)                |     |              |           |
| CNH​                                     | P             | ✓   | [neherbaria.org](neherbaria.org)                                      |     |              |           |
| Tri-Trophic Thematic Collections Network | P, At         |     | [tcn.amnh.org](tcn.amnh.org)                                        |     |              |           |
| BISON                                    | P, A          | ✓   | [bison.usgs.gov](bison.usgs.gov)                                      | ✓   | Rbison^10     |           |
| VertNET                                  | V             | ✓   | [vertnet.org](vertnet.org)                                         | ✓   | RVertNet^11   |           |

*Abbreviations:* *Aggregators*- ALA (Atlas of Living Australia), CNABH (Consortium of North American Bryophyte Herbaria), GBIF (Global Biodiversity Information Facility), LepNet (Lepidoptera of North America Network), MyCoPortal (Mycology Collections data Portal), OBIS (Ocean Biogeographic Information System), SERNEC (Southeast Regional Network of Expertise and Collections), SCAN (Symbiota Collections of Arthropods Network), CNH (Consortium of Northeastern Herbaria), BISON (Biodiversity Information Serving Our Nation). *Focus*-A (Animals), Am (Marine Plants), Ap (amphibians), At (Arthropod​), B (Broad taxonomically), Br (Bryophytes), Bi (Birds), F (Fish), Fu (Fungus​), I (invertebrates), Lep (Lepidoptera​), Li (Lichen​), Ma (macroalgae) Mm (Mammals), P (Plants), Pm (Marine plants), V (Vertebrates).
  
**References**.   
[1:] [Raymond B, VanDerWal J, Belbin L. 2019. ALA4R: Atlas of Living Australia (ALA) data and resources in R. (14 May 2019; https://github.com/AtlasOfLivingAustralia/ALA4R)](https://github.com/AtlasOfLivingAustralia/ALA4R). 
  
[2:] [Ram K. 2017. ecoengine: Programmatic Interface to the Web Service Methods Provided by UC Berkeley's Natural History Data. R package version 1.11.0. (14 May 2019; https://CRAN.R-project.org/package=ecoengine)](https://CRAN.R-project.org/package=ecoengine).  
  
3. [Strimas-Mackey M, Miller E, Hochachka W. 2017. auk: eBird Data Extraction and Processing with AWK. R package version. (14 May 2019; https://​github.com/​CornellLabofOrnithology/​auk)](https://​github.com/​CornellLabofOrnithology/​auk). 
  
4. [Chamberlain S, Barve V, Mcglinn D, Oldoni D. 2018a. rgbif: Interface to the Global Biodiversity Information Facility API. R package version 1.1.0. (14 May 2019; https://CRAN.R-project.org/package=rgbif)](https://CRAN.R-project.org/package=rgbif).       
5. [Michonneau F, and Collins M. 2017. ridigbio: Interface to the iDigBio Data API. R package version 0.3.5. (14 May 2019; https://CRAN.R-project.org/package=ridigbio)](https://CRAN.R-project.org/package=ridigbio). 
  
6. [Barve V, Hart E. 2014. rinat: Access iNaturalist data through APIs. R package version 0.1.4. [cited 16 May 2019]](https://github.com/ropensci/rinat). 
  
7. [Araya‐Salas M, Smith‐Vidaurre G. 2017. warbleR: An R package to streamline analysis of animal acoustic signals. Methods in Ecology and Evolution 8:184-191.](https://besjournals.onlinelibrary.wiley.com/doi/full/10.1111/2041-210X.12624). 
  
8. [Krah FS, Bates ST, Miller AN. 2019. rMyCoPortal-an R package to interface with the Mycology Collections Portal. Biodiversity Data Journal 7.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6341041/).  
  
9. [Provoost P, Bosch S. 2019. “robis: R Client to access data from the OBIS API.” Ocean Biogegraphic Information System. Intergovernmental Oceanographic Commision of UNESCO. R package version 2.1.0. (14 May 2019; https://cran.r-project.org/package-robis)](https://cran.r-project.org/package-robis). 
  
10. [Chamberlain S. 2019. rbison: Interface to the ‘USGS’ ‘BISON’ API. R package version 0.8.0. (14 May 2019; https://github.com/ropensci/rbison)] 
  
11. Chamberlain S. 2018. rvertnet: Search 'Vertnet', a 'Database' of Vertebrate Specimen Records. R package version 0.7.0. (14 May 2019; https://CRAN.R-project.org/package=rvertnet). 

