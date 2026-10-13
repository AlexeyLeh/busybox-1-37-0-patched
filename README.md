# busybox-1-37-0-patched
The patch and some warning fixes busybox ver. 1.37.0 for ARM build

- Version 1.37.0 is used - [busybox-1_37_0.tar.bz2](https://git.busybox.net/busybox/snapshot/busybox-1_37_0.tar.bz2)

## The following patches have been applied to version 1.37.0 

**busybox-1.37.0.patched.tar.bz2**

- [fixes non-i386 and x86 builds](https://lists.busybox.net/pipermail/busybox/2024-October/090953.html)

- *networking/tc.c:236:27: 'TCA_CBQ_MAX' undeclared* \
    - [This bug was submitted to the official BusyBox](https://bugs.busybox.net/show_bug.cgi?id=15931)

    - [there is a patch](https://bugs.busybox.net/attachment.cgi?id=9751)

- Fixed warnings about bugs in C code