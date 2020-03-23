# Download media based on specimen record search

## Conditions

1. User needs to identify media records based on specimen record search.
1. User needs to download media files automatically.
1. Download process cannot break when an unresolvable download URL is passed.
1. Output should be a directory with image files.
1. Number of images expected is relatively small (<100,000?).

## Example scenario

Researcher searches for herbarium specimens of species in the genus "Acer" and would like to download media associated with any records returned by this search. Media downloaded must retain relationship to specimen record.

## Solutions

For iDigBio, using R (view in browser): [download-media-from-specimens_solution.html](download-media-from-specimens_solution.html)
For iDigBio, using R (download to run locally): [download-media-from-specimens_solution.Rmd](download-media-from-specimens_solution.Rmd)
