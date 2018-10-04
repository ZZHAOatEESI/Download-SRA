# Download-SRA
## look for SRP project number

* search project number: PRJNA237362 in NBCI SRA database

* click on one of the sample link

* the forth field is Study, we can find SRP040765 there. 

## Download metadata from Run Selector
A slightly different set of metadata can be downloaded in a tab-delimited file from Run Selector offsite image.

* To download metadata for each Run in your Entrez query (https://www.ncbi.nlm.nih.gov/Traces/study/?go=home):

* search for SRP study number: SRP040765 (for example)

* Click the RunInfo Table button. This will generate a tabular SraRunTable.txt file with metadata available for each Run.

## download SRA data

* project ftp directory ftp://ftp-trace.ncbi.nlm.nih.gov/sra/sra-instant/reads/ByStudy/sra/SRP/SRP040/SRP040765/
* parse the metadata file and download (see Jupyter notebook file)
