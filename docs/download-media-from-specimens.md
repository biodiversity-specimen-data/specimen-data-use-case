# Download media based on specimen record search

## Conditions

1. User needs to identify media records based on specimen record search.
1. User needs to download media files automatically.
1. Download process cannot break when an unresolvable download URL is passed.
1. Output should be a directory with image files.

## Example scenario

Researcher searches for herbarium specimens of species in the genus "Acer" and would like to download media associated with any records returned by this search. Media downloaded must retain relationship to specimen record.

## Solutions

For iDigBio, using R (download to run locally): [downloadMedia_ridigbio.Rmd](https://github.com/biodiversity-specimen-data/howto-specimen-data-R/blob/master/solutions/downloadMedia_ridigbio.Rmd)

For iDigBio, using R (view in browser): [downloadMedia_ridigbio.html](https://biodiversity-specimen-data.github.io/howto-specimen-data-R/downloadMedia_ridigbio.html)
