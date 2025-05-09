![Sunplus](https://www.sunplus.com/images/sunpluslogo.jpg)

## ISPEditor
ISPBOOOT.BIN file editor good for scripting and automation.
```
Usage: ./ispe <img> [-v] <cmd> [cmdparams]
        [-v] verbose mode (-vvv.. increase verbosity)
        <cmd> [params] one of the following:
        list - list partitions in the image
        crea - create an empty image
        extb <0xXX> <dlen> - extract <dlen> (dec) bytes at XX offset
        setb <0xXX> <name> - save raw binary file <name> at <0xXX> offset
        head exts - extract header script
        head flag <0xXX> - set image header flag
        head sets <file> - update header script from script image file
        part <name> dele - delete the partition from the image
        part <name> addp - create new partition
        part <name> extp - extract partition to ...
        part <name> file <file> - load data for the partition from the raw file
        part <name> flag <0xXX> - set flag = 0xXX to partition <name>
        part <name> size <0xXX> - set size = 0xXX to partition <name>
        part <name> nand <0xXX> - set NAND offset = 0xXX to partition <name>
        part <name> emmc <0xXX> - set EMMC start block off = 0xXX
```
### Clone and Build
```bash
git clone https://github.com/tibbotech/ispe.git
cd ispe
make
sudo cp ispe /usr/bin/
```

## Frimware
- [klipsch](firmware/klipsch/README.md)
- [carpuride](firmware/carpuride/README.md)
- [kenwood](firmware/kenwood/README.md)
- [JVC](firmware/jvc/README.md)
- [car and driver](firmware/caranddriver/README.md)
