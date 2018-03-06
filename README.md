# Singularity container with PyMOL & OpenBabel

## To build this container from scratch execute this:

```bash
sudo singularity build singularity-pymol-openbabel.img singularity-pymol-openbabel
```

## To list the available apps inside the container

```bash
singularity apps singularity-pymol-openbabel.img
```

## To execute one of the apps

```bash
singularity run --app lddt singularity-pymol-openbabel.img
```

