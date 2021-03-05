# MACHINIST X99Z V102

<a href="https://www.paypal.com/donate?hosted_button_id=ASF2H5CU95MUQ">
  <img src="https://raw.githubusercontent.com/BIOS-iEngineer/PNG/main/PayPal.png" alt="Donate with PayPal" />
</a>
<a href="https://www.paypal.com/donate?hosted_button_id=ASF2H5CU95MUQ">
  <img src="https://raw.githubusercontent.com/BIOS-iEngineer/PNG/main/QR-PayPal.png" alt="Donate with PayPal" />
</a>

### <a target="_blank" rel="noopener noreferrer" href="https://machinist.de.aliexpress.com/store/3666028">Sponsored by (AliExpress) MACHINIST Store</a>
* ### This motherboard has been discontinued, BIOS updates will be no longer be released.
* #### Running X99Z-V102 / Kllisre X99Z-V102 / ALZENIT X99M-CE5, X99-PE7(X99 V1.2) / XLZ X99Z-V102
* ##### Release C612RD24 November-02-2020
    <a href="https://github.com/BIOS-iEngineer/MACHINIST-X99ZV102/releases/latest">
        <img src="https://img.shields.io/github/release/BIOS-iEngineer/MACHINIST-X99ZV102.svg?color=silver&style=for-the-badge&logo=appveyor" alt="latest version"/>
    </a>
    <a href="https://github.com/BIOS-iEngineer/MACHINIST-X99ZV102/releases">
        <img src="https://img.shields.io/github/downloads/BIOS-iEngineer/MACHINIST-X99ZV102/total.svg?color=silver&style=for-the-badge&logo=appveyor" alt="downloads"/>
    </a>
    <a href="https://github.com/BIOS-iEngineer/MACHINIST-X99ZV102/blob/master/License">
        <img src="https://img.shields.io/github/license/BIOS-iEngineer/MACHINIST-X99ZV102.svg?style=for-the-badge&logo=appveyor" alt="license"/>
    </a>

## C612RD24 BIOS for MACHINIST X99Z V102 Motherboard
### Attention! 
#### C612RD23 support: any V3 & V4 final revision CPUs with UDIMM / RDIMM DDR4 memory module. 
#### C612RD24 support: only V3 final revision CPUs with only UDIMM DDR4 memory module. 
#### Add on 'REPUBLIC OF BELARUS' Download and modified separately for any version BIOS, see description below. 
  
![Latest BIOS for Machinist X99Z-V102 Motherboard](Motherboard.PNG)

<img src="https://raw.githubusercontent.com/BIOS-iEngineer/PNG/main/C612RD24-001.png" alt="Machinist X99Z C612RD24 BIOS" />
<img src="https://raw.githubusercontent.com/BIOS-iEngineer/PNG/main/C612RD24-002.png" alt="Machinist X99Z C612RD24 BIOS" />
<img src="https://raw.githubusercontent.com/BIOS-iEngineer/PNG/main/C612RD24-003.png" alt="Machinist X99Z C612RD24 BIOS" />
<img src="https://raw.githubusercontent.com/BIOS-iEngineer/PNG/main/C612RD24-004.png" alt="Machinist X99Z C612RD24 BIOS" />
  
  Builder: iEngineer
  
  Manufacturer Bug Fixed, Latest updates, set FSB 100MHz
  
  Update:
1) ME Firmware (last serviceable) version 9.1.37.1002 (1,5MiB).
2) EFI/OROM for RSTe SATA(Port 0-3) firmware up to 5.5.5.1005 ((latest) Full I/O speed).
3) CPU microcode (latest).

  Changes:
1) Enable DUAL/QUAD SPI for Winbond 25Q128FVSG & 25Q128JVSQ.
2) Changes Master Acces from Debug/Manufacturing to Production.
3) Increased BBBS up to 1MiB.
4) Hidden BIOS items that do not control.

  How to update Firmware:
1) Burn the Firmware to programmer device. (e.g. EZP-2019)
2) Clear CMOS.
3) After restart go to the BIOS setting & use 'Restore Default' / 'F10' / 'Enter'
4) Configure RAM timings & enjoy.

Addon: 7BB28B99-61BB-11D5-9A5D-0090273FC14D.FFS
![Belarus Edition](BELARUS-EDITION.png)

  How to install addon:
1) Open BIOS file in UEFITool
2) Find (Ctrl+F) GUID 7BB28B99-61BB-11D5-9A5D-0090273FC14D then select (Ctrl+R) Replace as is (choise new downloaded  7BB28B99-61BB-11D5-9A5D-0090273FC14D.FFS file).
3) File (Ctrl+S) Save image file.

* #### tRFC Table
![tRFC Table](tRFC-Table.png)
