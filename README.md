# mesonet_env
A conda environment for the Montana Mesonet

## Building the environment

Use the terminal or an Anaconda Prompt for the following steps from inside this directory:

```bash
conda env create -f environment.yml
```
Activate the new environment:

```bash
conda activate mesonet
```

Deactivate the environment:

```bash
conda deactivate
```

Verify that the new environment was installed correctly:

```bash
conda list
```

## Updating the environment
From within the environment:

```bash
conda update --all
```

## Removing the environment

```bash
conda remove --name mesonet --all
```