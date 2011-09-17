Final_Script_using_BLAST_2.2.25_executables_RUNALL.py is a python script that performs the following:

> Creates a BLASTable database from a FASTA file containing a list of all parts
> Performs a blast (2.2.25) of user's query sequence against database
> Displays top %n hits with additional information (User designates the number of hits %n)
> User can download the GenBank files of these top %n sequences (Y/N prompt)
> User is informed what RFC standard the top %n BioBricks hit(s) follow(s)

To USER:

The following files must be kept within the directory "Final_Script_using_BLAST_2.2.25_executables_RUNALL.py" is in:

> makeblastdb.exe
> blastn.exe
> All_Parts_NO_BLANKS_SIMPLE_HEADERS.fna.txt

The desired query sequence must be in FASTA format and saved within the file:

> Test_Sequence.fna.txt

Example of FASTA format:

> Test_Sequence_Header
aagcgtcgctaaa...

Only one header and sequence should be saved witin "Test_Sequence.fna.txt"

Future versions will allow or incluse:

> Multiple query sequences
> Prompt user for a threshold for the e-value
