[![https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg](https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg)](https://singularity-hub.org/collections/1928)
                

# Singularity config for rseqc container

A [Singularity Hub](https://www.singularity-hub.org/) definition for a lncRNA workflow.

If [Singularity](http://singularity.lbl.gov) is installed locally, the container can be build (needs root access) locally like this:

```bash
sudo singularity build simg-rseqc.simg Singularity
```

The container can alos be downloaded from [Singularity Hub](https://www.singularity-hub.org/) without root access to the local machine like this:

```bash
singularity pull --name "simg-rseqc.simg" sschmeier/simg-rseqc:latest 
```

Then, it can be used, e.g.:

```bash
singularity exec simg-rseqc.simg junction_annotation.py --help
```
