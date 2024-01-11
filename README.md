# environment-modules
A collection of my environment modules files

## mamba env
A couple of examples on how to create envs in *mamba* ready for modules:

```bash=
mamba create -c conda-forge -c bioconda -n snakemake_7.13.0 snakemake=7.13.0
mamba create -c bioconda -c conda-forge -n salmon-1.10.2 salmon=1.10.2
mamba create -c bih-cubi -n bcl2fastq2 bcl2fastq2
```
