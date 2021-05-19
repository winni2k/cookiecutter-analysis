{{cookiecutter.project_name}}
####

Author: {{cookiecutter.full_name}}



## Setup

```bash
conda env create
conda activate {{cookiecutter.project_slug}}
```

## Run

```bash
snakemake --use-conda --printshellcmds -j 1
```
