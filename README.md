# intel vs. amd | z790 vs. x670e

intel </br>
ASRock Z790 LiveMixer </br>
vs. </br>
AMD </br>
ASRock X670E PG Lightning </br>

features wise... almost the same </br>
Cardboard box is better in Z790 LiveMixer, </br>
X670E Box is "economic" type. </br>
but both have same foam, similar manual, and accesories SATA cable and M.2 screws. </br>

According to ASRock the B650 LiveMixer is the AMD equivalent, </br>
but... does Not have [X670E "Dual" Chipset](https://www.digitalcitizen.life/x670e-x670-b650e-b650-chipsets/), does Not have 1x PCIe x1 </br>
has B650 Non-E = does Not have PCIe v5 support. </br>

[B650 LiveMixer](https://www.asrock.com/mb/AMD/B650%20LiveMixer/Specification.us.asp#Specification) has 3x PCIe v4 x16, electrically: x16 x4 x4. </br>
[X670E PG Lightning](https://pg.asrock.com/MB/AMD/X670E%20PG%20Lightning/index.asp) has 1x PCIe v5 x16 | 2x PCIe v4 x16 electrical: x4 x1 + 1x PCIe x1. </br>
[Z790 LiveMixer](https://www.asrock.com/mb/Intel/Z790%20LiveMixer/Specification.asp) has 1x PCIe v5 x16 | 2x PCIe v4 x16 electrical: x4 x4 + 1x PCIe x1. 

B650 LiveMixer has 2x SATA-III 6Gbps </br>
X670E has 4x SATA-III 6Gbps + 1x 20 Gbps USB-C 3.2 Gen2x2 </br>

For Booting Linux external using USB-C 3.2 2x2 is faster on X670E </br>
requires a 20G USB 3 or 40G USB 4 [Orinco M.2 NVMe & SATA SSD Drive Enclosure](https://www.orico.cc/us/product/subcategory/115.html) </br>
booting external using Thunderbolt chassis + eGPU + M.2 to PCIe x4 card is another option. </br>

there is No 100% equivalent on AMD of the intel Z790 LiveMixer, </br>
X670E PG Lightning vs. B650 LiveMixer </br>
you win some, you lose some, depends on your needs. </br>

for example:</br>
does [Thunderbolt 4 AIC PCIe x4 card](https://www.asrock.com/mb/spec/product.asp?Model=Thunderbolt%204%20AIC) work in x1 electric PCIe v4 slot? </br>
TB4 has a maximum thoughput of 40 Gb/s but... thats Not always used, Not in my case. </br>
im Not using all features of Thunderbolt 4 </br>

Razer Core X Chroma [eGPU](https://egpu.io/best-egpu-buyers-guide/) chassis is PCIe v3, and Thunderbolt3. </br>
PCIe v4 x1 has a thoughput of [2GB/s](https://en.wikipedia.org/wiki/PCI_Express#Comparison_table) "16 Gbit/s" </br>
PCIe v3 x2 has same. </br>
PCIe v2 x4 same. </br>
Thunderbolt3 has maximum througput of 40 Gbit/s (5 GB/s). </br>

Avid HDX PCIe card requires PCIe v2 x4 = 16 Gbits/s (2 GB/s) </br>
works on Macmini 2014 [Thunderbot 2](https://en.wikipedia.org/wiki/Thunderbolt_(interface)#Thunderbolt_2) at 20 Gbit/s ("2.5GB/s") </br>
physical level, Thunderbolt 1 & 2 bandwidth are identical. </br>
TB 1 cabling is compatible with TB 2 interfaces </br>
TB 2 has channel aggregation, 2x TB1 10 Gbit/s channels combined on 1x 20 Gbit/s channel. </br>

Sonnet 10G Solo "10Gbit/s = 1.25GB/s = 1250MB/s" PCIe SFP+ FiberOptic Network adapter </br>
ASUS XG-C100F 10G SFP+ Network adapter or similar </br>
requires PCIe v2 x4 ("2GB/s / 16Gbit/s") </br>

Other differences: </br>

X670E PG Lightning CPU Power connector is 8+4 in AMD, 
Z790 LiveMixer is 8+8 intel </br>
B650 LiveMixer is 8+8 AMD. </br>

is 8+4 enough for AMD 16-core 9950x or 7950x 170w ? </br>
or will happens similar to Nvidia 4090 connector? </br>

Z790 LiveMixer has 4x SATA-III 6Gbps connectors in 1x large connector, </br>
X670E PG Lightning has 4x SATA-III 6Gbps connectors separated in pairs. </br>
B650 LiveMixer only has 2x SATA-III 6Gbps connectors. </br>

same features: </br>
TBT Thunderbolt4 header. </br>
1x PCIe v5 x16 shared with M.2 PCIe v5 x4 slot 1, using a switch. </br>
1x PCIe v4 connector x1 electrical </br>
2x PCIe v4 connector x4 x4 electrical or x4 x1 </br>
4x DDR5 DIMM Slots. </br>
HDMI out </br>
DisplayPort 1.4 out. </br>
same Hardware monitor: SIO NCT6796D </br>
same HDAudio: ALC897 </br>
2x USB-A Low Latency "Lightning Gaming" [Ports](https://www.asrock.com/microsite/2021EmbraceTheFuture/single-post3.html) </br> 
8-Layer PCB. </br>
14-Vcore Phases + 2 SOC Phases + 1 VDO Misc Phase on AMD, 14-Phases on intel</br>
2.5GbE Realtek LAN. </br>

WQHD monitors like LG 34GP63 are: 3440x1440 x160fps </br>
160fps requires DisplayPort 1.4 or better, </br>
HDMI is limited to 50fps. </br>

intel or AMD iGPU does Not play 3D games at 3440x1440 x 160fps, </br>
AMD most powerful iGPU is the 8700G CPU. </br>

FlashRom is connected directly to CPU on intel board, requires CPU to flash Bios. </br>
FlashRom is connected to X670E Chipset, allows to FlashBios in Standby mode "Turned-Off, No CPU." </br>

AMD has 1x USB-C 3.2 Gen 2x2 "20Gbps" </br>
intel has Optical Toslink Audio Output.  </br>

