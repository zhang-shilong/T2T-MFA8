# T2T-MFA8

T2T-MFA8, is pronounced T2T-macfallite.

We generated a parthenogenesis cell line, MFA582-1, from a crab-eating macaque, from which we produced 53× PacBio HiFi, 77× ONT, 32× Illumina WGS, and 156× Hi-C data. Then, we constructed a telomere-to-telomere assembly of the crab-eating macaque (T2T-MFA8). All resources are available on this site.

## Resources

### The UCSC Genome Browser

All tracks are available on [the UCSC Genome Browser](https://genome.ucsc.edu/cgi-bin/hgTracks?hubUrl=https://synplotter.sjtu.edu.cn/trackhub/MaoHub/hub.txt&genome=hub_4292128_T2TMACFA_1.0&position=lastDbPos).

### Assembly

- [T2T-MFA8v1.0](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/T2T-MFA8v1.0.fasta.gz): unmasked, 20 autosomes + chrX + chrMT
- [T2T-MFA8v1.0](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/T2T-MFA8v1.0.soft_masked.fasta.gz): soft-masked (segmental duplications, tandem repeats and RepeatMasker), 20 autosomes + chrX + chrMT

### Sequencing data

- PacBio HiFi: [SRX22719293](https://www.ncbi.nlm.nih.gov/sra/SRX22719293)
- Oxford Nanopore Technology: [SRX22719294](https://www.ncbi.nlm.nih.gov/sra/SRX22719294)
- Illumina WGS: [SRX22702646](https://www.ncbi.nlm.nih.gov/sra/SRX22702646)
- Hi-C: [SRX22702647](https://www.ncbi.nlm.nih.gov/sra/SRX22702647)

### Gene annotation

- [Curated gene annotation](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/T2T-MFA8v1.0.curated_gene_annotation.gtf.gz): LiftOff result from [Mmul _10](https://www.ncbi.nlm.nih.gov/datasets/genome/GCF_003339765.1/) RefSeq and lso-Seq transcripts annotated by GeneMarkS-T, with manual curation
- [GeneMarkS-T](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/T2T-MFA8v1.0.GeneMarkST.gtf.gz): annotated Iso-Seq FLNC transcripts
- [LiftOff from Mmul_10 RefSeq](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/T2T-MFA8v1.0.liftoff_Mmul_10.polished.gff3.gz)
- [LiftOff from MFA1912RKSv2 RefSeq](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/T2T-MFA8v1.0.liftoff_MFA1912RKSv2.polished.gff3.gz)

### Mappability
- [24-mer with no error](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/T2T-MFA8v1.0.genmap_24_0.bed.gz): produced by [GenMap](https://github.com/cpockrandt/genmap)
- [36-mer with no error](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/T2T-MFA8v1.0.genmap_36_0.bed.gz): produced by [GenMap](https://github.com/cpockrandt/genmap)

### Repeat annotation

- [Centromere](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/T2T-MFA8v1.0.centromere.bed)
- [CenSat](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/T2T-MFA8v1.0.CenSat.bed): the 500-kbp extended regions of centromeres
- Segmental duplications: [native bed format](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/T2T-MFA8v1.0.SD.native.bed.gz) or [merged bed format](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/T2T-MFA8v1.0.SD.merged.bed.gz)
- [Tandem repeats](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/T2T-MFA8v1.0.TRF.bed.gz)
- RepeatMasker:  [native out format](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/T2T-MFA8v1.0.RepeatMasker.out.gz) or [bed format](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/T2T-MFA8v1.0.RepeatMasker.bed.gz)
- [WindowMasker (with SDust)](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/T2T-MFA8v1.0.WindowMasker.bed.gz)
- Centromere suprachromosomal family annotation
  - [humSF](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/T2T-MFA8v1.0.humSF.bed.gz)
  - [owmSF](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/T2T-MFA8v1.0.owmSF.bed.gz)
  - [owmSF strand](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/T2T-MFA8v1.0.owmSF_strand.bed.gz)
- [rDNA models](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/T2T-MFA8v1.0.rDNA.bed)

### Epigenetic profile

- [CpG islands](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/T2T-MFA8v1.0.CpG_islands.bed.gz)
- [CpG methylation from ONT](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/T2T-MFA8v1.0.ONT_methylation.bed.gz): identified by [Nanopolish](https://github.com/jts/nanopolish) v0.14.0

### Non-syntenic regions

- Crab-eating macaque assemblies
  - [macFas6](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/T2T-MFA8v1.0.non_syntenic_regions_to_macFas6.bed.gz)
  - [MFA1912RKSv2](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/T2T-MFA8v1.0.non_syntenic_regions_to_MFA1912RKSv2.bed.gz)
- Rhesus macaque assemblies
  - [Mmul_10](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/T2T-MFA8v1.0.non_syntenic_regions_to_Mmul_10.bed.gz)
  - [rheMacS](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/T2T-MFA8v1.0.non_syntenic_regions_to_rheMacS.bed.gz)

## Citation

We would appreciate if you would acknowledge and cite our paper:

Zhang, S. *et al*. [Comparative genomics of macaques and integrated insights into genetic variation and population history](https://doi.org/10.1101/2024.04.07.588379). *bioRxiv* (2024).

## License

All data is released to the public domain ([CC0](https://creativecommons.org/publicdomain/zero/1.0/)).
