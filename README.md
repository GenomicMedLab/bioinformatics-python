# bioinformatics-python

This repo contains exercises for the CSHL 2024 Seqtec course

Clone the repo:

```shell
git clone https://github.com/GenomicMedLab/bioinformatics-python.git
```

## Installing `pyenv`

Run the following prerequisite commands in ubuntu:

```shell
sudo apt update; sudo apt install build-essential libssl-dev zlib1g-dev \
libbz2-dev libreadline-dev libsqlite3-dev curl git \
libncursesw5-dev xz-utils tk-dev libxml2-dev libxmlsec1-dev libffi-dev liblzma-dev
```

Once these commands are complete, run:

```shell
curl https://pyenv.run | bash
```

and

```shell
echo 'export PYENV_ROOT="$HOME/.pyenv"' >> ~/.bashrc
echo 'command -v pyenv >/dev/null || export PATH="$PYENV_ROOT/bin:$PATH"' >> ~/.bashrc
echo 'eval "$(pyenv init -)"' >> ~/.bashrc
```

When done, open the `virtual-environments-lab` folder
