---
title: Extend the Root Volume 
sidebar_label: Extend the Root Volume
sidebar_position: 3 
---


### In this tutorial, we'll show you how to extend **Windows VM's root volume.**

- We assume that, You have changed the virtual instance root volume size, for example, **40 GB to 50 GB** while creating the instance.

<img alt="stackbill Cloud billing solution" src="/user-guide/storage-and-snapshot/extend-root-volume/stackbill-cloud-managament-portal-root-disk.png" width="90%" />

- Once you logged in the server, open run command and type diskmgmt.msc

<img alt="stackbill Cloud billing solution" src="/user-guide/storage-and-snapshot/extend-root-volume/stackbill-cloud-managament-portal-run.png" width="70%" />

- Your additional space will be show as **unallocated** in the disk management snap-in.

<img alt="stackbill Cloud billing solution" src="/user-guide/storage-and-snapshot/extend-root-volume/stackbill-cloud-management-portal-unallocated.png" width="80%" />

- To extend your root volume, right click on c: drive and click on extend volume.

<img alt="stackbill Cloud billing solution" src="/user-guide/storage-and-snapshot/extend-root-volume/stackbill-cloud-managament-portal-extended-volume.png" width="80%" />

- A new wizard will be open and click Next to continue.

<img alt="stackbill Cloud billing solution" src="/user-guide/storage-and-snapshot/extend-root-volume/stackbill-cloud-managament-portal-next.png" width="70%" />

- Specify the amount of space that you willing to expand and click Next button.

<img alt="stackbill Cloud billing solution" src="/user-guide/storage-and-snapshot/extend-root-volume/stackbill-cloud-management-portal-wizard.png" width="70%" />

- Click finish to complete the wizard.

<img alt="stackbill Cloud billing solution" src="/user-guide/storage-and-snapshot/extend-root-volume/stackbill-cloud-managament-portal-completing-root-volume.png" width="70%" />
- Now you can able to see your root volume with new disk size.

<img alt="stackbill Cloud billing solution" src="/user-guide/storage-and-snapshot/extend-root-volume/stackbill-cloud-managament-portal-root-volume-extended.png" width="90%" />