
This simple example DMA memory copy on QEMU raspi3 model. 

This program only supports QEMU raspi3 model, and does not work on real hardware.

```
$make run
qemu-system-aarch64 -M raspi3 -m 1024 -serial null -serial mon:stdio -nographic -kernel kernel.elf
qemu exit: Ctrl-A x / qemu monitor: Ctrl-A c
dma01
 c_irq_handler
 print destination string : hello world

```
