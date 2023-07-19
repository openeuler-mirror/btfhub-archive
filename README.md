# btfhub-archive

## 介绍

本仓库为 openEuler BTF 管理基础设施的 BTF 资源归档仓，为 openEuler 系统提供预构建的内核 BTF。详细介绍、支持系统版本等文档请参见 [`openeuler/btfhub`](https://gitee.com/openeuler/btfhub) 仓库。

本仓库提供的 BTF 文件格式、目录结构与原 [BTFHub Archive](https://github.com/aquasecurity/btfhub-archive) 相同，可以混合使用。具体目录结构如下所示：

```
btfhub-archive
└── openEuler (os-release ID)
    └── 20.03 (os-release VERSION_ID)
        └── x86_64 (uname -m)
            └── 4.19.90-2112.8.0.0131.oe1.x86_64.btf.tar.xz (uname -r + ".btf.tar.xz")
```
