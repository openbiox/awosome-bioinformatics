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
  - [Books&Tutorial](#bookstutorial)

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
  - [CDD](https://www.ncbi.nlm.nih.gov/Structure/cdd/cdd.shtml)
- [ExPASy](http://www.expasy.org/)
- [EMBL-EBI](http://www.ebi.ac.uk/)
- [TCGA](https://cancergenome.nih.gov/)
- [COSMIC](http://cancer.sanger.ac.uk/cosmic)
- [St. Jude PeCan Data Portal](https://pecan.stjude.org/#/home)
- [BIG Data Center](http://bigd.big.ac.cn/)
- [DAVID Bioinformatics Resources](https://david.ncifcrf.gov/)
- [cBioPortal](http://www.cbioportal.org/)
  - [Oncoprinter](http://www.cbioportal.org/oncoprinter.jsp)
  - [MutationMapper](http://www.cbioportal.org/mutation_mapper.jsp)
- [Oncotator](http://portals.broadinstitute.org/oncotator/)
- [QIAGEN Analysis Platform](https://www.qiagenbioinformatics.com/)
- [Wordcloud](https://www.jasondavies.com/wordcloud/)
- [Omictools](https://omictools.com/sequencing-category)
- [CSCD - Cancer-specific circular RNAs database](http://gb.whu.edu.cn/CSCD/)
- [iCoMut](http://firebrowse.org/iCoMut/?cohort=LAML)
- [UniProt](http://www.uniprot.org/)
- [Pfam](http://pfam.xfam.org/)
- [SMART](http://smart.embl-heidelberg.de/help/smart_glossary.shtml)
- [STRING](https://string-db.org/)
- [DiseaseEnhancer](http://biocc.hrbmu.edu.cn/DiseaseEnhancer/)
- [SEECancer](http://biocc.hrbmu.edu.cn/SEECancer/)
- [eQTL Browser](http://eqtl.rc.fas.harvard.edu/eqtlbrowser/about.html)
- [Cistrome Project](http://www.cistrome.org/Cistrome/Cistrome_Project.html)
  - [Cistrome Data Browser](http://cistrome.org/db/#/)
  - [Cistrome Cancer](http://cistrome.org/CistromeCancer/)
  - [Chromatin Regulator Cistrome](http://cistrome.org/cr/)

#### Sequencing Data Portal

- [GDC](https://portal.gdc.cancer.gov/)
- [EGA](https://www.ebi.ac.uk/ega/home)
- [dbGaP](https://www.ncbi.nlm.nih.gov/gap)
- [DDBJ](http://www.ddbj.nig.ac.jp/)
- [GEO](https://www.ncbi.nlm.nih.gov/geo/)
- [ICGC](https://dcc.icgc.org/)

#### Local tools

##### Quality Control

- [FastQC](http://www.bioinformatics.bbsrc.ac.uk/projects/fastqc/)
- [PRINSEQ](https://sourceforge.net/projects/prinseq)
- [SolexaQA](https://sourceforge.net/projects/solexaqa)
- [fastx_toolkit](https://github.com/agordon/fastx_toolkit)
- [picard](https://github.com/broadinstitute/picard)
- [ngsqctoolkit](http://14.139.61.3:8080/ngsqctoolkit/)
- [MultiQC](https://github.com/ewels/MultiQC)
- [mosdepth](https://github.com/brentp/mosdepth)

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
- [MECAT](https://github.com/xiaochuanle/MECAT)

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
- [speedseq](https://github.com/hall-lab/speedseq)
- [GRIDSS](https://github.com/PapenfussLab/gridss)
- [PancanQTL](http://bioinfo.life.hust.edu.cn/PancanQTL/)
- [TumorFusions](http://www.tumorfusions.org/)

##### Variant Annotation

- [ANNOVAR](http://annovar.openbioinformatics.org/en/latest/)
- [SnpEff](http://snpeff.sourceforge.net/index.html)
- [gemini](https://github.com/arq5x/gemini)
- [VEP](http://www.ensembl.org/info/docs/tools/vep/index.html)
- [Variant Annotation Integrator](http://genome.ucsc.edu/cgi-bin/hgVai)

##### Gene Expression Data Analysis

- [Cufflinks](http://cole-trapnell-lab.github.io/cufflinks/)
- [DESeq2](http://www.bioconductor.org/packages/release/bioc/html/DESeq2.html)
- [edgeR](http://www.bioconductor.org/packages/release/bioc/html/edgeR.html)
- [HTSeq](https://github.com/simon-anders/htseq)
- [sRNAnalyzer](http://srnanalyzer.systemsbiology.net/)

##### Expression Quantitative Trait Loci, eQTL

- [CaVEMaN](https://github.com/funpopgen/CaVEMaN)

##### ChIP-seq analysis

- [MACS](https://github.com/taoliu/MACS)
- [CEAS](http://liulab.dfci.harvard.edu/CEAS/)
- [MDSeqPos](https://bitbucket.org/cistrome/cistrome-applications-harvard/src/c477732c5c88/mdseqpos/)
- [conservation_plot](https://github.com/taoliu/taolib/blob/master/Scripts/conservation_plot.py)

##### Work flow

- [bcbio-nextgen](https://github.com/chapmanb/bcbio-nextgen)
- [nextflow](https://github.com/nextflow-io/nextflow)
- [orange3](https://github.com/biolab/orange3)

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
- [MeQA](http://life.tongji.edu.cn/meqa/index.html)
- [IdCheck](http://eqtl.rc.fas.harvard.edu/idcheck/)

##### Statistical and Visualization

- [medcalc](https://www.medcalc.org/index.php)
- [GraphPad](http://www.graphpad.com/)
- [ImageJ](https://imagej.nih.gov/ij/download.html)
- [SPSS](https://en.wikipedia.org/wiki/SPSS)
- [R](https://www.r-project.org/)
- [gvmap](https://github.com/ytdai/gvmap)
- [easySVG](https://github.com/ytdai/easySVG)
- [hexmapr](https://github.com/sassalley/hexmapr)
- [clustergrammer](https://github.com/MaayanLab/clustergrammer)
- [chromVAR](https://github.com/GreenleafLab/chromVAR)
- [echarts](https://github.com/ecomfe/echarts)
- [plotly](https://github.com/plotly/plotly.js)

##### Text editor and IDE

- [Vim](http://www.vim.org/)
- [Emacs](http://www.gnuemacs.org/)
- [Atom](https://atom.io/)
- [Sublime](http://www.sublimetext.com/)
- [Rstudio](https://www.rstudio.com/)
- [Eclipse](https://www.eclipse.org/downloads/)
- [PyCharm](http://www.jetbrains.com/pycharm/)
- [Visual Studio](https://www.visualstudio.com/)

##### Remote Connection (SSH)

- [mobaXterm](http://mobaxterm.mobatek.net/)
- [Cygwin](http://www.cygwin.com/)
- [Xshell & Xsftp](http://www.netsarang.com/products/xsh_overview.html)
- [Putty](http://www.putty.org/)

##### Remote Connection (Desktop)

- [Teamviewer](https://www.teamviewer.com/)
- [Sunlogin](https://sunlogin.oray.com)
- [Splashtop](http://www.splashtop.com/)
- [Chrome Remote Desktop app](https://support.google.com/chrome/answer/1649523?hl=en)
- [Logmein](https://secure.logmein.com/)
- [PC Anywhere](http://in.norton.com/symantec-pcanywhere/)
- [GoToMyPC](http://www.gotomypc.com/remote-access/)
- [Radmin](http://www.radmin.com/)
- [UltraVNC](http://pcsupport.about.com/od/remote-access/fl/ultravnc-review.htm)

##### Other

- [igraph](https://github.com/igraph/igraph)
- [root](https://root.cern.ch/)
- [boost](http://www.boost.org/)
- [libtbb](https://github.com/01org/tbb)
- [docker](https://www.docker.com/)

### Books&Tutorial

#### R

- [R packages](http://r-pkgs.had.co.nz/)
- [stringr](https://cran.r-project.org/web/packages/stringr/vignettes/stringr.html)
- [Bioconductor Tutorial](http://master.bioconductor.org/help/course-materials/2003/MGED6/MGED6I.pdf)
- [limma](https://www.bioconductor.org/packages/devel/bioc/vignettes/limma/inst/doc/usersguide.pdf)
- [30分钟学会ggplot2](https://cos.name/wp-content/uploads/2012/05/3-xiaokai-ggplot2.pdf)
- [R Graphics Cookbook](https://ase.tufts.edu/bugs/guide/assets/R%20Graphics%20Cookbook.pdf)
- [Introduction to data.table](https://cran.r-project.org/web/packages/data.table/vignettes/datatable-intro.html)
- [RSQLite](https://cran.r-project.org/web/packages/RSQLite/vignettes/RSQLite.html)
- [R Graphics](https://www.stat.auckland.ac.nz/~paul/RGraphics/rgraphics.html)
- [Wordcloud2](https://cran.r-project.org/web/packages/wordcloud2/vignettes/wordcloud.html)

#### Linux&Shell

- [The Linux Command Line](http://linuxcommand.org/)
- [Advanced Bash-Scripting Guide](http://www.tldp.org/LDP/abs/abs-guide.pdf)
- [Wicked Cool Shell Scripts](http://shop.oreilly.com/product/9781593276027.do)
- [鸟哥的 Linux 私房菜](http://cn.linux.vbird.org/)
- [菜鸟教程](http://www.runoob.com/)

#### Python

- [Learning Python, 5th Edition](http://shop.oreilly.com/product/0636920028154.do)
- [Python Examples](https://github.com/geekcomputers/Python)
- [Learning Python](https://github.com/MrAlex6204/Books/blob/master/Learning%20Python,%205th%20Edition.pdf)
- [Python学习手册](https://www.gitbook.com/download/pdf/book/yulongjun/learning-python-in-chinese)

#### C/C++

- [C Primer Plus](https://doc.lagout.org/programmation/C/C%20Primer%20Plus%20%286th%20ed.%29%20%5BPrata%202013-12-06%5D.pdf)
- [C++ Primer Plus 6th Edition](http://freepdf-books.com/download/?file=5587)

#### JAVA

- [The Java™ Tutorials](https://docs.oracle.com/javase/tutorial/)

#### Statistics

- [SPSS Beginners Tutorials](https://www.spss-tutorials.com/basics/)
- [维基百科 - K-Means聚类算法](https://en.wikipedia.org/wiki/K-means_clustering)
- [维基百科 - KNN算法](https://en.wikipedia.org/wiki/K-nearest_neighbors_algorithm)
- [维基百科 - SVM算法](https://en.wikipedia.org/wiki/Support_vector_machine)
- [维基百科 - HMM模型](https://en.wikipedia.org/wiki/Hidden_Markov_model)
- [维基百科 - KNN算法](https://en.wikipedia.org/wiki/K-nearest_neighbors_algorithm)
- [STAT115课程 - HMM算法PPT](https://github.com/Miachol/ftp/raw/master/files/ppt/STAT115_HMM.ppt)
- [机器学习常用算法](https://en.wikipedia.org/wiki/Outline_of_machine_learning#Machine_learning_algorithms)
- [机器学习资源列表](https://github.com/adeshpande3/Machine-Learning-Links-And-Lessons-Learned)

#### Git

- [Git tutorials](https://www.atlassian.com/git/tutorials)
- [Git 教程](http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000)
- [Github Guides](https://guides.github.com/activities/hello-world/)

#### Cloud

- [Cloud Computing](https://en.wikipedia.org/wiki/Cloud_computing)
- [Docker入门教程](http://dockone.io/article/111)

#### Bioinfomatics

- [华大基因生物信息学培训教材](http://pan.baidu.com/s/1nuO5lZN)
- [生物信息学入门](http://pan.baidu.com/s/1jIb2Di2)
- [《生物信息学入门最佳实践》](http://www.biotrainee.com/jmzeng/book/basic/)
- [The Biostar Handbook: A Beginner's Guide to Bioinformatics](https://www.biostarhandbook.com/)
- [Bioinformatics Data Skills](http://shop.oreilly.com/product/0636920030157.do)
- [生信菜鸟团博客](http://www.bio-info-trainee.com/)
- [生信技能树论坛](https://vip.biotrainee.com)

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

- [Jianfeng Li](https://github.com/Miachol)
- [Bowen Cui](https://github.com/xcpanda)
- [Shixiang Wang](https://github.com/ShixiangWang)
