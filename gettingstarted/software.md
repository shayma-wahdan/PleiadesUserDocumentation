---
title: "Getting Started: Software"
---

## Getting Started: Software

<!-- Available software and load modules. -->
<!-- more at [some link] -->

### File System
A [BeeGFS](https://www.beegfs.io/) cluster file system is installed on fugg1.pleiades.uni-wuppertal.de login machine and on all cluster worker nodes, i.e. the file system is shared among all nodes and can be used to develop code and to save output files from cluster jobs.  In general, no „copy constructions“ are needed. A group quota according to the share of each participating group has been applied. If needed additional user quotas can also be applied.  You find your home directory at:

```bash
/beegfs/USERNAME
```

if you need real local space on the worker nodes, use „/tmp“, but please clean up inside your jobs scripts, otherwise you will overload the nodes.


**Heads up!**
There is no backup for the /beegfs file system. However, this file system is running on raid systems.


**Heads up! WHEP users**

You have a different home directory (`/common/home/USERNAME`).

Hence, you need to have the same files in
```bash
/common/home/USERNAME/.ssh
```
and

```bash
/beegfs/USERNAME/.ssh
```

This can easily be achieved by copying the whole directory.

<!-- more at [some link] -->