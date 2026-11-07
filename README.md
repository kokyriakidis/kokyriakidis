### Konstantinos Kyriakidis

Computational genomics software engineer at **UC Santa Cruz** (labs of Benedict Paten and Karen Miga), working in the
**Human Pangenome Reference Consortium**. I build fast, accurate software for **genome assembly**, **pangenome graphs** and **long-read
variant calling**, in C++, Python and Mojo.

#### Selected projects

- **pgphase**: pangenome graph-aware variant calling and phasing for long
  reads. On HG002 PacBio HiFi: 55% fewer small-variant errors than DeepVariant, and 99.08% of reads phased correctly
  against 94.41% for HiPhase.
- **[Shasta](https://github.com/paoloshasta/shasta)**: core developer of the de novo assembler for Oxford Nanopore
  reads behind NIH CARD's Napu pipeline.
- **sporos**: library for the seeds that mappers and aligners start from (minimizers, syncmers, MEMs, MUMs,
  SMEMs). SMEMs 4.8× faster than minibwa; MEMs and MUMs 4.2–43× faster than MUMmer4, with identical output.
- **plegma**: fast partial-order multiple sequence alignment. In Shasta2's local
  assemblies it leaves 40% fewer consensus errors than abPOA, and in pgphase it makes 7× fewer false heterozygous calls.
- **karan**: exact pairwise sequence alignment for the CPU and the GPU,
  1.3–7× faster than the next fastest exact aligner on real reads.
- **dromos**: reads vg pangenome graph alignments at disk speed.
- **periodos**: tandem repeat discovery. It scans human chr1 in about 18 s and, on HG002, recovers 99.9% of
  TRF's loci and 100% of GIAB's perfect short tandem repeats.

#### Contact

[LinkedIn](https://www.linkedin.com/in/kokyriakidis/) ·
[Google Scholar](https://scholar.google.com/citations?user=0W9NP_EAAAAJ) ·
[kokyriakidis@gmail.com](mailto:kokyriakidis@gmail.com)
