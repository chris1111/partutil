# partutil
- partutil 0.15 - Copyright 2014-2015 JrCs

### This version of parutil is updated and its work on macOS system SIP enable

partutil 0.15
Copyright 2014-2015 JrCs.

```bash
Usage: partutil [QUERY OPTION] [DEVICE|UUID]
       partutil [SEARCH OPTION]

Query options:
	--show-fstype           display the filesytem type of the partition
	--show-bsdname          display the device name of the partition
	--show-mountpoint       display the mount point of the partition
	--show-volumename       display the volume name of the partition
	--show-uuid             display the UUID of the partition
	--show-blocksize        display the prefer blocksize of the partition
	--show-partitionscheme  display the partition scheme of a disk
	--show-contenttype      display the content type of the device
	--show-pbrtype          display the filesystem type from the PBR of the device
	--show-wholedisk        display the whole disk of the device
	--dump                  dump properties of the partition

Search options: 
	--search-uuid UUID      search a partition with the specific UUID

Other options:
	-h, --help              display this message and exit
	-V, --version           print version information and exit
	-v, --verbose           print verbose messages

example: partutil --show-fstype disk0s4
         partutil --show-bsdname 6A9017D9-2B9E-4786-B0A5-A75BD2264239
         partutil --show-blocksize disk0s4
         partutil --search-uuid 2C97F84A-F488-4917-A312-5D64BAE5BCFC
chris@iMac-de-chris ~ % 
```

- [x] `Build project: simply download then run partutil.xcworkspace`

Note: - The software used here is a copyright software which is available free to use. 
- There is no code written by me, I have only update the Xcode project and the macOS Deployment Target
- This document is only meant to help for how to use this software. 
- Any suggestions regarding the software can be directly send at JrCs
