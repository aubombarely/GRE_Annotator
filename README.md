# GREAT
Genomic Repetitive Elements Annotation Tool
---

The Genomic Repetitive Elements Annotation Pipeline (GREAT)
Perl pipeline designed to combine different tools and 
programs to annotate repetitive elements.

There are different repetitive elements that we can find
in a genome:

1. Transposons
   - Class I:
     - LTR
       - LTR/Copia
       - LTR/Gypsy
       - ERV
     - Non-LTR
       - LINE
       - SINE 
   - Class II:
     - TIRs Order
     - Helitron Order
     - Maverick Order
   - MITEs
2. NUPTs and NUMTs
3. Satellite DNA (e.g. telomeres and centromeres)
4. rDNA and tDNA
5. High copy number genes (e.g. R-genes)

This script will run different tools to annotate from 1 to 4
and then it will filter 5 out of the possible 1-4 annotations.

The tools that this program uses are:
 - BLAST+ (ftp://ftp.ncbi.nlm.nih.gov/blast/executables/blast+/LATEST/).
 - GenomeTools (http://genometools.org/tools.html).
 - LTR_Finder (https://github.com/xzhub/LTR_Finder).
 - MGESCAN (https://github.com/MGEScan/mgescan).
 - LTR_retriever (https://github.com/oushujun/LTR_retriever).
 - HelitronScanner (https://sourceforge.net/p/helitronscanner).
 - MITE_Hunter (http://target.iplantcollaborative.org/).
 - MITE_FinderII (https://github.com/screamer/miteFinder).
 - RepeatMasker (http://www.repeatmasker.org/RMDownload.html).
 - RepeatModeler (http://www.repeatmasker.org/RepeatModeler/).
 - PFScan from InterProScan (https://github.com/ebi-pf-team/interproscan).
 - HMMER (http://hmmer.org/).
 - Infernal (http://eddylab.org/infernal/).
 - tRNAScan-SE (http://lowelab.ucsc.edu/tRNAscan-SE/).
 - BARRNAp (https://github.com/tseemann/barrnap).
 - Bedtools (https://bedtools.readthedocs.io/en/latest/content/bedtools-suite.html).
 - Muscle (https://www.ebi.ac.uk/Tools/msa/muscle/).

Additionally this program uses Bioperl (https://bioperl.org/).
