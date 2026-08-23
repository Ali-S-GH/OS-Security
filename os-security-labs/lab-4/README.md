# Lab 4

This Lab about setup Windows server and Domain Controller and Install Active Directory

### **Requirements :**

**1- VirtualBox Or VMware**

**2-** [**Windows Server 2012 or Newest**](pre-installation-preparation.md#id-1-windows-server-2012-and-product-keys)

### Configuring the Virtual Machine Network:

<details>

<summary>How to create Nat Network in VirtualBox:</summary>

You can change the Nat Network settings if you want

</details>

<details>

<summary>How to create Nat Network in VMware:</summary>

After open the VMware press Edit then "Virtal Network Editor"

You can chose any Network number you want put only one can be the Nat

Select Nat then edit the "Subnet IP" and "Subnet mask"

then go to Nat Settings and edit the Gateway IP to Fit your Subnet IP

Then press Apply ✅

{% hint style="info" %}
note: the same way if you going to create it for Host-only
{% endhint %}

After Finishing go to your VM and enter **"Edit virtual machine settings"**

Then go to Network Adapter -> Select Custom and choose the same network number you configured

</details>
