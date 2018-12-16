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

## Running the container

```
singularity run centos7-python36.sif
```

or

```
singularity shell centos7-python36.sif
```

After running the container, you will be dropped into a shell that looks very much like the shell you started from (if you're running on CentOS 7). Type `exit` or Ctrl-D to exit the container.

## Links

See the Singularity [User Guide](https://www.sylabs.io/guides/3.0/user-guide/index.html) for more information
