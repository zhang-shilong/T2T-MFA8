# T2T-MFA8

We generated a parthenogenesis cell line, MFA582-1, from a crab-eating macaque, from which we produced 53× PacBio HiFi, 77× ONT, 32× Illumina WGS, and 156× Hi-C data. Then, we constructed a telomere-to-telomere assembly of the crab-eating macaque. All resources are available on this site.

## Resources

### The UCSC Genome Browser

All tracks are available in [the UCSC Genome Browser](https://genome.ucsc.edu/cgi-bin/hgTracks?hubUrl=https://synplotter.sjtu.edu.cn/trackhub/MaoHub/hub.txt).

### Assembly

- T2T-MFA8v1.0: unmasked, 20 autosomes + chrX + chrMt
- T2T-MFA8v1.0: soft-masked, 20 autosomes + chrX + chrMt

### Sequencing data

- PacBio HiFi: [SRX22719293](https://www.ncbi.nlm.nih.gov/sra/SRX22719293)
- Oxford Nanopore Technology: [SRX22719294](https://www.ncbi.nlm.nih.gov/sra/SRX22719294)
- Illumina WGS: [SRX22702646](https://www.ncbi.nlm.nih.gov/sra/SRX22702646)
- Hi-C: [SRX22702647](https://www.ncbi.nlm.nih.gov/sra/SRX22702647)

### Gene annotation

- Curated gene annotation: LiftOff from [Mmul_10](https://www.ncbi.nlm.nih.gov/datasets/genome/GCF_003339765.1/) RefSeq + GeneMarkS-T, with manual curation
- GeneMarkS-T: The *de novo* prediction from Iso-seq data with GeneMarkS-T
- LiftOff from [Mmul_10](https://www.ncbi.nlm.nih.gov/datasets/genome/GCF_003339765.1/) RefSeq
- LiftOff from [MFA1912RKSv2](https://www.ncbi.nlm.nih.gov/datasets/genome/GCF_012559485.2/) RefSeq

### Mappability
- 24-mer with no error: produced by [GenMap](https://github.com/cpockrandt/genmap)

### Repeat annotation

- Centromere
- CenSat: the 500-kbp extended regions of centromeres
- Segmental duplications: native bed format or merged bed format
- Tandem repeats: native out format or bed format
- RepeatMasker:  native out format or bed format
- WindowMasker (with SDust)
- Centromere suprachromosomal family annotation
  - humSF
  - owmSF
  - owmSF strand
- rDNA models

### Epigenetic profile

- CpG islands
- CpG methylation from ONT: identified by [Nanopolish](https://github.com/jts/nanopolish) v0.14.0

### Non-syntenic regions

- Human assemblies
  - T2T-CHM13v2.0
  - GRCh38
- Crab-eating macaque assemblies
  - macFas6
  - macFas5
  - MFA1912RKSv2
- Rhesus macaque assemblies
  - Mmul_10
  - rheMacS

## Citation

We would appreciate if you would acknowledge and cite our paper:

comming soon

## License

All data is released to the public domain ([Unlicense](https://unlicense.org/)).
