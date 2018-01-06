# Bioinformatics-Resources

**Abstract**: A curated list of resources for learning bioinformatics. Some of this repo resources were collected by [BioInstaller](https://github.com/JhuangLab/BioInstaller/blob/master/inst/extdata/config/db/db_meta.toml) project. You can use [BioInstaller](https://github.com/JhuangLab/BioInstaller) to directly download the source code or database files, or fetch the meta information by `BioInstaller::get.meta()$item`.

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
  - [Sequencing Technology](#sequencing-technology)
  - [Tools](#tools)
  - [Books&Tutorial](#bookstutorial)

- [Skills](#skills)
- [Institute](#institute)
- [People](#people)
- [Contributors](#contributors)

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

##### Clinical Annotation

- [CIViC](https://civic.genome.wustl.edu/home)
- [DoCM](http://docm.genome.wustl.edu/)
- [ClinVar](https://www.ncbi.nlm.nih.gov/clinvar/)
- [Intogen](https://www.intogen.org/downloads)
- [Cancer Hotspots](http://cancerhotspots.org/#/home)
- [DisGeNET](http://www.disgenet.org/web/DisGeNET/menu)
- [Cancer Biomarkers database](https://www.cancergenomeinterpreter.org/biomarkers)

##### Noncoding RNA Related Database

- [CSCD - Cancer-specific circular RNAs database](http://gb.whu.edu.cn/CSCD/)
- [AtCircDB](http://genome.sdau.edu.cn/circRNA/index.php)
- [CircNet](http://circnet.mbc.nctu.edu.tw/)
- [circBase](http://circrna.org/)
- [circRNADb](http://202.195.183.4:8000/circrnadb/circRNADb.php)
- [exoRBase](http://www.exorbase.org/exoRBase/toIndex)
- [EVLncRNAs](http://biophy.dzu.edu.cn/EVLncRNAs.)

##### eQTL Related Database

- [exsnp](http://www.exsnp.org)
- [rVarBase](http://rv.psych.ac.cn)
- [seeQTL](http://www.bios.unc.edu/research/genomic_software/seeQTL/)

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
- [fastp](https://github.com/OpenGene/fastp)

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
- [SVScore](https://github.com/lganel/SVScore)
- [SVTools](https://github.com/hall-lab/svtools)
- [RDDpred](http://epigenomics.snu.ac.kr/RDDpred/)
- [iseq](https://github.com/JhuangLab/iseq)
- [deepvariant](https://github.com/google/deepvariant)
- [SV2](https://github.com/dantaki/SV2)

##### Variant Annotation

- [ANNOVAR](http://annovar.openbioinformatics.org/en/latest/)
- [SnpEff](http://snpeff.sourceforge.net/index.html)
- [gemini](https://github.com/arq5x/gemini)
- [VEP](http://www.ensembl.org/info/docs/tools/vep/index.html)
- [Variant Annotation Integrator](http://genome.ucsc.edu/cgi-bin/hgVai)
- [vcfanno](https://github.com/brentp/vcfanno)
- [pcgr](https://github.com/sigven/pcgr)
- [annovarR](https://github.com/JhuangLab/annovarR)

##### Variant Screen

- [LARVA](http://larva.gersteinlab.org/)
- [DANN](https://cbcl.ics.uci.edu/public_data/DANN)

##### Alternative Splicing

- [LeafCutter](https://github.com/davidaknowles/leafcutter)
- [rMATS](http://rnaseq-mats.sourceforge.net/rmats3.2.5/)

##### Gene Expression Data Analysis

- [Cufflinks](http://cole-trapnell-lab.github.io/cufflinks/)
- [DESeq2](http://www.bioconductor.org/packages/release/bioc/html/DESeq2.html)
- [edgeR](http://www.bioconductor.org/packages/release/bioc/html/edgeR.html)
- [HTSeq](https://github.com/simon-anders/htseq)
- [sRNAnalyzer](http://srnanalyzer.systemsbiology.net/)

##### Virus Related

- [viral-ngs](https://github.com/broadinstitute/viral-ngs)
- [qap](https://github.com/mingjiewang/qap)

##### Single Cell

- [seurat](https://github.com/satijalab/seurat)
- [SCnorm](http://www.biostat.wisc.edu/~kendzior/SCNORM/)

##### Protein Data Related

- [interproscan](http://www.ebi.ac.uk/interpro)

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
- [SAMBLASTER](https://github.com/GregoryFaust/samblaster)
- [ngstk](https://github.com/JhuangLab/ngstk)
- [BioInstaller](https://github.com/JhuangLab/BioInstaller)
- [ChromHMM](https://github.com/jernst98/ChromHMM)

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
- [Ira M. Hall](http://genome.wustl.edu/people/individual/ira-hall/)

### Contributors

- [Jianfeng Li](https://github.com/Miachol)
- [Bowen Cui](https://github.com/xcpanda)
- [Shixiang Wang](https://github.com/ShixiangWang)
- [l0o0](https://github.com/l0o0)
