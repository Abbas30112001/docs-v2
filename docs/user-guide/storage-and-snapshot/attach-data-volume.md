---
title: Attach Data Volume
sidebar_label: Attach Data Volume
sidebar_position: 4
---

### Steps to attach a data volume in windows VM

- Let's assume that you have already created a VM and volume has been attached to your windows instance.

<img alt="stackbill Cloud billing solution" src="/user-guide/storage-and-snapshot/attach-data-volume/stackbill-cloud-management-portal-data-volume-my-storage.png" width="90%" />


- Login into your windows instance and right click on the windows button and select **disk management.**

<img alt="stackbill Cloud billing solution" src="/user-guide/storage-and-snapshot/attach-data-volume/stackbill-cloud-management-portal-disk-management.png" width="40%" />

- While access the disk management snap-in, it automatically detects your attached disk and prompt to initialize the disk. Click **OK** to continue.

<img alt="stackbill Cloud billing solution" src="/user-guide/storage-and-snapshot/attach-data-volume/stackbill-cloud-management-portal-disk-ok.png" width="90%" />

- Currently, your attached disk will be in **unallocated** state. 
- Right click on the disk and select **New Simple Volume**.

<img alt="stackbill Cloud billing solution" src="/user-guide/storage-and-snapshot/attach-data-volume/stackbill-cloud-management-portal-new-simple-volume.png" width="90%" />

- New wizard will popup, click **Next** to continue.

<img alt="stackbill Cloud billing solution" src="/user-guide/storage-and-snapshot/attach-data-volume/stackbill-cloud-management-portal-next.png" width="70%" />

- Specify the volume size, by default it takes **total disk space.** Then click **Next.**

<img alt="stackbill Cloud billing solution" src="/user-guide/storage-and-snapshot/attach-data-volume/stackbill-cloud-management-portal-volume-size.png" width="80%" />

- Assign a **drive to your disk** and click **Next.**

<img alt="stackbill Cloud billing solution" src="/user-guide/storage-and-snapshot/attach-data-volume/stackbill-cloud-management-portal-assign-drive.png" width="80%" />

- Specify a filesystem for your disk. By default, **NTFS will be selected and Next.**

<img alt="stackbill Cloud billing solution" src="/user-guide/storage-and-snapshot/attach-data-volume/stackbill-cloud-management-portal-volume-wizard.png" width="80%" />

- Click **Finish** to complete the wizard.

<img alt="stackbill Cloud billing solution" src="/user-guide/storage-and-snapshot/attach-data-volume/stackbill-cloud-management-portal-completing-wizard.png" width="80%" />

- After few seconds, your drive will be available to use.

<img alt="stackbill Cloud billing solution" src="/user-guide/storage-and-snapshot/attach-data-volume/stackbill-cloud-management-portal-disk-created.png" width="80%" />