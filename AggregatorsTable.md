# Biodiversity Record Aggregators   
ML Gaynor - Updated April 2020.

Are we missing a biodiversity aggregator? Let us know!

**Warning** - Some of these repositories feed into each other, duplicate records may exsist among data aggregators. Methods to detect and remove duplicates for different research applications are avaliable and/or in development. 

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">It&#39;s important to note some of these feed off eachother. The head of BISON spoke at UF once and showed this slide <a href="https://t.co/4uCjTZI9bU">pic.twitter.com/4uCjTZI9bU</a></p>&mdash; Shawn Taylor (@dataEcologist) <a href="https://twitter.com/dataEcologist/status/1255344750682611713?ref_src=twsrc%5Etfw">April 29, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
    
## **Table of Biodiversity Record Aggregators**    
Overview of a subset of biodiversity occurrence record aggregators, webportals are linked in the aggregators column. If a collection is stored or available in Darwin Core (DwC) format, a checkmark is indicated. Checkmarks also indicate that an Application Programming Interface (API) is available, R packages, or Python libraries are available, which streamlines access to data and standardizes formatting.
  
  
| Aggregators                              | Focus         | DwC | API | R packages   | Python    |
|------------------------------------------|---------------|-----|-----|--------------|-----------|
| [ALA - Atlas of Living Australia](https://www.ala.org.au/) | P, A   | ✓   | ✓   | ALA4R<sup>[1](<#1>)</sup>  |       |
| Berkeley Ecoengine                       | P, A          | ✓  |  ✓   | Ecoengine<sup>[2](<#2>)</sup>   |           |
| [CNABH](https://bryophyteportal.org/portal/)  | Br       | ✓   |     |             |              |           
| [eBird](https://ebird.org/home)  | Bi            | ✓  | ✓   | Auk<sup>[3](<#3>)</sup>         | ebird-api |
| [FishNet2](http://fishnet2.net/) | F    | ✓  | ✓   |              | fishnet   |
| [GBIF](https://www.gbif.org/)   | B             | ✓   | ✓   | Rgbif<sup>[4](<#4>)</sup>      | pygbif    |
| [iDigBio](https://www.idigbio.org/)  | B             | ✓   | ✓   | Ridigbio<sup>[5](<#5>)</sup>    | idigbio   |
| [iNaturalist](https://www.inaturalist.org) | P, A          | ✓   | ✓   | Rinat<sup>[6](<#6>)</sup>       |           |
| [LepNet](http://symbiota4.acis.ufl.edu/scan/lepnet/portal/index.php) | Lep           | ✓   |   |              |           |
| [Lichen Portal](https://lichenportal.org/cnalh/#) | Li            | ✓   |     |              |  |
| [Macaulay Library](https://www.macaulaylibrary.org/)  | Bi, F, Ap, Mm |     |    |  WarbleR<sup>[7](<#7>)</sup>     |      |
| [Macroalgal Herbarium Consortium Portal](https://macroalgae.org/portal/)  | Ma   | ✓  |     |              |           |
| [Mid-AtlanticHerbaria Consortium](http://midatlanticherbaria.org/portal/) | P    | ✓   |    |   |           |
| [MyCoPortal](https://mycoportal.org/portal/)| Fu            | ✓   |     | RMyCoPortal<sup>[8](<#8>)</sup> |           |
| [OBIS](https://mapper.obis.org/)| Pm, Am        | ✓  | ✓   | Robis<sup>[9](<#9>)</sup>       |           |
| [SEINet North American plant network](http://swbiodiversity.org/seinet/) | P             | ✓   |     |              |      |
| [SERNEC](http://sernecportal.org/portal/)| P | ✓ |     |              |           |
| [SCAN](http://symbiota4.acis.ufl.edu/scans/portal/)| At |  ✓  |      |              |           |
| [CNH](http://portal.neherbaria.org/portal/)| P | ✓ |     |              |           |
| [Tri-Trophic Thematic Collections Network](http://tcn.amnh.org/) | P, At |     |     |              |           |
| [BISON](https://bison.usgs.gov/#home) | P, A | ✓  | ✓   | Rbison<sup>[10](<#10>)</sup>     |           |
| [VertNET](http://vertnet.org/)| V | ✓ | ✓   | RVertNet<sup>[11](<#11>)</sup>   |           |
| [Canadensys](http://www.canadensys.net/)| B | ✓ | ✓ | | |
| [Chinese virtual herbarium](http://www.cvh.ac.cn/en) | P | | | 

*Abbreviations:* *Aggregators*- ALA (Atlas of Living Australia), CNABH (Consortium of North American Bryophyte Herbaria), GBIF (Global Biodiversity Information Facility), LepNet (Lepidoptera of North America Network), MyCoPortal (Mycology Collections data Portal), OBIS (Ocean Biogeographic Information System), SERNEC (Southeast Regional Network of Expertise and Collections), SCAN (Symbiota Collections of Arthropods Network), CNH (Consortium of Northeastern Herbaria), BISON (Biodiversity Information Serving Our Nation). *Focus*-A (Animals), Am (Marine Plants), Ap (amphibians), At (Arthropod​), B (Broad taxonomically), Br (Bryophytes), Bi (Birds), F (Fish), Fu (Fungus​), I (invertebrates), Lep (Lepidoptera​), Li (Lichen​), Ma (macroalgae) Mm (Mammals), P (Plants), Pm (Marine plants), V (Vertebrates).
  
## **References**. 
#### 1    
[Raymond B, VanDerWal J, Belbin L. 2019. ALA4R: Atlas of Living Australia (ALA) data and resources in R. (14 May 2019; https://github.com/AtlasOfLivingAustralia/ALA4R)](https://github.com/AtlasOfLivingAustralia/ALA4R). 
  
#### 2  
[Ram K. 2017. ecoengine: Programmatic Interface to the Web Service Methods Provided by UC Berkeley's Natural History Data. R package version 1.11.0. (14 May 2019; https://CRAN.R-project.org/package=ecoengine)](https://CRAN.R-project.org/package=ecoengine). |
  
#### 3  
[Strimas-Mackey M, Miller E, Hochachka W. 2017. auk: eBird Data Extraction and Processing with AWK. R package version. (14 May 2019; https://​github.com/​CornellLabofOrnithology/​auk)](https://​github.com/​CornellLabofOrnithology/​auk). 
  
#### 4     
[Chamberlain S, Barve V, Mcglinn D, Oldoni D. 2018a. rgbif: Interface to the Global Biodiversity Information Facility API. R package version 1.1.0. (14 May 2019; https://CRAN.R-project.org/package=rgbif)](https://CRAN.R-project.org/package=rgbif).

#### 5    
[Michonneau F, and Collins M. 2017. ridigbio: Interface to the iDigBio Data API. R package version 0.3.5. (14 May 2019; https://CRAN.R-project.org/package=ridigbio)](https://CRAN.R-project.org/package=ridigbio). 
  
#### 6
[Barve V, Hart E. 2014. rinat: Access iNaturalist data through APIs. R package version 0.1.4. [cited 16 May 2019]](https://github.com/ropensci/rinat). 
  
#### 7    
[Araya‐Salas M, Smith‐Vidaurre G. 2017. warbleR: An R package to streamline analysis of animal acoustic signals. Methods in Ecology and Evolution 8:184-191.](https://besjournals.onlinelibrary.wiley.com/doi/full/10.1111/2041-210X.12624). 
  
#### 8    
[Krah FS, Bates ST, Miller AN. 2019. rMyCoPortal-an R package to interface with the Mycology Collections Portal. Biodiversity Data Journal 7.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6341041/).  
  
#### 9    
[Provoost P, Bosch S. 2019. “robis: R Client to access data from the OBIS API.” Ocean Biogegraphic Information System. Intergovernmental Oceanographic Commision of UNESCO. R package version 2.1.0. (14 May 2019; https://cran.r-project.org/package-robis)](https://cran.r-project.org/package-robis). 
  
#### 10    
[Chamberlain S. 2019. rbison: Interface to the ‘USGS’ ‘BISON’ API. R package version 0.8.0. (14 May 2019; https://github.com/ropensci/rbison)](https://github.com/ropensci/rbison). 
  
#### 11    
[Chamberlain S. 2018. rvertnet: Search 'Vertnet', a 'Database' of Vertebrate Specimen Records. R package version 0.7.0. (14 May 2019; https://CRAN.R-project.org/package=rvertnet)](https://CRAN.R-project.org/package=rvertnet).  

