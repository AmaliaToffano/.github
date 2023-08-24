![](https://github.com/3d-omics/.github/blob/b345f29044584474a23b5bd5a58a8eda5a1f23ad/profile/3domics-logo.png
)

## Welcome to the 3D'omics code hub

The **3D'omics code hub** is the common space to develop, share and discuss about bioinformatic and statistical code used in 3D'omics. It contains multiple repositories dedicated to specific data processing and analysis steps. 3D'omics deals with two main types of omic data, conventional data generated at the macroscopic level (from faecal samples, gut contents, mucosal scrapes, etc.), and data generated at the micro-scale from intestinal microdissections. The multiple repositories stored in this hub are organised accordingly:

### Bioinformatics
Bioinformatics repositories are snakemake-based pipelines converting raw sequencing files into datasets ready for downstream statistical analyses and visualisations.
If you don't have snakemake installed, you can do it on your terminal through miniconda, using the following lines of code


  ```
  # Download the installer script (linux)
  wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
  # Make the script executable
  chmod +x Miniconda3-latest-Linux-x86_64.sh
  # Run the installer script
  ./Miniconda3-latest-Linux-x86_64.sh
  # Create a conda environment for Snakemake, you can substitute 'snakemake' with the name you want to assign to the environment
  conda create -n snakemake
  # Activate the environment
  conda activate snakemake
  # Install snakemake
  pip install snakemake==7.28.3
  # Deactivate environment once you are done using snakemake
  conda deactivate
```

![image](https://github.com/3d-omics/.github/assets/103645443/84280f4f-d381-467b-8094-28fb730476ef)


#### Macro-scale multi-omics

* [Host genomics](https://github.com/3d-omics/Bioinfo_Macro_Host_Genomics)
* [Host transcriptomics](https://github.com/3d-omics/Bioinfo_Macro_Host_Transcriptomics)
* [Microbial genome-resolved metagenomics](https://github.com/3d-omics/Bioinfo_Macro_Genome_Resolved_Metagenomics)
* [Microbial metatranscriptomics](https://github.com/3d-omics/Bioinfo_Macro_Microbial_Metatranscriptomics)

#### Micro-scale multi-omics
These repositories are under development.

* Microbial metagenomics
* Microbial metatranscriptomics

### Statistics
Statistics repositories principally contain RMarkdown documents with useful scripts for analysing both macro- and micro-scale multi-omic data.

#### Macro-scale multi-omics
These repositories are under development.

#### Micro-scale multi-omics
These repositories are under development.

## Reference genomes

In 3D'omics we are analysing host genomic and microbial metagenomic data of various animals and their associated microbial communities. Many of the pipelines included in this code hub require the usage of reference animal genomes, for removing host reads, for mapping against protein-coding genes, etc. The reference genomes selected for 3D'omics analyses are the following:

### Swine (Sus scrofa)

* **Reference assembly**: https://www.ncbi.nlm.nih.gov/genome/84?genome_assembly_id=317145
* **Sequence**: https://ftp.ncbi.nlm.nih.gov/genomes/all/GCF/000/003/025/GCF_000003025.6_Sscrofa11.1/GCF_000003025.6_Sscrofa11.1_genomic.fna.gz
* **Annotations**: https://ftp.ncbi.nlm.nih.gov/genomes/all/GCF/000/003/025/GCF_000003025.6_Sscrofa11.1/GCF_000003025.6_Sscrofa11.1_genomic.gff.gz

## What is 3D'omics?

3D'omics is a H2020 project that aims to reconstruct host-microbiota interactions in 3D at the micro-scale through a novel technology. Using poultry and swine production systems, we are analysing the effects of different factors, including animal development, diet, exposure to pathogens, and management practices on the so-called 3D omics landscapes of animal intestines. Further information about the project can be found in the [project website](https://www.3domics.eu/).

## Why cannot I access some repositories?

3D'omics is an ongoing project, and as such, many of the code chunks and pipelines stored in this hub are under development. For that reason, some of the repositories are only accessible for project members. When those repositories contain consolidated contents, we will make them public so that other researchers can also implement the procedures in their research.

```
This project has received funding from the European Union’s Horizon 2020 Research and Innovation programme under grant agreement number No. 101000309
```
