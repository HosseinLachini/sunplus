![Sunplus](logo.png)

# Carpuride W702
Download link:
[Carpuride W702](https://drive.google.com/drive/folders/1mKXS6cGNAtefQ6bXbLUDyjRSDkivm2yx?usp=drive_link)

```bash
ispe ISPBOOOT.BIN list                                          
HEADER 0x100000 :
	sign (str,32/32): Gemini_ISP_image
	sign (hex,32/32): 47656D696E695F4953505F696D6167650000000000000000
	init script (str,16/1976): if test "$isp_if<skipped...>
	init script size: 947
	flags: 0x1
PARTITION[0]
	filename: xboot1
	md5sum: 27dbd437caf8184cefa2bf1ede3f4fb7
	file offset: 0x104000
	file size: 21504
	nand part start addr: 0x100000
	part size: 5
	flags: 0x0
	emmc part start block: 0x0
PARTITION[1]
	filename: uboot1
	md5sum: edd35aa038a3ed8c354a8c571713e2bf
	file offset: 0x109400
	file size: 429056
	nand part start addr: 0x100000
	part size: 5
	flags: 0x0
	emmc part start block: 0x0
PARTITION[2]
	filename: uboot2
	md5sum: edd35aa038a3ed8c354a8c571713e2bf
	file offset: 0x172000
	file size: 429056
	nand part start addr: 0x100000
	part size: 3
	flags: 0x0
	emmc part start block: 0x0
PARTITION[3]
	filename: env
	md5sum: d41d8cd98f00b204e9800998ecf8427e
	file offset: 0x1DAC00
	file size: 0
	nand part start addr: 0x80000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[4]
	filename: env_redund
	md5sum: d41d8cd98f00b204e9800998ecf8427e
	file offset: 0x1DAC00
	file size: 2251799813685248
	nand part start addr: 0x80000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[5]
	filename: ecos
	md5sum: 5f32952bc8d096e8bf8074f3a45755f5
	file offset: 0x1DAC00
	file size: 4503599630267392
	nand part start addr: 0x400000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[6]
	filename: kernel
	md5sum: bad61b1f478adfdccc5aa87fc9b74397
	file offset: 0x49E000
	file size: 22517998141584384
	nand part start addr: 0x4A0000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[7]
	filename: rootfs.
	md5sum: 3816751f450e66fabf40872329321938
	file offset: 0x921400
	file size: 43347146417741824
	nand part start addr: 0x500000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[8]
	filename: opt.
	md5sum: d41d8cd98f00b204e9800998ecf8427e
	file offset: 0xD3B400
	file size: 65865144550293504
	nand part start addr: 0xC0000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[9]
	filename: spsdk.
	md5sum: e364aff6f1e2ee1663dd71ba667a3a67
	file offset: 0xD3B400
	file size: 69242844315987968
	nand part start addr: 0x3000000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[10]
	filename: spapp.
	md5sum: 6c56010c274f6c60702939fa1f6dfa38
	file offset: 0x384E400
	file size: 285415626394877952
	nand part start addr: 0xCA0000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[11]
	filename: nvm
	md5sum: d41d8cd98f00b204e9800998ecf8427e
	file offset: 0x421A400
	file size: 342273571680157696
	nand part start addr: 0x1000000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[12]
	filename: pq
	md5sum: 60f3758daf8bb4a6a1612bb6629496f7
	file offset: 0x421A400
	file size: 414331165718089728
	nand part start addr: 0x20000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[13]
	filename: logo
	md5sum: 2be5079f1172b10fefc0cb6fb4f1381c
	file offset: 0x421B400
	file size: 414894115673965568
	nand part start addr: 0x260000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[14]
	filename: tcon
	md5sum: f98dbc9dfbbdbf1c6b55579d9bfa4e9a
	file offset: 0x4473800
	file size: 425590164786557952
	nand part start addr: 0x20000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[15]
	filename: iop_car
	md5sum: a3bda7c842fd454e0332dbc6e86e650e
	file offset: 0x447EC00
	file size: 426153114739943424
	nand part start addr: 0x40000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[16]
	filename: runtime_cfg
	md5sum: 8b5557365a677a1fcac1a9c5834f7c16
	file offset: 0x4481400
	file size: 427279014646791168
	nand part start addr: 0x100000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[17]
	filename: vi
	md5sum: 5f00303146210e373210ec003bb8af9b
	file offset: 0x4485000
	file size: 431782614274147328
	nand part start addr: 0x20000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[18]
	filename: isp_logo
	md5sum: 190c1203f6dd17852c3a44cab905e4fd
	file offset: 0x4485400
	file size: 432345564233099264
	nand part start addr: 0x980000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[19]
	filename: vendordata
	md5sum: 09d76d6e27f28e2b144ecdc8f979b8a1
	file offset: 0x49CBC00
	file size: 475129760687589376
	nand part start addr: 0x40000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[20]
	filename: pat_logo
	md5sum: 5c1ae68f89798e7d0e87f9c7ebaf1426
	file offset: 0x49CC400
	file size: 476255660596892672
	nand part start addr: 0xBC0000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[21]
	filename: version_info
	md5sum: b36d4a6336dabe25d54f1f85ab50e8c9
	file offset: 0x4C25800
	file size: 529172956216034304
	nand part start addr: 0x40000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[22]
	filename: vd_restore
	md5sum: 09d76d6e27f28e2b144ecdc8f979b8a1
	file offset: 0x4C25C00
	file size: 530298856122877952
	nand part start addr: 0x40000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
PARTITION[23]
	filename: anm_logo
	md5sum: d41d8cd98f00b204e9800998ecf8427e
	file offset: 0x4C26400
	file size: 531424756029718528
	nand part start addr: 0x20000
	part size: 0
	flags: 0x0
	emmc part start block: 0x0
Last part EOF: 0x760000004C26400
Image EOF: 0x4CA8C00
Tail data len: -531424756029184000
```
