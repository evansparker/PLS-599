# PLS-599
# This is a list of commands that can convert a fastq file to a fasta file.  
sed -n'1~4s/^@/>/p;2~4p' "fastqFile"> FastaOutputFile 
cut -d' ' -f1 < FastaOutputFile
