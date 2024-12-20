# Bioinformatics with Python

Exercises for the "Bioinformatics with Python" module at the 2024 Advanced Sequencing 
Technologies and Applications course at Cold Spring Harbor Laboratories.

## Installation

### Installation Prerequisites

Install prerequisite software using the following commands in ubuntu:

```shell
sudo apt update; sudo apt install build-essential libssl-dev zlib1g-dev \
libbz2-dev libreadline-dev libsqlite3-dev curl git \
libncursesw5-dev xz-utils tk-dev libxml2-dev libxmlsec1-dev libffi-dev liblzma-dev
```

### Install `pyenv`

Once these commands are complete, run:

```shell
curl https://pyenv.run | bash
```

### Configure environment variables

```shell
echo 'export PYENV_ROOT="$HOME/.pyenv"' >> ~/.bashrc
echo 'command -v pyenv >/dev/null || export PATH="$PYENV_ROOT/bin:$PATH"' >> ~/.bashrc
echo 'eval "$(pyenv init -)"' >> ~/.bashrc
```
