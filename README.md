# Telomere-to-Telomere diploid Indian Genome 
We have sequenced a EBV-immortalized human male cell line from SG10k samples on different platforms. The data contains ~106x of Pacbio HiFi, ~64x of Oxford Nanopore (ONT) Duplex, ~222x ONT Ultralong (ULONT), ~100x MGI WGS short reads, ~33x Illumina WGS short reads and ~120x Omni-C for the child sample (I002C). Statistics of BioNano will be added soon.

For parental samples:
SampleType | SampleID | HiFi (REVIO) | Duplex | MGI
---|:---:|:---:|:---:|:---:|
Father|I002A|60x|21x|35x
Mother|I002B|61x|20x|37x

The data statistics are provided in an [excel](Data/Reads)

# Assembly release
### v0.2
This version of the assembly contains Telomere-to-Telomere chromsomes for both maternal and paternal haplotypes including a mitochondria. In this version of the genomes, rDNAs have not been resolved. 

 &nbsp;|Maternal|Paternal
---|:---:|:---:
T2T Chromosomes|23|23
Size|3,022,465,370|2,934,829,127
NG50|154,891,367|146,273,588
%GC|40.82|40.79

Assembly files: 
- Maternal: [Fasta](https://figshare.com/ndownloader/files/44506250)
- Paternal: [Fasta](https://figshare.com/ndownloader/files/44506241)
- Mitochondira: [Fasta](https://figshare.com/ndownloader/files/44506232)

Assembly QV is calculated with [yak](https://github.com/lh3/yak) tool using I002C MGI WGS dataset. Per chromosome QV values are provided in an [excel](Data/Assembly) file

**Note:** The data available on this GitHub page can be accessed either from [LHG](https://github.com/LHG-GG/I002C) or [LBCB](https://github.com/lbcb-sci/I002C) GitHub pages
