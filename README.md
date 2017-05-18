Genome Updater v0.03 by Vitor C. Piro (vitorpiro@gmail.com, http://github.com/pirovc)

 -d Database [all, genbank, refseq]
        Default: refseq
		
 -g Organism group [archaea, bacteria, fungi, invertebrate, metagenomes (only genbank), other (synthetic genomes - only genbank), plant, protozoa, vertebrate_mammalian, vertebrate_other, viral (only refseq)]
        Default: bacteria
		
 -c RefSeq Category [all, reference genome, representative genome, na]
        Default: all
		
 -l Assembly level [all, Complete Genome, Chromosome, Scaffold, Contig]
        Default: all
		
 -f File formats [genomic.fna.gz,assembly_report.txt, ... - check ftp://ftp.ncbi.nlm.nih.gov/genomes/all/README.txt for all file formats]
        Default: genomic.fna.gz
		
 -k Just check for updates, keep current version
 
 -x Delete any extra files inside the folder
 
 -u Output list of updated indices (added/removed)
 
 -o Output folder
        Default: db/
		
 -t Threads
        Default: 1
		
