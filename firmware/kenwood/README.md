![kenwood](logo01.gif)

# kenwood
Download link: 
 [DMX7018BTS](https://www.kenwood.com/cs/ce/mm/firmware/2018/2018t/eng2.html)
![DMX7018BTS](18_DMX7018BTS_F_H_CP.png)

```bash
ispe ISPBOOOT.BIN list             
HEADER 0x100000 :
	sign (str,32/32): Gemini_ISP_image
	sign (hex,32/32): 47656D696E695F4953505F696D6167650000000000000000
	init script (str,16/1976): if test "$isp_if<skipped...>
	init script size: 1266
	flags: 0x1
PARTITION[0]
	filename: xboot1
	md5sum: 6bea11bbedd3fbe5388865ed6692c369
	file offset: 0x104000
	file size: 34816
	nand part start addr: 0x100000
	part size: 5
	flags: 0x0
	emmc part start block: 0x0
PARTITION[1]
	filename: uboot1
	md5sum: 3ed06fb3dde37f31eaf7bedad737b317
	file offset: 0x10C800
	file size: 868352
	nand part start addr: 0x100000
	part size: 5
	flags: 0x0
	emmc part start block: 0x0
PARTITION[2]
	filename: uboot2
	md5sum: 3ed06fb3dde37f31eaf7bedad737b317
	file offset: 0x1E0800
	file size: 868352
	nand part start addr: 0x100000
	part size: 3
	flags: 0x0
	emmc part start block: 0x0
PARTITION[3]
	filename: env
	md5sum: d41d8cd98f00b204e9800998ecf8427e
	file offset: 0x2B4800
	file size: 0
	nand part start addr: 0x80000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[4]
	filename: env_redund
	md5sum: d41d8cd98f00b204e9800998ecf8427e
	file offset: 0x2B4800
	file size: 2251799813685248
	nand part start addr: 0x80000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[5]
	filename: ecos
	md5sum: e31afbf3fda19e44859ca747ba42ada8
	file offset: 0x2B4800
	file size: 4503599631801344
	nand part start addr: 0x800000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[6]
	filename: kernel
	md5sum: 3c5a85f11f3291b3b44ca4061fe1d1de
	file offset: 0x6EE400
	file size: 40532396648391680
	nand part start addr: 0x600000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[7]
	filename: rootfs
	md5sum: 254b3bbfcf99001c73df0a929b93e3fa
	file offset: 0x8E4800
	file size: 67553994414587904
	nand part start addr: 0x5A0000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[8]
	filename: spsdk
	md5sum: 63e644bafc5d23b2d529f451b2c255e9
	file offset: 0xCBC800
	file size: 92886742353330176
	nand part start addr: 0x34E0000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[9]
	filename: spapp
	md5sum: 2151582643d22d51d73e05bd7cfd25ce
	file offset: 0x31C0800
	file size: 331014572638466048
	nand part start addr: 0x2000000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[10]
	filename: nvm
	md5sum: d41d8cd98f00b204e9800998ecf8427e
	file offset: 0x4B3F800
	file size: 475129760687587328
	nand part start addr: 0x6400000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[11]
	filename: pq
	md5sum: 2c4a84169d85646ef5d26681996fb0d5
	file offset: 0x4B3F800
	file size: 925489723424663552
	nand part start addr: 0x20000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[12]
	filename: logo
	md5sum: 8a112f79ab4eb857fe3a8f69a663d593
	file offset: 0x4B46000
	file size: 926052673379595264
	nand part start addr: 0x200000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[13]
	filename: tcon
	md5sum: df5438a52db02e9df295bd5de5d1453a
	file offset: 0x4CBD400
	file size: 935059872632845312
	nand part start addr: 0x20000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[14]
	filename: iop_car
	md5sum: e2f6dcdaf95bd75af26b54c3c1fa48ea
	file offset: 0x4CC8800
	file size: 935622822586231808
	nand part start addr: 0x200000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[15]
	filename: runtime_cfg
	md5sum: 9811109d091bcf25367a86ac2ed24284
	file offset: 0x4CCB400
	file size: 944630021840969728
	nand part start addr: 0x100000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[16]
	filename: vi
	md5sum: eb8ea58af22172a1c9160078bb7600b6
	file offset: 0x4CCD400
	file size: 949133621468333056
	nand part start addr: 0x20000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[17]
	filename: isp_logo
	md5sum: 1344d7d94feb6ab3edf404199ab45457
	file offset: 0x4CCD800
	file size: 949696571426362368
	nand part start addr: 0x500000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[18]
	filename: vendordata
	md5sum: 2a38998443d189892a1d883a6bd32b8d
	file offset: 0x5132C00
	file size: 972214569558608896
	nand part start addr: 0x40000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[19]
	filename: pat_logo
	md5sum: 8c89f7704ad118fdceee60f5242825ac
	file offset: 0x5133800
	file size: 973340469477737472
	nand part start addr: 0xD00000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[20]
	filename: version_info
	md5sum: 8d3f5c1714568079286287433c939584
	file offset: 0x5CEBC00
	file size: 1031887264621265920
	nand part start addr: 0x20000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[21]
	filename: vd_restore
	md5sum: 2a38998443d189892a1d883a6bd32b8d
	file offset: 0x5CEC000
	file size: 1032450214574689280
	nand part start addr: 0x40000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[22]
	filename: anm_logo
	md5sum: d41d8cd98f00b204e9800998ecf8427e
	file offset: 0x5CECC00
	file size: 1033576114481528832
	nand part start addr: 0x600000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
Last part EOF: 0xE58000005CECC00
Image EOF: 0x5D00800
Tail data len: -1033576114481447936

```
