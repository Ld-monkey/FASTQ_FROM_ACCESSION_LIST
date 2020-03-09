# FASTQ FROM ACCESSION LIST
Get all sequences of interest from the accession list of a ncbi database in one fastq file.

# Using the script
```bash
python get_database_from_accession_list.py -id only_five_accesssion_list.seq -o result
```
* The -id parameter is the path to the accesssion list file.
* The -o parameter is the name of the output file.

# Dependencies
* [BioPython](https://biopython.org/)
* Accession list (sequence.seq) from your database.
