# OmaDB 1.99.1 (Release data: 2018-12-28)
- fixes bioconductor CI warnings on missing links in deprecated functions

# OmaDB 1.99.0 (Release data: 2018-12-21)
- major refactoring of codebase:
  - getData split into getProtein, getGenome, getOMAGroup
  - renamed getAnnotation -> annotateSequence
  - renamed getXref -> searchSequence
- getProtein allows to retrieve many protein ids at once
- improved documenation by a lot.

# OmaDB 1.1.4 (Release date: 2018-10-11)
- format option (geneID2GO or GO2geneID) included in getInfo()
- automatic loading and updating of object attributes which are given as URLs upon accession 

# OmaDB 1.1.3 (Release date: 2018-09-03)
- Merging of the functions dealing with the members df into one master function getInfo()
- Increased support for paginated responses
- Increased support for larger responses
- Extension of the getData() function (extra param 'detail')
- Extension of the getGenomeAlignment() function (extra param 'rel_type')

# OmaDB 1.1.2 (Release date: 2018-09-03)
- addition of the bulkRetrieve() function that handles POST requests

# OmaDB 1.0.1 (Release date: 2018-06-29)
- Improved robustness of API calls

# OmaDB 1.0.0 (Release date: 2018-05-01)
Initial release in Bioconductor 3.7

# OmaDB 0.99.9 (Release date: 2017-10-14)
Initial release to Bioconductor development
