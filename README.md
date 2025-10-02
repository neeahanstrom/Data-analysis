# Diet composition and environmental niche drive parasitic Syndiniales interactions with crustacean zooplankton

This repository includes the datasets and the code to reproduce the analysis and the figures for the scientific research paper "Diet composition and environmental niche drive parasitic Syndiniales interactions with crustacean zooplankton".

The code provided is in an RMarkdown format and is annotated throughout for each step. The input data files are RDS files to match the code provided.
The Environmental data includes the variables measured at the same location and time as the zooplankton samples were collected from. 

The datasets contain annotated DNA sequences of zooplankton and water samples. The dataframe has the following columns:

**OTU**: DNA sequence identified by Illumina sequencing and DADA2.
**Sample**: Unique zooplankton or water sample ID
**SORTED_genus**: Microscopically identified genus of pooled zooplankton individuals. Alternatively Water for water samples.
**SAMPLE_date**: Date of environmental sampling.
**Domain**: Assigned clade of OTU sequence in the PR2 database.
**Supergroup**: Assigned clade of OTU sequence in the PR2 database.
**Phylum**: Assigned clade of OTU sequence in the PR2 database.
**Class**: Assigned clade of OTU sequence in the PR2 database.
**Order**: Assigned clade of OTU sequence in the PR2 database.
**Family**: Assigned clade of OTU sequence in the PR2 database.
**Genus**: Assigned clade of OTU sequence in the PR2 database.
**Species**: Assigned clade of OTU sequence in the PR2 database.
**STATION_ID**: Id of sampling location
**Abundance**: Relative read abundance of OTU, relative to all OTUs per Sample
