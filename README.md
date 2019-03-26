# single cell pipeline example
This repo is an educational reminder on how to start snakemake pipelines for single cell RNA-Seq projects.

It basically casts the boilerplate, or weaves the bamboo steamer, whichever metaphor you prefer.

## Testing pipeline
```bash
cd scpipe/pipeline
snakemake --cluster 'sbatch' --jobs 1
```
