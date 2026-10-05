# Praktikum 3 – Ubuntu ja LVM

Reevo Veelmaa · OS-Veelmaa-Ubuntu26

Ubuntu 26.04 koos Lubuntu LXQt töölauaga.

## Lubuntu ja screenfetch

![Lubuntu ja screenfetch](01-lubuntu-screenfetch.png)

## LVM-i laiendamine

Lisatud 3 GB ketas `/dev/sdb`. Volüümigrupis `veelmaa-vg` on nüüd kaks füüsilist volüümi. `veelmaa-lv` suurus on 24,99 GiB ja grupis vaba ruumi 0.

### sudo vgdisplay

![vgdisplay](02-vgdisplay.png)

### sudo lvdisplay

![lvdisplay](03-lvdisplay.png)

### lsblk

![lsblk](04-lsblk.png)

### df -h

![df -h](05-df-h.png)
