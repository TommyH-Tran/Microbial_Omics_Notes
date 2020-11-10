Notes\_Meren\_Omics
================

Here are notes I have taken from a 6 week video series that was provided
by Meren Lab. A link to the videos is provided here:
<https://www.youtube.com/channel/UCVFH6ULygyqqLGfDnmf0G4A>

Tommy Hiller Tran

# 01 A brief introduction to microbial life and ’omics strategies

  - Microbes were the first life forms on earth
      - Microbes sustain the habitable climate of Earth by catalyzing
        chemical reactions within global biogeochemical cycles
      - Microbial life is extremely abundant and diverse
  - For a long time observational morphology of life was used
      - We did not know how far into depth we could go to show true
        diversity at the microbe level
      - Start to learn about microbes from sequencing (comparing their
        sequences), a higher resolution to compare at.
      - To fully understand life you would have to understand microbes,
        microbes are like the owners of this planet.
      - Microbes are able to exploit earth to it’s full potential,
        compared to how humans utilize the earth.
  - Ribosomal RNA in easier, cheaper, and shorter time frame to analyze
    vs. Omics, which can take a long time and be more expensive.
    1.  Environmental sampling and extract DNA or RNA is the same for
        both RNA and Omics analyizes
    2.  However, then apply high throughput sequence strategies to the
        entire genetic material, whether it is DNA or RNA.
    3.  High throughput omics factors in all members of life vs. just
        PCR amplicons (can include viruses and many other factors)

Vocab:

  - Genomics: study of genomes, identify metabolic pathways, look at
    sequence composition or other properties of genomes.
  - Metagenomics: entire DNA content of a given environment, includes
    many many genomes and they are all in a mixture.
  - Single cell genomics:
  - Pangenomics: to what extent are genomes similar to each other, how
    do the genomes compare to each other? Used when genomes are closely
    related.
  - Phylogeneomics: understanding genomes that are distinct from each
    other vs. pangenomics.
  - Metapangenomics: understanding how these genomes relate to one
    another, to their ecology through a metagenomic prespective in a
    systematic fashion.

Roland speaker:

  - Each method has it’s strong points and flaws, need to combine them.

  - Problem in a field that we do not know what many proteins encode
    for.

  - Low abundance does not mean it is low importance

  - Presence of a gene does not mean it is expressed

-----

# 02 The Power Of Metagenomic Read Recruitment

Amplicon Sequencing: you have an environment, and use universal primers
to land on 16s highly preserved sites sites. It allows you to amplify
the sites and then sequence them to learn about their differences.
(there are many questions that cannot be answered from this method) +
very affordable + sustained protocol

Shotgun Sequencing: extract DNA from an environment, will include reads
that are more than just the primers. Will also get reads from eukaroytic
DNA if it is present. Viruses will also be included and plasmids. Takes
all reads into account. They called metagenomic short reads. + Takes all
reads and small things of an environment that are ignored by primers in
16s. + Small things matter, (viruses, plasmids)

Read recruitment: takes metagenomic short reads from shotgun sequencing
and tries to map the short reads against a reference genome from a
database. You do not need to characterize short reads before mapping
them. (Uses the terms detection and coverage)

Genome Resolved Metagenomics: uses shotgun sequencing to get metagnomic
short reads and map against reference genomes.

Vocabulary: \* Plasmids: tiny genomes microbes can exchange \*
Prevalence: is the gene present? \* Amplicons: small fragments that
allow you to identify organisms \* Coverage: how much short reads total
does it match to reference context for that environment. 8x , 4x etc.
The depth. \* Detection: how much of the full reference context genome
is detected in the given environment. \* De novo assembly: taking
metagenomic short reads and overlapping them to create a bigger contigs.
\* Metagenomic Binning: the process of using contigs assembled from
metagenomic short reads and creating Metagenome assembled genomes \*
MAGS: metagenomic assembled genomes from contigs \* Metagenomic short
reads: use these for mapping against reference genomes, short reads can
be obtained from shotgun sequencing

Questions from others:

  - Prevalence answers the question “is X in this metagenome?”.
    Abundance answers the question “are there more X in this sample than
    Y?”.
  - Reference sequence can be anything\! In next week’s seminar, for
    instance, our reference sequences will be thousands of assembled
    contigs for read recruitment :)
  - n cases when the biomass is extremely low, strategies such as
    multiple displacement amplification (MDA,
    <https://en.wikipedia.org/wiki/Multiple_displacement_amplification>
    ) can be used in metagenomic settings (these are random primers to
    amplify DNA without a target). But typically shotgun sequencing does
    not rely on primers.

-----

# 03 Reconstructing Genomes from Metagenomes

k mer \# = takes the number of nucleotides and creates a matrix of it.
This is how you are able to identify the origination of contigs to a
species if you do not know who they belong to. *The longer the sequence
of contigs the better for k-mer analysis it is 1000 or more nucleotides
sequences is preferred *Tertranucleotide matrix is generally used in the
field today k mer = 4

# 04 Pangenomics