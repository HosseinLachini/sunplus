![klipsch](https://support.klipsch.com/hc/theming_assets/01HZP9RA6NN5Z4BQ5VCQ1DYP90)

# klipsch
This firmware is old version have Device tree! and use squashfs and overlayfs.
 [Cinema 800 - Updating Older Firmware](https://support.klipsch.com/hc/en-us/articles/12221464668436-Cinema-800-Updating-Older-Firmware)

```bash
ispe ISPBOOOT.BIN list
HEADER 0x100000 :
	sign (str,32/32): Pentagram_ISP_image
	sign (hex,32/32): 50656E74616772616D5F4953505F696D6167650000000000000
	init script (str,16/1976): if test "$isp_if<skipped...>
	init script size: 883
	flags: 0x1
PARTITION[0]
	filename: xboot1
	md5sum: 1491feec38ed32efb5462c3cf3110769
	file offset: 0x104000
	file size: 19456
	nand part start addr: 0x100000
	part size: 146028888069
	flags: 0x0
	emmc part start block: 0x0
WRN: virtually ends at 146029953029 (146017495045 bytes after)
WRN: image eof is at 12457984
PARTITION[1]
	filename: uboot1
	md5sum: fab95373c5e0439a5b8f4e037a1d2500
	file offset: 0x108C00
	file size: 346112
	nand part start addr: 0x100000
	part size: 146028888069
	flags: 0x0
	emmc part start block: 0x0
WRN: virtually ends at 146029972485 (146017514501 bytes after)
WRN: image eof is at 12457984
PARTITION[2]
	filename: uboot2
	md5sum: fab95373c5e0439a5b8f4e037a1d2500
	file offset: 0x15D400
	file size: 346112
	nand part start addr: 0x100000
	part size: 8942121910275
	flags: 0x0
	emmc part start block: 0x0
WRN: virtually ends at 8942123340803 (8942110882819 bytes after)
WRN: image eof is at 12457984
PARTITION[3]
	filename: env
	md5sum: d41d8cd98f00b204e9800998ecf8427e
	file offset: 0x1B1C00
	file size: 0
	nand part start addr: 0x80000
	part size: 17738214932480
	flags: 0x0
	emmc part start block: 0x0
WRN: virtually ends at 17738216709120 (17738204251136 bytes after)
WRN: image eof is at 12457984
PARTITION[4]
	filename: env_redund
	md5sum: d41d8cd98f00b204e9800998ecf8427e
	file offset: 0x1B1C00
	file size: 2251799813685248
	nand part start addr: 0x80000
	part size: 22136261443584
	flags: 0x0
	emmc part start block: 0x0
WRN: virtually ends at 22136263220224 (22136250762240 bytes after)
WRN: image eof is at 12457984
PARTITION[5]
	filename: dtb
	md5sum: 8d412d6fafa1848c4011fbd42ddecb97
	file offset: 0x1B1C00
	file size: 4503599627380736
	nand part start addr: 0x40000
	part size: 26534307954688
	flags: 0x0
	emmc part start block: 0x0
WRN: virtually ends at 26534309731328 (26534297273344 bytes after)
WRN: image eof is at 12457984
PARTITION[6]
	filename: kernel
	md5sum: f849a26e9e189d440e27a9f9605374c5
	file offset: 0x1B4400
	file size: 5629499536048128
	nand part start addr: 0x500000
	part size: 28733331210240
	flags: 0x0
	emmc part start block: 0x0
WRN: virtually ends at 28733332997120 (28733320539136 bytes after)
WRN: image eof is at 12457984
PARTITION[7]
	filename: rootfs
	md5sum: 7b234394fbe3c6060b7baf6116ac610d
	file offset: 0x374400
	file size: 28147497679884288
	nand part start addr: 0x1000000
	part size: 72713796321280
	flags: 0x0
	emmc part start block: 0x0
WRN: virtually ends at 72713799943168 (72713787485184 bytes after)
WRN: image eof is at 12457984
Last part EOF: 0x64000000BDD400
Image EOF: 0xBE1800
Tail data len: -28147497671048192

```
