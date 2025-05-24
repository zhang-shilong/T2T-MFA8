# T2T-MFA8

T2T-MFA8, is pronounced T2T-macfallite.

We generated a parthenogenesis cell line, MFA582-1, from a crab-eating macaque, from which we produced 53× PacBio HiFi, 77× ONT, 32× Illumina WGS, and 156× Hi-C data. Then, we constructed a telomere-to-telomere assembly of the crab-eating macaque (T2T-MFA8). All resources are available on this site.

## Resources

### NCBI Genome

- T2T-MFA8v1.1: [GCF\_037993035.2](https://www.ncbi.nlm.nih.gov/datasets/genome/GCF_037993035.2)

### The UCSC Genome Browser

All tracks are available on [the UCSC Genome Browser](https://genome.ucsc.edu/cgi-bin/hgTracks?hubUrl=https://synplotter.sjtu.edu.cn/trackhub/MaoHub/hub.txt&genome=hub_4292128_T2TMACFA_1.0&position=lastDbPos).

### Assembly

- [T2T-MFA8v1.1](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/v1.1/T2T-MFA8v1.1.AXYM.no_mask.fasta.gz): unmasked, 20 autosomes + chrX + chrMT + chrY from MFA0214
- [T2T-MFA8v1.1](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/v1.1/T2T-MFA8v1.1.AXYM.soft.fasta.gz): soft-masked (segmental duplications, tandem repeats and RepeatMasker), 20 autosomes + chrX + chrMT + chrY from MFA0214
- [T2T-MFA8v1.1](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/v1.1/T2T-MFA8v1.1.AXYM.soft.chrY_PAR_hard.fasta.gz): soft-masked T2T-MFA8v1.1 + hard-masked chrY PAR

### Sequencing data

- MFA582-1
  - PacBio WGS: [SRX22719293](https://www.ncbi.nlm.nih.gov/sra/SRX22719293)
  - Oxford Nanopore Technology WGS: [SRX22719294](https://www.ncbi.nlm.nih.gov/sra/SRX22719294)
  - Illumina WGS: [SRX22702646](https://www.ncbi.nlm.nih.gov/sra/SRX22702646)
  - Hi-C: [SRX22702647](https://www.ncbi.nlm.nih.gov/sra/SRX22702647)
- MFA0214
  - PacBio WGS: [SRX22874566](https://www.ncbi.nlm.nih.gov/sra/SRX22874566) and [SRX25542261](https://www.ncbi.nlm.nih.gov/sra/SRX25542261)
  - Oxford Nanopore Technology WGS: [SRX22874568](https://www.ncbi.nlm.nih.gov/sra/SRX22874568)
  - Illumina WGS: [SRX22874666](https://www.ncbi.nlm.nih.gov/sra/SRX22874666) and [SRX25542262](https://www.ncbi.nlm.nih.gov/sra/SRX25542262)

### Gene annotation

- [NCBI RefSeq GCF\_037993035.2-RS\_2025\_03](https://www.ncbi.nlm.nih.gov/datasets/genome/GCF_037993035.2)
- [Curated gene annotation](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/v1.1/T2T-MFA8v1.1.curated_gene_annotation.gtf.gz): LiftOff result from [Mmul\_10](https://www.ncbi.nlm.nih.gov/datasets/genome/GCF_003339765.1/) RefSeq and lso-Seq transcripts annotated by GeneMarkS-T, with manual curation
- [GeneMarkS-T](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/v1.0/T2T-MFA8v1.0.GeneMarkST.gtf.gz): annotated Iso-Seq FLNC transcripts (autosomes + chrX)
- [LiftOff from Mmul\_10 RefSeq](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/v1.1/T2T-MFA8v1.1.liftoff_Mmul_10.polished.gff3.gz)

### Mappability
- [21-mer with no error](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/v1.1/T2T-MFA8v1.1.k21_e0_mappability.bedgraph.gz): produced by [GenMap](https://github.com/cpockrandt/genmap)
- [24-mer with no error](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/v1.1/T2T-MFA8v1.1.k24_e0_mappability.bedgraph.gz): produced by [GenMap](https://github.com/cpockrandt/genmap)

### Repeat annotation

- [Centromere](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/v1.1/T2T-MFA8v1.1.centromere.bed)
- [CenSat](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/v1.1/T2T-MFA8v1.1.CenSat.bed): the 500-kbp extended regions of centromeres
- Segmental duplications: [native bed format](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/v1.1/T2T-MFA8v1.1.SDs.bed.gz) or [merged bed format](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/v1.1/T2T-MFA8v1.1.SDs.merged.bed.gz)
- Tandem repeats: [bed format](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/v1.1/T2T-MFA8v1.1.TRF.bed.gz) or [merged bed format](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/v1.1/T2T-MFA8v1.1.TRF.merged.bed.gz)
- RepeatMasker: [native out format](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/v1.1/T2T-MFA8v1.1.RepeatMasker_Dfam3.6.RepeatModeler.out.gz) or [bed format](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/v1.1/T2T-MFA8v1.1.RepeatMasker_Dfam3.6.RepeatModeler.bed.gz) or [merged bed format](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/v1.1/T2T-MFA8v1.1.RepeatMasker_Dfam3.6.RepeatModeler.merged.bed.gz)
- [WindowMasker (with SDust)](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/v1.1/T2T-MFA8v1.1.WindowMasker_SDust.bed.gz)
- [Centromere suprachromosomal family annotation](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/v1.1/T2T-MFA8v1.1.suprachromosomal_family.bed.gz)
- [rDNA models](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/v1.1/T2T-MFA8v1.1.rDNA.bed)
- chrY annotations
  - [PAR](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/v1.1/T2T-MFA8v1.1.PAR.bed)
  - [Sequence classes](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/v1.1/T2T-MFA8v1.1.chrY_sequence_class.bed)
  - [Palindromes](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/v1.1/T2T-MFA8v1.1.chrY_palindromes.bedpe)
  - [Non-B-DNA](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/v1.1/T2T-MFA8v1.1.chrY_non_B_DNA.bed)

### Epigenetic profile

- [CpG islands](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/v1.1/T2T-MFA8v1.1.CpG_islands.bed.gz)
- CpG methylation from ONT: [autosomes + chrX](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/v1.1/T2T-MFA8v1.1.ONT_methylation.nanopolish_v0.14.0.AX.bed.gz) or [chrY](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/v1.1/T2T-MFA8v1.1.ONT_methylation.nanopolish_v0.14.0.Y.bed.gz), identified by [Nanopolish](https://github.com/jts/nanopolish) v0.14.0

### Non-syntenic regions

- Crab-eating macaque assemblies
  - [macFas6](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/v1.0/T2T-MFA8v1.0.non_syntenic_regions_to_macFas6.bed.gz)
  - [MFA1912RKSv2](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/v1.0/T2T-MFA8v1.0.non_syntenic_regions_to_MFA1912RKSv2.bed.gz)
- Rhesus macaque assemblies
  - [Mmul\_10](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/v1.0/T2T-MFA8v1.0.non_syntenic_regions_to_Mmul_10.bed.gz)
  - [rheMacS](https://synplotter.sjtu.edu.cn/disk2/T2T-MFA8/v1.0/T2T-MFA8v1.0.non_syntenic_regions_to_rheMacS.bed.gz)

## Previous versions

To avoid confusion, previous versions are not displayed on this page, but you can still access them through the links.

## Citation

We would appreciate if you would acknowledge and cite our paper:

Zhang, S., Xu, N., Fu, L. *et al*. Integrated analysis of the complete sequence of a macaque genome. *Nature* (2025). [https://doi.org/10.1038/s41586-025-08596-w](https://doi.org/10.1038/s41586-025-08596-w)

## License

All data is released to the public domain ([CC0](https://creativecommons.org/publicdomain/zero/1.0/)).
