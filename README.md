# Characterization of a Plastid Genome – Vitis vinifera

Student: JASMIN GRACE T. BULLANDAY  
Course: Cell & Molecular Biology  
Date genome retrieved: October 1, 2026  

## Chosen Organism

Genus: Vitis 
Species: Vitis vinifera (grape / grapevine)  
Family: Vitaceae  
NCBI Accession: NC_007957.1  
Source link: https://www.ncbi.nlm.nih.gov/nuccore/NC_007957.1  
Genome size: 160,928 bp  
Topology: Circular  
GC content: 37.40 %

## How the Genome Was Obtained

1. Searched NCBI Nucleotide for “*Vitis vinifera* chloroplast complete genome”.
2. Selected the RefSeq record NC_007957.1.
3. Downloaded both the FASTA sequence and the GenBank annotation.
4. Uploaded the FASTA file to usegalaxy.org.

## Galaxy Analysis

History name: Plastid_Vitis_Bullanday  
Tools used: Fasta Statistics / SeqKit stats  
Results:
  - Number of sequence records: 1
  - Total length: 160,928 bp
  - GC content: 37.40 %

## Plastid Genome Organization

The Vitis vinifera plastid genome has the classic quadripartite structure:

| Region     | Size (bp)   |
|------------|-------------|
| LSC        | 89,147      |
| SSC        | 19,065      |
| IR (each)  | 26,358      |
| Total      |    160,928 |


## Gene Content Summary

| Category                        | Number |
|---------------------------------|--------|
| Total genes (with IR duplicates)| 131    |
| Unique genes                    | 113    |
| Protein-coding genes            | 85     |
| tRNA genes                      | 37     |
| rRNA genes                      | 8      |

Genes located in the inverted repeat (IR) regions appear in two copies.


## Important Observations

- The genome is a single circular molecule.
- Typical angiosperm plastid gene content is conserved.
- IR regions contain duplicated rRNA and several tRNA and protein-coding genes.
- No major rearrangements or unusual gene losses are reported for this reference genome.


## How Another Student Can Repeat This Analysis

1. Download NC_007957.1 from NCBI (FASTA + GenBank).
2. Upload the FASTA to a personal Galaxy account.
3. Run Fasta Statistics or SeqKit stats.
4. Compare results with the values in this README.


## References

- Jansen et al. (2006). Phylogenetic analyses of *Vitis* based on complete chloroplast genome sequences. *BMC Evolutionary Biology*.  
- NCBI RefSeq: NC_007957.1  
- usegalaxy.org
