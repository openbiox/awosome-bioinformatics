# awosome-bioinformatics

**Abstract**: A curated list of resources for learning bioinformatics. Some of this repo resources were collected by [BioInstaller](https://github.com/JhuangLab/BioInstaller/blob/master/inst/extdata/config/db/db_meta.toml) project. You can use [BioInstaller](https://github.com/JhuangLab/BioInstaller) to directly download the source code or database files, or fetch the meta information by `BioInstaller::get.meta()$item`.

**Purpose**:

- Provide some of bioinformatics learning resources for beginners
- Provide a profiling of bioinformatics

**Field**:

- Next generation sequencing (NGS)
- Bioinformatics Data Analysis

<details>
<summary>Table of content</summary>

## Table of content

- [Resources](#resources)

  - [General](#general)
  - [Journal](#journal)
  - [Sequencing Technology](#sequencing-technology)
  - [Tools](#tools)
  - [Books&Tutorial](#bookstutorial)
  - [Paper](#paper)

- [Skills](#skills)
- [Organization](#organization)
- [Institute](#institute-or-business-company)
- [People](#people)
- [Blog](#blog)
- [Contributors](#contributors)

</details>

---

## Resources

### General

- [Wikipedia](https://en.wikipedia.org/wiki/Bioinformatics)
- [Org](http://www.bioinformatics.org/)

### Journal

#### Bioinformatics
- [Bioinformatics](https://academic.oup.com/bioinformatics)
- [BMC Bioinformatics](https://bmcbioinformatics.biomedcentral.com/)
- [Nucleic Acids Research](https://academic.oup.com/nar/pages/About)
- [bioRxiv Bioinformatics](https://www.biorxiv.org/collection/bioinformatics)
- [Current Bioinformatics](https://www.eurekaselect.com/642/journal/current-bioinformatics)
- [Advances in Bioinformatics](https://www.hindawi.com/journals/abi/)
- [Briefings in Bioinformatics](https://academic.oup.com/bib/issue/19/6)
- [Current Protocols in Bioinformatics](https://currentprotocols.onlinelibrary.wiley.com/journal/1934340x)
- [Journal of Bioinformatics and Computational Biology](https://www.worldscientific.com/worldscinet/jbcb)
- [Evolutionary Bioinformatics](https://journals.sagepub.com/home/evb)
- [Bioinformatics and Biology Insights](https://journals.sagepub.com/home/bbi)
- [Advances and Applications in Bioinformatics and Chemistry](https://www.dovepress.com/advances-and-applications-in-bioinformatics-and-chemistry-journal)
- [Genomics, Proteomics and Bioinformatics](http://www.sciencedirect.com/science/journal/16720229?sdc=1)

#### Genomics
- [Genomics](https://www.sciencedirect.com/journal/genomics)
- [Human Genomics](https://humgenomics.biomedcentral.com/)
- [Current Genomics](https://www.eurekaselect.com/601/journal/current-genomics)
- [Genome Research](http://genome.cshlp.org/)
- [Nature Genetics](http://www.nature.com/ng/index.html)
- [Nature Method](http://www.nature.com/nmeth/index.html)
- [BMC Genomics](https://bmcgenomics.biomedcentral.com/)
- [Marine Genomics](https://www.sciencedirect.com/journal/marine-genomics)
- [BMC Medical Genomics](https://bmcmedgenomics.biomedcentral.com/)
- [Briefings in Functional Genomics](https://academic.oup.com/bfg/issue/17/4)
- [Cancer Genomics & Proteomics](http://cgp.iiarjournals.org/)
  
#### Proteomics
- [Journal of Proteomics](https://www.sciencedirect.com/journal/journal-of-proteomics)
- [Molecular & Cellular Proteomics](https://www.mcponline.org/)
- [Clinical Proteomics](https://clinicalproteomicsjournal.biomedcentral.com/)
- [Expert Review of Proteomics](https://www.tandfonline.com/loi/IERU)

#### Transcripteomics
- [Transcription](https://www.tandfonline.com/loi/ktrn20)
  
#### Metabolomics
- [Metabolomics](https://www.springer.com/journal/11306)

#### Epigenomics
- [Epigenomics](https://www.futuremedicine.com/journal/epi)

### Sequencing Technology

This section mainly copied from [enseqlopedia](http://enseqlopedia.com/enseqlopedia/).

Thanks this work: Hadfield, J. & Retief, J. A profusion of confusion in NGS methods naming. Nat Methods 15, 7-8 (2018).

#### RNA Sequencing Methods

##### **[Low-Level RNA Detection](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/low-level-rna-detection/)**

  - [CEL-Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/low-level-rna-detection/cel-seq/)
  - [CirSeq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/low-level-rna-detection/cirseq/)
  - [CLaP](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/low-level-rna-detection/clap/)
  - [CytoSeq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/low-level-rna-detection/cytoseq/)
  - [Digital RNA Sequencing](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/low-level-rna-detection/digital-rna-sequencing/)
  - [DP-Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/low-level-rna-detection/dp-seq/)
  - [Drop-Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/low-level-rna-detection/drop-seq/)
  - [Hi-SCL](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/low-level-rna-detection/hi-scl/)
  - [InDrop](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/low-level-rna-detection/indrop/)
  - [MARS-Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/low-level-rna-detection/mars-seq/)
  - [Nuc-Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/low-level-rna-detection/nuc-seq/)
  - [PAIR](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/low-level-rna-detection/pair/)
  - [Quartz-Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/low-level-rna-detection/quartz-seq/)
  - [scM&amp;T-Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/low-level-rna-detection/scmt-seq-2/)
  - [SCRB-Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/low-level-rna-detection/scrb-seq/)
  - [scRNA-Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/low-level-rna-detection/scrna-seq/)
  - [scTrio-seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/low-level-rna-detection/sctrio-seq/)
  - [Smart-Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/low-level-rna-detection/smart-seq/)
  - [Smart-Seq2](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/low-level-rna-detection/smart-seq2/)
  - [snRNA-Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/low-level-rna-detection/snrna-seq/)
  - [STRT-Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/low-level-rna-detection/strt-seq/)
  - [SUPeR-Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/low-level-rna-detection/super-seq/)
  - [TCR-LA-MC PCR](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/low-level-rna-detection/tcr-la-mc-pcr/)
  - [TIVA](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/low-level-rna-detection/tiva/)
  - [UMI](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/low-level-rna-detection/umi/)
  - [5C](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/low-level-rna-detection/5c/)
  - [Div-Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/low-level-rna-detection/div-seq/)
  - [FRISCR](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/low-level-rna-detection/friscr/)
  - [TCR Chain Pairing](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/low-level-rna-detection/tcr-chain-pairing/)
  - [AbPair](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/low-level-rna-detection/abpair/)

##### **[RNA Modifications](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-modifications/)**

  - [ICE](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-modifications/ice/)
  - [MeRIP-Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-modifications/merip-seq/)
  - [miCLIP-m6A](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-modifications/miclip-m6a/)
  - [Pseudo-Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-modifications/pseudo-seq/)
  - [PSI-Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-modifications/psi-seq/)

##### **[RNA Structure](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-structure/)**

  - [CAP-seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-structure/cap-seq/)
  - [Cap-Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-structure/cap-seq-2/)
  - [CIP-TAP](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-structure/cip-tap/)
  - [PARS-Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-structure/pars-seq/)
  - [SPARE](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-structure/spare/)
  - [Structure-Seq/DMS-Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-structure/structure-seqdms-seq/)
  - [CIRS-Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-structure/cirs-seq/)
  - [icSHAPE](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-structure/icshape/)
  - [SHAPE-MaP](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-structure/shape-map/)
  - [SHAPE-Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-structure/shape-seq/)

##### **[RNA Transcription](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-transcription/)**

  - [2P-Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-transcription/2p-seq/)
  - [3&#39;NT Method](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-transcription/3nt-method/)
  - [3P-Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-transcription/3p-seq/)
  - [3Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-transcription/3seq/)
  - [3′-Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-transcription/3-seq/)
  - [5′-GRO-Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-transcription/5-gro-seq/)
  - [BruChase-Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-transcription/bruchase-seq/)
  - [BruDRB-Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-transcription/brudrb-seq/)
  - [Bru-Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-transcription/bru-seq/)
  - [CAGE](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-transcription/cage/)
  - [CHART](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-transcription/chart/)
  - [ChIRP](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-transcription/chirp/)
  - [ClickSeq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-transcription/clickseq/)
  - [GRO-seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-transcription/gro-seq/)
  - [NET-Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-transcription/net-seq/)
  - [PAL-Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-transcription/pal-seq/)
  - [PARE-Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-transcription/pare-seq/)
  - [PEAT](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-transcription/peat/)
  - [PRO-Cap](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-transcription/pro-cap/)
  - [PRO-Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-transcription/pro-seq/)
  - [RAP](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-transcription/rap/)
  - [RARseq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-transcription/rarseq/)
  - [RASL-Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-transcription/rasl-seq/)
  - [RNA-Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-transcription/rna-seq/)
  - [SMORE-Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-transcription/smore-seq/)
  - [TAIL-Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-transcription/tail-seq/)
  - [TATL-Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-transcription/tatl-seq/)
  - [TIF-Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-transcription/tif-seq/)
  - [TL-Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-transcription/tl-seq/)
  - [4sUDRB-Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-transcription/4sudrb-seq/)
  - [CaptureSeq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-transcription/captureseq/)
  - [cP-RNA-Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-transcription/cp-rna-seq/)
  - [FRT-Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-transcription/frt-seq/)
  - [GMUCT](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-transcription/gmuct/)
  - [mNET-Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-transcription/mnet-seq/)

##### **[RNA-Protein Interactions](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-protein-interactions/)**

  - [AGO-CLIP](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-protein-interactions/ago-clip/)
  - [CLASH](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-protein-interactions/clash/)
  - [CLIP-Seq or HITS-CLIP](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-protein-interactions/clip-seq-or-hits-clip/)
  - [DLAF](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-protein-interactions/dlaf/)
  - [eCLIP](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-protein-interactions/eclip/)
  - [hiCLIP](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-protein-interactions/hiclip/)
  - [iCLIP](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-protein-interactions/iclip/)
  - [miR-CLIP](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-protein-interactions/mir-clip/)
  - [miTRAP](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-protein-interactions/mitrap/)
  - [PAR-CLIP](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-protein-interactions/par-clip/)
  - [PIP-Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-protein-interactions/pip-seq/)
  - [Pol II CLIP](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-protein-interactions/pol-ii-clip/)
  - [RBNS](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-protein-interactions/rbns/)
  - [Ribo-Seq or ARTSeq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-protein-interactions/ribo-seq-or-artseq/)
  - [RIP-Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-protein-interactions/rip-seq/)
  - [TRAP-Seq](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-protein-interactions/trap-seq/)
  - [TRIBE](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-protein-interactions/tribe/)
  - [BrdU-CLIP](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-protein-interactions/brdu-clip/)
  - [HiTS-RAP](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-protein-interactions/hits-rap/)
  - [irCLIP](http://enseqlopedia.com/wiki-entry/rna-sequencing-methods/rna-protein-interactions/irclip/)

#### **DNA Sequencing Methods**

##### **[Protein-Protein Interaction](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/protein-protein-interaction/)**

  - [PD-Seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/protein-protein-interaction/pd-seq/)
  - [ProP-PD/PDZ-Seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/protein-protein-interaction/prop-pdpdz-seq/)

##### **[Sequence Rearrangements](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/sequence-rearrangements/)**

  - [2b-RAD](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/sequence-rearrangements/2b-rad/)
  - [CPT-seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/sequence-rearrangements/cpt-seq/)
  - [ddRADseq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/sequence-rearrangements/ddradseq/)
  - [Digenome-seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/sequence-rearrangements/digenome-seq/)
  - [EC-seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/sequence-rearrangements/ec-seq/)
  - [hyRAD](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/sequence-rearrangements/hyrad/)
  - [RAD-Seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/sequence-rearrangements/rad-seq/)
  - [Rapture](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/sequence-rearrangements/rapture/)
  - [RC-Seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/sequence-rearrangements/rc-seq/)
  - [Repli-Seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/sequence-rearrangements/repli-seq/)
  - [SLAF-seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/sequence-rearrangements/slaf-seq/)
  - [TC-Seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/sequence-rearrangements/tc-seq/)
  - [Tn-Seq/INSeq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/sequence-rearrangements/tn-seqinseq/)
  - [Bubble-Seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/sequence-rearrangements/bubble-seq/)
  - [NSCR](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/sequence-rearrangements/nscr/)
  - [NS-Seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/sequence-rearrangements/ns-seq/)
  - [Rep-Seq/Ig-Seq/MAF](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/sequence-rearrangements/rep-seqig-seqmaf/)

##### **[DNA Break Mapping](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/dna-break-mapping/)**
  - [BLESS](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/dna-break-mapping/bless/)
  - [DSB-Seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/dna-break-mapping/dsb-seq/)
  - [GUIDE-seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/dna-break-mapping/guide-seq/)
  - [HTGTS](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/dna-break-mapping/htgts/)
  - [LAM-HTGTS](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/dna-break-mapping/lam-htgts/)
  - [Break-seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/dna-break-mapping/break-seq/)
  - [SSB-Seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/dna-break-mapping/ssb-seq/)

##### **[DNA Protein Interactions](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/dna-protein-interactions/)**

  - [DNaseI Seq or DNase-Seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/dna-protein-interactions/dnasei-seq-or-dnase-seq/)
  - [Pu-seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/dna-protein-interactions/pu-seq/)
  - [3-C/Capture-C/Hi-C](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/dna-protein-interactions/3-ccapture-chi-c/)
  - [4C-seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/dna-protein-interactions/4c-seq/)
  - [5C](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/dna-protein-interactions/5c/)
  - [ATAC-Seq/Fast-ATAC](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/dna-protein-interactions/atac-seqfast-atac/)
  - [CATCH\_IT](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/dna-protein-interactions/catch_it/)
  - [Chem-seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/dna-protein-interactions/chem-seq/)
  - [ChIA-PET](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/dna-protein-interactions/chia-pet/)
  - [ChIPmentation](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/dna-protein-interactions/chipmentation/)
  - [ChIP-Seq/HT-ChIP/ChIP-exo/Mint-ChIP](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/dna-protein-interactions/chip-seqht-chipchip-exomint-chip/)
  - [DamID](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/dna-protein-interactions/damid/)
  - [DNase I SIM](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/dna-protein-interactions/dnase-i-sim/)
  - [FAIRE-seq/Sono-Seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/dna-protein-interactions/faire-seqsono-seq/)
  - [FiT-Seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/dna-protein-interactions/fit-seq/)
  - [HiTS-FLIP](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/dna-protein-interactions/hits-flip/)
  - [MINCE-seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/dna-protein-interactions/mince-seq/)
  - [MNase-Seq/MAINE-Sequcleo-Sequc-seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/dna-protein-interactions/mnase-seqmaine-sequcleo-sequc-seq/)
  - [MPE-seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/dna-protein-interactions/mpe-seq/)
  - [NG Capture-C](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/dna-protein-interactions/ng-capture-c/)
  - [NOMe-Seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/dna-protein-interactions/nome-seq/)
  - [ORGANIC](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/dna-protein-interactions/organic/)
  - [PAT-ChIP](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/dna-protein-interactions/pat-chip/)
  - [PB\_seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/dna-protein-interactions/pb_seq/)
  - [SELEX or SELEX-seq / HT-SELEX](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/dna-protein-interactions/selex-or-selex-seq-ht-selex/)
  - [THS-seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/dna-protein-interactions/ths-seq/)
  - [UMI-4C](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/dna-protein-interactions/umi-4c/)
  - [X-ChIP-seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/dna-protein-interactions/x-chip-seq/)

##### **[Epigenetics](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/epigenetics/)**

  - [Aba-seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/epigenetics/aba-seq/)
  - [BisChIP-Seq/ChIP-BS-Seq/ChIP-BMS](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/epigenetics/bischip-seqchip-bs-seqchip-bms/)
  - [BSAS](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/epigenetics/bsas/)
  - [BSPP](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/epigenetics/bspp/)
  - [BS-Seq/Bisulfite-Seq/WGBS](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/epigenetics/bs-seqbisulfite-seqwgbs/)
  - [CAB-Seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/epigenetics/cab-seq/)
  - [EpiRADseq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/epigenetics/epiradseq/)
  - [fCAB-seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/epigenetics/fcab-seq/)
  - [fC-CET](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/epigenetics/fc-cet/)
  - [fC-Seal](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/epigenetics/fc-seal/)
  - [hMeDIP-seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/epigenetics/hmedip-seq/)
  - [JBP1-seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/epigenetics/jbp1-seq/)
  - [MAB-seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/epigenetics/mab-seq/)
  - [MBDCap-seq/MethylCap-Seq/MiGS](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/epigenetics/mbdcap-seqmethylcap-seqmigs/)
  - [MeDIP-Seq/DIP-seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/epigenetics/medip-seqdip-seq/)
  - [MIRA](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/epigenetics/mira/)
  - [MRE-Seq and Methyl-Seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/epigenetics/mre-seq-and-methyl-seq/)
  - [xBS-Seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/epigenetics/oxbs-seq/)
  - [PBAT](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/epigenetics/pbat/)
  - [redBS-Seq/caMAB-seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/epigenetics/redbs-seqcamab-seq/)
  - [RRBS-Seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/epigenetics/rrbs-seq/)
  - [RRMAB-seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/epigenetics/rrmab-seq/)
  - [TAB-Seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/epigenetics/tab-seq/)
  - [TAmC-Seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/epigenetics/tamc-seq/)
  - [T-WGBS](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/epigenetics/t-wgbs/)

##### **[Low-Level DNA Detection](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/low-level-dna-detection/)**

  - [Safe-SeqS](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/low-level-dna-detection/safe-seqs/)
  - [scAba-seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/low-level-dna-detection/scaba-seq/)
  - [scATAC-Seq (Cell index variation)](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/low-level-dna-detection/scatac-seq-cell-index-variation/)
  - [scATAC-Seq (Microfluidics variation)](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/low-level-dna-detection/scatac-seq-microfluidics-variation/)
  - [scBS-Seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/low-level-dna-detection/scbs-seq/)
  - [scM&amp;T-Seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/low-level-dna-detection/scmt-seq/)
  - [scRC-Seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/low-level-dna-detection/scrc-seq/)
  - [SMDB](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/low-level-dna-detection/smdb/)
  - [smMIP](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/low-level-dna-detection/smmip/)
  - [G&amp;T-Seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/low-level-dna-detection/gt-seq/)
  - [5C](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/low-level-dna-detection/5c/)
  - [DR-Seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/low-level-dna-detection/dr-seq/)
  - [G&amp;T-Seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/low-level-dna-detection/gt-seq-2/)
  - [MALBAC](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/low-level-dna-detection/malbac/)
  - [MDA](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/low-level-dna-detection/mda/)
  - [MIDAS/IMS-MDA/ddMDA](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/low-level-dna-detection/midasims-mdaddmda/)
  - [scM&amp;T-Seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/low-level-dna-detection/scmt-seq-2-2/)
  - [Drop-ChIP/scChIP-seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/low-level-dna-detection/drop-chipscchip-seq/)
  - [Duplex-Seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/low-level-dna-detection/duplex-seq/)
  - [MIPSTR](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/low-level-dna-detection/mipstr/)
  - [nuc-seq/SNES](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/low-level-dna-detection/nuc-seqsnes/)
  - [OS-Seq](http://enseqlopedia.com/wiki-entry/dna-sequencing-methods/low-level-dna-detection/os-seq/)

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
- [Spack](https://github.com/spack/spack)

#### Web Application Developement Framework

- [Galaxy](https://usegalaxy.org/)
- [Bootstrap](http://getbootstrap.com/2.3.2/)
- [Django](https://www.djangoproject.com/)
- [Yi](http://www.yiiframework.com/)

#### Web-based Service

- [Hiplot](https://hiplot.com.cn): a simple and user-friendly visualization platform for scientific data.
- [UCSC](https://genome.ucsc.edu/)
- [NCBI](https://www.ncbi.nlm.nih.gov/)
  - [CDD](https://www.ncbi.nlm.nih.gov/Structure/cdd/cdd.shtml)
- [ExPASy](http://www.expasy.org/)
- [EMBL-EBI](http://www.ebi.ac.uk/)
- [TCGA](https://cancergenome.nih.gov/)
- [COSMIC](http://cancer.sanger.ac.uk/cosmic)
  - [COSMIC-3D](https://cancer.sanger.ac.uk/cosmic3d): a comprehensive integration of cancer mutations with protein structure across the human genome and structural proteome, seeking to support the identification and characterization of protein targets for novel drug design in precision oncology
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
  - [TIMER](http://cistrome.org/TIMER/)
- [VarCards](http://varcards.biols.ac.cn/)
- [superdrug2](http://cheminfo.charite.de/superdrug2/)
- [MeDReaders](http://medreader.org)
- [ECOdrug](http://www.ecodrug.org/)
- [rSNPBase3.0](http://rsnp3.psych.ac.cn/index.do)
- [MNDR](http://www.rna-society.org/mndr/)
- [MSDD](http://www.bio-bigdata.com/msdd/)
- [funcoup](http://funcoup.sbc.su.se/search/)
- [proteinatlas](https://www.proteinatlas.org/)
- [DGIdb](http://dgidb.org/)
- [Drugbank](https://www.drugbank.ca)
- [InterPro](http://www.ebi.ac.uk/interpro)
- [ncbi-biosystems](https://www.ncbi.nlm.nih.gov/biosystems)
- [denovo-db](http://denovo-db.gs.washington.edu/denovo-db)
- [The Human Phenotype Ontology (HPO)](http://human-phenotype-ontology.github.io)
- [FANTOM](http://fantom.gsc.riken.jp)
- [dbNSFP](https://sites.google.com/site/jpopgen/dbNSFP)
- [regSNP-intron](http://clark.compbio.iupui.edu/regsnp_intron_web/)
- [RADAR](http://rnaedit.com/)
- [DARNED](http://darned.ucc.ie/)
- [REDIportal](http://srv00.recas.ba.infn.it/atlas/)
- [LNCediting](http://bioinfo.life.hust.edu.cn/LNCediting)
- [EggNOG](http://eggnogdb.embl.de/#/app/home)
- [MiSTIC](https://github.com/iric-soft/MiSTIC)
- [DTMiner](https://gdr-web.rwebox.com/public_html/index.php)
- [PDBFlex](http://pdbflex.org/)
- [Cancer3d](http://www.cancer3d.org/)
- [Dsysmap](https://dsysmap.irbbarcelona.org/)
- [CBS Prediction Servers](http://www.cbs.dtu.dk/services/)
- [wANNOVAR](http://wannovar.wglab.org/): Public web service of ANNOVAR
- [Harmonizome](http://amp.pharm.mssm.edu/Harmonizome): Search for genes or proteins and their functional terms extracted and organized from over a hundred publicly available resources
- [GDA](http://gda.unimore.it/): A web-based tool that combines NCI60 uniquely large number of drug sensitivity data with CCLE and NCI60 gene mutation and expression profiles
- [CLUE](https://clue.io/): Unravel biology with the world’s largest perturbation-driven gene expression dataset
- [CMAP](https://portals.broadinstitute.org/cmap/): The Connectivity Map (also known as cmap) is a collection of genome-wide transcriptional expression data from cultured human cells treated with bioactive small molecules and simple pattern-matching algorithms that together enable the discovery of functional connections between drugs, genes and diseases through the transitory feature of common gene-expression changes.
- [pssmsearch](http://slim.ucd.ie/pssmsearch/): a web application to discover novel protein motifs (SLiMs, mORFs, miniMotifs) and PTM sites
- [bammmotif](https://bammmotif.mpibpc.mpg.de/): Bayesian Markov Models (BaMMs), a web server for de-novo motif discovery and regulatory sequence analysis
- [LOLAweb](http://lolaweb.databio.org/): a containerized web server for interactive genomic locus overlap enrichment analysis
- [GeNets](https://apps.broadinstitute.org/genets): a unified web platform for network-based genomic analyses
- [HiCExplorer](https://hicexplorer.usegalaxy.eu/): a web server for reproducible Hi-C data analysis, quality control and visualization
- [paintomics](http://www.paintomics.org/): a web resource for the pathway analysis and visualization of multi-omics data
- [kinact](http://biosig.unimelb.edu.au/kinact/): a computational approach for predicting activating missense mutations in protein kinases
- [VAReporter](http://rnd.cgu.edu.tw/vareporter/): VAReporter can provide comprehensive annotation by integrating a wide variety of biomedical databases
- [SNPnexus](http://www.snp-nexus.org/): SNPnexus was designed to simplify and assist in the selection of functionally relevant Single Nucleotide Polymorphisms (SNP) for large-scale genotyping studies of multifactorial disorders
- [Oncoscape](https://oncoscape.sttrcancer.org/): an online open-access dataanalysis and visualization platform that empowers researchers and clinicians to discover novel patterns and relationships between linked clinical and molecular data
- [cellmarker](http://biocc.hrbmu.edu.cn/CellMarker): a manually curated resource of cell markers in human and mouse
- [awesome](http://www.awesome-hust.com): a database of SNPs that affect protein post-translational modifications
- [hmdb](http://www.hmdb.ca/system): an online database of small molecule metabolites found in the human body, which facilitates human metabolomics research including the identification and characterization of human metabolites using NMR and MS
- [redoxdb](https://biocomputer.bio.cuhk.edu.hk/RedoxDB): a curated database of protein oxidative modification
- [instruct](http://instruct.yulab.org): a database of 3D protein interactome networks with structural resolution
- [consensuspathdb](http://cpdb.molgen.mpg.de): integrates interaction networks in Homo sapiens including binary and complex protein-protein, genetic, metabolic, signaling, gene regulatory and drug-target interactions, as well as biochemical pathways
- [phosphonetworks](http://www.phosphonetworks.org): a database for experimentally determined kinase-substrate relationships
- [dbsno](http://140.138.144.145/~dbSNO): protein S-nitrosylation (SNO) is a reversible post-translational modification (PTM) and involves the covalent attachment of nitric oxide (NO) to the thiol group of cysteine (Cys) residues. Given the increasing number of proteins reported to be regulated by this modification, S-nitrosylation is considered to act, in a manner analogous to phosphorylation, as a pleiotropic regulator that elicits dual effects to regulate diverse pathophysiological processes by altering protein function, stability, and conformation change in various cancers and human disorders
- [hpdi](http://bioinfo.wilmer.jhu.edu/PDI): Human Protein-DNA Interactome (hPDI)
- [islandviewer](http://www.pathogenomics.sfu.ca/islandviewer): an integrated interface for computational identification and visualization of genomic islands
- [appris](http://apprisws.bioinfo.cnio.es): a system that deploys a range of computational methods to provide annotations of alternative splice isoforms and identify principal isoforms for vertebrate species
- [rbpdb](http://rbpdb.ccbr.utoronto.ca): a collection of RNA-binding proteins linked to a curated database of published observations of RNA binding
- [type2diabetesgenetics](http://www.type2diabetesgenetics.org/home/portalHome): providing data and tools to promote understanding and treatment of type 2 diabetes and its complications
- [pepquery](http://www.pepquery.org/): a peptide-centric search engine for novel peptide identification and validation
- [Gene Info eXtension (GIX)](https://gene-info.org/): a browser extension that allows you to retrieve information about a gene product directly on any webpage simply by double clicking an official gene name, synonym or supported accession.
- [cancermine](http://bionlp.bcgsc.ca/cancermine/): a literature-mined resource for drivers, oncogenes and tumor suppressors in cancer.
- [gpcrdb](https://www.gpcrdb.org/): contains data, diagrams and web tools for G protein-coupled receptors (GPCRs). Users can browse all GPCR structures and the largest collections of receptor mutants. Diagrams can be produced and downloaded to illustrate receptor residues (snake-plot and helix box diagrams) and relationships (phylogenetic trees). Reference (structure) structure-based sequence alignments take into account helix bulges and constrictions, display statistics of amino acid conservation and have been assigned generic residue numbering for equivalent residues in different receptors.
- [FPbase](https://www.fpbase.org):  a free, open-source, web-based, communityeditable database for fluorescent proteins (FPs) and their properties. 
- [Image Data Resource (IDR)](https://idr.openmicroscopy.org/): Image Data Resource (IDR) is a public repository of image datasets from published scientific studies, where the community can submit, search and access high-quality bio-image data.
- [Allen Brain Atlases and Data](http://portal.brain-map.org/): The Allen Institute for Brain Science uses a unique approach to generate data, tools and knowledge for researchers to explore the biological complexity of the mammalian brain. This portal provides access to high quality data and web-based applications created for the benefit of the global research community.
- [Allen Cell Explorer](https://www.allencell.org/): a python-based, open-source toolkit that combines classic 3D image segmentation with artificial intelligence to detect cellular structures.
- [Mitotic Cell Atlas](https://www.mitocheck.org/mitotic_cell_atlas/): Provides a comprehensive and quantitative 4D model of the mitotic protein localization network in a dividing human cell. Mitotic Cell Atlas is an integrated experimental and computational framework that provides a standardized yet dynamic spatio-temporal reference system for the mitotic cell. It can be used to integrate quantitative information on any number of protein distributions sampled in thousands of different experiments.
- [Broad Bioimage Benchmark Collection](https://data.broadinstitute.org/bbbc/): a collection of freely downloadable microscopy image sets. In addition to the images themselves, each set includes a description of the biological application and some type of "ground truth" (expected results).
- [Cell Image Library](http://www.cellimagelibrary.org/home): a repository for images and movies of cells from a variety of organisms. It demonstrates cellular architecture and functions with high quality images, videos, and animations. This comprehensive and easily accessible Library is designed as a public resource first and foremost for research, and secondarily as a tool for education. The long-term goal is the construction of a library of images that will serve as primary data for research.
- [Mitocheck](https://www.mitocheck.org/index.shtml): the goal of this resource is to integrate information on cellular functions of human genes while also giving access to supporting information such as microscopy images of phenotypes. Although its primary focus is on the biology of mitosis, the resource also integrates data relevant to many other cellular functions.
- [ssbd](http://ssbd.qbic.riken.jp/): Systems Science of Biological Dynamics (SSBD) database provides a rich set of open resources for analyzing quantitative data and microscopy images of biological objects, such as single-molecule, cell, gene expression nuclei, etc. Quantitative biological data and microscopy image are collected from a variety of species, sources and methods. These include data obtained from both experiment and computational simulation.
- [IMPC](https://www.mousephenotype.org/): the International Mouse Phenotyping Consortium (IMPC) is an international effort by 19 research institutions to identify the function of every protein-coding gene in the mouse genome. The entire genome of many species has now been published and whole genome sequencing is becoming relatively quick and cheap to complete. Despite these advancements the function of the majority of genes remains unknown.
- [elixir](https://elixir-europe.org/): ELIXIR unites Europe’s leading life science organisations in managing and safeguarding the increasing volume of data being generated by publicly funded research. It coordinates, integrates and sustains bioinformatics resources across its member states and enables users in academia and industry to access services that are vital for their research.
- [Global BioImaging Project](http://www.eurobioimaging.eu/global-bioimaging): the imaging landscape changed significantly in the last 10 years as the the concept of open user access to cutting-edge technologies became valued and well recognized. In Europe imaging experts from 25 countries joined their forces and draw the vision of a pan-European imaging infrastructure, which gave momentum to the project of founding a Euro-BioImaging European Research Infrastructure Consortium (the EuBI ERIC).

##### Clinical Annotation

- [CIViC](https://civic.genome.wustl.edu/home)
- [DoCM](http://docm.genome.wustl.edu/)
- [ClinVar](https://www.ncbi.nlm.nih.gov/clinvar/)
- [Intogen](https://www.intogen.org/downloads)
- [Cancer Hotspots](http://cancerhotspots.org/#/home)
- [DisGeNET](http://www.disgenet.org/web/DisGeNET/menu)
- [Cancer Biomarkers database](https://www.cancergenomeinterpreter.org/biomarkers)
- [OncoKB](http://oncokb.org/): Precision Oncology Knowledge Base
- [LncRNADisease](http://www.cuilab.cn/lncrnadisease): Not only a resource that curated the experimentally supported lncRNA-disease association data but also a platform that integrated tool(s) for predicting novel lncRNA-disease associatons
- [fusiongdb](https://ccsm.uth.edu/FusionGDB): fusion gene annotation DataBase, which collected 48 117 FGs across pan-cancer from three representative fusion gene resources: the improved database of chimeric transcripts and RNA-seq data (ChiTaRS 3.1), an integrative resource for cancerassociated transcript fusions (TumorFusions), and The Cancer Genome Atlas (TCGA) fusions by Gao et al.
- [sedb](http://www.licpathway.net/sedb/): the comprehensive human Super-Enhancer database.
- [pmkb](https://pmkb.weill.cornell.edu/): the cancer precision medicine knowledge base for structured clinical-grade mutations and interpretations
- [ewasdb](http://www.bioapp.org/ewasdb): epigenome-wide association study database
- [dcdb](http://www.cls.zju.edu.cn/dcdb): DCDB (Drug Combination Database), Accumulating scientific and clinical evidences have suggested the use of drug combinations as a safe and effective approach, to treat complicated and refractory diseases. The Drug Combination Database (DCDB) is devoted to the research and development of multi-component drugs. The current version of DCDB collected 1363 drug combinations (330 approved and 1033 investigational, including 237 unsuccessful usages), involving 904 individual drugs, 805 targets

##### Noncoding RNA Related Database

- [CSCD](http://gb.whu.edu.cn/CSCD/)
- [AtCircDB](http://genome.sdau.edu.cn/circRNA/index.php)
- [CircNet](http://circnet.mbc.nctu.edu.tw/)
- [circBase](http://circrna.org/)
- [circRNADb](http://202.195.183.4:8000/circrnadb/circRNADb.php)
- [exoRBase](http://www.exorbase.org/exoRBase/toIndex)
- [EVLncRNAs](http://biophy.dzu.edu.cn/EVLncRNAs.)
- [NONCODE](http://www.noncode.org/): an integrated knowledge database dedicated to non-coding RNAs (excluding tRNAs and rRNAs)
- [MiTranscriptome](http://www.mitranscriptome.org/):  a catalog of human long poly-adenylated RNA transcripts derived from computational analysis of high-throughput RNA sequencing (RNA-Seq) data from over 6,500 samples spanning diverse cancer and tissue types
- [FANTOM CAT](http://fantom.gsc.riken.jp/cat/): an atlas of human long non-coding RNAs with accurate 5’ ends
- [lnc2cancer2](http://www.bio-bigdata.net/lnc2cancer): an updated database that provides comprehensive experimentally supported associations between lncRNAs and human cancers
- [sm2mir](http://www.jianglab.cn/SM2miR/): a manual curated database which collects and incorporates the experimentally validated small molecules' effects on miRNA expression in 20 species from the published papers. Each entry contains the detailed information about small molecules, miRNAs and their relationships, including species, small molecule name, DrugBank Accession number, PubChem CID, approved by FDA or not, miRNA name, miRBase Accession number, expression pattern of miRNA, experimental detection method, tissues or conditions for detection, evidences in the reference, PubMed ID and the published year of the reference
- [oncomirdb](http://lifeome.net/database/oncomirdb): a Database for Oncogenic & Tumor-Suppressive MicroRNAs
- [mircancer](http://mircancer.ecu.edu): provides comprehensive collection of microRNA (miRNA) expression profiles in various human cancers which are automatically extracted from published literatures in PubMed. It utilizes text mining techniques for information collection. Manual revision is applied after auto-extraction to provide 100% precision
- [lncipedia](https://lncipedia.org): a public database for long non-coding RNA (lncRNA) sequence and annotation. The current release contains 127,802 transcripts and 56,946 genes
- [mirnest](http://rhesus.amu.edu.pl/mirnest): an integrative collection of animal, plant and virus microRNA data
- [mirtarbase](http://mirtarbase.mbc.nctu.edu.tw): the experimentally validated microRNA-target interactions database
- [mirdb](http://mirdb.org): an online resource for microRNA target prediction and functional annotations

##### eQTL Related Database

- [exsnp](http://www.exsnp.org)
- [rVarBase](http://rv.psych.ac.cn)
- [seeQTL](http://www.bios.unc.edu/research/genomic_software/seeQTL/)
- [cancersplicingqtl](http://www.cancersplicingqtl-hust.com): a database for genome-wide identification of splicing QTLs in human cancer

#### Sequencing Data Portal

- [GDC](https://portal.gdc.cancer.gov/)
- [EGA](https://www.ebi.ac.uk/ega/home)
- [dbGaP](https://www.ncbi.nlm.nih.gov/gap)
- [DDBJ](http://www.ddbj.nig.ac.jp/)
- [GEO](https://www.ncbi.nlm.nih.gov/geo/)
- [ICGC](https://dcc.icgc.org/)

#### Plant-related platforms

- [Plant Regulomics](http://bioinfo.sibs.ac.cn/plant-regulomics/)

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
- [fastp](https://github.com/OpenGene/fastp)
- [ChronQC](https://github.com/nilesh-tawari/ChronQC)

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
- [DART](https://github.com/hsinnan75/DART)
- [rHAT](https://github.com/HIT-Bioinformatics/rHAT)
- [taxmaps](https://github.com/nygenome/taxmaps): large DNA/RNA metagenomics samples
- [MARVEL](https://github.com/schloi/MARVEL): consists of a set of tools that facilitate the overlapping, patching, correction and assembly of noisy (not so noisy ones as well) long reads.
- [vg](https://github.com/vgteam/vg): tools for working with genome variation graphs
- [TransLiG](https://sourceforge.net/projects/transcriptomeassembly/files/): a de novo transcriptome assembler that uses line graph iteration.
- [stringtie](https://github.com/gpertea/stringtie): Transcript assembly and quantification for RNA-Seq

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
- [SVScore](https://github.com/lganel/SVScore)
- [SVTools](https://github.com/hall-lab/svtools)
- [RDDpred](http://epigenomics.snu.ac.kr/RDDpred/)
- [iseq](https://github.com/JhuangLab/iseq)
- [deepvariant](https://github.com/google/deepvariant)
- [SV2](https://github.com/dantaki/SV2)
- [facets](https://github.com/mskcc/facets)
- [MutScan](https://github.com/OpenGene/MutScan)
- [svaba](https://github.com/walaj/svaba): structural variation and indel detection by local assembly
- [manta](https://github.com/Illumina/manta): structural variant and indel caller using mapped sequencing data
- [JAFFA](https://github.com/Oshlack/JAFFA): a multi-step pipeline that takes either raw RNA-Seq reads, or pre-assembled transcripts, then searches for gene fusions
- [Picky](https://github.com/TheJacksonLaboratory/Picky): structural variants pipeline for long reads
- [CREST](http://www.stjuderesearch.org/site/lab/zhang): a algorithm for detecting genomic structural variations at base-pair resolution using next-generation sequencing data
- [Control-FREEC](http://boevalab.com/FREEC/): a tool for detection of copy-number changes and allelic imbalances (including LOH) using deep-sequencing data
- [Strelka](ftp://strelka@ftp.illumina.com/): accurate somatic small-variant calling from sequenced tumor–normal sample pairs
- [GISTIC2](http://portals.broadinstitute.org/cgi-bin/cancer/publications/pub_paper.cgi?mode=view&paper_id=216&p=t): facilitates sensitive and confident localization of the targets of focal somatic copy-number alteration in human cancers
- [BreaKmer](https://github.com/ccgd-profile/BreaKmer): A method to identify structural variation from sequencing data in target regions
- [deTiN](https://github.com/broadinstitute/deTiN): DeTiN is designed to measure tumor-in-normal contamination and improve somatic variant detection sensitivity when using a contaminated matched control.
- [vadir](https://academic.oup.com/gigascience/article/7/2/gix122/4757064): an integrated approach to Variant Detection in RNA
- [CN_Learn](https://github.com/girirajanlab/CN_Learn): a framework to integrate Copy Number Variant (CNV) predictions made by multiple algorithms using exome sequencing datasets
- [SVseq2](https://sourceforge.net/projects/svseq2/)
- [SoftSV](https://sourceforge.net/projects/softsv/): a tool for the detection of small and large deletions, inversions, tandem duplications and translocations from paired-end sequencing data.
- [wham](https://github.com/zeeev/wham): consists of two programs, wham and whamg. wham, the original tool, is a very sensitive method with a high false discovery rate. The second program, whamg, is more accurate and better suited for general structural variant (SV) discovery.

##### Variant Annotation

- [ANNOVAR](http://annovar.openbioinformatics.org/en/latest/)
- [SnpEff](http://snpeff.sourceforge.net/index.html)
- [gemini](https://github.com/arq5x/gemini)
- [VEP](http://www.ensembl.org/info/docs/tools/vep/index.html)
- [Variant Annotation Integrator](http://genome.ucsc.edu/cgi-bin/hgVai)
- [vcfanno](https://github.com/brentp/vcfanno)
- [pcgr](https://github.com/sigven/pcgr)
- [annovarR](https://github.com/JhuangLab/annovarR)
- [OncodriveCLUST](http://bg.upf.edu/group/projects/oncodrive-clust.php): exploiting the positional clustering of somatic mutations to identify cancer genes
- [bystro](https://github.com/akotlar/bystro): Bystro genetic analysis (annotation, filtering, statistics
- [contest](http://www.broadinstitute.org/cancer/cga/contest): a tool (and method) for estimating the amount of cross-sample contamination in next generation sequencing data.  Using a Bayesian framework, contamination levels are estimated from array based genotypes and sequencing reads
- [pathopredictor](https://github.com/samesense/pathopredictor): Predict pathogenic and benign missense variant status.

##### Variant Visualization (SNVs, INDELs, SVs)

- [ProteinPaint](https://proteinpaint.stjude.org/)
- [AGFusion](https://github.com/murphycj/AGFusion)
- [GenomeUPlot](https://github.com/gaitat/GenomeUPlot)
- [BreakPointSurveyor](https://github.com/ding-lab/BreakPointSurveyor)
- [chimeraviz](https://github.com/stianlagstad/chimeraviz)
- [Oncoprinter](http://www.cbioportal.org/oncoprinter.jsp)
- [MutationMapper](http://www.cbioportal.org/mutation_mapper.jsp)
- [pv](https://github.com/biasmv/pv): 3D structure visualization in WEB
- [g2s](https://github.com/genome-nexus/g2s): mappings between protein sequence positions and PDB 3D protein structure models
- [NGB](https://github.com/epam/NGB): structural Variations (SVs) visualization capabilities, high performance, scalability, and cloud data support

##### Variant Screen

- [LARVA](http://larva.gersteinlab.org/)
- [DANN](https://cbcl.ics.uci.edu/public_data/DANN)
- [NCBoost](https://github.com/RausellLab/NCBoost): Classifier of pathogenic non-coding variants in Mendelian diseases

##### Alternative Splicing

- [LeafCutter](https://github.com/davidaknowles/leafcutter/) Annotation-free quantification of RNA splicing.
- [rMATS](http://rnaseq-mats.sourceforge.net/rmats3.2.5/)
- [MMSplice](https://github.com/gagneurlab/MMSplice): variant effect predictions on splicing
- [pram](https://github.com/pliu55/pram) predict intergenic transcript models from RNA-seq (Genome Res 2020)
- [shark](https://github.com/AlgoLab/shark) Mapping-free filtering of irrelevant RNA-Seq reads（Bioinformatics 202）
- [PAIRADISE](https://github.com/Xinglab/PAIRADISE) Paired Replicate Analysis of Allelic Differential Splicing Events (AJHG 2020)
- [IRFinder](https://github.com/williamritchie/IRFinder) Detecting intron retention from RNA-Seq experiments
- [iread](https://github.com/genemine/iread) Detect intron retention(IR) events from RNA-seq datasets
- [DARTS](https://github.com/Xinglab/DARTS) Deep-learning Augmented RNA-seq analysis of Transcript Splicing
- [SpliceAI](https://github.com/Illumina/SpliceAI) A deep learning-based tool to identify splice variants
- DEXSeq Detecting differential usage of exons from RNA-seq data
- [MATS](http://intron.healthcare.uiowa.edu/MATS/)
- [cash](https://soft.novelbio.com/cash/) Comprehensive alternative splicing hunting
- [tappas](https://app.tappas.org/downloads/) a comprehensive computational framework for the analysis of the functional impact of differential splicing
- [dsreg](https://bitbucket.org/cmartiga/dsreg) dSreg is a library to perform joint inference of differential splicing and regulatory mechanisms using RNA-seq data.
- [PSI-Sigma](https://github.com/wososa/PSI-Sigma)  a comprehensive splicing detection method for short-read and long-read RNAseq analysis.
- [PsiCLASS](https://github.com/splicebox/PsiCLASS) Simultaneous multi-sample transcript assembler for RNA-seq data
- [IsoformSwitchAnalyzeR](http://bioconductor.org/packages/release/bioc/html/IsoformSwitchAnalyzeR.html) Identify, Annotate and Visualize Alternative Splicing and Isoform Switches with Functional Consequences from both short- and long-read RNA-seq data.
- [yanagi](https://github.com/HCBravoLab/yanagi) Transcript Segment Library Construction for RNA-Seq Quantification
- [AStrap](https://github.com/BMILAB/AStrap) Identification of alternative splicing from transcript sequences without a reference genome
- [DSC](https://github.com/louadi/DSC) A deep learning approach for classification of alternative splicing events
- [CATANA](https://github.com/shiauck/CATANA)  Comprehensive Alternative Transcripts Atlas based oN Annotation (CATANA) to identify all 10 known AS and AT events.
- [benchmarkingDiffExprAndSpl](https://github.com/gamerino/benchmarkingDiffExprAndSpl) A benchmarking of workflows for detecting differential splicing and differential expression at isoform level in human RNA-seq studies
- [psichomics](https://academic.oup.com/nar/article/47/2/e7/5114259) psichomics: graphical application for alternative splicing quantification and analysis
- [matt](http://matt.crg.eu/#INST) A Unix toolkit for analyzing genomic sequences with focus on down-stream analysis of alternative splicing events
- [PathwaySplice](https://bioconductor.org/packages/release/bioc/html/PathwaySplice.html) An R Package for Unbiased Splicing Pathway Analysis

##### Gene Expression Data Analysis

- [Cufflinks](http://cole-trapnell-lab.github.io/cufflinks/)
- [DESeq2](http://www.bioconductor.org/packages/release/bioc/html/DESeq2.html)
- [edgeR](http://www.bioconductor.org/packages/release/bioc/html/edgeR.html)
- [HTSeq](https://github.com/simon-anders/htseq)
- [RESM](https://github.com/deweylab/RSEM): RNA-Seq by Expectation-Maximization, accurate quantification of gene and isoform expression from RNA-Seq data.
- [sRNAnalyzer](http://srnanalyzer.systemsbiology.net/)
- [mrnn](https://github.com/hendrixlab/mRNN): an implementation of a Gated Recurrent Unit (GRU) network for classification of transcripts as either coding or noncoding
- [prada](https://sourceforge.net/projects/prada): pipeline for RNA-Sequencing Data Analysis
- [ballgown](https://github.com/alyssafrazee/ballgown): a software package designed to facilitate flexible differential expression analysis of RNA-Seq data. It also provides functions to organize, visualize, and analyze the expression measurements for your transcriptome assembly.
- [subread](http://subread.sourceforge.net/): comprises a suite of software programs for processing next-gen sequencing read data, i.e. featureCounts: a software program developed for counting reads to genomic features such as genes, exons, promoters and genomic bins. High-performance read alignment, quantification and mutation discovery. 
- [kallisto](https://pachterlab.github.io/kallisto/manual): a program for quantifying abundances of transcripts from bulk and single-cell RNA-Seq data, or more generally of target sequences using high-throughput sequencing reads. It is based on the novel idea of pseudoalignment for rapidly determining the compatibility of reads with targets, without the need for alignment.
- [salmon](https://combine-lab.github.io/salmon/): a tool for quantifying the expression of transcripts using RNA-seq data. Salmon uses new algorithms (specifically, coupling the concept of quasi-mapping with a two-phase inference procedure) to provide accurate expression estimates very quickly (i.e. wicked-fast) and while using little memory. Salmon performs its inference using an expressive and realistic model of RNA-seq data that takes into account experimental attributes and biases commonly observed in real RNA-seq data.
- [mixcr](https://github.com/milaboratory/mixcr): a universal software for fast and accurate extraction of T- and B- cell receptor repertoires from any type of sequencing data. Free for academic use only
- [trust](https://bitbucket.org/liulab/trust/): Tcr Receptor Utilities for Solid Tissue (TRUST) is a computational tool to analyze TCR and BCR sequences using unselected RNA sequencing data, profiled from solid tissues, including tumors. TRUST performs de novo assembly on the hypervariable complementarity-determining region 3 (CDR3) and reports contigs containing the CDR3 DNA and amino acid sequences. TRUST then realigns the contigs to IMGT reference gene sequences to report the corresponding variable (V) or joining (J) genes.
- [topconfects](https://github.com/pfh/topconfects): is intended for RNA-seq or microarray Differntial Expression analysis and similar, where we are interested in placing confidence bounds on many effect sizes--one per gene--from few samples.
- [PLIER](https://github.com/wgmao/PLIER): Pathway-Level Information Extractor (PLIER): a generative model for gene expression data.

##### Virus and Microbial Related

- [viral-ngs](https://github.com/broadinstitute/viral-ngs)
- [qap](https://github.com/mingjiewang/qap)
- [ROP](https://github.com/smangul1/rop): discovering the source of all RNA-seq reads, including those originating from repeat sequences, recombinant B and T cell receptors, and microbial communities
- [ViFi](https://github.com/namphuon/ViFi): pipeline for identifying viral integration and fusion mRNA reads from NGS data
- [hgtid](http://kalarikrlab.org/Software/HGT-ID.html): an efficient and sensitive workflow to detect human-viral insertion sites using next-generation sequencing data
- [MicroPro](https://github.com/zifanzhu/MicroPro): a software to perform profiling of both known and unknown microbial organisms for metagenomic dataset.
- [FEAST](https://github.com/cozygene/FEAST): a scalable algorithm for quantifying the origins of complex microbial communities.
- [mcorr](https://github.com/kussell-lab/mcorr): inferring bacterial recombination rates from large-scale sequencing datasets.
- [VirusFinder2](https://bioinfo.uth.edu/VirusFinder/): a new software tool for characterizing intra-host viruses through next generation sequencing (NGS) data.
- [VirusSeq](https://odin.mdacc.tmc.edu/~xsu1/VirusSeq.html): a algorithmic tool for detecting known viruses and their integration sites using next-generation sequencing of human cancer tissue.
- [BatVI](http://biogpu.ddns.comp.nus.edu.sg/~ksung/batvi/index.html): a fast and sensitive method to determine viral integrations.

##### Single Cell

- [seurat](https://github.com/satijalab/seurat)
- [SCnorm](http://www.biostat.wisc.edu/~kendzior/SCNORM/)
- [dropClust](https://github.com/debsin/dropClust)
- [scran](https://bioconductor.org/packages/release/bioc/html/scran.html): batch effect adjust
- [trendsceek](https://github.com/edsgard/trendsceek): spatial expression trends in single-cell gene expression data
- [scRNA-tools](https://www.scrna-tools.org/): a database of software tools for the analysis of single-cell RNA-seq data.
- [awesome-single-cell](https://github.com/seandavi/awesome-single-cell): list of software packages (and the people developing these methods) for single-cell data analysis, including RNA-seq, ATAC-seq, etc.
- [SAVER](https://github.com/mohuangx/SAVER): SAVER (Single-cell Analysis Via Expression Recovery) implements a regularized regression prediction and empirical Bayes method to recover the true gene expression profile in noisy and sparse single-cell RNA-seq data.
- [CellSIUS](https://github.com/Novartis/CellSIUS): an R package enabling the identification and characterization of (rare) cell sub-populations from complex scRNA-seq datasets: it takes as input expression values of N cells grouped into M(>1) clusters. Within each cluster, genes with a bimodal distribution are selected and only genes with cluster-specific expression are retained. Among these candidate marker genes, sets with correlated expression patterns are identified by graph-based clustering. Finally, cells are assigned to subgroups based on their average expression of each gene set. The CellSIUS algorithm output provides the rare/ sub cell types by cell indices and their transcriptomic signatures.
- [SCRABBLE](https://github.com/software-github/SCRABBLE): Single Cell RNA-Seq imputAtion constrained By BuLk RNAsEq data (SCRABBLE)
- [Melissa](https://github.com/andreaskapou/Melissa): a Bayesian hierarchical method to quantify spatially-varying methylation profiles across genomic regions from single-cell bisulfite sequencing data (scBS-seq). Melissa clusters individual cells based on local methylation patterns, enabling the discovery of epigenetic diversities and commonalities among individual cells. The clustering also acts as an effective regularisation method for imputation of methylation on unassayed CpG sites, enabling transfer of information between individual cells.
- [paga](https://github.com/theislab/paga): mapping out the coarse-grained connectivity structures of complex manifolds.
- [clonealign](https://github.com/kieranrcampbell/clonealign): Bayesian inference of clone-specific gene expression estimates by integrating single-cell RNA-seq and single-cell DNA-seq data
- [CellFishing.jl](https://github.com/bicycle1885/CellFishing.jl): (cell finder via hashing) is a tool to find similar cells of query cells based on their transcriptome expression profiles.
- [VIPER](https://github.com/ChenMengjie/VIPER): variability-preserving imputation for accurate gene expression recovery in single-cell RNA sequencing studies.
- [scgen](https://github.com/theislab/scgen): a tensorflow implementation of scGen. scGen is a generative model to predict single-cell perturbation response across cell types, studies and species.
- [conos](https://github.com/hms-dbmi/conos): a package to wire together large collections of single-cell RNA-seq datasets. It focuses on uniform mapping of homologous cell types across heterogeneous sample collections. For instance, a collection of dozens of peripheral blood samples from cancer patients, combined with dozens of controls. And perhaps also including samples of a related tissue, such as lymph nodes.
- [MAGIC](https://github.com/KrishnaswamyLab/MAGIC): Markov Affinity-based Graph Imputation of Cells (MAGIC) is an algorithm for denoising high-dimensional data most commonly applied to single-cell RNA sequencing data. MAGIC learns the manifold data, using the resultant graph to smooth the features and restore the structure of the data.
- [zinbwave](https://github.com/drisso/zinbwave): a zero-inflated negative binomial model for single-cell RNA-seq data, with latent factors.
- [SIMLR_PY](https://github.com/bowang87/SIMLR_PY): Visualization and analysis of single-cell RNA-seq data by kernel-based similarity learning.
- [dca](https://github.com/theislab/dca): a deep count autoencoder network to denoise scRNA-seq data and remove the dropout effect by taking the count structure, overdispersed nature and sparsity of the data into account using a deep autoencoder with zero-inflated negative binomial (ZINB) loss function.
- [scVI](https://github.com/YosefLab/scVI): deep generative modeling for single-cell transcriptomics.
- [PhenoGraph](https://github.com/jacoblevine/PhenoGraph): a clustering method designed for high-dimensional single-cell data. It works by creating a graph ("network") representing phenotypic similarities between cells and then identifying communities in this graph.
- [splatter](https://github.com/Oshlack/splatter-paper): simulation of Single-cell RNA sequencing data.
- [DeepNovo-DIA](https://github.com/nh2tran/DeepNovo-DIA): de novo peptide sequencing for DDA and DIA by deep learning.
- [scVI](https://github.com/YosefLab/scVI): Deep generative modeling for single-cell transcriptomics.

##### Protein Data Related

- [interproscan](http://www.ebi.ac.uk/interpro)
- [effusion](http://www.babbittlab.ucsf.edu/effusion): prediction of Protein Function from Sequence Similarity Networks

##### Expression Quantitative Trait Loci, eQTL

- [CaVEMaN](https://github.com/funpopgen/CaVEMaN)

##### ChIP-seq analysis

- [MACS](https://github.com/taoliu/MACS)
- [CEAS](http://liulab.dfci.harvard.edu/CEAS/)
- [MDSeqPos](https://bitbucket.org/cistrome/cistrome-applications-harvard/src/c477732c5c88/mdseqpos/)
- [conservation_plot](https://github.com/taoliu/taolib/blob/master/Scripts/conservation_plot.py)

##### Primer Design

- [CEMAsuite](https://sourceforge.net/projects/cemasuite/)
- [Primer3plus](http://www.bioinformatics.nl/cgi-bin/primer3plus/primer3plus.cgi)

Followling Copy From https://pcrprimerdesign.github.io/.

**Primer3**

|  | Publications | Availability | Interface | Language |
| --- | --- | --- | --- | --- |
| [Primer3](https://sourceforge.net/projects/primer3/files/primer3/) | Rozen and Skaletsky, Koressaar and Remm, Untergasser et al. | Open | WUI/CUI | C |

**Sanger**

|  | Publication | Availability | Primer3-Based? | Interface | Language |
| --- | --- | --- | --- | --- | --- |
| [PrimerZ](http://grch37.genepipe.ncgm.sinica.edu.tw/primerz/beginDesign.do) | Tsai et al. | Free | Yes | WUI | Java |
| [JCVI Primer Designer](https://sourceforge.net/projects/primerdesigner/) | Li et al. | Open | No | CUI | Perl |
| [ExonPrimer](https://ihg.helmholtz-muenchen.de/ihg/ExonPrimer.html) | N/P | Free | Yes | WUI | Perl |
| [MPDP3 (abbr.)](http://flypush.imgen.bcm.tmc.edu/primer/) | N/P | Free | Yes | WUI | ? |
| [ConservedPrimer2.0](https://probes.pw.usda.gov/ConservedPrimers/index.html) | You et al. | Open | Yes | WUI/CUI | Java |
| [PrimerDesign-M](https://www.hiv.lanl.gov/content/sequence/PRIMER_DESIGN/primer_design.html) | Yoon and Leitner | Free | No | WUI | ? |

**RT-qPCR**

|  | Publication | Availability | Primer3-Based? | Interface | Language |
| --- | --- | --- | --- | --- | --- |
| [AutoPrime](http://www.autoprime.de/AutoPrimeWeb) | Wrobel et al. | Open | Yes | WUI | Perl |
| [QuantPrime](http://www.quantprime.de/) | Arvidsson et al. | Free | Yes | WUI | Python/PHP |
| [Primer-BLAST](https://www.ncbi.nlm.nih.gov/tools/primer-blast/) | Ye et al. | Open | Yes | WUI | C++ |

**SNP**

|  | Publication | Availability | Primer3-Based? | Interface | Language |
| --- | --- | --- | --- | --- | --- |
| [PIRA PCR designer](http://primer1.soton.ac.uk/primer2.html) | Ke et al. | Free | No | WUI | Java |
| [PRIMER1](http://primer1.soton.ac.uk/primer1.html) | Ye | Free | No | WUI | Java |
| [PCR designer](http://primer1.soton.ac.uk/primer.html) | Ke et al. | Free | No | WUI | ? |

**Splicing Variant**

|  | Publication | Availability | Primer3-Based? | Interface | Language |
| --- | --- | --- | --- | --- | --- |
| [RASE](http://designs.lgfus.ca/cgi-bin/bsp_designs/index.pl) | Brosseau et al. | Free | Yes | WUI | Perl |
| [PRIMEGENS-v2](http://primegens.org/) | Srivastava et al. | Open | Yes | WUI/CUI | C |
| [PrimerSeq](http://primerseq.sourceforge.net/) | Tokheim et al. | Open | Yes | GUI | Java |

**Methylation**

|  | Publication | Availability | Primer3-Based? | Interface | Language |
| --- | --- | --- | --- | --- | --- |
| [Methprimer](http://www.urogene.org/methprimer/) | Li and Dahiya | Free | Yes | WUI | C/Perl |
| [BiSearch](http://bisearch.enzim.hu/?m=search) | Tusnady et al. | Free | No | WUI | ? |
| [Bisprimer](https://www.ibp.cz/local/software/BisPrimer/) | Kovacova and Janousek | Free | No | GUI | ? |
| [MSP-HTPrimer](https://sourceforge.net/projects/msp-htprimer/) | Pandey et al. | Open | Yes | WUI | Python |

**Microsatellite**

|  | Publication | Availability | Primer3-Based? | Interface | Language |
| --- | --- | --- | --- | --- | --- |
| [MSATCOMMANDER](https://code.google.com/archive/p/msatcommander/) | Faircloth | Open | Yes | CUI/GUI | Python |
| [WebSat](http://wsmartins.net/websat/) | Martins et al. | Free | Yes | WUI | Javascript/PHP |
| [QDD](http://net.imbe.fr/~emeglecz/qdd.html) | Meglécz et al. | Free | Yes | CUI/Galaxy | Perl |

**Conserved/ Degenerate**

|  | Publication | Availability | Primer3-Based? | Interface | Language |
| --- | --- | --- | --- | --- | --- |
| [HYDEN](http://acgt.cs.tau.ac.il/hyden/) | Linhart and Shamir | Free | No | CUI | C++ |
| [Amplicon](http://amplicon.sourceforge.net/) | Jarman | Open | No | GUI | Python |
| [Primaclade](http://webhome.auburn.edu/~santosr/primaclade.htm) | Gadberry et al. | Free | Yes | WUI | Bioperl |
| [PriFi](https://services.birc.au.dk/prifi/) | Fredslund et al. | Free | No | WUI | ? |
| [GeneFisher2](https://bibiserv.cebitec.uni-bielefeld.de/genefisher2) | Lamprecht et al. | Free | No | WUI | Javascript/XML |
| [PrimerIdent](http://primerident.up.pt/primerident_1.htm) | Pessoa et al. | Free | Yes | WUI | Perl |
| [TOPSI](http://www.bhsai.org/downloads/topsi.tar.gz) | Vijaya Satya et al. | Open | Yes | WUI/CUI | BioPerl |
| [Gemi](https://sourceforge.net/projects/gemi/) | Sobhy and Colson | Open | Yes | GUI | C# |
| [easyPAC](https://sourceforge.net/projects/easypac/) | Rosenkranz | Free | No | CUI | Perl |

**Multiplex**

|  | Publication | Availability | Primer3-Based? | Interface | Language |
| --- | --- | --- | --- | --- | --- |
| [MultiPLX](http://bioinfo.ut.ee/multiplx/) | Kaplinski and Remm | Free | No | CUI/WUI | C++ |
| [MuPlex](http://genomics14.bu.edu:8080/MuPlex/Muplex.html) | Rachlin et al. | Free | No | WUI | Java |
| [PrimerStation](https://ps.cb.k.u-tokyo.ac.jp/) | Yamada et al. | Free | No | WUI | ? |
| [MPprimer](https://code.google.com/archive/p/mpprimer/) | Shen et al. | Open | Yes | CUI/WUI | Python |
| [Optimus Primer](http://op.pgx.ca/) | Brown et al. | Free | Yes | WUI | ? |
| [MCMC-ODPR](https://warwick.ac.uk/fac/sci/lifesci/research/archaeobotany/downloads/MCMC_ODPR) | Kitchen et al. | Free | No | CUI | Perl/Java |
| [MPD](https://wingolab-org.github.io/mpd-c/) | Wingo et al. | Open | No | WUI/CUI | C/Perl |
| [Oli2go](http://oli2go.ait.ac.at/) | Hendling et al. | Free | Yes | WUI | Python |

**Multifunctional**

|  | Publication | Availability | Primer3-Based? | Interface | Language |
| --- | --- | --- | --- | --- | --- |
| [Primo](http://www.changbioscience.com/primo/) | Li et al. | Free | No | WUI | C |
| [PerlPrimer](http://perlprimer.sourceforge.net/) | Marshall | Open | No | GUI | Perl/TK |
| [The PCR suite](http://pcrsuite.cse.ucsc.edu/) | Baren and Heutink | Open | Yes | WUI | Perl |
| [BatchPrimer3](https://probes.pw.usda.gov/batchprimer3/) | You et al. | Free | Yes | WUI | Perl |
| [jPCR](http://primerdigital.com/tools/) | Kalendar et al. | Free | No | GUI | Java |

**Niche Applications**

|  | Function | Publication | Availability | Primer3-Based? | Interface | Language |
| --- | --- | --- | --- | --- | --- | --- |
| [RJPrimers](https://probes.pw.usda.gov/RJPrimers/) | Transposon | You et al. | Open | Yes | WUI/CUI | Perl/Java |
| [PrimerX](http://www.bioinformatics.org/primerx/) | Mutagenesis | N/P | Free | ? | WUI | ? |
| [AcePrimer](http://elegans.bcgsc.ca/gko/aceprimer.shtml) | C. elegans | Mckay and Jones | Free | Yes | WUI | Perl |
| [PrecisePrimer](https://absynth.issb.genopole.fr/PrecisePrimer) | Cloning | Pauthenier and Faulon | Free | No | WUI | ? |
| [MultiMPrimer3](http://bioinfo.ut.ee/multimprimer3/) | Pathogen | Koressaar et al. | Free | Yes | WUI | Perl |
| [AmplifX](https://inp.univ-amu.fr/en/amplifx-manage-test-and-design-your-primers-for-pcr) | Management | N/P | Free | No | GUI | ? |

##### Work flow

- [bcbio-nextgen](https://github.com/chapmanb/bcbio-nextgen)
- [nextflow](https://github.com/nextflow-io/nextflow)
- [orange3](https://github.com/biolab/orange3)
- [sequana](https://github.com/sequana/sequana)
- [snakemake](https://snakemake.readthedocs.io/en/latest/)
- [WDL](https://github.com/openwdl/wdl)
- [cromwell](https://github.com/broadinstitute/cromwell)
- [CWL](http://www.commonwl.org/)
- [bpipe](https://github.com/ssadedin/bpipe)

##### Unclassified

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
- [bedops](https://github.com/bedops/bedops): a suite of tools to address common questions raised in genomic studies — mostly with regard to overlap and proximity relationships between data sets. It aims to be scalable and flexible, facilitating the efficient and accurate analysis and management of large-scale genomic data.
- [vcftools](https://github.com/vcftools/vcftools)
- [bcftools](https://github.com/samtools/bcftools)
- [bamtools](https://github.com/pezmaster31/bamtools)
- [maftools](https://github.com/PoisonAlien/maftools)
- [bamUtil](https://github.com/statgen/bamUtil)
- [vcflib](https://github.com/vcflib/vcflib)
- [samstat](https://sourceforge.net/projects/samstat)
- [seqtk](https://github.com/lh3/seqtk)
- [sratools](http://ncbi.github.io/sra-tools/)
- [bcl2fastq2](https://support.illumina.com/sequencing/sequencing_software/bcl2fastq-conversion-software.html)
- [ucsc_utils](http://hgdownload.cse.ucsc.edu/admin/exe/)
- [MeQA](http://life.tongji.edu.cn/meqa/index.html)
- [IdCheck](http://eqtl.rc.fas.harvard.edu/idcheck/)
- [SAMBLASTER](https://github.com/GregoryFaust/samblaster)
- [ngstk](https://github.com/JhuangLab/ngstk)
- [BioInstaller](https://github.com/JhuangLab/BioInstaller)
- [ChromHMM](https://github.com/jernst98/ChromHMM)
- [ABSOLUTE](http://archive.broadinstitute.org/cancer/cga/absolute)
- [HAPSEG](http://software.broadinstitute.org/cancer/software/genepattern/modules/docs/HAPSEG/1)
- [Atlas-SNP, Atlas2 Suite](https://sourceforge.net/p/atlas2)
- [Beagle](http://faculty.washington.edu/browning/beagle/beagle.html)
- [CIBERSORT](https://cibersort.stanford.edu/index.php)
- [biobloom](https://github.com/bcgsc/biobloom)
- [APAtrap](https://apatrap.sourceforge.io)
- [phenopredict](https://github.com/leekgroup/phenopredict): predicting phenotype sample information using gene expression
- [recount](https://github.com/leekgroup/recount)
- [bart](http://faculty.virginia.edu/zanglab/bart/): predicting functional transcription factors using gene set or a ChIP-seq dataset as input
- [LSMM (Latent Sparse Mixed Model)](https://github.com/mingjingsi/LSMM): integrating functional annotations with genome-wide association studies
- [vcf2maf](https://github.com/mskcc/vcf2maf/): Convert a VCF into a MAF, where each variant is annotated to only one of all possible gene isoforms
- [r2d3](https://github.com/rstudio/r2d3): R Interface to D3 Visualizations
- [liteq](https://github.com/r-lib/liteq): Serverless R message queue using SQLite
- [ReLaXed](https://github.com/RelaxedJS/ReLaXed): Create PDF documents using web technologies
- [dash](https://github.com/jonocarroll/dash): RStudio Addin to Run a Selection as a Background Job
- [threadpool](https://github.com/rdpeng/threadpool): Parallel Processing in R using a Thread Pool
- [marina](http://califano.c2b2.columbia.edu/): master Regulator Inference Algorithm
- [paradigm](http://paradigm.five3genomics.com): PAthway Representation and Analysis by Direct Inference on Graphical Models
- [hupan](http://cgm.sjtu.edu.cn/hupan/index.html): a pan-genome analysis pipeline for human genomes.
- [RaPID](https://github.com/ZhiGroup/RaPID): an ultra-fast tool for the identification of identity-by-descent segments among genotyped individuals.
- [gemini](https://github.com/sellerslab/gemini): a variational Bayesian approach to identify genetic interactions from combinatorial CRISPR screens.
- [CONFINED](https://github.com/cozygene/CONFINED): for the purpose of capturing replicable sources of biological variability in methylation data. These sources include, for example, age, sex, and cell-type composition. Importantly, the variation captured by CONFINED does not include any variability from technical or batch effects.
- [marginPhase](https://github.com/benedictpaten/marginPhase): a program for simultaneous haplotyping and genotyping.
- [osca](http://cnsgenomics.com/software/osca/): (OmicS-data-based Complex trait Analysis) is a software tool written in C/C++ for the analysis of complex traits using multi-omics data.
- [ChiCMaxima](https://github.com/yousra291987/ChiCMaxima): a pipeline for analyzing and identificantion of chromation loops in CHi-C promoters data.
- [circBrain](https://github.com/yangence/circBrain): Detection of circular RNA expression and related quantitative trait loci in the human dorsolateral prefrontal cortex.
- [bazam](https://github.com/ssadedin/bazam): A read extraction and realignment tool for next generation sequencing data.
- [DegNorm](https://nustatbioinfo.github.io/DegNorm/): short for degradation normalization, is a bioinformatics pipeline designed to correct for bias due to the heterogeneous patterns of transcript degradation in RNA-seq data. DegNorm helps improve the accuracy of the differential expression analysis by accounting for this degradation.
- [conbase](https://github.com/conbase/conbase): a software for unsupervised discovery of clonal somatic mutations in single cells through read phasing
- [3DChromatin_ReplicateQC](https://github.com/kundajelab/3DChromatin_ReplicateQC): Software to compute reproducibility and quality scores for Hi-C data.
- [rnbeads](https://rnbeads.org/): an R package for comprehensive analysis of DNA methylation data obtained with any experimental protocol that provides single-CpG resolution. Supported assays include Infinium and EPIC microarrays and bisulfite sequencing protocols, and also MeDIP-seq and MBD-seq once the data have been preprocessed with DNA methylation level inference software. 
- [I-Boost](https://github.com/alexwky/I-Boost): a statistical boosting method that integrates multiple types of high-dimensional genomics data with clinical data for predicting survival time.
- [bin3C](https://github.com/cerebis/bin3C): extract metagenome-assembled genomes (MAGs) from metagenomic data using Hi-C.
- [dStruct](https://github.com/AviranLab/dStruct): method for identifying differential reactive regions from RNA structurome profiling data.
- [Skmer](https://github.com/shahab-sarmashghi/Skmer): a fast tool for estimating distances between genomes from low-coverage sequencing reads (genome-skims), without needing any assembly or alignment step.
- [iGUIDE](https://github.com/cnobles/iGUIDE): a pipeline written in snakemake for processing and analyzing double-strand DNA break events. These events may be induced, such as by designer nucleases like Cas9, or spontaneous, as produced through DNA replication or ionizing radiation.
- [plyranges](https://github.com/sa-lee/plyranges): provides a consistent interface for importing and wrangling genomics data from a variety of sources. The package defines a grammar of genomic data manipulation based on dplyr and the Bioconductor packages IRanges, GenomicRanges, and rtracklayer. 
- [FORGe](https://github.com/langmead-lab/FORGe): tool for ranking variants and building an optimal graph genome.
- [SE-MEI](https://github.com/dpryan79/SE-MEI): tools for finding mobile element insertions from single-end datasets.
- [Anchor](https://github.com/GuanLab/Anchor): trans-cell Type Prediction of Transcription Factor Binding Sites
- [adVNTR](https://github.com/mehrdadbakhtiari/adVNTR): a tool for genotyping Variable Number Tandem Repeats (VNTR) from sequence data. It works with both NGS short reads (Illumina HiSeq) and SMRT reads (PacBio) and finds diploid repeating counts for VNTRs and identifies possible mutations in the VNTR sequences.
- [ldsc](https://github.com/bulik/ldsc): a command line tool for estimating heritability and genetic correlation from GWAS summary statistics. ldsc also computes LD Scores.
- [BigStitcher](https://github.com/PreibischLab/BigStitcher): ImgLib2/BDV implementation of Stitching for large datasets.
- [ivtnmr](https://github.com/systemsnmr/ivtnmr): In Vitro Transcription NMR. Protocol, code and examples for the co-transcriptional RNA folding network reconstruction.
- [DIVERS](https://github.com/hym0405/DIVERS): (Decomposition of Variance Using Replicate Sampling), including absolute abundance estimation from spike-in sequencing and the variance/covariance decompostion of absolute bacterial abundances.
- [prosit](https://github.com/kusterlab/prosit/): offers high quality MS2 predicted spectra for any organism and protease as well as iRT prediction
- [DeepCell](http://github.com/vanvalenlab/deepcell-tf): Software library for deep-learning-enabled single-cell analysis in the
cloud. Users manage their own cloud deployment; model training and
deployment are performed through a web interface.
- [CDeep3M](http://github.com/CRBS/cdeep3m): Amazon machine image for training and deploying deep learning models
for 2D and 3D image segmentation
- [U-Net](http://github.com/lmb-freiburg/Unet-Segmentation): ImageJ plug-in for single-cell image segmentation with U-Net.
- [CellProfiler](http://github.com/CellProfiler/CellProfiler): Python-based software for single-cell segmentation and morphological profiling. Single-cell segmentation with U-Net available through a REST API.
- [Mask R-CNN](https://github.com/matterport/Mask_RCNN): Mask R-CNN for object detection and instance segmentation on Keras and TensorFlow.
- [Cell Cognition Explorer](https://software.cellcognition-project.org/): an open-source image processing tool for the analysis of cellular phenotypes in microscopy. CellCognition Explorer enables phenotype classification by supervised machine learning. To detect rare phenotypes, outlier morphologies can be automatically found by novelty detection methods. A key feature of CellCognition Explorer is an improved classifier training procedure based on automated pre-processing of the full data set into cell gallery images, which can be automatically sorted based on phenotype similarity for efficient iterative classifier training.
- [DeepLabCut](https://alexemg.github.io/DeepLabCut/): a toolbox for markerless pose estimation of animals performing various tasks.
- [LEAP](https://github.com/talmo/leap): LEAP Estimates Animal Pose, a framework for animal body part position estimation via deep learning.
- [idtracker.ai](https://gitlab.com/polavieja_lab/idtrackerai): a software that tracks and identifies animals in collectives from videos.
- [In silico labeling](https://github.com/google/in-silico-labeling): Predicting fluorescent labels in unlabeled images.
- [Image restoration](http://csbdeep.bioimagecomputing.com/): a toolbox for Content-aware Image Restoration (CARE).
- [trackViewer](https://github.com/jianhong/trackViewer.documentation): a Bioconductor package for interactive and integrative visualization of multi-omics data
- [cistopic](https://github.com/aertslab/cistopic): probabilistic modelling of cis-regulatory topics from single cell epigenomics data
- [selene](https://github.com/FunctionLab/selene): a framework for training sequence-level deep learning networks.
- [sirius](https://bio.informatik.uni-jena.de/software/sirius/): a rapid tool for turning tandem mass spectra into metabolite structure information.
- [SDA](https://github.com/mvollger/SDA): Segmental Duplication Assembler (SDA).
- [fmriprep](https://github.com/poldracklab/fmriprep): a robust and easy-to-use pipeline for preprocessing of diverse fMRI data. The transparent workflow dispenses of manual intervention, thereby ensuring the reproducibility of the results.
- [unifrac](https://github.com/biocore/unifrac): for high-performance phylogenetic diversity calculations

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
- [qvalue](https://github.com/StoreyLab/qvalue): estimating q-values and false discovery rate quantities
- [GenVisR](https://github.com/griffithlab/GenVisR): genome data visualizations
- [r-color-palettes](https://github.com/EmilHvitfeldt/r-color-palettes): Comprehensive list of color palettes available in r
- [sequenza](http://www.cbs.dtu.dk/biotools/sequenza/): a novel set of tools providing a fast python script to genotype cancer samples, and an R package to estimate cancer cellularity, ploidy, genome wide copy number profile and infer for mutated alleles
- [opencpu](https://github.com/opencpu/opencpu): A system for embedded scientific computing and reproducible research with R
- [ggthemr](https://github.com/cttobin/ggthemr): Themes for ggplot2
- [paletter](https://github.com/AndreaCirilloAC/paletter): Build your ggplot2 palette from a picture
- [ggdag](https://github.com/malcolmbarrett/ggdag): An R package for working with causal directed acyclic graphs (DAGs), [homepage](https://ggdag.malco.io/)
- [ggseqlogo](https://github.com/omarwagih/ggseqlogo): Publication-quality sequence logos in R. 
- [threejs](https://github.com/mrdoob/three.js): JavaScript 3D library
- [higlass](https://github.com/hms-dbmi/higlass): Fast contact matrix visualization for the web, [homepage(http://higlass.io)

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
- [babun](https://github.com/babun/babun)
- [cmder](https://github.com/cmderdev/cmder)

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

#### Statistics and Deep learning

- [SPSS Beginners Tutorials](https://www.spss-tutorials.com/basics/)
- [Machine learning](https://en.wikipedia.org/wiki/Machine_learning)
- [Deep learning](https://en.wikipedia.org/wiki/Deep_learning)
- [Loss function](https://en.wikipedia.org/wiki/Loss_function)
- [Maximum likelihood estimation](https://en.wikipedia.org/wiki/Maximum_likelihood_estimation)
- [Bayes' theorem](https://en.wikipedia.org/wiki/Bayes%27_theorem)
- [Perceptron](https://en.wikipedia.org/wiki/Perceptron)
- [SVM](https://en.wikipedia.org/wiki/Support_vector_machine)
- [k-nearest neighbors algorithm](https://en.wikipedia.org/wiki/K-nearest_neighbors_algorithm)
- [Convolutional Neural Network](https://en.wikipedia.org/wiki/Convolutional_neural_network)
- [K-Means](https://en.wikipedia.org/wiki/K-means_clustering)
- [HMM](https://en.wikipedia.org/wiki/Hidden_Markov_model)
- [STAT115 - HMM PPT](https://github.com/Miachol/ftp/raw/master/files/ppt/STAT115_HMM.ppt)
- [机器学习常用算法](https://en.wikipedia.org/wiki/Outline_of_machine_learning#Machine_learning_algorithms)
- [机器学习资源列表](https://github.com/adeshpande3/Machine-Learning-Links-And-Lessons-Learned)
- [Review:Deep learning, genomics, and precision medicine](https://github.com/greenelab/deep-review)
- [ML book list](http://www.hankcs.com/ml/machine-learning-entry-list.html):

```
│  李航.统计学习方法.pdf
│  机器学习及其应用.pdf
│  All of Statistics - A Concise Course in Statistical Inference - Larry Wasserman - Springer.pdf
│  Machine Learning - Tom Mitchell.pdf
│  PRML.pdf
│  PRML读书会合集打印版.pdf
│  Programming Collective Intelligence.pdf
│  [奥莱理] Machine Learning for Hackers.pdf
│  [机器学习]Tom.Mitchell.pdf
│  《大数据：互联网大规模数据挖掘与分布式处理》迷你书.pdf
│  推荐系统实践.pdf
│  数据挖掘-实用机器学习技术（中文第二版）.pdf
│  数据挖掘_概念与技术.pdf
│  机器学习-Mitchell-中文-清晰版.pdf
│  机器学习导论.pdf
│  模式分类第二版中文版Duda.pdf（全）.pdf
│  深入搜索引擎--海量信息的压缩、索引和查询.pdf
│  矩阵分析.美国 Roger.A.Horn.扫描版.pdf
│  统计学习基础 数据挖掘、推理与预测.pdf
│  
├─机器学习实战
│      machinelearninginaction.zip
│      机器学习实战 单页.pdf
│      机器学习实战.pdf
│      
└─论文文集
    └─LDA
            LDA-wangyi.pdf
            LDA数学八卦.pdf
            text-est.pdf
```

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
- [生信技能树开源语雀知识库](https://www.yuque.com/biotrainee)

### Paper

#### Basic of High-throughput sequencing technology

-   Hadfield, J. & Retief, J. A profusion of confusion in NGS methods naming. Nat Methods 15, 7-8 (2018): [http://enseqlopedia.com/enseqlopedia/](http://enseqlopedia.com/enseqlopedia/)，
-   Schuster S C. Next-generation sequencing transforms today's biology[J]. Nature methods, 2008, 5(1): 16-18.
-   Ozsolak F, Milos P M. RNA sequencing: advances, challenges and opportunities.[J]. Nature Reviews Genetics, 2011, 12(2):87-98.
-   Stark R, Grzelak M, Hadfield J. RNA sequencing: the teenage years[J]. Nature Reviews Genetics, 2019, 20(11): 631-656
-   Ansorge W J. Next-generation DNA sequencing techniques[J]. New biotechnology, 2009, 25(4): 195-203.
-   Heather J M, Chain B. The sequence of sequencers: The history of sequencing DNA[J]. Genomics, 2016, 107(1): 1-8.
-   Schneider G F, Dekker C. DNA sequencing with nanopores[J]. Nature biotechnology, 2012, 30(4): 326.
-   Restrepo-Pérez L, Joo C, Dekker C. Paving the way to single-molecule protein sequencing[J]. Nature nanotechnology, 2018, 13(9): 786-796.

#### Large research project

-   Cancer Genome Atlas Research, N., et al., *The Cancer Genome Atlas Pan-Cancer analysis project.* Nat Genet, 2013. 45(10): p. 1113-20.
-   International Cancer Genome, C., et al., *International network of cancer genome projects.* Nature, 2010. 464(7291): p. 993-8.
-   Consortium, G.T., *The Genotype-Tissue Expression (GTEx) project.* Nat Genet, 2013. 45(6): p. 580-5.
-   G.P., *Enhancing GTEx by bridging the gaps between genotype, gene expression, and disease.* Nat Genet, 2017. 49(12): p. 1664-1670.
-   Consortium, G.T., et al., *Genetic effects on gene expression across human tissues.* Nature, 2017. 550(7675): p. 204-213.

#### Precision medicine

-   Byron, S.A., et al., *Translating RNA sequencing into clinical diagnostics: opportunities and challenges.* Nat Rev Genet, 2016. 17(5): p. 257-71.
-   Price, N.D., et al., *A wellness study of 108 individuals using personal, dense, dynamic data clouds.* Nat Biotechnol, 2017. 35(8): p. 747-756.
-   Kumar-Sinha, C. and A.M. Chinnaiyan, *Precision oncology in the age of integrative genomics.* Nat Biotechnol, 2018. 36(1): p. 46-60.
-   Torkamani, A., N.E. Wineinger, and E.J. Topol, *The personal and clinical utility of polygenic risk scores.* Nat Rev Genet, 2018.
-   Berdasco, M. and M. Esteller, *Clinical epigenetics: seizing opportunities for translation.* Nat Rev Genet, 2018.

#### Tumor biology

-   Stratton, M.R., P.J. Campbell, and P.A. Futreal, *The cancer genome.* Nature, 2009. 458(7239): p. 719-24.
-   Sanchez-Vega, F., et al., *Oncogenic Signaling Pathways in The Cancer Genome Atlas.* Cell, 2018. 173(2): p. 321-337 e10.
-   Huang, K.L., et al., *Pathogenic Germline Variants in 10,389 Adult Cancers.* Cell, 2018. 173(2): p. 355-370 e14.
-   Kahles, A., et al., *Comprehensive Analysis of Alternative Splicing Across Tumors from 8,705 Patients.* Cancer Cell, 2018.
-   Castro-Giner, F., P. Ratcliffe, and I. Tomlinson, *The mini-driver model of polygenic cancer evolution.* Nat Rev Cancer, 2015. 15(11): p. 680-5.
-   Salk, J.J., M.W. Schmitt, and L.A. Loeb, *Enhancing the accuracy of next-generation sequencing for detecting rare and subclonal mutations.* Nat Rev Genet, 2018.
-   Winters, I.P., C.W. Murray, and M.M. Winslow, *Towards quantitative and multiplexed in vivo functional cancer genomics.* Nat Rev Genet, 2018. 19(12): p. 741-755.
-   Pesavento, P.A., et al., *Cancer in wildlife: patterns of emergence.* Nat Rev Cancer, 2018.
-   Maman, S. and I.P. Witz, *A history of exploring cancer in context.* Nat Rev Cancer, 2018. 18(6): p. 359-376.
-   Hamidi, H. and J. Ivaska, *Every step of the way: integrins in cancer progression and metastasis.* Nat Rev Cancer, 2018.
-   Archetti, M. and K.J. Pienta, *Cooperation among cancer cells: applying game theory to cancer.* Nat Rev Cancer, 2018.

#### Bioinformatics databases and tools

-   Ding, L., et al., *Expanding the computational toolbox for mining cancer genomes.* Nat Rev Genet, 2014. 15(8): p. 556-70.
-   Cheng, F., J. Zhao, and Z. Zhao, *Advances in computational approaches for prioritizing driver mutations and significantly mutated genes in cancer genomes.* Brief Bioinform, 2016. 17(4): p. 642-56.
-   Zhang, Z., et al., *A survey and evaluation of Web-based tools/databases for variant analysis of TCGA data.* Brief Bioinform, 2018.
-   Casper J, Zweig A S, Villarreal C, et al. The UCSC genome browser database: 2018 update[J]. Nucleic acids research, 2017, 46(D1): D762-D769.
-   Afgan, E., et al., *The Galaxy platform for accessible, reproducible and collaborative biomedical analyses: 2018 update.* Nucleic Acids Res, 2018. 46(W1): p. W537-W544.
-   Sondka, Z., et al., *The COSMIC Cancer Gene Census: describing genetic dysfunction across all human cancers.* Nat Rev Cancer, 2018. 18(11): p. 696-705.

#### Application of machine learning on bioinformatics

-   Zou, J., et al., *A primer on deep learning in genomics.* Nat Genet, 2019. 51(1): p. 12-18.
-   Eraslan, G., et al., *Deep learning: new computational modelling techniques for genomics.* Nat Rev Genet, 2019.
-   Wainberg, M., et al., *Deep learning in biomedicine.* Nat Biotechnol, 2018. 36(9): p. 829-838.
-   Ching, T., et al., *Opportunities and obstacles for deep learning in biology and medicine.* J R Soc Interface, 2018. 15(141).
-   Min, S., B. Lee, and S. Yoon, *Deep learning in bioinformatics.* Brief Bioinform, 2017. 18(5): p. 851-869.
-   Jones, W., et al., *Computational biology: deep learning.* Emerging Topics in Life Sciences, 2017. 1(3): p. 257-274.
-   Angermueller, C., et al., *Deep learning for computational biology.* Mol Syst Biol, 2016. 12(7): p. 878.
-   Zhou, J., et al., *Deep learning sequence-based ab initio prediction of variant effects on expression and disease risk.* Nat Genet, 2018. 50(8): p. 1171-1179.
-   Sundaram, L., et al., *Predicting the clinical impact of human mutation with deep neural networks.* Nat Genet, 2018.
-   Libbrecht, M.W. and W.S. Noble, *Machine learning applications in genetics and genomics.* Nat Rev Genet, 2015. 16(6): p. 321-32.
-   Camacho, D.M., et al., *Next-Generation Machine Learning for Biological Networks.* Cell, 2018. 173(7): p. 1581-1592.

#### Whole-genome sequencing

-   Kosugi, Shunichi, et al. "Comprehensive evaluation of structural variation detection algorithms for whole genome sequencing."*Genome biology*20.1 (2019): 117. 

#### Single cell sequencing

-   Kiselev, V.Y., T.S. Andrews, and M. Hemberg, *Challenges in unsupervised clustering of single-cell RNA-seq data.* Nat Rev Genet, 2019. 20(5): p. 273-282.
-   McInnes, L., J. Healy, and J. Melville *UMAP: Uniform Manifold Approximation and Projection for Dimension Reduction*. arXiv e-prints, 2018.
-   Maaten, L.v.d.a.H., Geoffrey, *Visualizing Data using t-SNE.* Journal of Machine Learning Research, 2008. 9: p. 2579--2605.
-   Lake, B.B., et al., *Integrative single-cell analysis of transcriptional and epigenetic states in the human adult brain.* Nat Biotechnol, 2018. 36(1): p. 70-80.
-   Cusanovich, D.A., et al., *A Single-Cell Atlas of In Vivo Mammalian Chromatin Accessibility.* Cell, 2018. 174(5): p. 1309-1324 e18.
-   Haghverdi, L., et al., *Batch effects in single-cell RNA-sequencing data are corrected by matching mutual nearest neighbors.* Nat Biotechnol, 2018.
-   Raj, B., et al., *Simultaneous single-cell profiling of lineages and cell types in the vertebrate brain.* Nat Biotechnol, 2018. 36(5): p. 442-450.
-   Edsgard, D., P. Johnsson, and R. Sandberg, *Identification of spatial expression trends in single-cell gene expression data.* Nat Methods, 2018. 15(5): p. 339-342.

#### Non-coding region and synonymous mutation 

-   Fredriksson, N.J., et al., *Systematic analysis of noncoding somatic mutations and gene expression alterations across 14 tumor types.* Nat Genet, 2014. 46(12): p. 1258-63.
-   Weinhold, N., et al., *Genome-wide analysis of noncoding regulatory mutations in cancer.* Nat Genet, 2014. 46(11): p. 1160-5.
-   Uszczynska-Ratajczak, B., et al., *Towards a complete map of the human long non-coding RNA transcriptome.* Nat Rev Genet, 2018.
-   Chamary J V, Parmley J L, Hurst L D. Hearing silence: non-neutral evolution at synonymous sites in mammals[J]. Nature Reviews Genetics, 2006, 7(2): 98.
-   Sauna Z E, Kimchi-Sarfaty C. Understanding the contribution of synonymous mutations to human disease[J]. Nature Reviews Genetics, 2011, 12(10): 683.
-   Supek F, Miñana B, Valcárcel J, et al. Synonymous mutations frequently act as driver mutations in human cancers[J]. Cell, 2014, 156(6): 1324-1335.
-   Sharma, Y., et al., *A pan-cancer analysis of synonymous mutations.* Nat Commun, 2019. 10(1): p. 2569.

#### Pan-genome

-   Li, R., et al., *Building the sequence map of the human pan-genome.* Nat Biotechnol, 2010. 28(1): p. 57-63.
-   Duan Z, Qiao Y, Lu J, et al. HUPAN: a pan-genome analysis pipeline for human genomes[J]. Genome biology, 2019, 20(1): 149.

#### 3D genome

-   Spielmann, M., D.G. Lupianez, and S. Mundlos, *Structural variation in the 3D genome.* Nat Rev Genet, 2018. 19(7): p. 453-467.

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

## Organization

### Google Summer of Code Registered

- [Open Bioinformatics Foundation](https://summerofcode.withgoogle.com/organizations/5857327278718976/): Promoting practice & philosophy of OSS & Open Science in biological research.
- [National Resource for Network Biology (NRNB)](https://summerofcode.withgoogle.com/organizations/6020714008674304/): The National Resource for Network Biology (NRNB) organizes the development of free, open source software to enable network-based visualization, analysis, and biomedical discovery.
- [INCF](https://summerofcode.withgoogle.com/organizations/5984693862793216/): INCF advances data reuse and reproducibility in brain research by coordinating the development of Open, FAIR, and Citable tools and resources for neuroscience.
- [Computational Biology @ University of Nebraska-Lincoln](https://summerofcode.withgoogle.com/organizations/6229192392310784/): Our organization develops tools for bioinformatics and computational biology research. Our goal is to further knowledge in health through data visualization and analysis.
- [Biomedical Informatics, Emory University](https://summerofcode.withgoogle.com/organizations/6338471594033152/): Big Data for Healthcare and Biomedical Research
- [Ensembl](https://summerofcode.withgoogle.com/organizations/6339185571528704/): The Ensembl project maintains and updates databases that annotate a wide number of genome sequences and distributes them freely to the worldwide research community.
- [R project for statistical computing](https://summerofcode.withgoogle.com/organizations/4934391420157952/): R provides a wide variety of statistical and graphical techniques, and is highly extensible. R is often the tool of choice for research in statistical methodology.
- [InterMine](https://summerofcode.withgoogle.com/organizations/5071439196061696/): InterMine integrates biological data sources and makes it easy to query, visualise, and analyse the data via a graphical user interface or via APIs in Python, R, Perl, and more.
- [NumFOCUS](https://summerofcode.withgoogle.com/organizations/5447807656263680/): NumFOCUS supports and promotes world-class, innovative, open source scientific software.
- [PEcAn Project](https://summerofcode.withgoogle.com/organizations/5925364795179008/): PEcAn is an integrated ecoinformatics toolbox that consists of a set of scientific workflows that wrap around ecosystem models and manage flow of information in and out of models

### Project-based community

- [galaxyproject](https://galaxyproject.orrg): Galaxy is an open, web-based platform for accessible, reproducible, and transparent computational biomedical research.
- [bioconda](https://bioconda.github.io/): A channel for the conda package manager specializing in bioinformatics software.
- [biopython](https://github.com/biopython/biopython): An international association of developers of freely available Python tools for computational molecular biology.
- [samtools](https://github.com/samtools/samtools): Tools (written in C using htslib) for manipulating next-generation sequencing data.
- [opengene](https://github.com/OpenGene): Open source tools for NGS data analysis.
- [MultiQC](https://github.com/ewels/MultiQC): Aggregate results from bioinformatics analyses across many samples into a single report.
- [Gatk](https://github.com/broadinstitute/gatk): GATK4 aims to bring together well-established tools from the GATK and Picard codebases under a streamlined framework, and to enable selected tools to be run in a massively parallel way on local clusters or in the cloud using Apache Spark. It also contains many newly developed tools not present in earlier releases of the toolkit.
- [nextflow](https://github.com/nextflow-io/nextflow): A bioinformatics workflow manager that enables the development of portable and reproducible workflows.
- [spack](https://github.com/spack/spack): A flexible package manager that supports multiple versions, configurations, platforms, and compilers.
- [omicX](https://omictools.com/): Reap the rewards of a biological insight engine.

### Communication-based community

- [Biotrainee](https://vip.biotrainee.com/): Chinese Community in Bioinformatics
- [bioinformatics.org](http://www.bioinformatics.org/): Bioinformatics community open to all people.
- [Zhihu | Bioinformatics](https://www.zhihu.com/topic/19592675/hot): Chinese Q&A Community.
- [muchong](http://muchong.com/bbs/): Chinese BBS for scientific research.

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
- [Ira M. Hall](http://genome.wustl.edu/people/individual/ira-hall/)

## Blog

- [Jianfeng Li's blog](https://life2cloud.com/)
- [RNA-seq Blog](https://www.rna-seqblog.com/)
- [Jianming Zeng's blog](http://www.bio-info-trainee.com/)
- [Yihui Xie's blog](https://yihui.name/)
- [Fei Zhao's blog](https://kaopubear.top/)
- [Mengyuan Shen's blog](http://shemy.site/)
- [Boqiang Hu's blog](http://huboqiang.cn/)
- [Bob's Blog](https://www.tanboyu.com/)
- [Homolog.us - Frontier in Bioinformatics](http://www.homolog.us/blogs/)
- [r-bloggers](https://www.r-bloggers.com/)
- [DataTau](http://www.datatau.com/)
- [Bits of DNA, Lior Pachter](https://liorpachter.wordpress.com/)
- [Next Generation Technologist](http://www.yuzuki.org/)
- [Simply Statistics](https://simplystatistics.org/)
- [Massgenomics](http://massgenomics.org/)
- [OpenHelix](http://blog.openhelix.com/)
- [QIAGEN](https://www.qiagenbioinformatics.com/blog/)
- [Loman Labs Blog](http://lab.loman.net/)
- [Living in an Ivory Basement Stochastic thoughts on science, testing, and programming](http://ivory.idyll.org/blog/)
- [Neil Saunders](https://nsaunders.wordpress.com/blog/)
- [Mike Love’s blog](https://mikelove.wordpress.com/)
- [Ewan Birney](https://ewanbirney.wordpress.com/)
- [In between lines of code](https://flxlexblog.wordpress.com/)
- [Heng Li's blog](http://lh3.github.io/)
- [MacArthur Lab](https://macarthurlab.org/blog/)
- [Blue Collar Bioinformatics](https://bcbio.wordpress.com/)
- [Simpson Lab](http://simpsonlab.github.io/blog/)
- [Bits of Bioinformatics](https://pmelsted.wordpress.com/)
- [Shixiang Wang's blog](https://shixiangwang.github.io/home/)

### Contributors

- [Jianfeng Li](https://github.com/Miachol)
- [Bowen Cui](https://github.com/xcpanda)
- [Shixiang Wang](https://github.com/ShixiangWang)
- [l0o0](https://github.com/l0o0)
