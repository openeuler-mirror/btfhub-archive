# btfhub-archive

#### Introduction
This repository is a BTF resource archive for the openEuler BTF management  infrastructure and provides pre-built kernel BTF for the openEuler  system. For more information and supporting system versions, please  refer to `openeuler/btfhub` Warehouse.

The BTF file format and directory structure provided by this repository are the same as those of the original BTFHub Archive, and can be mixed. The specific directory structure is as follows:

```
btfhub-archive
└── openEuler (os-release ID)
    └── 20.03 (os-release VERSION_ID)
        └── x86_64 (uname -m)
            └── 4.19.90-2112.8.0.0131.oe1.x86_64.btf.tar.xz (uname -r + ".btf.tar.xz")
```
