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

| Name | Description |
|:------|-----------|
| [conda](https://conda.io/docs/intro.html) | Package, dependency and environment management for any language: Python, R, Scala, Java, Javascript, C/ C++, FORTRAN
| [Bioconductor](http://www.bioconductor.org/) | Bioconductor provides tools for the analysis and comprehension of high-throughput genomic data. Bioconductor uses the R statistical programming language, and is open source and open development. It has two releases each year, 1383 software packages, and an active user community. Bioconductor is also available as an AMI (Amazon Machine Image) and a series of Docker images.
| [CRAN](https://cran.r-project.org/) | CRAN is a network of ftp and web servers around the world that store identical, up-to-date, versions of code and documentation for R. Please use the CRAN mirror nearest to you to minimize network load (10577 available packages).
| [CPAN](http://www.cpan.org/) | The Comprehensive Perl Archive Network (CPAN) currently has 185,183 Perl modules in 35,190 distributions, written by 13,071 authors, mirrored on 245 servers.
| [PyPi](https://pypi.python.org/pypi) | The Python Package Index is a repository of software for the Python programming language. There are currently 107772 packages here.
| [npm](https://www.npmjs.com/) | npm is the package manager for JavaScript and the world’s largest software registry. Discover packages of reusable code — and assemble them in powerful new ways.
| [bower](https://bower.io/) | Bower can manage components that contain HTML, CSS, JavaScript, fonts or even image files. Bower doesn’t concatenate or minify code or do anything else - it just installs the right versions of the packages you need and their dependencies.
| [gradle](https://gradle.org/) | From mobile apps to microservices, from small startups to big enterprises, Gradle helps teams build, automate and deliver better software, faster.
| [ant](http://ant.apache.org/) | Apache Ant is a Java library and command-line tool whose mission is to drive processes described in build files as targets and extension points dependent upon each other. The main known usage of Ant is the build of Java applications. Ant supplies a number of built-in tasks allowing to compile, assemble, test and run Java applications. Ant can also be used effectively to build non Java applications, for instance C or C++ applications. More generally, Ant can be used to pilot any type of process which can be described in terms of targets and tasks.
| [maven](https://maven.apache.org/) | Apache Maven is a software project management and comprehension tool. Based on the concept of a project object model (POM), Maven can manage a project's build, reporting and documentation from a central piece of information.

#### Web Application Developement Framework

| Name | Description
|------|------|
| [Galaxy](https://usegalaxy.org/) | Galaxy is an open source, web-based platform for data intensive biomedical research. If you are new to Galaxy start here or consult our help resources. You can install your own Galaxy by following the tutorial and choose from thousands of tools from the Tool Shed.
| [Bootstrap](http://getbootstrap.com/2.3.2/) | Bootstrap is the most popular HTML, CSS, and JS framework for developing responsive, mobile first projects on the web.
| [Django](https://www.djangoproject.com/) | Django is a high-level Python Web framework that encourages rapid development and clean, pragmatic design. Built by experienced developers, it takes care of much of the hassle of Web development, so you can focus on writing your app without needing to reinvent the wheel. It’s free and open source.
| [Yi](http://www.yiiframework.com/) | Yii is a high-performance PHP framework best for developing Web 2.0 applications.

#### Web-based Service

| Name | Description
|------|------|
| [UCSC](https://genome.ucsc.edu/) | On June 22, 2000, UCSC and the other members of the International Human Genome Project consortium completed the first working draft of the human genome assembly, forever ensuring free public access to the genome and the information it contains. A few weeks later, on July 7, 2000, the newly assembled genome was released on the web at http://genome.ucsc.edu, along with the initial prototype of a graphical viewing tool, the UCSC Genome Browser. In the ensuing years, the website has grown to include a broad collection of vertebrate and model organism assemblies and annotations, along with a large suite of tools for viewing, analyzing and downloading data.
| [NCBI](https://www.ncbi.nlm.nih.gov/) | The National Center for Biotechnology Information advances science and health by providing access to biomedical and genomic information.
| [ExPASy](http://www.expasy.org/) | ExPASy is the SIB Bioinformatics Resource Portal which provides access to scientific databases and software tools (i.e., resources) in different areas of life sciences including proteomics, genomics, phylogeny, systems biology, population genetics, transcriptomics etc. (see Categories in the left menu). On this portal you find resources from many different SIB groups as well as external institutions.
| [EMBL-EBI](http://www.ebi.ac.uk/) | At EMBL-EBI, we use bioinformatics — the science of storing, sharing and analysing biological data — to help people everywhere understand how living systems work, and what makes them change.
| [TCGA](https://cancergenome.nih.gov/) | The Genomic Data Commons (GDC) Data Portal is an interactive data system for researchers to search, download, upload, and analyze harmonized cancer genomic data sets, including TCGA.
| [COSMIC](http://cancer.sanger.ac.uk/cosmic) | COSMIC, the Catalogue Of Somatic Mutations In Cancer, is the world's largest and most comprehensive resource for exploring the impact of somatic mutations in human cancer.
| [St. Jude PeCan Data Portal](https://pecan.stjude.org/#/home) | PeCan provides interactive visualizations of pediatric cancer mutations across various projects at St. Jude Children's Research Hospital and its collaborators.(SAMPLES: 2,422; PATIENTS: 2,299; DIAGNOSES: 17; GENES: 11,770; MUTATIONS: 29,578)
| [DAVID Bioinformatics Resources](https://david.ncifcrf.gov/) | The Database for Annotation, Visualization and Integrated Discovery (DAVID ) v6.8 comprises a full Knowledgebase update to the sixth version of our original web-accessible programs. DAVID now provides a comprehensive set of functional annotation tools for investigators to understand biological meaning behind large list of genes.
| [cBioPortal](http://www.cbioportal.org/) | The cBioPortal for Cancer Genomics provides visualization, analysis and download of large-scale cancer genomics data sets.
| [Oncotator](http://portals.broadinstitute.org/oncotator/) | Oncotator is a web application for annotating human genomic point mutations and indels with data relevant to cancer researchers. Annotations are aggregated from the following resources:Genomic Annotations;Protein Annotations;Cancer Variant Annotations;Non-Cancer Variant Annotations.

#### Local tools


##### NGS Quality Control

 Name | Description | Tag
------|------|:-------:
[FastQC](http://www.bioinformatics.bbsrc.ac.uk/projects/fastqc/) | A quality control tool for high throughput sequence data. | quality control
[PRINSEQ](https://sourceforge.net/projects/prinseq) | A bioinformatics tool to PRe-process and show INformation of SEQuence data. The tool is written in Perl and can be helpful if you want to filter, reformat, or trim your sequence data. It also generates basic statistics for your sequences. | preprocess
[SolexaQA](https://sourceforge.net/projects/solexaqa) | SolexaQA is a software to calculate quality statistics and visual representations of data quality for second-generation sequencing data. | quality control
[fastx_toolkit](https://github.com/agordon/fastx_toolkit) | The FASTX-Toolkit is a collection of command line tools for Short-Reads FASTA/FASTQ files preprocessing. | preprocess
[picard](https://github.com/broadinstitute/picard) | A set of Java command line tools for manipulating high-throughput sequencing (HTS) data and formats | preprocess


##### NGS Alignment And Assembly

 Name | Description | Tag
------|------|:-------:
[BWA](https://github.com/lh3/bwa) | Mapping low-divergent sequences against a large reference genome, such as the human genome | alignment DNA-seq
[STAR](https://github.com/alexdobin/STAR) | Ultrafast universal RNA-seq aligner |  alignment RNA-seq
[TMAP](https://github.com/iontorrent/TS/tree/master/Analysis/TMAP) | TMAP is a fast and accurate alignment software for short and long nucleotide sequences produced by next-generation sequencing technologies. | alignment panel
[NovoAlign](http://www.novocraft.com/products/novoalign/) | Powerful tool designed for mapping of short reads onto a reference genome from Illumina, Ion Torrent, and 454 NGS platforms. | alignment short
[GMAP](http://research-pub.gene.com/gmap/) | A Genomic Mapping and Alignment Program for mRNA and EST Sequences and Genomic Short-read Nucleotide Alignment Program | alignment short
[bowtie](https://github.com/BenLangmead/bowtie) |An ultrafast memory-efficient short read aligner |alignment CHIP-seq short
[bowtie2](https://github.com/BenLangmead/bowtie2) | A fast and sensitive gapped read aligner | alignment CHIP-seq short
[tophat2](https://github.com/infphilo/tophat) | A fast splice junction mapper for RNA-Seq reads | alignment  expression
[hisat2](https://github.com/infphilo/hisat2) | A fast splice junction mapper for RNA-Seq reads | alignment  expression
[Edean](http://www.genomic.ch/edena/) | De novo short reads assembler | assembler short
[ABySS](https://github.com/bcgsc/abyss) | ABySS is a de novo sequence assembler intended for short paired-end reads and large genomes. | assembler, short
[SSAHA2](http://www.sanger.ac.uk/science/tools/ssaha2-0) | SSAHA2 (Sequence Search and Alignment by Hashing Algorithm) is a pairwise sequence alignment program designed for the efficient mapping of sequencing reads onto genomic reference sequences. SSAHA2 reads of most sequencing platforms (ABI-Sanger, Roche 454, Illumina-Solexa) and a range of output formats (SAM, CIGAR, PSL etc.) are supported. A pile-up pipeline for analysis and genotype calling is available as a separate package.  | alignment
[oases](https://github.com/dzerbino/oases) | De novo transcriptome assembler based on the Velvet genome assembler core. |assembler RNA-seq
[Velvet](http://www.ebi.ac.uk/~zerbino/velvet/) | Sequence assembler for very short reads | assembler short
[Trinity](https://github.com/trinityrnaseq/trinityrnaseq) | Trinity, developed at the Broad Institute and the [Hebrew University of Jerusalem] (http://www.cs.huji.ac.il), represents a novel method for the efficient and robust de novo reconstruction of transcriptomes from RNA-seq data. Trinity combines three independent software modules: Inchworm, Chrysalis, and Butterfly, applied sequentially to process large volumes of RNA-seq reads. Trinity partitions the sequence data into many individual de Bruijn graphs, each representing the transcriptional complexity at a given gene or locus, and then processes each graph independently to extract full-length splicing isoforms and to tease apart transcripts derived from paralogous genes. | alignment RNA-seq
[MapSplice2](http://www.netlab.uky.edu/p/bioinfo/MapSplice2) | MapSplice is a software for mapping RNA-seq data to reference genome for splice junction discovery that depends only on reference genome, and not on any further annotations. | alignment RNA-seq
[RUM](https://github.com/itmat/rum) | RUM is an alignment, junction calling, and feature quantification pipeline specifically designed for Illumina RNA-Seq data. | alignment RNA-seq

##### NGS Variant Detection (SNVs, INDELs, SVs)
 Name | Description | Tag
------|------|:-------:
[GATK](https://software.broadinstitute.org/gatk/) | Developed by the Data Science and Data Engineering group at the Broad Institute, the toolkit offers a wide variety of tools with a primary focus on variant discovery and genotyping. Its powerful processing engine and high-performance computing features make it capable of taking on projects of any size | SNVs INDELs
[MuTect](http://archive.broadinstitute.org/cancer/cga/mutect/) | A method developed at the Broad Institute for the reliable and accurate identification of somatic point mutations in next generation sequencing data of cancer genomes | SNVs
[lofreq](http://csb5.github.io/lofreq/) | Sensitive variant calling from sequencing data |SNVs, INDELs
[VarScan2](http://dkoboldt.github.io/varscan/) | Variant calling and somatic mutation/CNV detection for next-generation sequencing data | SNVs INDELs
[freebayes](https://github.com/ekg/freebayes) | Bayesian haplotype-based polymorphism discovery and genotyping. | SNVs INDELs
[TVC](https://github.com/iontorrent/TS) | TVC is the Torrent Suite variant caller for Ion Torrent next-generation sequencing platform. | SNVs INDELs
[SomaticSniper](https://github.com/genome/somatic-sniper) | The purpose of this program is to identify single nucleotide positions that are different between tumor and normal (or in theory, any two bam files). It takes a tumor bam and a normal bam and compares the two to determine the differences. |SNVs INDELs
[speedseq](https://github.com/hall-lab/speedseq) | A flexible framework for rapid genome analysis and interpretation |SNVs INDELs SVs
[FusionCatcher](https://github.com/ndaniel/fusioncatcher) | FusionCatcher searches for novel/known somatic fusion genes, translocations, and chimeras in RNA-seq data (paired-end or single-end reads from Illumina NGS platforms like Solexa/HiSeq/NextSeq/MiSeq/MiniSeq) from diseased samples. | SVs
[svtoolkit](http://software.broadinstitute.org/software/genomestrip/) | Genome STRiP (Genome STRucture In Populations) is a suite of tools for discovering and genotyping structural variations using sequencing data. The methods are designed to detect shared variation using data from multiple individuals. | SVs
[pindel](https://github.com/genome/pindel) | Detect breakpoints of large deletions, medium sized insertions, inversions, tandem duplications and other structural variants at single-based resolution from next-gen sequence data |INDELs SVs
[breakdancer](https://github.com/genome/breakdancer) | A Cpp package that provides genome-wide detection of structural variants from next generation paired-end sequencing reads. It includes two complementary programs. BreakDancerMax predicts five types of structural variants: insertions, deletions, inversions, inter- and intra-chromosomal translocations from next-generation short paired-end sequencing reads using read pairs that are mapped with unexpected separation distances or orientation.  BreakDancerMini focuses on detecting small indels (usually between 10bp and 100bp) using normally mapped read pairs. | SVs
[delly](https://github.com/dellytools/delly) | Delly2 is an integrated structural variant prediction method that can discover, genotype and visualize deletions, tandem duplications, inversions and translocations at single-nucleotide resolution in short-read massively parallel sequencing data. It uses paired-ends and split-reads to sensitively and accurately delineate genomic rearrangements throughout the genome. Structural variants can be visualized using Delly-maze and Delly-suave. | SVs
[CNVkit](https://github.com/etal/cnvkit) | A command-line toolkit and Python library for detecting copy number variants and alterations genome-wide from targeted DNA sequencing. | CNVs

##### NGS Variant Annotation
 Name | Description | Tag
------|------|:-------:
[ANNOVAR](http://annovar.openbioinformatics.org/en/latest/) | An efficient software tool to utilize update-to-date information to functionally annotate genetic variants detected from diverse genomes (including human genome hg18, hg19, hg38, as well as mouse, worm, fly, yeast and many others | annotation perl
[SnpEff](http://snpeff.sourceforge.net/index.html) | Genetic variant annotation and effect prediction toolbox. | annotation

##### NGS Gene Expression Data Analysis
 Name | Description | Tag
------|------|:-------:
[Cufflinks](http://cole-trapnell-lab.github.io/cufflinks/) | Cufflinks assembles transcripts, estimates their abundances, and tests for differential expression and regulation in RNA-Seq samples. It accepts aligned RNA-Seq reads and assembles the alignments into a parsimonious set of transcripts. Cufflinks then estimates the relative abundances of these transcripts based on how many reads support each one, taking into account biases in library preparation protocols. | expression
[DESeq2](http://www.bioconductor.org/packages/release/bioc/html/DESeq2.html) | Differential gene expression analysis based on the negative binomial distribution. Estimate variance-mean dependence in count data from high-throughput sequencing assays and test for differential expression based on a model using the negative binomial distribution. |  expression R package


##### NGS Utils
 Name | Description | Tag
------|------|:-------:
[htslib](https://github.com/samtools/htslib) | C-library for handling high-throughput sequencing data | library
[samtools](https://github.com/samtools/samtools) | Mpileup and other tools for handling SAM, BAM, CRAM | SAM BAM
[bedtools](https://github.com/arq5x/bedtools2) | A powerful toolset for genome arithmetic. [More](http://bedtools.readthedocs.io/en/latest/) detail. | BED BAM FASTQ
[vcftools](https://github.com/vcftools/vcftools) | A set of tools written in Perl and C++ for working with VCF files, such as those generated by the 1000 Genomes Project | VCF
[bcftools](https://github.com/samtools/bcftools) | Calling and other tools for handling VCF, BCF | BCF VCF
[bamtools](https://github.com/pezmaster31/bamtools) | BamTools provides both a programmer's API and an end-user's toolkit for handling BAM files. | BAM
[sratools](http://ncbi.github.io/sra-tools/) | The SRA Toolkit and SDK from NCBI is a collection of tools and libraries for using data in the INSDC Sequence Read Archives. | SRA
[bamUtil](https://github.com/statgen/bamUtil) | Provide some programs for working on SAM/BAM files. | BAM
[vcflib](https://github.com/vcflib/vcflib) | A simple C++ library for parsing and manipulating VCF files, + many command-line utilities. | VCF
[samstat](https://sourceforge.net/projects/samstat) | SAMStat displays various properties of next-generation sequencing reads stored in SAM/BAM format. | SAM
[jvarkit](https://github.com/lindenb/jvarkit) | Java utilities for Bioinformatics. | library JAVA
[HTSeq](https://github.com/simon-anders/htseq) | A Python library to facilitate processing and analysis of data from high-throughput sequencing (HTS) experiments | expression Python
[seqtk](https://github.com/lh3/seqtk) | Seqtk is a fast and lightweight tool for processing sequences in the FASTA or FASTQ format. It seamlessly parses both FASTA and FASTQ files which can also be optionally compressed by gzip. |  FASTA FASTQ
[bcl2fastq2](https://support.illumina.com/sequencing/sequencing_software/bcl2fastq-conversion-software.html) | bcl2fastq Conversion Software both demultiplexes data and converts BCL files generated by Illumina sequencing systems to standard FASTQ file formats for downstream analysis. | BCL FASTQ
[ucsc_utils](http://hgdownload.cse.ucsc.edu/admin/exe/) | UCSC genome browser 'kent' bioinformatic utilities (blat, liftOver, and other command line utilities) are freely downloadable for academic, noncommercial, and personal use. | utils

##### Other

 Name | Description | Tag       
------|------|:-------------
[MACS](https://github.com/taoliu/MACS) | MACS -- Model-based Analysis of ChIP-Seq. [More](http://liulab.dfci.harvard.edu/MACS/) detail. | CHIP-seq
[CESA](http://liulab.dfci.harvard.edu/CEAS/) | Cis-regulatory Element Annotation System | annotation
[ImageJ](https://imagej.nih.gov/ij/download.html) | ImageJ is a public domain Java image processing program inspired by NIH Image for the Macintosh. It runs, either as an online applet or as a downloadable application, on any computer with a Java 1.4 or later virtual machine. Downloadable distributions are available for Windows, Mac OS, Mac OS X and Linux. | image
[igraph](https://github.com/igraph/igraph) | igraph is a library for creating and manipulating graphs. It is intended to be as powerful (ie. fast) as possible to enable the analysis of large graphs. | Network Analysis
[root](https://root.cern.ch/) | A modular scientific software framework. It provides all the functionalities needed to deal with big data processing, statistical analysis, visualisation and storage. It is mainly written in C++ but integrated with other languages such as Python and R. | library C++
[boost](http://www.boost.org/) | Boost provides free peer-reviewed portable C++ source libraries. | library, C++
[libtbb](https://github.com/01org/tbb) | Intel(R) Threading Building Blocks (Intel(R) TBB) lets you easily write parallel C++ programs that take full advantage of multicore performance, that are portable, composable and have future-proof scalability. | library computation

### Books&Tutorial

#### Chinese

- [鸟哥的 Linux 私房菜](http://cn.linux.vbird.org/): 本书是最具知名度的Linux入门书《鸟哥的Linux私房菜基础学习篇》的最新版，全面而详细地介绍了Linux操作系统。全书分为5个部分：第一部分着重说明Linux的起源及功能，如何规划和安装Linux主机；第二部分介绍Linux的文件系统、文件、目录与磁盘的管理；第三部分介绍文字模式接口 shell和管理系统的好帮手shell脚本，另外还介绍了文字编辑器vi和vim的使用方法；第四部分介绍了对于系统安全非常重要的Linux账号的管理，以及主机系统与程序的管理，如查看进程、任务分配和作业管理；第五部分介绍了系统管理员(root)的管理事项，如了解系统运行状况、系统服务，针对登录文件进行解析，对系统进行备份以及核心的管理等。本书内容丰富全面，基本概念的讲解非常细致，深入浅出。各种功能和命令的介绍，都配以大量的实例操作和详尽的解析。本书是初学者学习Linux不可多得的一本入门好书。
- [菜鸟教程](http://www.runoob.com/): 菜鸟教程提供了最全的基础编程技术教程: HTML/CSS, Bootstrap, Javascript, PHP, Django, Linux, Docker, C/C++, JAVA, Perl, SQL
- [Python学习手册：第4版（涵盖Python2.6和3.X）](http://product.dangdang.com/21063086.html): 学习Python的主要内建对象类型：数字、列表和字典。使用Python语句创建和处理对象，并且学习Python的通用语法模型。使用函数构造和重用代码，函数是Python的基本过程工具。学习Python模块：封装语句、函数以及其他工具，以便构建较大的组件。学习Python的面向对象编程工具，用于组织程序代码。学习异常处理模型，以及用于编写较大程序的开发工具。了解高级Python工具，如装饰器、描述器、元类和Unicode处理等。

#### English

- [The Linux Command Line](http://linuxcommand.org/): Designed for the new command line user, this 540-page volume covers the same material as LinuxCommand.org but in much greater detail. In addition to the basics of command line use and shell scripting, The Linux Command Line includes chapters on many common programs used on the command line, as well as more advanced topics.
- [Learning Python, 5th Edition](http://shop.oreilly.com/product/0636920028154.do): Get a comprehensive, in-depth introduction to the core Python language with this hands-on book. Based on author Mark Lutz’s popular training course, this updated fifth edition will help you quickly write efficient, high-quality code with Python. It’s an ideal way to begin, whether you’re new to programming or a professional developer versed in other languages.

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

## Institute or business company

| Name | Description 
|:------:|:-------------
| [Broad Institute](https://www.broadinstitute.org/) | Broad Institute is committed to making the extensive data, methods, and technologies it generates rapidly and readily accessible to the scientific community to drive biomedical progress around the world.
| [The European Bioinformatics Institute](http://www.ebi.ac.uk/) | Provide freely available data and bioinformatics services to the scientific community; Contribute to the advancement of biology through investigator-driven research. Provide advanced bioinformatics training to scientists at all levels.
| [illumina](https://www.illumina.com/) | Illumina, Inc. is an American company incorporated in April 1998 that develops, manufactures and markets integrated systems for the analysis of genetic variation and biological function. In 2014, Illumina was named the world's smartest company by MIT Technology Review. Using its technologies, the company provides a line of products and services that serve the sequencing, genotyping and gene expression markets. This technology had purportedly by 2013 reduced the cost of sequencing a human genome to US$4,000, down from a price of US$1 million in 2007.[1] Customers include genomic research centers, pharmaceutical companies, academic institutions, clinical research organizations and biotechnology companies. Its tools provide researchers with the capability to perform genetic tests needed to extract medical information from advances in genomics and proteomics. Its headquarters are located in San Diego, California.
| [Life Technologies](http://corporate.thermofisher.com/en/home.html) | Life Technologies Corporation was a biotech company founded in November 2008 through a US$6.7 billion merger of Invitrogen Corporation and Applied Biosystems Inc. The joint sales of the combined companies were about $3.5 billion; they had about 9,500 employees, and owned more than 3,600 licenses and patents.
| [QIAGEN](https://www.qiagen.com/am/) | Qiagen is a provider of sample and assay technologies for molecular diagnostics, applied testing, academic and pharmaceutical research. Consolidated under the Dutch holding Qiagen N.V., the company operates more than 35 offices in over 25 countries.[1] Qiagen’s shares are listed at the technology-focused U.S. stock exchange Nasdaq (using ticker QGEN) and at the Frankfurt Stock Exchange in the Prime Standard (using ticker QIA). Peer M. Schatz is the company’s Chief Executive Officer. The main operative headquarters are located in Hilden, Germany (near Düsseldorf).

## People
| Name | Title 
|:---------:|---------
| [Eric Lander](https://www.broadinstitute.org/bios/eric-s-lander) | President and founding director of the Broad Institute of MIT and Harvard |
| [Leroy Hood](https://www.systemsbiology.org/bio/leroy-hood/) | President and Co-founder, ISB; SVP & CSO, Providence St. Joseph Health 
| [Mark Gerstein](http://www.gersteinlab.org/) | Williams Professor of Biomedical Informatics, Yale
| [Shirley Liu](http://liulab.dfci.harvard.edu/) | Professor of Biostatistics and Computational Biology, Harvard T.H. Chan School of Public Health
| [Chuan He](https://chemistry.uchicago.edu/faculty/chuan-he) | John T. Wilson Distinguished Service Professor
| [Bing Ren](http://bioinformatics-renlab.ucsd.edu/rentrac/) | Professor, Department of Cellular and Molecular Medicine, UCSD School of Medicine
| [Job Dekker](http://jobdekkerlab.umassmed.edu/) | Professor and co-director Program in Systems Biology Department of Biochemistry and Molecular Pharmacology
| [Michael Snyder](http://snyderlab.stanford.edu/) | STANFORD W. ASCHERMAN, MD, FACS, PROFESSOR IN GENETICS
| [Howard Chang](https://profiles.stanford.edu/howard-chang) | Professor of Dermatology
| [Mitch Guttman](http://changlab.stanford.edu) | Assistant Professor in the Division of Biology and Biological Engineering at the California Institute of Technology
| [John Rinn](http://www.rinnlab.com/) | Principal Investigator Professor
| [Bradley E. Bernstein](http://bernstein.mgh.harvard.edu/) | Institute Member, Director of the Epigenomics Program
| [Richard Michael Durbin](http://www.sanger.ac.uk/people/directory/durbin-richard) | British computational biologist, Senior Group Leader at the Wellcome Trust Sanger Institute and an Honorary Professor of Computational Genomics at the University of Cambridge
| [Pavel A. Pevzner](http://cseweb.ucsd.edu/~ppevzner/)| Ronald R. Taylor Professor of Computer Science Director, NIH Center for Computational Mass Spectrometry
| [Brendan J. Frey](http://www.psi.toronto.edu/~frey/) | Professor Department of Electrical and Computer Engineering, and Banting and Best Department of Medical Research, and Department of Computer Science University of Toronto
| [Jinghui Zhang](https://www.stjude.org/directory/z/jinghui-zhang.html) | Chair, Department of Computational Biology St. Jude Endowed Chair in Bioinformatics


### Contributors

* [Jianfeng Li](https://github.com/Miachol)