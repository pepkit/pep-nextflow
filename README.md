### Note: This repository has been archived and consolidated into: https://github.com/pepkit/pep-pipelines/

This repository aims to show users how to run `nf-core` pipeline with PEP as input, using [taxprofiler](https://nf-co.re/taxprofiler) pipeline as an example.

The command would look something like that:
```
nextflow run main.nf -profile test_pep,docker --outdir <output_directory>
```
