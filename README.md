# bioinformatics-python

This repo contains exercises for the CSHL 2024 Seqtec course

## Accessing the exercises

Clone the repo. Then, create a virtual environment using the following steps:

```shell
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

Please place the VCF file (`Exome_Norm_HC_calls.filtered.vcf.gz`) in the `data` directory

## Installing `pyenv`

Run the following commands to install pysam:

```shell
sudo apt update; sudo apt install build-essential libssl-dev zlib1g-dev \
libbz2-dev libreadline-dev libsqlite3-dev curl git \
libncursesw5-dev xz-utils tk-dev libxml2-dev libxmlsec1-dev libffi-dev liblzma-dev
```
