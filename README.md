# singularity-centos7-python36

## Summary

This is a basic Singularity definition file to show how to create a CentOS 7
container with Python 3.6 from EPEL.

## Build instructions

Assuming you already have Singularity installed, run the following command to build the container:

```
sudo singularity build centos7-python36.sif centos7-python36.def
```

This will pull the official CentOS 7, add the EPEL repository, and install the EPEL version of Python 3.6.x.
