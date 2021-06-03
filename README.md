# Illuminating the bacterial microbiome of Australian ticks with 16S and Rickettsia-specific next-generation sequencing

These scripts were used to bioinformatically process the 16S V1-2 paired-end MiSeq Illumina NGS data associated with the manuscript entitled "Illuminating the bacterial microbiome of Australian ticks from companion animals with next-generation sequencing", authored by Telleasha L. Greay, Kimberly L. Evasco, Megan L. Evans, Charlotte L. Oskam, Paola Magni, Una M. Ryan and Peter J. Irwin. The shells were painstakingly written by PhD student Telleasha, so if you use them, credit (reference to the paper and this github repository) would be much appreciated :) The raw data is deposited in NCBI's sequence read archive (SRA) under the BioProject accession PRJNA640465. These shells can be modified to process other amplicon NGS datasets too.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------

Before running the shell scripts...

--------------------------------------------------------------------------------------------------------------------------------------------------------------------

1. Install required software:

USEARCH v10.0 - https://www.drive5.com/usearch/manual10/

USEARCH v9.2 - https://drive5.com/usearch/manual9.2/

USEARCH v8.1 - https://drive5.com/usearch/manual8.1/

USEARCH installation instructions: https://drive5.com/usearch/manual8.1/install.html

Optional software installation: http://www.figlet.org/

Figlet is not required, it just makes command line a little more fun :) 

Note! These shells were written using a Linux system. For Windows, replace forward-slashes with backslashes.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------

2. Set $PATH variables for the different USEARCH versions, otherwise you need to specify the full path to the USEARCH programs in each script. 

For help, see:

https://en.wikipedia.org/wiki/PATH_(variable)

https://linuxize.com/post/how-to-add-directory-to-path-in-linux/

https://helpdeskgeek.com/windows-10/add-windows-path-environment-variable/

--------------------------------------------------------------------------------------------------------------------------------------------------------------------

3. Create a folder for your analysis, save the shell scripts within this folder with your raw data in a sub-folder, and update Script 1 with the raw data folder name.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------

Have fun :) 
