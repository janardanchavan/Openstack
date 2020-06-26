# Openstack

1. Create a new VM in VirtualBox - Redhat7-5_Openstack
2. Allocate Ram - 8192 MB
3. Hard Disk - Create a virtual hard disk now
4. Hard disk file type - VDI (VirtualBox Disk Image)
5. Storage on physical hard disk - Dynamically allocated
6. 

If option `Enable Nested VT-x/AMD-V` is grayed out on 'Processor' or 'Acceleration' tab, run below command on the command prompt.

```
VBoxManage modifyvm yourvirtualmachinename --nested-hw-virt on
```



