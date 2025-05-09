![Car And Driver](logo.68b8e69.svg)

# Car And Driver
Download link:
[- -- -](https://fescogroup.sharepoint.com/:u:/s/FirmwareUpdater/EYPLM-AQ6PFGr6q_7xHPQlkBonTN2SoGDByviQO_VnLsYQ?e=QiiJ8y&download=1)

```bash
 ispe ISPBOOOT.BIN list
HEADER 0x100000 :
	sign (str,32/32): Gemini_ISP_image
	sign (hex,32/32): 47656D696E695F4953505F696D6167650000000000000000
	init script (str,16/1976): if test "$isp_if<skipped...>
	init script size: 1328
	flags: 0x1
PARTITION[0]
	filename: xboot1
	md5sum: 92d4c560eacdf7b6b9c86ce7d07b8b29
	file offset: 0x104000
	file size: 20480
	nand part start addr: 0x100000
	part size: 5
	flags: 0x0
	emmc part start block: 0x0
PARTITION[1]
	filename: uboot1
	md5sum: a0e023a626a63fda51b9ef10aec8d63b
	file offset: 0x109000
	file size: 418816
	nand part start addr: 0x100000
	part size: 5
	flags: 0x0
	emmc part start block: 0x0
PARTITION[2]
	filename: uboot2
	md5sum: a0e023a626a63fda51b9ef10aec8d63b
	file offset: 0x16F400
	file size: 418816
	nand part start addr: 0x100000
	part size: 3
	flags: 0x0
	emmc part start block: 0x0
PARTITION[3]
	filename: env
	md5sum: d41d8cd98f00b204e9800998ecf8427e
	file offset: 0x1D5800
	file size: 0
	nand part start addr: 0x80000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[4]
	filename: env_redund
	md5sum: d41d8cd98f00b204e9800998ecf8427e
	file offset: 0x1D5800
	file size: 2251799813685248
	nand part start addr: 0x80000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[5]
	filename: ecos
	md5sum: 832c418fc3778ddcf810eca7282c8abc
	file offset: 0x1D5800
	file size: 4503599629907968
	nand part start addr: 0x400000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[6]
	filename: kernel
	md5sum: ad2245dcf2dea09c8acd87b7ceb6a0c4
	file offset: 0x441000
	file size: 22517998140965888
	nand part start addr: 0x480000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[7]
	filename: rootfs.
	md5sum: 3108037547a67e2459ddcac99a6d7447
	file offset: 0x82D400
	file size: 42784196462125056
	nand part start addr: 0x360000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[8]
	filename: opt.
	md5sum: 67d6619fcc67360b066d94eee5bbdec9
	file offset: 0xA2F400
	file size: 57983845202649088
	nand part start addr: 0x60000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[9]
	filename: spsdk.
	md5sum: f8cbc1c02d264373a968cc421e7f09fd
	file offset: 0xA6D400
	file size: 59672695110721536
	nand part start addr: 0x3000000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[10]
	filename: spapp.
	md5sum: ef33e8df52f99ec12f18ca7b037dfde4
	file offset: 0x3843400
	file size: 275845477189611520
	nand part start addr: 0x1C00000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[11]
	filename: nvm
	md5sum: d41d8cd98f00b204e9800998ecf8427e
	file offset: 0x44D2400
	file size: 401946266742816768
	nand part start addr: 0xA00000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[12]
	filename: pq
	md5sum: d527d29bd731b142f40bd2d1bd56ba78
	file offset: 0x44D2400
	file size: 446982263016548352
	nand part start addr: 0x20000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[13]
	filename: logo
	md5sum: 3ae25f799656fec123357fb39ba9bdea
	file offset: 0x44D8C00
	file size: 447545212970559488
	nand part start addr: 0x260000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[14]
	filename: tcon
	md5sum: 9d908212d1fbe4fe4943aeeed29635f0
	file offset: 0x456F400
	file size: 458241262084994048
	nand part start addr: 0x20000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[15]
	filename: iop_car
	md5sum: 75cd4ac79f5b5c2fd89494ce7cba5e34
	file offset: 0x457A800
	file size: 458804212038379520
	nand part start addr: 0x40000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[16]
	filename: runtime_cfg
	md5sum: f7b9e9076f5aff82a72452bce0d5a6a7
	file offset: 0x457D000
	file size: 459930111945227264
	nand part start addr: 0x100000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[17]
	filename: vi
	md5sum: 61eac443194b3ab4f4abda5c17cbd5c7
	file offset: 0x4580C00
	file size: 464433711572583424
	nand part start addr: 0x20000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[18]
	filename: isp_logo
	md5sum: 190c1203f6dd17852c3a44cab905e4fd
	file offset: 0x4581000
	file size: 464996661531535360
	nand part start addr: 0x780000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[19]
	filename: vendordata
	md5sum: ffdacc240d0307bcb7b655a3c0b266a3
	file offset: 0x4AC7800
	file size: 498773658731284480
	nand part start addr: 0x40000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[20]
	filename: pat_logo
	md5sum: 5c1ae68f89798e7d0e87f9c7ebaf1426
	file offset: 0x4AC8000
	file size: 499899558640587776
	nand part start addr: 0x400000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[21]
	filename: version_info
	md5sum: a78201d4fecb0a7f19dfe58aa9883e71
	file offset: 0x4D21400
	file size: 517913957147608064
	nand part start addr: 0x40000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[22]
	filename: vd_restore
	md5sum: ffdacc240d0307bcb7b655a3c0b266a3
	file offset: 0x4D21800
	file size: 519039857054451712
	nand part start addr: 0x40000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[23]
	filename: anm_logo
	md5sum: d41d8cd98f00b204e9800998ecf8427e
	file offset: 0x4D22000
	file size: 520165756961292288
	nand part start addr: 0x500000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
Last part EOF: 0x738000004D22000
Image EOF: 0x4DA0C00
Tail data len: -520165756960773120
```
