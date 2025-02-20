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
has [B650 Non-E](https://www.digitalcitizen.life/x670e-x670-b650e-b650-chipsets/) does Not have x16 PCIe v5 support, but has M.2 x4 PCIe v5. </br>
according to Block Diagram, PCIe v5 support comes from the CPU, Not the Chipset. </br>

[B650 LiveMixer](https://www.asrock.com/mb/AMD/B650%20LiveMixer/Specification.us.asp#Specification) has 3x PCIe v4 x16, electrically: x16 x4 x4. </br>
[X670E PG Lightning](https://pg.asrock.com/MB/AMD/X670E%20PG%20Lightning/index.asp) has 1x PCIe v5 x16 | 2x PCIe v4 x16 electrical: x4 x1 + 1x PCIe x1. </br>
[Z790 LiveMixer](https://www.asrock.com/mb/Intel/Z790%20LiveMixer/Specification.asp) has 1x PCIe v5 x16 | 2x PCIe v4 x16 electrical: x4 x4 + 1x PCIe x1. 

B650 LiveMixer has 2x SATA-III 6Gbps </br>
X670E & Z790 have 4x SATA-III 6Gbps </br>
X670E has 1x 20 Gbps [USB-C 3.2 Gen2x2](https://en.wikipedia.org/wiki/USB_3.0#USB_3.2) </br>
B650 has 1x Front Panel USB-C 3.2 Gen2x2 Header, requires a special connector / case, Not included. </br>
there are PCIe Brackets $20usd. to $50usd. depending on cable lenght. </br>

For Booting Linux on external USB-C 3.2 2x2 is faster on X670E </br>
requires a 20G USB 3.2 or 40G USB 4.0 [Orinco M.2 NVMe & SATA SSD Drive Enclosure](https://www.orico.cc/us/product/subcategory/115.html) or similar enclosure, </br>
booting using Thunderbolt chassis + eGPU + M.2 to PCIe x4 card is another option. </br>

There is No 100% equivalent on AMD of the intel Z790 LiveMixer, </br>
X670E PG Lightning vs. B650 LiveMixer </br>
you win some, you lose some, depends on your needs. </br>

for example:</br>
does [Thunderbolt 4 AIC PCIe x4 card](https://www.asrock.com/mb/spec/product.asp?Model=Thunderbolt%204%20AIC) work in x1 electric PCIe v4 slot? </br>
TB4 has a maximum thoughput of 40 Gb/s but... thats Not always used, Not in my case. </br>
im Not using all features / bandwith of Thunderbolt 4 </br>

Razer Core X Chroma [eGPU](https://egpu.io/best-egpu-buyers-guide/) chassis is PCIe v3, and Thunderbolt3. </br>
Thunderbolt3 has maximum througput of 40 Gbit/s (5 GB/s = 5000 MB/s). </br>
PCIe v4 x1 has a thoughput of [2GB/s](https://en.wikipedia.org/wiki/PCI_Express#Comparison_table) "16 Gbit/s = 2000 MB/s" </br>
PCIe v3 x2 same. </br>
PCIe v2 x4 same. </br>

Avid HDX PCIe card requires PCIe v2 x4 = 16 Gbits/s (2 GB/s = 2000 MB/s) </br>
works on Macmini 2014 [Thunderbot 2](https://en.wikipedia.org/wiki/Thunderbolt_(interface)#Thunderbolt_2) at 20 Gbit/s ("2.5GB/s") </br>
physical level: Thunderbolt 1 & 2 bandwidth are identical. </br>
TB 1 cabling is compatible with TB 2 interfaces </br>
TB 2 has channel aggregation, 2x TB1 10 Gbit/s channels combined in 1x 20 Gbit/s channel. </br>

Sonnet 10G Solo "10Gbit/s = 1.25GB/s = 1250 MB/s" PCIe SFP+ FiberOptic Network adapter </br>
ASUS XG-C100F 10G SFP+ Network adapter or similar </br>
requires PCIe v2 x4 ("2GB/s / 16Gbit/s / 2000 MB/s") = PCIe v3 x2 = PCIe v4 x1. </br>

but cards do Not support PCIe v4 x1 only PCIe v2 maybe v3, </br>
if cards supports v3 x1 probably will run at 1GB/s = 1000MB/s, Not a big loss for SFP+ 10G </br>

Other differences: </br>

X670E PG Lightning CPU Power connector is 8+4  
Z790 LiveMixer is 8+8 </br>
B650 LiveMixer is 8+8 </br>

¿ is 8+4 enough for AMD 16-core 9950x or 7950x 170w ? </br>
or will happens similar to Nvidia 4090 connector? </br>

Z790 LiveMixer has 4x SATA-III 6Gbps connectors in 1x large connector, </br>
X670E PG Lightning has 4x SATA-III 6Gbps connectors separated in pairs. </br>
B650 LiveMixer has 2x SATA-III 6Gbps connectors. </br>

same: </br>
TBT Thunderbolt4 header. </br>
1x PCIe v5 x16 shared with M.2 PCIe v5 x4 slot 1, using a switch in Z790 and X670E. </br>
1x PCIe v4 connector x1 electrical, Not available in B650 LiveMixer </br>
2x PCIe v4 connector x4 x4 electrical or x4 x1 in X670E PG Lightning </br>
4x DDR5 DIMM Slots. </br>
HDMI out </br>
DisplayPort 1.4 out. </br>
Hardware monitor: SIO NCT6796D </br>
HDAudio: ALC897 </br>
2x USB-A Low Latency "Lightning Gaming" [Ports](https://www.asrock.com/microsite/2021EmbraceTheFuture/single-post3.html) </br> 
8-Layer PCB. </br>
14-Vcore Phases + 2 SOC Phases + 1 VDO Misc Phase on AMD, 14-Phases on intel</br>
2.5GbE Realtek LAN, RTL8125BG. </br>

WQHD monitors like LG 34GP63 are: 3440x1440 x160fps </br>
160fps requires DisplayPort 1.4 or better, </br>
HDMI is limited to 50fps. </br>

intel or AMD iGPU does Not play 3D games at 3440x1440 x 160fps, </br>
AMD most powerful iGPU is the 8700G CPU. </br>

FlashRom is connected directly to CPU on intel board, requires CPU to flash Bios. </br>
FlashRom is connected to X670E or B650 Chipset, allows to FlashBios in Standby PSU "Turned-Off, No CPU." </br>

AMD has 1x USB-C 3.2 Gen 2x2 "20Gbps" </br>
intel has Optical Toslink Audio Output.  </br>

