# No Hack No CTF 2025 - Crackme

This repository contains the question about the crackme challenge for the No Hack No CTF 2025 competition.

For the write-up, please refer to the: https://blog.ummit.dev/posts/ctf/nhnc/2025/

## Question about Crackme

Crack my virtual machine :D

Sample command of running the machine:

```shell
qemu-system-x86_64 \
  -enable-kvm \
  -machine q35 \
  -m 3024 \
  -smp sockets=1,cores=2,threads=2 \
  -cpu host \
  -drive file=crackme.qcow2,if=virtio,format=qcow2,discard=unmap \
  -device virtio-scsi-pci \
  -netdev user,id=net0 \
  -device virtio-net-pci,netdev=net0 \
  -vga qxl \
  -boot c
```

![](https://aniyuki.com/wp-content/uploads/2023/05/aniyuki-oshi-no-ko-gif-2.gif)

`Author: UmmIt`

### Download Crackme VM

> https://drive.proton.me/urls/CE30SCFGDC#UWjKvfJUZRFi
