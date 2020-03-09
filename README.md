# FASTQ FROM ACCESSION LIST
Get all sequences of interest from the accession list of a ncbi database in one fastq file.

# Using the script
```bash
python get_database_from_accession_list.py -id only_five_sequences.seq -o result
```
* The -id parameter is the path to the accession list file.
* The -o parameter is the name of the output file.

## Example of accesssion list (sequence.seq) from NCBI database
For example the first 5 ids of only_five_sequences.seq are :
```bash
NR_165790.1
NR_165789.1
NR_165788.1
NR_165787.1
NR_165786.1
```

# Dependencies
* [BioPython](https://biopython.org/)
* Accession list (sequence.seq) from your database.
