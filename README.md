# Bioinformatics-Resources

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

- [Skills](#skills)
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
- [Spack](https://github.com/spack/spack)

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
- [ROP](https://github.com/smangul1/rop): discovering the source of all RNA-seq reads, including those originating from repeat sequences, recombinant B and T cell receptors, and microbial communities
- [ViFi](https://github.com/namphuon/ViFi): Pipeline for identifying viral integration and fusion mRNA reads from NGS data

##### Single Cell

- [seurat](https://github.com/satijalab/seurat)
- [SCnorm](http://www.biostat.wisc.edu/~kendzior/SCNORM/)
- [dropClust](https://github.com/debsin/dropClust)
- [scran](https://bioconductor.org/packages/release/bioc/html/scran.html): batch effect adjust
- [trendsceek](https://github.com/edsgard/trendsceek): spatial expression trends in single-cell gene expression data
- [scRNA-tools](https://www.scrna-tools.org/): a database of software tools for the analysis of single-cell RNA-seq data.
- [awesome-single-cell](https://github.com/seandavi/awesome-single-cell): list of software packages (and the people developing these methods) for single-cell data analysis, including RNA-seq, ATAC-seq, etc.
- [SAVER](https://github.com/mohuangx/SAVER): SAVER (Single-cell Analysis Via Expression Recovery) implements a regularized regression prediction and empirical Bayes method to recover the true gene expression profile in noisy and sparse single-cell RNA-seq data.


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
- [sequana](https://github.com/sequana/sequana)
- [snakemake](https://snakemake.readthedocs.io/en/latest/)
- [WDL](https://github.com/openwdl/wdl)
- [CWL](http://www.commonwl.org/)

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

## Blog

- [Jianfeng Li's blog](https://life2cloud.com/)
- [RNA-seq Blog](https://www.rna-seqblog.com/)
- [Jianming Zeng's blog](http://www.bio-info-trainee.com/)
- [Yihui Xie's blog](https://yihui.name/)
- [Fei Zhao's blog](http://kaopubear.top/)
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

### Contributors

- [Jianfeng Li](https://github.com/Miachol)
- [Bowen Cui](https://github.com/xcpanda)
- [Shixiang Wang](https://github.com/ShixiangWang)
- [l0o0](https://github.com/l0o0)
