---
title: Extend the Data Volume 
sidebar_label: Extend the Data Volume
sidebar_position: 5
---

### In this tutorial, we'll show you how to extend **Windows VM's data volume.**


-   Let's assume that you have already created a VM and volume has been attached to your windows instance.

<img alt="stackbill Cloud billing solution" src="/user-guide/storage-and-snapshot/extend-data-volume/stackbill-cloud-management-portal-disk-full.png" width="70%" />

:::info
Note: Make sure that you virtual instance should be in **stopped state** before performing the below operation.
:::

- Also, For ex, you have resize your data disk by adding additional **10 GB through StackBill portal.**

<img alt="stackbill Cloud billing solution" src="/user-guide/storage-and-snapshot/extend-data-volume/stackbill-cloud-management-portal-resize.png" width="90%" />

<img alt="stackbill Cloud billing solution" src="/user-guide/storage-and-snapshot/extend-data-volume/stackbill-cloud-management-portal-disk-size.png" width="90%" />

- Start your virtual machine.

- Once you logged into your virtual machine, Open run window and type **diskmgmt.msc**

<img alt="stackbill Cloud billing solution" src="/user-guide/storage-and-snapshot/extend-data-volume/stackbill-cloud-management-portal-run.png" width="80%" />

- You are able to see the **additional disk space as an unallocated state.**

<img alt="stackbill Cloud billing solution" src="/user-guide/storage-and-snapshot/extend-data-volume/stackbill-cloud-management-portal-unallocated.png" width="90%" />

- Right click on the data disk and click on **extend volume.**

<img alt="stackbill Cloud billing solution" src="/user-guide/storage-and-snapshot/extend-data-volume/stackbill-cloud-management-portal-extend-volume.png" width="90%" />

-  A new wizard will be open and click **Next** to continue.

<img alt="stackbill Cloud billing solution" src="/user-guide/storage-and-snapshot/extend-data-volume/stackbill-cloud-management-portal-wizard-next.png" width="70%" />

- Specify the amount of space that you willing to expand and click **Next** button.

<img alt="stackbill Cloud billing solution" src="/user-guide/storage-and-snapshot/extend-data-volume/stackbill-cloud-management-portal-wizard-next-disk.png" width="80%" />

- Click **finish** to complete the wizard.

<img alt="stackbill Cloud billing solution" src="/user-guide/storage-and-snapshot/extend-data-volume/stackbill-cloud-management-portal-wizard-finish.png" width="80%" />

- Now you can able to see your data volume with new disk size.

<img alt="stackbill Cloud billing solution" src="/user-guide/storage-and-snapshot/extend-data-volume/stackbill-cloud-management-portal-disk-increased.png" width="90%" />
