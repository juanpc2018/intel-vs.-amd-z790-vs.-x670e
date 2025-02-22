# intel vs. amd | z790 vs. x670e

intel </br>
ASRock Z790 LiveMixer </br>
vs. </br>
AMD </br>
ASRock X670E PG Lightning </br>
ASRock B650 LiveMixer </br>

features wise... almost the same </br>
Cardboard box is better in Z790 LiveMixer, </br>
X670E Box is "economic" type. </br>
both have same foam, similar manual, and accesories: SATA cable and M.2 screws. </br>

According to ASRock, B650 LiveMixer is the AMD equivalent of Z790 LiveMixer, </br>
but... does Not have [X670E "Dual" Chipset](https://www.digitalcitizen.life/x670e-x670-b650e-b650-chipsets/), does Not have 1x PCIe x1 slot </br>
has [B650 Non-E](https://www.digitalcitizen.life/x670e-x670-b650e-b650-chipsets/) does Not have x16 PCIe v5 support, but has M.2 PCIe v5. </br>
according to Block Diagram, PCIe v5 support comes from the CPU, Not the Chipset, </br>
but PCIe x16 v5 requires a switch IC to share lanes when M.2 PCIe v5 is connected, </br>
B650 LiveMixer does Not have a switch ic, like Z790 & X670E </br>
CPU lanes are set Fixed by UEFI to PCIe x16 v4 to enable M.2 PCIe v5 "The most common set-up". </br>
B650 does Not have PCIe v5 x16, like Z790 or X670E, but All have M.2 PCIe v5 *IF CPU is 7000, 9000 or 4004. </br>
B650 LiveMixer is the only AMD board that has x16 x4 x4 electrical with 3x x16 plastic slots, similar to Z790 LiveMixer. </br>

PCIe v5 x16 could be used for RAID cards like: </br>
HighPoint [7608A](https://www.youtube.com/watch?v=IrsV-7knzME) HW & [1608](https://www.youtube.com/watch?v=suFHJYd_kks).[A](https://www.youtube.com/watch?v=dq8XnVIVJ_g) SW, ASUS Hyper M.2 x16 [Gen5](https://www.asus.com/motherboards-components/motherboards/accessories/hyper-m-2-x16-gen5-card/) 4x NVMe, Sonnet [8x4 PCIe v4](https://www.sonnettech.com/product/m2-8x4-pcie-card/overview.html) or Areca [ARC-1886-xNxI](https://www.areca.us/products/nvme-1886.html) </br>
GPU would have to be moved to x4 or x1 slot or use iGPU. </br>
AMD most powerful iGPU for AM5 is the [8700G](https://www.amd.com/en/products/processors/desktops/ryzen/8000-series/amd-ryzen-7-8700g.html) but does Not have PCIe v5, has A.i. NPU. </br>
Ryzen [7000](https://www.amd.com/en/products/processors/desktops/ryzen/7000-series/amd-ryzen-5-7600x.html), [9000](https://www.amd.com/en/products/processors/desktops/ryzen/9000-series/amd-ryzen-5-9600x.html) & Epyc [4004](https://www.amd.com/en/products/processors/server/epyc/4004-series/amd-epyc-4124p.html) have PCIe v5 but dont have A.i. NPU. </br>
AMD 4-core/8-threads [8300G](https://www.amd.com/en/products/processors/desktops/ryzen/8000-series/amd-ryzen-3-8300g.html) has PCIe v4 + A.i. NPU vs. 4c/8t [4124p](https://www.amd.com/en/products/processors/server/epyc/4004-series/amd-epyc-4124p.html) PCIe v5  No A.i. NPU. </br>
intel 4c/8t [i3-12100](https://www.intel.com/content/www/us/en/products/sku/134584/intel-core-i312100-processor-12m-cache-up-to-4-30-ghz/specifications.html) / 13100 / 14100 has PCIe v5 but does Not have A.i. NPU. Only Next Generation Ultra CPUs, Not compatible with Z790. </br>

[B650 LiveMixer](https://www.asrock.com/mb/AMD/B650%20LiveMixer/Specification.us.asp) has 3x PCIe v4 x16 electrical: x16 x4 x4. </br>
[X670E PG Lightning](https://pg.asrock.com/MB/AMD/X670E%20PG%20Lightning/index.asp) has 1x PCIe v5 x16 + 2x PCIe v4 x16 slots "x4 x1" + 1x PCIe x1 v4 = x16 x4 x1 x1. </br>
[Z790 LiveMixer](https://www.asrock.com/mb/Intel/Z790%20LiveMixer/Specification.asp) has 1x PCIe v5 x16 + 2x PCIe v4 x16 slots "x4 x4" + 1x PCIe x1 v4 = x16 x4 x4 x1. </br>

v4 x4 slot can be used for Thunderbolt4 card, or 10GbE SFP+ Ethernet card or more [SATA-III 6Gbps](http://ableconn.com/products_2.php?gid=163) ports or more [M.2 ports](http://ableconn.com/products_2.php?gid=106), </br>
or M.2 Raid card like [Ableconn PEXM2-130 PCIe Dual NVMe M.2](http://ableconn.com/products_2.php?gid=143) </br>

B650 LiveMixer has 2x SATA-III 6Gbps </br>
X670E & Z790 have 4x SATA-III 6Gbps </br>
X670E has 1x 20 Gbps [USB-C 3.2 Gen2x2](https://en.wikipedia.org/wiki/USB_3.0#USB_3.2) </br>
B650 & Z790 has 1x Front Panel USB-C 3.2 Gen2x2 Header, requires a special connector / case, Not included. </br>
there are PCIe Brackets $20usd. to $50usd. depending on cable lenght. </br>

Booting Linux on external SSD is faster on USB-C 3.2 2x2 </br> 
X670E does Not require special cable, has rear connector. </br>
but requires a 20G USB 3.2 or 40G USB 4.0 [Orico M.2 NVMe & SATA SSD Drive Enclosure](https://www.orico.cc/us/product/subcategory/115.html) or similar, </br>
booting using Thunderbolt3/4 + eGPU + M.2 to PCIe card is another option. </br>

There is No 100% equivalent on AMD of intel Z790 LiveMixer </br>
X670E PG Lightning vs. B650 LiveMixer </br>
you win some, you lose some, depends on your needs. </br>

### example: </br>

¿Does [Thunderbolt 4 AIC PCIe](https://www.asrock.com/mb/spec/product.asp?Model=Thunderbolt%204%20AIC) "Add-In Card" work in x1 electric PCIe v4 slot? </br>
TB4 box comes with install guide paper, but instructions are incomplete / outdated </br>
[download .pdf](https://download.asrock.com/Manual/Thunderbolt%204%20AIC.pdf) </br>
AMD boards require to change 1x jumper on TB4 card. </br>
.pdf has a list of supported Motherboards, and recommended PCIe slot. </br>

some boards are PCIe slot4 like Z790 LiveMixer, </br>
others PCIe slot3 like X670E PG Lightning, and others PCIe slot2 like B650 LiveMixer. </br>
Z790 PCIe slot4 goes to Z790 chipset </br>
X670E PCIe slot3 goes to CPU. </br>
B650 LiveMixer PCIe slot2 goes to CPU. </br>

Z790 LiveMixer + TB4 card does Not work when using 12th gen CPU like i3-12100 + latest Bios/Uefi 18.x designed for 14gen CPU´s, </br>
TB4 card works OK with [UEFI v9.03](https://www.asrock.com/mb/Intel/Z790%20LiveMixer/Specification.asp#BIOS) because it´s Universal, works with 12, 13 & 14th gen CPU´s </br>
Early Bios does Not support 14th gen CPU´s. </br>

AMD boards: To Be Tested... </br>

TB4 has a maximum thoughput of 40 Gb/s but... thats Not always used, Not in my case. </br>
im Not using all features / bandwith of Thunderbolt 4 </br>
ASRock TB4 AIC [Version1.0](https://www.asrock.com/mb/spec/product.asp?Model=Thunderbolt%204%20AIC) claims is PCIe v3 x4 = 4 GB/s = 4000 MB/s = [32 Gbit/s](https://en.wikipedia.org/wiki/Thunderbolt_(interface)#Thunderbolt_3) "8 Gbits = 1 GB/s = 1000 MB/s per lane." </br>
40 Gb/s combined including 4 lanes of DisplayPort. </br>

Razer Core X Chroma [eGPU](https://egpu.io/best-egpu-buyers-guide/) chassis is PCIe v3, and Thunderbolt3. </br>
Thunderbolt3 has 4x lanes of PCI Express 3.0 (32.4 Gbit/s) 4 GB/s = 4000 MB/s. </br>
PCIe v4 x1 has a thoughput of [2GB/s](https://en.wikipedia.org/wiki/PCI_Express#Comparison_table) "16 Gbit/s = 2000 MB/s" </br>
______________ ______________ PCIe v3 x1 = PCIe v2 x2 </br>
______________ PCIe v4 x1 = PCIe v3 x2 = PCIe v2 x4 </br>
PCIe v5 x1 = PCIe v4 x2 = PCIe v3 x4 = PCIe v2 x8 </br>
PCIe v5 x2 = PCIe v4 x4 = PCIe v3 x8 = PCIe v2 x16 </br>
PCIe v5 x4 = PCIe v4 x8 = PCIe v3 x16 </br>
PCIe v5 x8 = PCIe v4 x16 </br>

Avid HDX PCIe card requires PCIe v2 x4 = 16 Gbits = 2 GB/s = 2000 MB/s </br>
works on Macmini 2014 [Thunderbot 2](https://en.wikipedia.org/wiki/Thunderbolt_(interface)#Thunderbolt_2) at 20 Gbit/s ("2.5GB/s") </br>

PCIe v4 x1 = PCIe v2 x4, in theory should work </br>
IF TB4 card supports v4 x1, but [manual](https://www.asrock.com/mb/spec/product.asp?Model=Thunderbolt%204%20AIC#Manual) say does Not. </br>
TB4 AIC [Version2.0](https://www.asrock.com/mb/spec/product.asp?Model=Thunderbolt%204%20AIC%20R2.0#Support) also does Not. </br>
TB4 v1 & v2 cards only support PCIe v3 x4, working at v3 x1 = 8 Gbit/s per lane = 1 GB/s = 1000 MB/s per lane. </br>
half the speed required for max operation, </br>
could work for lower I/O channel count, </br>
Not the whole [2x 32-channel mini DigiLink™ connectors (64 channel total)](https://cdn-www.avid.com/-/media/avid/files/products-pdf/carbon/pro-tools-carbon-vs-hdx-mtrx-studio-bundle-comparison.pdf) </br>

1x Thundebolt4 PCIe card in PCIe x1 slot + 1x TB3 cable port. </br>
and leave the other PCIe v4 x4 for other card. </br>
more requires to move the Thunderbolt4 card to the x4 PCIe slot in the X670E PG Lightning, Not in the others. </br>

physical level: Thunderbolt 1 & 2 bandwidth are same. </br>
TB 1 & 2 cabling same. </br>
TB 2 has channel aggregation: </br>
2x TB-1 10 Gbit/s channels combined in 1x 20 Gbit/s channel. </br>

Sonnet [10G Solo SFP+](https://www.sonnettech.com/product/solo10g-sfp-pcie-card.html) 10Gbit/s = 1.25GB/s = 1250 MB/s PCIe SFP+ FiberOptic Network adapter </br>
ASUS [XG-C100F](https://www.asus.com/networking-iot-servers/wired-networking/all-series/xg-c100f/) 10G SFP+ Network adapter or similar </br>
supports PCIe v3 x4, but works in PCIe v2 x4 ("2GB/s / 16Gbit/s / 2000 MB/s") = PCIe v3 x2 = PCIe v4 x1. </br>
but do Not support PCIe v4 x1, Only PCIe v3 </br>
IF card run at v3 x1, will run at 1GB/s = 1000MB/s, Not a big loss for SFP+ 10G, Untested. </br>

Maybe Bios does Not detect TB4 card if Not installed in the "recommended" PCIe slot. </br>
More Tests Needed. </br>

### Other differences: </br>

CPU Power connector: </br>
X670E PG Lightning is 8+4 </br>
Z790 LiveMixer is 8+8 </br>
B650 LiveMixer is 8+8 </br>

¿ is 8+4 enough for AMD 16-core 9950x or 7950x 170w ? </br>
or will happen the same as [Nvidia 4090 power connector](https://en.wikipedia.org/wiki/16-pin_12VHPWR_connector#Reliability_and_design_changes)? </br>

[AWG18](https://www.powerstream.com/Wire_Size.htm) 12V Power Connector: </br>
Molex* 39-01-2040 or equivalent, </br>
Contact: Molex 44476-1112 (HCS) or equivalent </br>
Mating motherboard connector Molex 39-29-9042 or equivalent). </br>
2.3A per AWG18 wire x 12v = 8+4 = 27.6 </br>
8+4 = 27.6 x 6 = 165.6 watts. </br>
8+8 = 27.6 x 8 = 220.8 watts. </br>
24-Pin connector has +12v Pins 10 & 11 = 2.3A * 12 * 2 = 55 watts
8+6 "165watts" + 55watts = 220watts minus PCIe +12v & RAM power consumption. </br>

[EPS12v specification](https://web.archive.org/web/20201205140420/http://www.enermax.cn/enermax_pdf/EPS12V%20Spec2_92.pdf) has a recommended limit of 240VA for each 4-pin 12v CPU conector, </br>
Assuming 75w limit each 4-pin CPU connector, 8+4 = 225watts. </br>
8+4 seem enough, but depends... on PCIe configuration, RAM and PSU cables, [AWG](https://www.powerstream.com/Wire_Size.htm) must be true [AWG16](https://www.powerstream.com/Wire_Size.htm), Not rubber AWG16. </br>
3.7A per AWG16 x 12V = 44.4watts, 4-pin connector has 2x +12v = 88watts maximum. </br>
theoretic maximum: 264watts for AWG16 8+4 CPU connector or 165watts for AWG18. </br>

Each PCIe x4 electric slot is limited to [25w](https://en.wikipedia.org/wiki/PCI_Express#Power) = 220w "AWG18" - 25w = 195w - 25w = 170w </br>
Each x1 PCIe slot is limited to 0.5A at +12V (6W) 10W combined. </br>
x16 graphics card that does Not have VGA 6-pin power connector, like some GTX 1050 Ti, RTX A2000 draw up to 5.5A at +12V (66W) 75W combined. </br>
Optional VGA connectors add: +75W (6-pin) / +150W (8-pin) of +12V. </br>
M.2 drives draw up to 12watts each. </br>

8+4 Works but requires a well designed PSU. </br>
IF disable "HyperThreading / CPU SMT", ACME PSU or Overclocking could work. </br>

### SATA-III

Z790 LiveMixer has 4x SATA-III 6Gbps connectors in 1x large connector, </br>
X670E PG Lightning has 4x SATA-III 6Gbps connectors separated in pairs. </br>
B650 LiveMixer has 2x SATA-III 6Gbps connectors. </br>

### Same: </br>

TBT Thunderbolt4 header. </br>
1x PCIe v5 x16 shared with M.2 PCIe v5 x4 slot 1, using a switch in Z790 and X670E. </br>
1x PCIe v4 connector x1 electrical, Not available in B650 LiveMixer </br>
2x PCIe v4 connector x4 x4 electrical or x4 x1 in X670E PG Lightning </br>
4x DDR5 DIMM Slots. </br>
HDMI out </br>
DisplayPort 1.4 out. </br>
Hardware monitor: SIO NCT6796D </br>
HDAudio: ALC897 but Analog Audio Circuit may be different. </br>
2x USB-A Low Latency ["Lightning Gaming"](https://www.asrock.com/microsite/2022EmbraceTheFuture/single-post8.html) [Ports](https://www.asrock.com/microsite/2021EmbraceTheFuture/single-post3.html) </br> 
8-Layer PCB. </br>
14-Vcore Phases + 2 SOC Phases + 1 VDO Misc Phase on AMD, 14-Phases on intel</br>
2.5GbE Realtek LAN: RTL8125BG. </br>

WQHD monitors like LG 34GP63 are: 3440x1440 x 160fps </br>
160fps requires DisplayPort 1.4 or better </br>
HDMI is limited to 50fps. </br>

intel or AMD iGPU does Not play 3D games at 3440x1440 x 160fps, </br>


FlashRom is connected directly to CPU on intel board, requires CPU to flash Bios. </br>
FlashRom is connected to X670E or B650 Chipset, allows to FlashBios in Standby PSU "Turned-Off, No CPU." </br>

AMD has 1x USB-C 3.2 Gen 2x2 "20Gbps" </br>
intel has Optical Toslink Audio Output.  </br>

