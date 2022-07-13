# Triple Machine Repository: hardware choices

This part will be dedicated to display the hardware choices for the different machines, listing multiple possible good choices and messages of direction. The triple machine naming comes from having the idea of redudant, separated functions from separate machines.

---

## NAS - Network attached storage

The point of a NAS is that it can run all day, everyday while being accessible for other machine on the local network (or wider) and providing them storage reachable through the local network. The NAS has to have a good connection, reliable parts either through software and hardware solutions, while providing huge storage with low power solutions. Let's list, what we have here!

**Notes**: if the NAS only has file hosting functionality, low TDP, low price and lower core count wins. Otherwise, it needs to have more cores, and a graphics card to do possible videostreaming without problems

---

### CPU

1. i5-10400, with cooler

    Its a good cpu with a lot of cores (6C, 12T), somewhat fresh platform. The problem is power consuption and price.

2. i3-12100, with cooler

    Similar price as the i5-10400, but stronger single core performance, while having lower cores (4C,8T). Its price is lower but very fresh which may be disadvantageous.

---
### MOBO


1. LGA-1200: ASUS PRIME H510M-R-SI

    Form factor: Micro-ATX

    **Notes**: The small formfactor comes handy, not a lot of IOs. Low tier chipset my have limits.

2. LGA-1700: ASROCK H610M-HDV/M.2

    Form factor: Micro-ATX

    **Notes**: Same form factor, newer platform.
---
### Storage

*Storage is a bit different as I have to list NAS capable storage, SSDs and M.2 NVMe ssds too!*

**HDD**

**Notes**: a lower RPM corresponds to lowerr speeds but lower noise too! NAS HDDs are somewhat dedicated to this task.

1. Western Digital WD Red Plus 3.5 8TB 7200rpm 256MB SATA3
2. Western Digital WD Red 3.5 6TB 5400rpm 256MB SATA3
3. Seagate IronWolf NAS 3.5 6TB 5400rpm 256MB SATA3

**SSD**

**Notes**: in some cases, a faster storage is handy for caching information.

1. Samsung 2.5 870 EVO 500/1000 GB SATA3
2. KIOXIA EXCERIA 2.5 480/960 GB SATA
3. Western Digital WD Blue 3D NAND 2.5 500GB SATA3

**NVMe**

**Notes**: this requires an m.2 slots, rather than a SATA3

1. Samsung 970 EVO Plus 500GB M.2 PCIe
2. Western Digital WD Black SN750 SE 500GB M.2 PCIe
3. KIOXIA EXCERIA 500GB M.2 PCIe

---

### Accesories

---

### Alternative

The alternative is having one machine that can handle everything. Lower redundancy, but stronger parts. This also give better insing to virtualisation and virtual machines while having multiple machines could give insight to clustering. Hard choices are made

* CPU: intel xeon W-1290P
* MOBO: gigabyte w480

**Notes**: this would be a workstation/server machines, could handle a GPU as an extra too. Higher individual pwer draw, which is not favored for the project.