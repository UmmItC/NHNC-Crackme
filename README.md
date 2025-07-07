# No Hack No CTF 2025 - Crackme

This repository contains the question about the crackme challenge for the No Hack No CTF 2025 competition.

Not writeup not finished yet. tmr will be updated :)

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
