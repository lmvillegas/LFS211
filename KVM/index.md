# 1 INTRODUCCIÓN A VIRTUALIZACIÓN EN RED HAT Y SUS CARACTERISTICAS

Este Capitulo describe los productos principales y sus caracteristicas disponibles en Red Hat Enterprise Linux 7.

## 1.1 Virtualización y KVM en Red Hat Enterprise o CentOS Linux 7

KVM (Kernel-based Virtual Machine) es una solución para linux en una gran variedad de infraestructuras. Esta integrado en el Kernel standar de Red Hat, Centos, Fedora y Oracle Linux e integrado con el Quick Emulator (QEMU), y puede utilizar multiples sistemas operativos invitados. El KVM hypervisor en Red Hat es maneajado por libvirt API, y herramientas construidas para libvirt (como virt-manager y virsh). las maquinas virtuales son ejecutadas com procesos controladas por estas herramientas.

```markdown
Advertencia!!!

**QEMU** y **lirvirt** tambien es soportado por el modo de traducción dinámica utilizando 
el Generador de código minúsculo QEMU(TCG). 

```

