# Practical RISC-V Education in Computer Architecture

The goal of this repository is to provide access to ressources for practical RISC-V education in computer architecture. What I found in my own courses in computer science is that RTL and waveforms are not very accessible to students and thus I created [pipeline-viewer](https://pypi.org/project/pipelineviewer/).

## Install `pipeline-viewer`

You can install `pipeline-viewer` directly with pip:

```
pip install pipeline-viewer
```

## Update the processor core submodules

The processor cores sit in git submodule folders, which you need to fetch.

```
git submodule update --init --recursive
```

## Run BOOM demo

```
cd chipyard
./scripts/init-submodules-no-riscv-tools.sh
cd sims/verilator
```