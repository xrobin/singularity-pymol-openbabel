# Singularity container with PyMOL & OpenBabel

https://www.singularity-hub.org/collections/695

## To pull a pre-built container:
```bash
singularity pull shub://xrobin/singularity-pymol-openbabel
```

## To build this container from scratch execute this:

```bash
sudo singularity build singularity-pymol-openbabel.img singularity-pymol-openbabel.def
```

## To list the available apps inside the container

```bash
singularity apps singularity-pymol-openbabel.img
```

## To execute one of the apps

```bash
singularity run --app lddt singularity-pymol-openbabel.img
```

