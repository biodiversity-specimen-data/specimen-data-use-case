## iDigBio API info

- [iDigBio API overview](https://www.idigbio.org/wiki/index.php/IDigBio_API)
- [iDigBio Search API documentation](https://github.com/iDigBio/idigbio-search-api/wiki)
- [iDigBio R package](https://github.com/idigbio/ridigbio)
- [iDigBio Python library](https://github.com/idigbio/idigbio-python-client/)

## R packages we like

### Essential R packages
- [tidyverse](https://www.tidyverse.org/): must-have suite of packages for data wrangling and analysis that includes many other packages, e.g.:
  - dplyr for data management
  - tidyr for tidying your data
  - ggplot2 for data visualization
  - stringr for string filtering and manipulation (recommended by [@frog_phylo](https://twitter.com/frog_phylo/status/1265633360153579520?s=20))

### R packages for biodiversity informatics
- [bdchecks](https://bdverse.org/bdchecks/): performs data check for biodiversity data
- [bdclean](https://bdverse.org/bdclean/): cleans biodiversity data
- [bddwc](https://bdverse.org/bddwc/): standardizes data to Darwin Core (DwC) format
- [bdverse](https://bd-r.github.io/The-bdverse/index.html): suite of packages to facilitate biodiversity science for "inexperienced R users"
- [BIEN](https://cran.r-project.org/web/packages/BIEN/index.html): access to the Botanical Information and Ecology Network database; see [tutorial](https://github.com/bmaitner/RBIEN/blob/master/tutorials/RBIEN_tutorial.Rmd)
- [coordinatecleaner](https://ropensci.github.io/CoordinateCleaner/): spatial and temporal data quality
- [rgbif](https://github.com/ropensci/rgbif): access to data from GBIF via the GBIF API
- [ridigbio](https://github.com/idigbio/ridigbio): access to data from the iDigBio Portal via the iDigBio API
- [scrubr](https://docs.ropensci.org/scrubr/): biodiversity occurrence data quality
- [spocc](https://docs.ropensci.org/spocc/): access to multiple biodiversity occurrence sources, including the iDigBio Portal and GBIF, via APIs
- [spThin](https://cran.r-project.org/web/packages/spThin/spThin.pdf): tools for reducing spatial sampling bias of occurrence records (recommended by [@maverickpandion](https://twitter.com/maverickpandion/status/1265643410163187713?s=20))
- [taxize](https://docs.ropensci.org/taxize/): access to multiple taxonomic data sources via APIs
- [taxizedb](https://docs.ropensci.org/taxizedb/): access to taxonomic data sources via local database
- [wallace](https://wallaceecomod.github.io/): "R-based platform for reproducible modeling of species niches and distributions"; note that this requires rJava

### Other Important R packages

- [biogeo](https://cran.r-project.org/web/packages/biogeo/index.html): spatial data quality
- [checkpoint](https://cran.r-project.org/web/packages/checkpoint/vignettes/checkpoint.html): managing packages for reproducibility
- [dismo](https://cran.r-project.org/web/packages/dismo/index.html): species distribution modeling
- [ggmap](https://cran.r-project.org/web/packages/ggmap/index.html): geospatial analysis
- [knitr](https://yihui.org/knitr/): report generation from RMarkdown code
- [lubridate](https://lubridate.tidyverse.org/): for cleaning and converting dates
- [packrat](https://rstudio.github.io/packrat/): managing packages
- [rOpenSci](https://ropensci.org/packages/): "Our packages are carefully vetted, staff- and community-contributed R software tools that lower barriers to working with scientific data sources and data that support research applications on the web"

## Links for more learning

- [Twitter for R programmers](https://www.t4rstats.com/)
- [The Carpentries](https://carpentries.org/): "The Carpentries teaches foundational coding, and data science skills to researchers worldwide." This organization hosts workshops and makes its lesson plans available freely for self-learning and reuse. Main lessons are divided into...
  - [Software Carpentry](https://software-carpentry.org/lessons/)
  - [Data Carpentry](https://datacarpentry.org/lessons/)
  - [Library Carpentry](https://librarycarpentry.org/lessons/)
- [Hadley Wickham’s (of the Tidyverse) site with online books](http://hadley.nz/#teaching)
- [O'Reilly Head First Programming series](https://ssearch.oreilly.com/?q=Head+First+Programming)
- [Datacamp paid online courses](https://www.datacamp.com)
- [Tidyverse style guide for code](https://style.tidyverse.org/)
- [Unit testing for R](https://testthat.r-lib.org/)
- [Background reading on unit testing for R](http://r-pkgs.had.co.nz/tests.html)

## Non-R tools:
- [OpenRefine](https://openrefine.org/): can be used to clean data (ex. [Baldwin et al. 2017](https://doi.org/10.3732/ajb.1600326)).
- [Biodiverse](http://shawnlaffan.github.io/biodiverse/): "tool for the spatial analysis of diversity using indices based on taxonomic, phylogenetic, trait and matrix-based (e.g. genetic distance) relationships, as well as related environmental and temporal variations"
- [Glosario](https://carpentries.github.io/glosario/en/): A glossary of terms related to programming, designed for beginnings to reference
