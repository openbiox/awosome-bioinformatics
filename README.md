# Bioinformatics-Resources

**Abstract**: A curated list of resources for learning bioinformatics.

**Purpose**: 

- Provide some of bioinformatics learning resources for beginners
- Provide a profiling of bioinformatics

**Field**:

- Next generation sequencing (NGS)
- Bioinformatics Data Analysis

**Contents**: 

- [Resources](#resources)
    - [General](#general)
    - [Journal](#journal)
    - [Tools](#tools)
    - [Books&Tutorial](#books&tutorial)
- [Skills](#skills)
- [Institute](#institute)
- [People](#people)
- [Contributions](#contributions)

## Resources

### General

- [Wikipedia](https://en.wikipedia.org/wiki/Bioinformatics)
- [Org](http://www.bioinformatics.org/)

### Journal

- [Nature Method](http://www.nature.com/nmeth/index.html)
- [Nature Genetics](http://www.nature.com/ng/index.html)
- [Bioinformatics](https://academic.oup.com/bioinformatics)
- [BMC Bioinformatics](https://bmcbioinformatics.biomedcentral.com/)
- [Nucleic Acids Research](https://academic.oup.com/nar/pages/About)
- [Genome Research](http://genome.cshlp.org/)


### Tools

#### Package management

- [conda](https://conda.io/docs/intro.html)
- [Bioconductor](http://www.bioconductor.org/)
- [CRAN](https://cran.r-project.org/)
- [CPAN](http://www.cpan.org/)
- [PyPi](https://pypi.python.org/pypi)
- [npm](https://www.npmjs.com/)
- [bower](https://bower.io/)
- [gradle](https://gradle.org/)
- [ant](http://ant.apache.org/)
- [maven](https://maven.apache.org/)

#### Web Application Developement Framework

- [Galaxy](https://usegalaxy.org/)
- [Bootstrap](http://getbootstrap.com/2.3.2/)
- [Django](https://www.djangoproject.com/)
- [Yi](http://www.yiiframework.com/)

#### Web-based Service

- [UCSC](https://genome.ucsc.edu/)
- [NCBI](https://www.ncbi.nlm.nih.gov/)
- [ExPASy](http://www.expasy.org/)
- [EMBL-EBI](http://www.ebi.ac.uk/)
- [TCGA](https://cancergenome.nih.gov/)
- [COSMIC](http://cancer.sanger.ac.uk/cosmic)
- [St. Jude PeCan Data Portal](https://pecan.stjude.org/#/home)
- [DAVID Bioinformatics Resources](https://david.ncifcrf.gov/)
- [cBioPortal](http://www.cbioportal.org/)
- [Oncotator](http://portals.broadinstitute.org/oncotator/)

#### Local tools

##### Quality Control

- [FastQC](http://www.bioinformatics.bbsrc.ac.uk/projects/fastqc/)
- [PRINSEQ](https://sourceforge.net/projects/prinseq)
- [SolexaQA](https://sourceforge.net/projects/solexaqa)
- [fastx_toolkit](https://github.com/agordon/fastx_toolkit)
- [picard](https://github.com/broadinstitute/picard)

##### Alignment And Assembly

- [BWA](https://github.com/lh3/bwa)
- [STAR](https://github.com/alexdobin/STAR)
- [TMAP](https://github.com/iontorrent/TS/tree/master/Analysis/TMAP)
- [NovoAlign](http://www.novocraft.com/products/novoalign/)
- [GMAP](http://research-pub.gene.com/gmap/)
- [bowtie](https://github.com/BenLangmead/bowtie)
- [bowtie2](https://github.com/BenLangmead/bowtie2)
- [tophat2](https://github.com/infphilo/tophat)
- [hisat2](https://github.com/infphilo/hisat2)
- [Edean](http://www.genomic.ch/edena/)
- [ABySS](https://github.com/bcgsc/abyss)
- [SSAHA2](http://www.sanger.ac.uk/science/tools/ssaha2-0)
- [oases](https://github.com/dzerbino/oases)
- [Velvet](http://www.ebi.ac.uk/~zerbino/velvet/)
- [Trinity](https://github.com/trinityrnaseq/trinityrnaseq)
- [MapSplice2](http://www.netlab.uky.edu/p/bioinfo/MapSplice2)
- [RUM](https://github.com/itmat/rum)

##### Variant Detection (SNVs, INDELs, SVs)

- [GATK](https://software.broadinstitute.org/gatk/)
- [MuTect](http://archive.broadinstitute.org/cancer/cga/mutect/)
- [lofreq](http://csb5.github.io/lofreq/)
- [VarScan2](http://dkoboldt.github.io/varscan/)
- [freebayes](https://github.com/ekg/freebayes)
- [TVC](https://github.com/iontorrent/TS)
- [SomaticSniper](https://github.com/genome/somatic-sniper)
- [speedseq](https://github.com/hall-lab/speedseq)
- [FusionCatcher](https://github.com/ndaniel/fusioncatcher)
- [svtoolkit](http://software.broadinstitute.org/software/genomestrip/)
- [pindel](https://github.com/genome/pindel)
- [breakdancer](https://github.com/genome/breakdancer)
- [delly](https://github.com/dellytools/delly)
- [CNVkit](https://github.com/etal/cnvkit)

##### Variant Annotation

- [ANNOVAR](http://annovar.openbioinformatics.org/en/latest/)
- [SnpEff](http://snpeff.sourceforge.net/index.html)

##### Gene Expression Data Analysis

- [Cufflinks](http://cole-trapnell-lab.github.io/cufflinks/)
- [DESeq2](http://www.bioconductor.org/packages/release/bioc/html/DESeq2.html)
- [edgeR](http://www.bioconductor.org/packages/release/bioc/html/edgeR.html)
- [HTSeq](https://github.com/simon-anders/htseq)

##### ChIP-seq analysis

- [MACS](https://github.com/taoliu/MACS)
- [CEAS](http://liulab.dfci.harvard.edu/CEAS/)
- [MDSeqPos](https://bitbucket.org/cistrome/cistrome-applications-harvard/src/c477732c5c88/mdseqpos/)
- [conservation_plot](https://github.com/taoliu/taolib/blob/master/Scripts/conservation_plot.py)

##### Utils

- [biopython](http://biopython.org/wiki/Biopython)
- [IRanges](http://www.bioconductor.org/packages/release/bioc/html/IRanges.html)
- [org.Hs.eg.db](http://www.bioconductor.org/packages/release/data/annotation/html/org.Hs.eg.db.html)
- [Biobase](http://www.bioconductor.org/packages/release/bioc/html/Biobase.html)
- [GenomicAlignments](http://www.bioconductor.org/packages/release/bioc/html/GenomicAlignments.html)
- [GenomicRanges](http://www.bioconductor.org/packages/release/bioc/html/GenomicRanges.html)
- [Rsamtools](http://www.bioconductor.org/packages/release/bioc/html/Rsamtools.html)
- [jvarkit](https://github.com/lindenb/jvarkit)
- [htslib](https://github.com/samtools/htslib)
- [samtools](https://github.com/samtools/samtools)
- [bedtools](https://github.com/arq5x/bedtools2)
- [vcftools](https://github.com/vcftools/vcftools)
- [bcftools](https://github.com/samtools/bcftools)
- [bamtools](https://github.com/pezmaster31/bamtools)
- [bamUtil](https://github.com/statgen/bamUtil)
- [vcflib](https://github.com/vcflib/vcflib)
- [samstat](https://sourceforge.net/projects/samstat)
- [seqtk](https://github.com/lh3/seqtk)
- [sratools](http://ncbi.github.io/sra-tools/)
- [bcl2fastq2](https://support.illumina.com/sequencing/sequencing_software/bcl2fastq-conversion-software.html)
- [ucsc_utils](http://hgdownload.cse.ucsc.edu/admin/exe/)

##### Other

- [ImageJ](https://imagej.nih.gov/ij/download.html)
- [igraph](https://github.com/igraph/igraph)
- [root](https://root.cern.ch/)
- [boost](http://www.boost.org/)
- [libtbb](https://github.com/01org/tbb)

### Books&Tutorial

#### Chinese

- [鸟哥的 Linux 私房菜](http://cn.linux.vbird.org/)
- [菜鸟教程](http://www.runoob.com/)
- [Python学习手册：第4版（涵盖Python2.6和3.X）](http://product.dangdang.com/21063086.html)
- [Git 教程](http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000)

#### English

- [The Linux Command Line](http://linuxcommand.org/)
- [Learning Python, 5th Edition](http://shop.oreilly.com/product/0636920028154.do)
- [Python Examples](https://github.com/geekcomputers/Python)

## Skills

### Programming language

- [Shell](https://en.wikipedia.org/wiki/Command-line_interface)
- [Python](https://www.python.org/)
- [R](https://www.r-project.org/)
- [HTML](https://en.wikipedia.org/wiki/HTML)/[CSS](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
- [Javascript](https://en.wikipedia.org/wiki/JavaScript)
- [PHP](https://en.wikipedia.org/wiki/PHP)
- [SQL](https://en.wikipedia.org/wiki/SQL)
- [C/C++](https://en.wikipedia.org/wiki/C%2B%2B)
- [JAVA](https://www.java.com/en/)
- [Perl](https://www.perl.org/)

### Statistics

- [t-test](https://en.wikipedia.org/wiki/Student%27s_t-test)
- [Chi-squared test](https://en.wikipedia.org/wiki/Chi-squared_test)
- [ANOVA](https://en.wikipedia.org/wiki/Analysis_of_variance)
- [Normal distribution](https://en.wikipedia.org/wiki/Normal_distribution)
- [Wilcoxon signed-rank test](https://en.wikipedia.org/wiki/Wilcoxon_signed-rank_test)

### Code Management

- [Git](https://en.wikipedia.org/wiki/Git)
- [Github](https://en.wikipedia.org/wiki/GitHub)

## Institute or business company

- [Broad Institute](https://www.broadinstitute.org/)
- [The European Bioinformatics Institute](http://www.ebi.ac.uk/)
- [illumina](https://www.illumina.com/)
- [Life Technologies](http://corporate.thermofisher.com/en/home.html)
- [QIAGEN](https://www.qiagen.com/am/)

## People

- [Eric Lander](https://www.broadinstitute.org/bios/eric-s-lander)
- [Leroy Hood](https://www.systemsbiology.org/bio/leroy-hood/)
- [Mark Gerstein](http://www.gersteinlab.org/)
- [Shirley Liu](http://liulab.dfci.harvard.edu/)
- [Chuan He](https://chemistry.uchicago.edu/faculty/chuan-he)
- [Bing Ren](http://bioinformatics-renlab.ucsd.edu/rentrac/)
- [Job Dekker](http://jobdekkerlab.umassmed.edu/)
- [Michael Snyder](http://snyderlab.stanford.edu/)
- [Howard Chang](https://profiles.stanford.edu/howard-chang)
- [Mitch Guttman](http://changlab.stanford.edu)
- [John Rinn](http://www.rinnlab.com/)
- [Bradley E. Bernstein](http://bernstein.mgh.harvard.edu/)
- [Richard Michael Durbin](http://www.sanger.ac.uk/people/directory/durbin-richard)
- [Pavel A. Pevzner](http://cseweb.ucsd.edu/~ppevzner/)
- [Brendan J. Frey](http://www.psi.toronto.edu/~frey/)
- [Jinghui Zhang](https://www.stjude.org/directory/z/jinghui-zhang.html)


### Contributors

* [Jianfeng Li](https://github.com/Miachol)