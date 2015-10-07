# extract_seqs
extracting seqs from the count tables


#This is a program that takes a list of read names and well names and creates a fasta file of the reads we want for a single locus.
#input: text file with list of reads and well names associated
#for now, header on text file needs to read "name" and "well"
#also need working directory to contain all fasta files for a locus (.unique are best b/c smallest)
#NB: will break if the names of the wells are not represented in the file list

