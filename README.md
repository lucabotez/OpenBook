Botez Luca, 334CA

# OpenBook

## About
This project is a minimalist eBook Reader called OpenBook, built on the ESP32-C6 platform and equipped with a 7.5-inch e-paper display, a Li-Po battery, USB-C charging, and physical control buttons.

The device is designed to be energy-efficient and easy to use, featuring a simple interface controlled via GPIOs, with text display functions aimed at providing an optimal e-reading experience.

## Block Diagram

## BOM (Bill of Materials)

| Component | Purchase Link | Datasheet |
|-----------|---------------|-----------|
| BOOT_BUTTON | [https://ro.mouser.com/ProductDetail/Panasonic/EVQ-P7L01P](https://ro.mouser.com/ProductDetail/Panasonic/EVQ-P7L01P?qs=rJ%252BziJWpyszWhhNszc02jQ%3D%3D&_gl=1*xzqk3l*_ga*dW5kZWZpbmVk*_ga_15W4STQT4T*dW5kZWZpbmVk*_ga_1KQLCYKRX3*dW5kZWZpbmVk) | https://componentsearchengine.com/Datasheets/2/EVQP7L01P.pdf |
| C1 | [https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106](https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106?qs=zEY9bCHj09eCmUJdZuS5Lg%3D%3D) | https://componentsearchengine.com/Datasheets/2/CC0402MRX5R5BB106.pdf |
| C1_BAT | [https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106](https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106?qs=zEY9bCHj09eCmUJdZuS5Lg%3D%3D) | https://componentsearchengine.com/Datasheets/2/CC0402MRX5R5BB106.pdf |
| C1_BAT2 | [https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106](https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106?qs=zEY9bCHj09eCmUJdZuS5Lg%3D%3D) | https://componentsearchengine.com/Datasheets/2/CC0402MRX5R5BB106.pdf |
| C2 | [https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106](https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106?qs=zEY9bCHj09eCmUJdZuS5Lg%3D%3D) | https://componentsearchengine.com/Datasheets/2/CC0402MRX5R5BB106.pdf |
| C2_BAT | [https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106](https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106?qs=zEY9bCHj09eCmUJdZuS5Lg%3D%3D) | https://componentsearchengine.com/Datasheets/2/CC0402MRX5R5BB106.pdf |
| C3 | [https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106](https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106?qs=zEY9bCHj09eCmUJdZuS5Lg%3D%3D) | https://componentsearchengine.com/Datasheets/2/CC0402MRX5R5BB106.pdf |
| C4 | [https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106](https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106?qs=zEY9bCHj09eCmUJdZuS5Lg%3D%3D) | https://componentsearchengine.com/Datasheets/2/CC0402MRX5R5BB106.pdf |
| C4_USB | [https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106](https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106?qs=zEY9bCHj09eCmUJdZuS5Lg%3D%3D) | https://componentsearchengine.com/Datasheets/2/CC0402MRX5R5BB106.pdf |
| C5 | [https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106](https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106?qs=zEY9bCHj09eCmUJdZuS5Lg%3D%3D) | https://componentsearchengine.com/Datasheets/2/CC0402MRX5R5BB106.pdf |
| C5_USB | [https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106](https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106?qs=zEY9bCHj09eCmUJdZuS5Lg%3D%3D) | https://componentsearchengine.com/Datasheets/2/CC0402MRX5R5BB106.pdf |
| C6 | [https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106](https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106?qs=zEY9bCHj09eCmUJdZuS5Lg%3D%3D) | https://componentsearchengine.com/Datasheets/2/CC0402MRX5R5BB106.pdf |
| C7 | [https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106](https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106?qs=zEY9bCHj09eCmUJdZuS5Lg%3D%3D) | https://componentsearchengine.com/Datasheets/2/CC0402MRX5R5BB106.pdf |
| C8 | [https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106](https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106?qs=zEY9bCHj09eCmUJdZuS5Lg%3D%3D) | https://componentsearchengine.com/Datasheets/2/CC0402MRX5R5BB106.pdf |
| C9 | [https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106](https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106?qs=zEY9bCHj09eCmUJdZuS5Lg%3D%3D) | https://componentsearchengine.com/Datasheets/2/CC0402MRX5R5BB106.pdf |
| C10 | [https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106](https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106?qs=zEY9bCHj09eCmUJdZuS5Lg%3D%3D) | https://componentsearchengine.com/Datasheets/2/CC0402MRX5R5BB106.pdf |
| C10_SUPERCAP | [https://ro.mouser.com/ProductDetail/Seiko-Semiconductors/CPH3225A](https://ro.mouser.com/ProductDetail/Seiko-Semiconductors/CPH3225A?qs=3etwrb1wR%252BhUOph6lAO7eg%3D%3D) | https://ro.mouser.com/datasheet/2/360/Seiko_Instruments_MicroBattery_E_20230330_2024Jan_-3561061.pdf |
| CHANGE_BUTTON | [https://ro.mouser.com/ProductDetail/Panasonic/EVQ-P7L01P](https://ro.mouser.com/ProductDetail/Panasonic/EVQ-P7L01P?qs=rJ%252BziJWpyszWhhNszc02jQ%3D%3D&_gl=1*xzqk3l*_ga*dW5kZWZpbmVk*_ga_15W4STQT4T*dW5kZWZpbmVk*_ga_1KQLCYKRX3*dW5kZWZpbmVk) | https://componentsearchengine.com/Datasheets/2/EVQP7L01P.pdf |
| C_DELAY | [https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106](https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106?qs=zEY9bCHj09eCmUJdZuS5Lg%3D%3D) | https://componentsearchengine.com/Datasheets/2/CC0402MRX5R5BB106.pdf |
| D1 | [https://ro.mouser.com/ProductDetail/STMicroelectronics/USBLC6-2SC6Y](https://ro.mouser.com/ProductDetail/STMicroelectronics/USBLC6-2SC6Y?qs=gNDSiZmRJS%2FOgDexvXkdow%3D%3D) | https://ro.mouser.com/datasheet/2/389/usblc6_2sc6y-1852505.pdf |
| D2 | [https://ro.mouser.com/ProductDetail/KYOCERA-AVX/SD0805S020S1R0](https://ro.mouser.com/ProductDetail/KYOCERA-AVX/SD0805S020S1R0?qs=jCA%252BPfw4LHbpkAoSnwrdjw%3D%3D) | https://ro.mouser.com/datasheet/2/40/schottky-3165252.pdf |
| D3 | [https://ro.mouser.com/ProductDetail/Vishay-Semiconductors/MBR0530](https://ro.mouser.com/ProductDetail/Vishay-Semiconductors/MBR0530?qs=HoksaeI1MJOP4GvpzMgEDg%3D%3D) | https://www.onsemi.com/pdf/datasheet/mbr0530-d.pdf |
| D4 | [https://ro.mouser.com/ProductDetail/Vishay-Semiconductors/MBR0530](https://ro.mouser.com/ProductDetail/Vishay-Semiconductors/MBR0530?qs=HoksaeI1MJOP4GvpzMgEDg%3D%3D) | https://www.onsemi.com/pdf/datasheet/mbr0530-d.pdf |
| D5 | [https://ro.mouser.com/ProductDetail/Vishay-Semiconductors/MBR0530](https://ro.mouser.com/ProductDetail/Vishay-Semiconductors/MBR0530?qs=HoksaeI1MJOP4GvpzMgEDg%3D%3D) | https://www.onsemi.com/pdf/datasheet/mbr0530-d.pdf |
| D6 | [https://ro.mouser.com/ProductDetail/Littelfuse/PGB1010603MR](https://ro.mouser.com/ProductDetail/Littelfuse/PGB1010603MR?qs=gu7KAQ731URLg4GSnNNN7Q%3D%3D) | https://www.littelfuse.com/assetdocs/pulseguard-esd-suppressors-pgb1-datasheet?assetguid=8a337998-d54d-466b-be4e-dc5bcd1f9321 |
| D7 | [https://ro.mouser.com/ProductDetail/KYOCERA-AVX/SD0805S020S1R0](https://ro.mouser.com/ProductDetail/KYOCERA-AVX/SD0805S020S1R0?qs=jCA%252BPfw4LHbpkAoSnwrdjw%3D%3D) | https://ro.mouser.com/datasheet/2/40/schottky-3165252.pdf |
| D8 | [https://ro.mouser.com/ProductDetail/Littelfuse/PGB1010603MR](https://ro.mouser.com/ProductDetail/Littelfuse/PGB1010603MR?qs=gu7KAQ731URLg4GSnNNN7Q%3D%3D) | https://www.littelfuse.com/assetdocs/pulseguard-esd-suppressors-pgb1-datasheet?assetguid=8a337998-d54d-466b-be4e-dc5bcd1f9321 |
| D9 | [https://ro.mouser.com/ProductDetail/Littelfuse/PGB1010603MR](https://ro.mouser.com/ProductDetail/Littelfuse/PGB1010603MR?qs=gu7KAQ731URLg4GSnNNN7Q%3D%3D) | https://www.littelfuse.com/assetdocs/pulseguard-esd-suppressors-pgb1-datasheet?assetguid=8a337998-d54d-466b-be4e-dc5bcd1f9321 |
| D10 | [https://ro.mouser.com/ProductDetail/Littelfuse/PGB1010603MR](https://ro.mouser.com/ProductDetail/Littelfuse/PGB1010603MR?qs=gu7KAQ731URLg4GSnNNN7Q%3D%3D) | https://www.littelfuse.com/assetdocs/pulseguard-esd-suppressors-pgb1-datasheet?assetguid=8a337998-d54d-466b-be4e-dc5bcd1f9321 |
| D11 | [https://ro.mouser.com/ProductDetail/Littelfuse/PGB1010603MR](https://ro.mouser.com/ProductDetail/Littelfuse/PGB1010603MR?qs=gu7KAQ731URLg4GSnNNN7Q%3D%3D) | https://www.littelfuse.com/assetdocs/pulseguard-esd-suppressors-pgb1-datasheet?assetguid=8a337998-d54d-466b-be4e-dc5bcd1f9321 |
| D12 | [https://ro.mouser.com/ProductDetail/Littelfuse/PGB1010603MR](https://ro.mouser.com/ProductDetail/Littelfuse/PGB1010603MR?qs=gu7KAQ731URLg4GSnNNN7Q%3D%3D) | https://www.littelfuse.com/assetdocs/pulseguard-esd-suppressors-pgb1-datasheet?assetguid=8a337998-d54d-466b-be4e-dc5bcd1f9321 |
| EPD_C1 | [https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106](https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106?qs=zEY9bCHj09eCmUJdZuS5Lg%3D%3D) | https://componentsearchengine.com/Datasheets/2/CC0402MRX5R5BB106.pdf |
| EPD_C2 | [https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106](https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106?qs=zEY9bCHj09eCmUJdZuS5Lg%3D%3D) | https://componentsearchengine.com/Datasheets/2/CC0402MRX5R5BB106.pdf |
| EPD_C3 | [https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106](https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106?qs=zEY9bCHj09eCmUJdZuS5Lg%3D%3D) | https://componentsearchengine.com/Datasheets/2/CC0402MRX5R5BB106.pdf |
| EPD_C4 | [https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106](https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106?qs=zEY9bCHj09eCmUJdZuS5Lg%3D%3D) | https://componentsearchengine.com/Datasheets/2/CC0402MRX5R5BB106.pdf |
| EPD_C5 | [https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106](https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106?qs=zEY9bCHj09eCmUJdZuS5Lg%3D%3D) | https://componentsearchengine.com/Datasheets/2/CC0402MRX5R5BB106.pdf |
| EPD_C6 | [https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106](https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106?qs=zEY9bCHj09eCmUJdZuS5Lg%3D%3D) | https://componentsearchengine.com/Datasheets/2/CC0402MRX5R5BB106.pdf |
| EPD_C7 | [https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106](https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106?qs=zEY9bCHj09eCmUJdZuS5Lg%3D%3D) | https://componentsearchengine.com/Datasheets/2/CC0402MRX5R5BB106.pdf |
| EPD_C8 | [https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106](https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106?qs=zEY9bCHj09eCmUJdZuS5Lg%3D%3D) | https://componentsearchengine.com/Datasheets/2/CC0402MRX5R5BB106.pdf |
| EPD_C9 | [https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106](https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106?qs=zEY9bCHj09eCmUJdZuS5Lg%3D%3D) | https://componentsearchengine.com/Datasheets/2/CC0402MRX5R5BB106.pdf |
| EPD_C10 | [https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106](https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106?qs=zEY9bCHj09eCmUJdZuS5Lg%3D%3D) | https://componentsearchengine.com/Datasheets/2/CC0402MRX5R5BB106.pdf |
| EPD_C11 | [https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106](https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106?qs=zEY9bCHj09eCmUJdZuS5Lg%3D%3D) | https://componentsearchengine.com/Datasheets/2/CC0402MRX5R5BB106.pdf |
| EPD_C12 | [https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106](https://ro.mouser.com/ProductDetail/YAGEO/CC0402MRX5R5BB106?qs=zEY9bCHj09eCmUJdZuS5Lg%3D%3D) | https://componentsearchengine.com/Datasheets/2/CC0402MRX5R5BB106.pdf |
| IC1 | [https://ro.mouser.com/ProductDetail/ROHM-Semiconductor/BD5229G-TR](https://ro.mouser.com/ProductDetail/ROHM-Semiconductor/BD5229G-TR?qs=4kLU8WoGk0vvnhrrYwdszw%3D%3D) | https://fscdn.rohm.com/en/products/databook/datasheet/ic/power/voltage_detector/bd52xxg-e.pdf |
| IC4 | [https://ro.mouser.com/ProductDetail/Torex-Semiconductor/XC6220A331MR-G](https://ro.mouser.com/ProductDetail/Torex-Semiconductor/XC6220A331MR-G?qs=AsjdqWjXhJ8ZSWznL1J0gg%3D%3D) | https://ro.mouser.com/datasheet/2/760/xc6220-3371556.pdf |
| J1 | [https://ro.mouser.com/ProductDetail/Hirose-Connector/FH34SRJ-24S-0.5SH99](https://ro.mouser.com/ProductDetail/Hirose-Connector/FH34SRJ-24S-0.5SH99?qs=vcbW%252B4%252BSTIpKBl5ap9J8Fw%3D%3D) | https://ro.mouser.com/datasheet/2/185/FH34SRJ_24S_0_5SH_99__CL0580_1255_6_99_2DDrawing_0-1615044.pdf |
| J2 | [https://ro.mouser.com/ProductDetail/GCT/USB4110-GF-A](https://ro.mouser.com/ProductDetail/GCT/USB4110-GF-A?qs=KUoIvG%2F9IlYiZvIXQjyJeA%3D%3D) | https://ro.mouser.com/datasheet/2/837/GCT_USB4110_Product_Drawing___20k_cycles-3455479.pdf |
| J3 | [https://ro.mouser.com/ProductDetail/SparkFun/PRT-14417](https://ro.mouser.com/ProductDetail/SparkFun/PRT-14417?qs=wd5RIQLrsJhgdz%2FpmZ%2F3GQ%3D%3D) | https://ro.mouser.com/datasheet/2/813/Qwiic_Connector_Datasheet-1223982.pdf |
| J4 | https://store.comet.srl.ro/Catalogue/Product/43497/ | https://store.comet.bg/download-file.php?id=8824 |
| L1 | [https://ro.mouser.com/ProductDetail/Wurth-Elektronik/744043680](https://ro.mouser.com/ProductDetail/Wurth-Elektronik/744043680?qs=PGXP4M47uW6VkZq%252BkzjrHA%3D%3D) | https://www.we-online.com/components/products/datasheet/744043680.pdf |
| PFMF.050.1 | [https://ro.mouser.com/ProductDetail/KEMET/VE1812K401R050](https://ro.mouser.com/ProductDetail/KEMET/VE1812K401R050?qs=OycAS1CGnlizCtaoDVbQTA%3D%3D) | https://ro.mouser.com/datasheet/2/447/KEM_V0003_VE-3316901.pdf |
| Q1 | [https://ro.mouser.com/ProductDetail/Diodes-Incorporated/DMG2305UX-7](https://ro.mouser.com/ProductDetail/Diodes-Incorporated/DMG2305UX-7?qs=L1DZKBg7t5F%2FNBHrjfxC%252Bg%3D%3D) | https://www.diodes.com/assets/Datasheets/DMG2305UX.pdf |
| Q2 | [https://ro.mouser.com/ProductDetail/Diodes-Incorporated/DMG2305UX-7](https://ro.mouser.com/ProductDetail/Diodes-Incorporated/DMG2305UX-7?qs=L1DZKBg7t5F%2FNBHrjfxC%252Bg%3D%3D) | https://www.diodes.com/assets/Datasheets/DMG2305UX.pdf |
| Q3 | [https://ro.mouser.com/ProductDetail/Vishay-Semiconductors/SI1308EDL-T1-GE3](https://ro.mouser.com/ProductDetail/Vishay-Semiconductors/SI1308EDL-T1-GE3?qs=bX1%252BNvsK%2FBramh9tgpOaEw%3D%3D) | https://www.vishay.com/docs/63399/si1308edl.pdf |
| R1 | [https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL](https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL?qs=mnq%2FyloZIXzTlUn7JAHSWg%3D%3D) | https://ro.mouser.com/datasheet/2/447/YAGEO_PYu_RC_Group_51_RoHS_L_12-3313492.pdf |
| R1_PINH | [https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL](https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL?qs=mnq%2FyloZIXzTlUn7JAHSWg%3D%3D) | https://ro.mouser.com/datasheet/2/447/YAGEO_PYu_RC_Group_51_RoHS_L_12-3313492.pdf |
| R1_PINH1 | [https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL](https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL?qs=mnq%2FyloZIXzTlUn7JAHSWg%3D%3D) | https://ro.mouser.com/datasheet/2/447/YAGEO_PYu_RC_Group_51_RoHS_L_12-3313492.pdf |
| R1_BAT | [https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL](https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL?qs=mnq%2FyloZIXzTlUn7JAHSWg%3D%3D) | https://ro.mouser.com/datasheet/2/447/YAGEO_PYu_RC_Group_51_RoHS_L_12-3313492.pdf |
| R1_PWRUSB | [https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL](https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL?qs=mnq%2FyloZIXzTlUn7JAHSWg%3D%3D) | https://ro.mouser.com/datasheet/2/447/YAGEO_PYu_RC_Group_51_RoHS_L_12-3313492.pdf |
| R2 | [https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL](https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL?qs=mnq%2FyloZIXzTlUn7JAHSWg%3D%3D) | https://ro.mouser.com/datasheet/2/447/YAGEO_PYu_RC_Group_51_RoHS_L_12-3313492.pdf |
| R2_PINH | [https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL](https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL?qs=mnq%2FyloZIXzTlUn7JAHSWg%3D%3D) | https://ro.mouser.com/datasheet/2/447/YAGEO_PYu_RC_Group_51_RoHS_L_12-3313492.pdf |
| R2_PINH1 | [https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL](https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL?qs=mnq%2FyloZIXzTlUn7JAHSWg%3D%3D) | https://ro.mouser.com/datasheet/2/447/YAGEO_PYu_RC_Group_51_RoHS_L_12-3313492.pdf |
| R2_USB | [https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL](https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL?qs=mnq%2FyloZIXzTlUn7JAHSWg%3D%3D) | https://ro.mouser.com/datasheet/2/447/YAGEO_PYu_RC_Group_51_RoHS_L_12-3313492.pdf |
| R2_USB1 | [https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL](https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL?qs=mnq%2FyloZIXzTlUn7JAHSWg%3D%3D) | https://ro.mouser.com/datasheet/2/447/YAGEO_PYu_RC_Group_51_RoHS_L_12-3313492.pdf |
| R2_BAT | [https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL](https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL?qs=mnq%2FyloZIXzTlUn7JAHSWg%3D%3D) | https://ro.mouser.com/datasheet/2/447/YAGEO_PYu_RC_Group_51_RoHS_L_12-3313492.pdf |
| R3 | [https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL](https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL?qs=mnq%2FyloZIXzTlUn7JAHSWg%3D%3D) | https://ro.mouser.com/datasheet/2/447/YAGEO_PYu_RC_Group_51_RoHS_L_12-3313492.pdf |
| R4 | [https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL](https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL?qs=mnq%2FyloZIXzTlUn7JAHSWg%3D%3D) | https://ro.mouser.com/datasheet/2/447/YAGEO_PYu_RC_Group_51_RoHS_L_12-3313492.pdf |
| R5 | [https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL](https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL?qs=mnq%2FyloZIXzTlUn7JAHSWg%3D%3D) | https://ro.mouser.com/datasheet/2/447/YAGEO_PYu_RC_Group_51_RoHS_L_12-3313492.pdf |
| R6 | [https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL](https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL?qs=mnq%2FyloZIXzTlUn7JAHSWg%3D%3D) | https://ro.mouser.com/datasheet/2/447/YAGEO_PYu_RC_Group_51_RoHS_L_12-3313492.pdf |
| R7 | [https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL](https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL?qs=mnq%2FyloZIXzTlUn7JAHSWg%3D%3D) | https://ro.mouser.com/datasheet/2/447/YAGEO_PYu_RC_Group_51_RoHS_L_12-3313492.pdf |
| R8 | [https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL](https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL?qs=mnq%2FyloZIXzTlUn7JAHSWg%3D%3D) | https://ro.mouser.com/datasheet/2/447/YAGEO_PYu_RC_Group_51_RoHS_L_12-3313492.pdf |
| R9 | [https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL](https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL?qs=mnq%2FyloZIXzTlUn7JAHSWg%3D%3D) | https://ro.mouser.com/datasheet/2/447/YAGEO_PYu_RC_Group_51_RoHS_L_12-3313492.pdf |
| R10 | [https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL](https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL?qs=mnq%2FyloZIXzTlUn7JAHSWg%3D%3D) | https://ro.mouser.com/datasheet/2/447/YAGEO_PYu_RC_Group_51_RoHS_L_12-3313492.pdf |
| RESET_BUTTON | [https://ro.mouser.com/ProductDetail/Panasonic/EVQ-P7L01P](https://ro.mouser.com/ProductDetail/Panasonic/EVQ-P7L01P?qs=rJ%252BziJWpyszWhhNszc02jQ%3D%3D&_gl=1*xzqk3l*_ga*dW5kZWZpbmVk*_ga_15W4STQT4T*dW5kZWZpbmVk*_ga_1KQLCYKRX3*dW5kZWZpbmVk) | https://componentsearchengine.com/Datasheets/2/EVQP7L01P.pdf |
| R_BOOT | [https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL](https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL?qs=mnq%2FyloZIXzTlUn7JAHSWg%3D%3D) | https://ro.mouser.com/datasheet/2/447/YAGEO_PYu_RC_Group_51_RoHS_L_12-3313492.pdf |
| R_CAPACITOR | [https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL](https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL?qs=mnq%2FyloZIXzTlUn7JAHSWg%3D%3D) | https://ro.mouser.com/datasheet/2/447/YAGEO_PYu_RC_Group_51_RoHS_L_12-3313492.pdf |
| R_CHANGE | [https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL](https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL?qs=mnq%2FyloZIXzTlUn7JAHSWg%3D%3D) | https://ro.mouser.com/datasheet/2/447/YAGEO_PYu_RC_Group_51_RoHS_L_12-3313492.pdf |
| R_CL1 | [https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL](https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL?qs=mnq%2FyloZIXzTlUn7JAHSWg%3D%3D) | https://ro.mouser.com/datasheet/2/447/YAGEO_PYu_RC_Group_51_RoHS_L_12-3313492.pdf |
| R_RESET | [https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL](https://ro.mouser.com/ProductDetail/YAGEO/RC0402FR-07100KL?qs=mnq%2FyloZIXzTlUn7JAHSWg%3D%3D) | https://ro.mouser.com/datasheet/2/447/YAGEO_PYu_RC_Group_51_RoHS_L_12-3313492.pdf |
| SENSOR2 | [https://ro.mouser.com/ProductDetail/Bosch-Sensortec/BME680](https://ro.mouser.com/ProductDetail/Bosch-Sensortec/BME680?qs=v271MhAjFHjo0yA%2FC4OnDQ%3D%3D) | https://ro.mouser.com/datasheet/2/783/BST_BME680_DS001-1509608.pdf |
| SJ1 | https://grabcad.com/library/solder-jumpers-1 | https://grabcad.com/library/solder-jumpers-1 |
| TP1 | CUSTOM | CUSTOM |
| TP2 | CUSTOM | CUSTOM |
| TP3 | CUSTOM | CUSTOM |
| TP4 | CUSTOM | CUSTOM |
| TP5 | CUSTOM | CUSTOM |
| TP6 | CUSTOM | CUSTOM |
| TP7 | CUSTOM | CUSTOM |
| TP8 | CUSTOM | CUSTOM |
| TP9 | CUSTOM | CUSTOM |
| TP10 | CUSTOM | CUSTOM |
| TP11 | CUSTOM | CUSTOM |
| TP12 | CUSTOM | CUSTOM |
| TP13 | CUSTOM | CUSTOM |
| TP14 | CUSTOM | CUSTOM |
| TP15 | CUSTOM | CUSTOM |
| TP16 | CUSTOM | CUSTOM |
| TP17 | CUSTOM | CUSTOM |
| U1 | [https://ro.mouser.com/ProductDetail/Winbond/W25Q512JVEIQ](https://ro.mouser.com/ProductDetail/Winbond/W25Q512JVEIQ?qs=l7cgNqFNU1jw6svr3at6tA%3D%3D) | https://ro.mouser.com/datasheet/2/949/Winbond_W25Q512JV_Datasheet-3240039.pdf |
| U2 | [https://ro.mouser.com/ProductDetail/Espressif-Systems/ESP32-C6-WROOM-1-N8](https://ro.mouser.com/ProductDetail/Espressif-Systems/ESP32-C6-WROOM-1-N8?qs=8Wlm6%252BaMh8ST02Gmwp74cw%3D%3D) | https://ro.mouser.com/datasheet/2/891/Espressif_ESP32_C6_WROOM_1__Datasheet_V0_1_PRELIMI-3239987.pdf |
| U3 | [https://ro.mouser.com/ProductDetail/Analog-Devices-Maxim-Integrated/DS3231SN](https://ro.mouser.com/ProductDetail/Analog-Devices-Maxim-Integrated/DS3231SN?qs=1eQvB6Dk1vhUlr8%2FOrV0Fw%3D%3D) | https://ro.mouser.com/datasheet/2/609/DS3231-3421123.pdf |
| U4 | [https://ro.mouser.com/ProductDetail/Analog-Devices-Maxim-Integrated/MAX17048G+T10](https://ro.mouser.com/ProductDetail/Analog-Devices-Maxim-Integrated/MAX17048G%2bT10?qs=D7PJwyCwLAoGnnn8jEPRBQ%3D%3D) | https://ro.mouser.com/datasheet/2/609/MAX17048_MAX17049-3469099.pdf |
| U5 | [https://ro.mouser.com/ProductDetail/Microchip-Technology/MCP73831T-2ACI-OT](https://ro.mouser.com/ProductDetail/Microchip-Technology/MCP73831T-2ACI-OT?qs=yUQqVecv4qvbBQBGbHx0Mw%3D%3D) | https://ro.mouser.com/datasheet/2/268/MCP73831_Family_Data_Sheet_DS20001984H-3441711.pdf |

## Hardware Description

## Detailed ESP32-C6 View

**IO0 - INT_RTC**
- Interrupt signal that can wake up the ESP32 from deep sleep.
- Used by RTC.

**IO1 – 32KHZ**
- The DS3231’s 32.768 kHz clock output, routed to the ESP32‐C6.
- Used by ESP32‐C6.

**IO2 – MISO**
- Hardware-dedicated SPI pin, offering high speed and native compatibility.
- Used by NOR Flash, E-Paper, microSD.

**IO3 - EPD_BUSY**
- GPIO status signal sent by the EPD driver, ESP32 reads it to check if the screen is busy.
- Used by E-Paper Display.

**IO4 – SS_SD**
- Selects the SD card during reading; chosen to avoid conflicts with other CS lines already in use.
- Used by microSD Card.

**IO5 – EPD_DC**
- Control signal specific to EPD to differentiate between commands and data.
- Used by E-Paper Display.

**IO6 – SCK**
- Recommended pin for SPI clock in multi-device implementations; allows SPI bus sharing.
- Used by NOR Flash, E-Paper, microSD.

**IO7 – MOSI**
- Utilized for SPI data transmission, compatible with all connected SPI peripherals.
- Used by NOR Flash, E-Paper, microSD.

**IO9 – IO/BOOT**
- Standard pin for entering programming mode on the ESP32-C6.
- Used by BOOT Button.

**IO10 - EPD_CS**
- Selects the display during SPI transfers; doesn’t interfere with the rest of the SPI devices.
- Used by E-Paper Display.

**IO11 – FLASH_CS**
- Dedicated pin to activate the external Flash memory without interfering with other SPI peripherals.
- Used by External NOR Flash Memory.

**IO12 – USB_D-**
- Direct USB data lines for the built‐in USB peripheral, going to the USB connector.
- Used by USB-C connector.

**IO13 – USB_D+**
- Direct USB data lines for the built‐in USB peripheral, going to the USB connector.
- Used by USB-C connector.

**IO15 – IO/CHANGE**
- General-purpose GPIO chosen for user-defined actions (e.g. Next Page).
- Used by CHANGE Button.

**IO16 – TX**
- Traditional serial line used for flashing the older ESP chips and debug logs.
- Used by Serial Debug.

**IO17 – RX**
- Traditional serial line used for flashing the older ESP chips and debug logs.
- Used by Serial Debug.

**IO18 – RTC_RST**
- External manual reset for the RTC, useful for initial synchronization or watchdog purposes.
- Used by RTC.

**IO19 – I2C_PW**
- 3.3V rail dedicated to powering I2C peripherals (sensors, RTC, battery gauge).
- Used by RTC, BME680, Qwiic.

**IO20 – EPD_3V3_C**
- 3.3V supply line that powers the E‐paper Display module.
- Used by E-Paper Display.

**IO21 – SDA**
- Data line for I2C communication; can be shared between multiple sensors.
- Used by RTC, BME680, Qwiic.

**IO22 – SCL**
- I2C clock line; synchronizes with SDA for reliable transmission.
- Used by RTC, BME680, Qwiic.

**IO23 – EPD_RST**
- Resets the EPD circuit before initialization or display updates.
- Used by E-Paper Display.
