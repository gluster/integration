# Gluster Experience for Developers and Integration

Welcome to the landing page of the Gluster Experience for Developers and
Integration (GEDI) team. We are a group of people that are working on
integrations of Gluster in different projects, and help others on [our
mailinglist](https://lists.gluster.org/mailman/listinfo/integration).

This git repository does not intend to have any source code. Instead, it is
only used for [GitHub Issues](https://github.com/gluster/integration/issues)
that are the base for tracking progress on [different
projects](https://github.com/gluster/integration/projects).


## Integration Options for Projects

The main use-case for integrating projects closely with Gluster is to enhance
the usability and in many cases performance. Many projects use `libgfapi` to
natively connect to Gluster Volumes and perform I/O without going through a
mountpoint in the filesystem. libgfapi can be used from different programming
languages, bindings are available for:

 - C, native `libgfapi.so` from the [GlusterFS
   Project](https://github.com/gluster/glusterfs)
 - [Python](https://github.com/gluster/libgfapi-python)
 - [Java](https://github.com/gluster/libgfapi-java-io)
 - [Golang](https://github.com/gluster/gogfapi)


## Existing Integrations

Below follows a (likely incomplete) list of other software projects that have
been integrated with Gluster in some way or form. Additions, corrections and
improved descriptions can be contributed through [GitHub Pull
Requests](https://github.com/gluster/integration/edit/master/README.md).


### NFS-Ganesha

[NFS-Ganesha](http://nfs-ganesha.github.io/) is a userspace NFS-server that
supports different storage backends through the so called FSAL interface. There
is a `FSAL_GLUSTER` that uses `libgfapi` to connect to Gluster Volumes and
export those over NFSv3 and NFSv4.


### Samba
[Samba](https://samba.org)


### QEMU
[Quick EMUlator](https://qemu.org)


### oVirt
[oVirt](https://ovirt.org)


### Bareos
[Bareos](https://bareos.org)


### gluster-swift
[gluster-swift](https://github.com/gluster/gluster-swift)
Gluster-Swift provides object interface to GlusterFS volumes. It allows files and directories created on GlusterFS volume to be accessed as objects via the OpenStack Swift and S3 API.


### gluster-block
[gluster-block](https://github.com/gluster/gluster-block)


### GlusterFS Coreutils
[glusterfs-coreutils](https://github.com/gluster/glusterfs-coreutils)


### Wireshark
[Wireshark](https://wireshark.org)


### OpenStack
#### OpenStack Cinder
#### OpenStack Nova
#### OpenStack Manilla
