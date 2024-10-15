---
title: Create New SSH Key
sidebar_label: Create New SSH key
sidebar_position: 2
---

An **SSH key** is an **access credential** in the SSH protocol. Its function is similar to that of **user names and passwords**, but the keys are primarily used for **automated processes** and for implementing single sign-on by **system administrators and power users.**


- Click on the **Virtual Resources** dropdown button below the dashboard icon, Which is available in the top left corner. from the dropdown, Click on **SSH key**, to create a new SSH key.

<img alt="stackbill Cloud billing platform" src="/user-guide/ssh-key-manager/create-new-ssh-key/stackbill-cloud-management-portal-ssh-key.png" width="90%" />

- **SSH key** screen appears.
- At right side of the panel the user can able to see a option called **Add** button, click on it.

<img alt="stackbill Cloud billing platform" src="/user-guide/ssh-key-manager/create-new-ssh-key/stackbill-cloud-management-portal-add-ssh-key.png" width="90%" />

- **ADD SSH Key** option appears on the screen.

<img alt="stackbill Cloud billing platform" src="/user-guide/ssh-key-manager/create-new-ssh-key/stackbill-cloud-management-portal-add-ssh-button.png" width="50%" />

- **Name** - Specify a name for the key.
- **Description** - Give a short notes about the key.
- Finally click **ADD** button.

<img alt="stackbill Cloud billing platform" src="/user-guide/ssh-key-manager/create-new-ssh-key/stackbill-cloud-management-portal-add-ssh-successfull.png" width="80%" />

- Now the **SSH Key has been generated successfully.**
- In the **action option**, the user can download or delete the SSH key.

### How to generate SSH key from windows laptop

- To generate SSH key, first you need to download PuttyGen from the below link.

https://www.puttygen.com/download-putty#Download_PuTTY_073_for_Windows

<img alt="stackbill Cloud billing platform" src="/user-guide/ssh-key-manager/create-new-ssh-key/stackbill-cloud-management-portal-ssh-windows-content.png" width="90%" />

- Select the key type as RSA and then click on Generate button.

<img alt="stackbill Cloud billing platform" src="/user-guide/ssh-key-manager/create-new-ssh-key/stackbill-cloud-management-portal-ssh-windows-rsa.png" width="60%" />

- Just move your cursor over the blank area to generate SSH key.

<img alt="stackbill Cloud billing platform" src="/user-guide/ssh-key-manager/create-new-ssh-key/stackbill-cloud-management-portal-ssh-windows-key-loading.png" width="60%" />

- Once the key has been generated, click on the **save private key** button.


<img alt="stackbill Cloud billing platform" src="/user-guide/ssh-key-manager/create-new-ssh-key/stackbill-cloud-management-portal-ssh-windows-save-key.png" width="60%" />

- It will prompt us to save the key without passphrase. Click Yes to continue.

<img alt="stackbill Cloud billing platform" src="/user-guide/ssh-key-manager/create-new-ssh-key/stackbill-cloud-management-portal-ssh-putty-warning.png" width="80%" />

- Provide the name for your SSH Key and click on Save button.

<img alt="stackbill Cloud billing platform" src="/user-guide/ssh-key-manager/create-new-ssh-key/stackbill-cloud-management-portal-save-key.png" width="80%" />

### How to generate SSH key from Linux Laptop

- Go to the terminal and enter.

~~~
ssh-keygen
~~~

- After entering the command, you should see the following output:

~~~
Output
Generating public/private rsa key pair.
Enter file in which to save the key (/your_home/.ssh/id_rsa):
~~~

- If you choose to overwrite the key on disk, you will not be able to authenticate using the previous key anymore. Be very careful when selecting yes, as this is a destructive process that cannot be reversed.


- You should then see the following prompt:

~~~
Output
Enter passphrase (empty for no passphrase):
~~~

- Now the SHH key has been generated successfully.

<img alt="stackbill Cloud billing platform" src="/user-guide/ssh-key-manager/create-new-ssh-key/stackbill-cloud-management-portal-key-confirmation.png" width="100%" />


## Download SSH in StackBill Cloud Management Portal

- Click on the **Virtual Resources** dropdown button below the dashboard icon, Which is available in the top left corner. from the dropdown, Click on **SSH key**, to create a new SSH key.

<img alt="stackbill Cloud billing platform" src="/user-guide/ssh-key-manager/create-new-ssh-key/stackbill-cloud-management-portal-ssh-key.png" width="90%"/>

- **SSH key** screen appears.

<img alt="stackbill Cloud billing platform" src="/user-guide/ssh-key-manager/create-new-ssh-key/stackbill-cloud-management-portal-ssh-key-download.png" width="90%"/>

- Under the **action** option on the right side of the panel, users can see a download button.
- Click on it.

<img alt="stackbill Cloud billing platform" src="/user-guide/ssh-key-manager/create-new-ssh-key/stackbill-cloud-management-portal-download-key-confirmaton.png" width="70%"/>

- Now the Download confirmation screen appears, Click on the **Download** Button.

<img alt="stackbill Cloud billing platform" src="/user-guide/ssh-key-manager/create-new-ssh-key/stackbill-cloud-management-portal-key-listed.png" width="70%"/>

- Now the SSH Key has been downloaded successfully.

-----------------------------------------------------

**About StackBill**

**[StackBill](https://www.youtube.com/watch?v=nyV8oE3dfXs) is a complete self-service intuitive [Cloud Management Portal](https://www.stackbill.com/) with extensive features leveraging Apache CloudStack® with state of art years of expertise.**

