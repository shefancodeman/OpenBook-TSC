# TSC Openbook
 Un eBook reader format din PCB, carcasa, baterie si display, creat in AutoDesk Fusion. Fiecare component e asezat pe pcb pentru a intra corespunzator in carcasa.  
PCB-ul include:
Battery Charge Level
E-Paper Display Header
E-Paper Drive Circuit
Environmental Sensor BME688
EPD Power
ESP32 C6
External NOR Flash 64MB
LDO Voltage Regulator
Li-Po Battery Charging Controller
Qwiic / Stemma QT
RTC Module DS3231SN
SD Card
SPI ESD Protection Lines
Test Pads
USB C connector & ESD protection
Voltage Supervisor + Reset & Boot / IO Button

## BOM
| Component                     | Websites                                                                                                   | Datasheet                                                                                                    |
|-------------------------------|------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|
| ESP32-C6-WROOM-1-N8           | [Mouser](https://eu.mouser.com/ProductDetail/Espressif-Systems/ESP32-C6-WROOM-1U-N8?qs=1Kr7Jg1SGW%2FzPU4G%252ByMwkA%3D%3D) | [Datasheet](https://eu.mouser.com/datasheet/2/891/Espressif_Systems_7_11_2023_esp32_c6_wroom_1_wroom-3236277.pdf) |
| USB4110-GF-A                  | [Mouser](https://eu.mouser.com/ProductDetail/Same-Sky/UJC-H-G-SMT-2-P6-TR?qs=IKkN%2F947nfApFV8T6rOqww%3D%3D) | [Datasheet](https://eu.mouser.com/datasheet/2/1628/ujc_h_g_smt_2_p6_tr-3511211.pdf)                          |
| USBLC6-2SC6Y                  | [Mouser](https://eu.mouser.com/ProductDetail/STMicroelectronics/USBLC6-2SC6Y?qs=gNDSiZmRJS%2FOgDexvXkdow%3D%3D) | [Datasheet](https://eu.mouser.com/datasheet/2/389/usblc6_2sc6y-1852505.pdf)                                   |
| DMG2305UX-7                   | [Mouser](https://eu.mouser.com/ProductDetail/Diodes-Incorporated/DMG2305UX-7?qs=L1DZKBg7t5F%2FNBHrjfxC%252Bg%3D%3D) | [Datasheet](https://www.diodes.com/assets/Datasheets/DMG2305UX.pdf)                                           |
| SD0805S020S1R0                | [Mouser](https://eu.mouser.com/ProductDetail/KYOCERA-AVX/SD0805S020S1R0?qs=jCA%252BPfw4LHbpkAoSnwrdjw%3D%3D) | [Datasheet](https://eu.mouser.com/datasheet/2/40/schottky-3165252.pdf)                                       |
| XC6220A331MR-G                | [Mouser](https://eu.mouser.com/ProductDetail/Torex-Semiconductor/XC6220A331MR-G?qs=AsjdqWjXhJ8ZSWznL1J0gg%3D%3D) | [Datasheet](https://eu.mouser.com/datasheet/2/760/xc6220-3371556.pdf)                                         |
| 293D107X9010D2TE3             | [Mouser](https://eu.mouser.com/ProductDetail/Vishay-Sprague/293D107X9010D2TE3?qs=8dfOI6wKXonVqFgS8%252BQ%2FMA%3D%3D) | [Datasheet](https://www.vishay.com/docs/40002/293d.pdf)                                                       |
| IFDC5050JZER680M              | [Mouser](https://eu.mouser.com/ProductDetail/Vishay-Dale/IFDC5050JZER680M?qs=iLKYxzqNS745SePZd8tBoA%3D%3D) | [Datasheet](https://www.vishay.com/docs/34635/ifdc5050jz.pdf)                                                |
| MBR0530-TP                    | [Mouser](https://eu.mouser.com/ProductDetail/Micro-Commercial-Components-MCC/MBR0530-TP?qs=KFo7JewZbUECRHkxGanrdg%3D%3D) | [Datasheet](https://eu.mouser.com/datasheet/2/258/MBR0520_MBR0580_SOD123_-2492194.pdf)                      |
| SI1308EDL-T1-GE3              | [Mouser](https://eu.mouser.com/ProductDetail/Vishay-Semiconductors/SI1308EDL-T1-GE3?qs=bX1%252BNvsK%2FBramh9tgpOaEw%3D%3D) | [Datasheet](https://www.vishay.com/docs/63399/si1308edl.pdf)                                                |
| KGF21BR71H104KT               | [Mouser](https://eu.mouser.com/ProductDetail/KYOCERA-AVX/KGF21BR71H104KT?qs=Jm2GQyTW%2FbjYyKCvVWAEOw%3D%3D) | [Datasheet](https://eu.mouser.com/datasheet/2/40/KGF-3223650.pdf)                                            |
| MAASL105CC7105MFCA01          | [Mouser](https://eu.mouser.com/ProductDetail/TAIYO-YUDEN/MAASL105CC7105MFCA01?qs=HFfMDpzxxd1Fn%2FInbJA7vw%3D%3D) | [Datasheet](https://eu.mouser.com/datasheet/2/396/TAIYO_YUDEN_04_27_2024_c_mlcc_A_e1-3451516.pdf)           |
| CM05X5R475M16AH               | [Mouser](https://eu.mouser.com/ProductDetail/KYOCERA-AVX/CM05X5R475M16AH?qs=doiCPypUmgFT1xquZKhWtQ%3D%3D) | [Datasheet](https://eu.mouser.com/datasheet/2/40/Kyocera_AVX_Components_CM025_CM05_CM105_CM21_E217K-2932876.pdf) |
| CGA3EDX7T1A106M080AU          | [Mouser](https://eu.mouser.com/ProductDetail/TDK/CGA3EDX7T1A106M080AU?qs=ZcfC38r4PovL%2FBNBUzzBFw%3D%3D) | [Datasheet](https://product.tdk.com/system/files/dam/doc/product/capacitor/ceramic/mlcc/catalog/mlcc_automotive_general_en.pdf) |
| KAM21BR71H104JT               | [Mouser](https://eu.mouser.com/ProductDetail/KYOCERA-AVX/KAM21BR71H104JT?qs=Jm2GQyTW%2Fbic6Zk4McEt6w%3D%3D) | [Datasheet](https://eu.mouser.com/datasheet/2/40/AutoMLCCKAM-3216307.pdf)                                    |
| RNCL1210FT50L0                | [Mouser](https://eu.mouser.com/ProductDetail/SEI-Stackpole/RNCL1210FT50L0?qs=17ckDYBRdelVLOJ%252BDFjlUw%3D%3D) | [Datasheet](https://eu.mouser.com/datasheet/2/385/sei_rncl-3223524.pdf)                                      |
| RT1206FRE072R2L               | [Mouser](https://eu.mouser.com/ProductDetail/YAGEO/RT1206FRE072R2L?qs=XhSZopxZ3H6S0nYZD83pAA%3D%3D) | [Datasheet](https://eu.mouser.com/datasheet/2/447/PYu_RT_1_to_0_01_RoHS_L_15-3461507.pdf)                    |
| ERA-6AHD150V                  | [Mouser](https://eu.mouser.com/ProductDetail/Panasonic/ERA-6AHD150V?qs=MNPzkKEzRtQip8ZeekU%252BRw%3D%3D) | [Datasheet](https://industrial.panasonic.com/cdbs/www-data/pdf/RDM0000/AOA0000C307.pdf)                     |
| RP73C2B200RFTDF               | [Mouser](https://eu.mouser.com/ProductDetail/TE-Connectivity-Holsworthy/RP73C2B200RFTDF?qs=n4i9pByFsMR0dWGpf721CA%3D%3D) | [Datasheet](https://eu.mouser.com/datasheet/2/418/10/ENG_DS_1773272_M1-1588495.pdf)                          |
| ERA-3AED202V                  | [Mouser](https://eu.mouser.com/ProductDetail/Panasonic/ERA-3AED202V?qs=yocZuyCaXdM2cBmjcGkIyA%3D%3D) | [Datasheet](https://industrial.panasonic.com/cdbs/www-data/pdf/RDM0000/AOA0000C307.pdf)                     |
| MCS04020C5101FE000            | [Mouser](https://eu.mouser.com/ProductDetail/Vishay-Beyschlag/MCS04020C5101FE000?qs=wTZ%2FFzl837YsKPLPRIXUbg%3D%3D) | [Datasheet](https://www.vishay.com/docs/28705/mcx0x0xpro.pdf)                                               |
| RNWA0612BTE10K0               | [Mouser](https://eu.mouser.com/ProductDetail/SEI-Stackpole/RNWA0612BTE10K0?qs=IKkN%2F947nfD62pDKWE9ZTQ%3D%3D) | [Datasheet](https://eu.mouser.com/datasheet/2/385/SEI_RNWA-3473840.pdf)                                      |
| ERA-3AED104V                  | [Mouser](https://eu.mouser.com/ProductDetail/Panasonic/ERA-3AED104V?qs=MNPzkKEzRtQIWcmUWL4kjg%3D%3D) | [Datasheet](https://industrial.panasonic.com/cdbs/www-data/pdf/RDM0000/AOA0000C307.pdf)                     |
| MCP73831-2ACI-MC              | [Mouser](https://eu.mouser.com/ProductDetail/Microchip-Technology/MCP73831-2ACI-MC?qs=hH%252BOa0VZEiBneYTVdpuVdg%3D%3D) | [Datasheet](https://eu.mouser.com/datasheet/2/268/MCP73831_Family_Data_Sheet_DS20001984H-3441711.pdf)       |
| FH34SRJ-24S-0.5SH(99)         | [Mouser](https://eu.mouser.com/ProductDetail/Hirose-Connector/FH34SRJ-24S-0.5SH99?qs=vcbW%252B4%252BSTIpKBl5ap9J8Fw%3D%3D) | [Datasheet](https://eu.mouser.com/datasheet/2/185/FH34SRJ_24S_0_5SH_99__CL0580_1255_6_99_2DDrawing_0-1615044.pdf) |
| BME688                        | [Mouser](https://eu.mouser.com/ProductDetail/Bosch-Sensortec/BME688?qs=IS%252B4QmGtzzqQoVDscqwx3A%3D%3D) | [Datasheet](https://eu.mouser.com/datasheet/2/783/bst_bme688_fl000-2307034.pdf)                              |
| BD5229G-TR                    | [Mouser](https://eu.mouser.com/ProductDetail/ROHM-Semiconductor/BD5229G-TR?qs=4kLU8WoGk0vvnhrrYwdszw%3D%3D) | [Datasheet](https://fscdn.rohm.com/en/products/databook/datasheet/ic/power/voltage_detector/bd52xxg-e.pdf)  |
| MAX17048G+T10                 | [Mouser](https://eu.mouser.com/ProductDetail/Analog-Devices-Maxim-Integrated/MAX17048G%2bT10?qs=D7PJwyCwLAoGnnn8jEPRBQ%3D%3D) | [Datasheet](https://eu.mouser.com/datasheet/2/609/MAX17048_MAX17049-3469099.pdf)                             |
| DS3231SN#                     | [Mouser](https://eu.mouser.com/ProductDetail/Analog-Devices-Maxim-Integrated/DS3231SN?qs=1eQvB6Dk1vhUlr8%2FOrV0Fw%3D%3D) | [Datasheet](https://eu.mouser.com/datasheet/2/609/DS3231-3421123.pdf)                                        |
| CPH3225A                      | [Mouser](https://eu.mouser.com/ProductDetail/Seiko-Semiconductors/CPH3225A?qs=3etwrb1wR%252BhUOph6lAO7eg%3D%3D) | [Datasheet](https://eu.mouser.com/datasheet/2/360/Seiko_Instruments_MicroBattery_E_20230330_2024Jan_-3561061.pdf) |
| PRT-14417                     | [Mouser](https://eu.mouser.com/ProductDetail/Adafruit/4208?qs=PzGy0jfpSMtbScLbr0L5dw%3D%3D) | [Datasheet](https://learn.adafruit.com/introducing-adafruit-stemma-qt/technical-specs)                      |
| PGB1010603MR                  | [Mouser](https://eu.mouser.com/ProductDetail/Littelfuse/PGB1010603MR?qs=gu7KAQ731URLg4GSnNNN7Q%3D%3D) | [Datasheet](https://www.littelfuse.com/assetdocs/pulseguard-esd-suppressors-pgb1-datasheet?assetguid=8a337998-d54d-466b-be4e-dc5bcd1f9321) |
| W25Q512JVEIQ                  | [Mouser](https://eu.mouser.com/ProductDetail/Winbond/W25Q512JVEIQ?qs=l7cgNqFNU1jw6svr3at6tA%3D%3D) | [Datasheet](https://eu.mouser.com/datasheet/2/949/Winbond_W25Q512JV_Datasheet-3240039.pdf)                   |
| MT-DEPG0750BNU590F1           | [Mouser](https://eu.mouser.com/ProductDetail/Microtips-Technology/MT-DEPG0750BNU590F1?qs=DPoM0jnrROVRMMTX0WzK%252Bw%3D%3D) | [Datasheet](https://eu.mouser.com/datasheet/2/271/MT_DEPG0750BNU590F1_V2_7-1894282.pdf)                     |
| 112A-TAAR-R03                 | [Comet](https://store.comet.srl.ro/Catalogue/Product/43497/)                                               | [Datasheet](https://store.comet.bg/download-file.php?id=27596)                                                |
| LP584174                      | [TME](https://www.tme.eu/en/details/accu-lp584174_cl/rechargeable-batteries/cellevia-batteries/l584174/) | [Datasheet](https://www.tme.eu/Document/e0683d8c34e6d878124489f71bffb6ee/cel0014.pdf)                        |
