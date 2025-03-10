# motorola-vip1003
Hacking Telia tv box Motorola VIP1003

# Telia AES key

Symmetric AES-256-ECB key used to encrypt firmware:
```
cd1c2d78f2cba1f73ca7e697b4a485f49a8a7d0c8b0fdc9f51ced50f2530668a
```
Decrypted artifacts:
- Telia kernel 2.6.32.59: [telia-kernel.gz](telia-kernel.gz)

# Telia firmware boot log

```
System memory: 256 MB

Using Slot 1

Unpacking Image ...Done

Linux version 2.6.23.17_stm23_0123 (dailybuild@craigellachie) (gcc version 4.5.3 20111123 (STMicroelectronics Base) ) #1 PREEMPT Fri Aug 9 16:00:38 CEST 2013
Booting machvec: vip19x3
Reserve 10240 KiB for STAVMEM (0 KiB for graphics)
STx7105 version 4.x
Kernel command line: console=ttyAS0,115200 mtdparts=Onboard_Flash:0x00080000@0x00380000(FFS),0x00380000@0x0(Raw) bootdevice=nor bootfiles=raw systemmemsize=262144 rbl=2 rbl_mode=1 rbl_version=2.10 dbl=1 
Kernel has NOT DVR support
bpa2: partition 'bigphysarea' created at 0x40409000, size 4 kB (0x00001000 B)
Using tmu for system timer
Using 25.000 MHz high precision timer.
console [ttyAS0] enabled
Dentry cache hash table entries: 32768 (order: 5, 131072 bytes)
Inode-cache hash table entries: 16384 (order: 4, 65536 bytes)
Memory: 246784k/262144k available (1523k kernel code, 360k data, 92k init)
SH4 450.00 BogoMIPS PRESET (lpj=225000)
NET: Registered protocol family 16
PHY configuration mode: MII
Generic PHY: Registered new driver
NET: Registered protocol family 2
Time: SuperH clocksource has been installed.
IP route cache hash table entries: 2048 (order: 1, 8192 bytes)
TCP established hash table entries: 8192 (order: 4, 65536 bytes)
TCP bind hash table entries: 8192 (order: 3, 32768 bytes)
TCP: Hash tables configured (established 8192 bind 8192)
TCP reno registered
Unpacking initramfs...
Overmounted tmpfs
 done
Freeing initrd memory: 665k freed
JFFS2 version 2.2. © 2001-2006 Red Hat, Inc.
yaffs Aug  9 2013 15:59:46 Installing. 
io scheduler noop registered
io scheduler anticipatory registered (default)
stm_hwrandom stm_hwrandom: STM Random Number Generator ver. 0.1
Kboxdev: registered device with major 120
STMicroelectronics ASC driver initialized
stasc.0: ttyAS0 at MMIO 0xfd031000 (irq = 122) is a stasc
stasc.1: ttyAS1 at MMIO 0xfd032000 (irq = 121) is a stasc
Marvell 88E3015: Registered new driver
SMSC LAN8187: Registered new driver
SMSC LAN8700: Registered new driver
SMSC LAN911x Internal PHY: Registered new driver
SMSC LAN8710/LAN8720: Registered new driver
	GMAC - user ID: 0x10, Synopsys ID: 0x33
No valid MAC address yet; it will be set from the console later.
	eth0 - (dev. name: stmmaceth - id: 0, IRQ #134
	IO base addr: 0xfd110000)
STMMAC MII Bus: probed
eth0: PHY ID 01410e20 at 0 IRQ 246 (0:00) active
VIP19xx onboard NOR flash device
Onboard_Flash: Found 1 x16 devices at 0x0 in 16-bit bank
Using word write for ST M28WXX0 FLASH
cfi_cmdset_0001: Erase suspend on write enabled
2 cmdlinepart partitions found on MTD device Onboard_Flash
Creating 2 MTD partitions on "Onboard_Flash":
0x00380000-0x00400000 : "FFS"
first erase region 1 for slave @ 3670016
0x00000000-0x00380000 : "Raw"
first erase region 0 for slave @ 0
NAND device: Manufacturer ID: 0x20, Chip ID: 0x76 (ST Micro NAND 64MiB 3,3V 8-bit)
Creating 1 MTD partitions on "stm-nand-flex.1":
0x00000000-0x04000000 : "NAND home"
spi_stm_ssc: SSC SPI Driver
i2c /dev entries driver
Software Watchdog Timer: 0.07 initialized. soft_noboot=0 soft_margin=60 sec (nowayout= 1)
stm_rng hardware driver 1.0 configured
TCP cubic registered
NET: Registered protocol family 17
Freeing unused kernel memorDBL init started
Mounting tmpfs
Mounting procfs
Unable to update /proc/sys/net/unix/max_dgram_qlen
Mounting FFS
yaffs: dev is 32505858 name is "mtdblock2"
yaffs: passed flags ""
yaffs: Attempting MTD mount on 31.2, "mtdblock2"
yaffs: <4>block 4092 is marked bad
yaffs: <4>block 4093 is marked bad
yaffs: <4>block 4094 is marked bad
yaffs: <4>block 4095 is marked bad
Verifying system integrity...
System integrity is intact
Running on Motorola VIP1003 with KreaTV Firmware version 3.19.1
Using Vendor Class Id Motorola_VIP1003
Using Bootcast Id motorola-vip1003
Using SAP Id motorola.vip1003
frontpanel: Normal probing is used
frontpanel: VIP1003.
front_panel driver loaded
ir_vip: module license 'Proprietary' taints kernel.
input: Kreatel IR-keyboard/remote as /class/input/input0
ir_vip: enable interrupts
IR driver loaded
Initializing video
Entering video stand-by mode
Could not open /tmp/splash.bmp
ir_vip: resetting all keymaps
ir_vip: adding new keymap 3 34321
ir_vip: adding new keymap 3 61801
ir_vip: adding new keymap 3 18778
ir_vip: adding new keymap 3 17800
ir_vip: adding new keymap 3 64800
ir_vip: adding new keymap 3 64768
ir_vip: adding new keymap 3 34319
ir_vip: adding new keymap 2 3
ir_vip: adding new keymap 2 19
ir_vip: adding new keymap 2 21
ir_vip: adding new keymap 0 38
ir_vip: adding new keymap 0 37
ir_vip: adding new keymap 1 32
ir_vip: adding new keymap 0 32
ir_vip: adding new keymap 0 5
ir_vip: adding new keymap 0 2
ir_vip: adding new keymap 1 1
ir_vip: adding new keymap 1 0
ir_vip: adding new keymap 2 18
ir_vip: adding new keymap 4 121
Wakeup HDMI CEC on VIP18x3
DVB is NOT available
Using splash image in flash
Copying 1244216 bytes...
Uncompressed 24 bits image
Bringing up interface eth0
Reading link status...
PHY: 0:00 - Link is Up100/Full-> Link is up
Link speed: 100Mbps/Full
Using DHCP
Total DHCP timeout is 15 seconds
IP-Config: eth0 hardware address 00:02:9b:28:ef:8d mtu 1500 DHCP
IP-Config: eth0 complete (from 192.168.99.9):
 address: 192.168.99.88    broadcast: 192.168.99.255   netmask: 255.255.255.0   
 gateway: 192.168.99.9     dns0     : 192.168.99.9     dns1   : 0.0.0.0         
 nfsserver: 192.168.99.9
 nfspath: 
Download parameters:
  Splash boot order: 313
  Kernel boot order: 313
  Bootcast address : 224.2.2.2:22222
  Sap address      : 224.2.127.254:9875
  Http address     : :80
Bootcast download protocol registered
TFTP download protocol registered
Local Storage download protocol registered
SAP download protocol registered
HTTP download protocol registered
Loading splash image
Using Local Storage
LS: Image found
Retrieving network splash version from Bootcast...
Loading control file motorola-vip1003 from 224.2.2.2:22222
Connection timeout.
Child process (/usr/bin/multicast) exited with failure code 1
Will not search for new images on the network
Using splash image in flash
Copying 1244216 bytes...
Uncompressed 24 bits image
Splash is already displayed
Loading kernel image
Using Local Storage
LS: Image found
Retrieving network kernel version from Bootcast...
Loading control file motorola-vip1003 from 224.2.2.2:22222
Connection timeout.
Child process (/usr/bin/multicast) exited with failure code 1
Will not search for new images on the network
Using kernel image in flash
Copying 26188981 bytes...
Verifying image...
Uncompressing image...
Unmounting FFS2...
save exit: isCheckpointed 0
Unloading IR module...
Loading new kernel...
Initrd at 0x86dfb000, length 19567 bytes
Command line (348 bytes):  console=ttyAS0,115200 mtdparts=Onboard_Flash:0x00080000@0x00380000(FFS),0x00380000@0x0(Raw) ip=192.168.99.88::192.168.99.9:255.255.255.0 nwhwconf=device:eth0,hwaddr:00:02:9B:28:EF:8D rbl=2 rbl_mode=1 rbl_version=2.10 dbl=1 bootdevice=nor bootfiles=raw bch=224.2.2.2:22222 systemmemsize=262144 serverid=192.168.99.9 rootdisk=m:0x01783000@0x85678000
Kernel loaded successfully
Starting new kernel...
Starting new kernel
kexec information
  segment[0]: 0x80600000 - 0x808d4000 (0x002d4000)
  segment[1]: 0x86dfb000 - 0x86e00000 (0x00005000)
  segment[2]: 0x85678000 - 0x86dfb000 (0x01783000)
  start     : 0x80601000

Linux version 2.6.32.59_stm24_0211 (<build_user_removed>@<build_host_removed>) (gcc version 4.7.3 20130514 (GCC) ) #1 PREEMPT <timestamp_removed>
Boot params:
... MOUNT_ROOT_RDONLY - 00000001
... RAMDISK_FLAGS     - 00000000
... ORIG_ROOT_DEV     - 00000200
... LOADER_TYPE       - 00000001
... INITRD_START      - 06dfb000
... INITRD_SIZE       - 00004c6f
extend_cmd_line =  gfx_mem_size=0xCC8000
Booting machvec: vip19x3
Reserve 74528 KiB for STAVMEM (13088 KiB for graphics)
Node 0: start_pfn = 0x40000, low = 0x50000
Zone PFN ranges:
  Normal   0x00040000 -> 0x00050000
Movable zone start PFN for each node
early_node_map[1] active PFN ranges
    0: 0x00040000 -> 0x00050000
bpa2: partition 'bigphysarea' created at 0x40aea000, size 1600 kB (0x00190000 B)
STx7105 version 4.x
Built 1 zonelists in Zone order, mobility grouping on.  Total pages: 65024
Kernel command line:  console=ttyAS0,115200 mtdparts=Onboard_Flash:0x00080000@0x00380000(FFS),0x00380000@0x0(Raw) ip=192.168.99.88::192.168.99.9:255.255.255.0 nwhwconf=device:eth0,hwaddr:00:02:9B:28:EF:8D rbl=2 rbl_mode=1 rbl_version=2.10 dbl=1 bootdevice=nor bootfiles=raw bch=224.2.2.2:22222 systemmemsize=262144 serverid=192.168.99.9 rootdisk=m:0x01783000@0x85678000 gfx_mem_size=0xCC8000
PID hash table entries: 1024 (order: 0, 4096 bytes)
Dentry cache hash table entries: 32768 (order: 5, 131072 bytes)
Inode-cache hash table entries: 16384 (order: 4, 65536 bytes)
PVR=04909200 CVR=60880000 PRR=00009e40
I-cache : n_ways=2 n_sets=512 way_incr=16384
I-cache : entry_mask=0x00003fe0 alias_mask=0x00003000 n_aliases=4
D-cache : n_ways=2 n_sets=512 way_incr=16384
D-cache : entry_mask=0x00003fe0 alias_mask=0x00003000 n_aliases=4
Memory: 149888k/262144k available (2142k kernel code, 622k data, 128k init)
Hierarchical RCU implementation.
NR_IRQS:600
Failed to enable clk CLKA_PLL0LS, ignoring
Console: colour dummy device 80x25
console [ttyAS0] enabled
sh_tmu: TMU0 used for clock events
sh_tmu: TMU0 used for periodic clock events
sh_tmu: TMU1 used as clock source
Calibrating delay loop (skipped)... 450.00 BogoMIPS PRESET (lpj=225000)
Mount-cache hash table entries: 512
CPU: STx7105
[STM][PM-Sys]: ilc3 @ 4096
NET: Registered protocol family 16
PHY configuration mode: MII
bio: create slab <bio-0> at 0
SCSI subsystem initialized
Switching to clocksource TMU1
NET: Registered protocol family 2
IP route cache hash table entries: 2048 (order: 1, 8192 bytes)
TCP established hash table entries: 8192 (order: 4, 65536 bytes)
TCP bind hash table entries: 8192 (order: 3, 32768 bytes)
TCP: Hash tables configured (established 8192 bind 8192)
TCP reno registered
NET: Registered protocol family 1
Unpacking initramfs...
Overmounted tmpfs
Freeing initrd memory: 19k freed
[STM]: [CPUFreq] Registered
[STM]: [PM]: Suspend support registered
squashfs: version 4.0 (2009/01/31) Phillip Lougher
Registering unionfs 2.5.5 (for 2.6.32.18)
JFFS2 version 2.2. © 2001-2006 Red Hat, Inc.
yaffs Feb 27 2019 11:12:14 Installing. 
msgmni has been set to 293
alg: No test for stdrng (krng)
io scheduler noop registered
io scheduler cfq registered (default)
STMicroelectronics ASC driver initialized
stm-asc.0: ttyAS0 at MMIO 0xfd031000 (irq = 122) is a stm-asc
stm-asc.1: ttyAS1 at MMIO 0xfd032000 (irq = 121) is a stm-asc
loop: module loaded
VIP19xx onboard NOR flash device
Onboard_Flash: Found 1 x16 devices at 0x0 in 16-bit bank
 Intel/Sharp Extended Query Table at 0x0035
Using word write for ST M28WXX0 FLASH
cfi_cmdset_0001: Erase suspend on write enabled
2 cmdlinepart partitions found on MTD device Onboard_Flash
Creating 2 MTD partitions on "Onboard_Flash":
0x000000380000-0x000000400000 : "FFS"
0x000000000000-0x000000380000 : "Raw"
NAND device: Manufacturer ID: 0x20, Chip ID: 0x76 (ST Micro NAND 64MiB 3,3V 8-bit)
stm-nand-flex: Using legacy platform timing data
Creating 1 MTD partitions on "stm-nand-flex.0":
0x000000000000-0x000004000000 : "NAND home"
stmmac - user ID: 0x10, Synopsys ID: 0x33
 No HW DMA feature register supported
 Enhanced/Alternate descriptors
 RX Checksum Offload Engine supported
 TX Checksum insertion supported
 Wake-Up On Lan supported
nwhw_config: (eth0) setting mac address: 00:02:9b:28:ef:8d
mice: PS/2 mouse device common for all mice
i2c /dev entries driver
Software Watchdog Timer: 0.07 initialized. soft_noboot=0 soft_margin=60 sec (nowayout= 1)
sh_tmu: TMU0 kept as earlytimer
sh_tmu: TMU1 kept as earlytimer
[STM][PM-Sys]: emi @ 40
[STM][PM-Sys]: gpio @ 20
stm-hwrandom stm-hwrandom: STM Random Number Generator ver. 0.1
stm-rng hardware driver 1.0 configured
stm-rtc stm-rtc: rtc core: registered stm-rtc as rtc0
TCP cubic registered
NET: Registered protocol family 17
stm-rtc stm-rtc: setting system clock to 2000-11-16 08:36:01 UTC (974363761)
eth0: device MAC address 00:02:9b:28:ef:8d
STMMAC MII Bus: probed
eth0: PHY ID 01410e20 at 0 IRQ 246 (0:00) active
stmmac_timer: (eth0) sh_tmu Timer (freq 256Hz)
 No MAC Management Counters available
IP-Config: Complete:
     device=eth0, addr=192.168.99.88, mask=255.255.255.0, gw=192.168.99.9,
     host=192.168.99.88, domain=, nis-domain=(none),
     bootserver=255.255.255.255, rootserver=255.255.255.255, rootpath=
Freeing unused kernel memory: 128k freed

starting pid 20, tty '/dev/console': '/etc/rc.sysinit'
Thu Jan  1 00:00:00 UTC 1970
frontpanel: Normal probing is used
frontpanel: VIP1003
stos_core: module license 'ST Microelectronics' taints kernel.
Disabling lock debugging due to kernel taint
Load module stos_core [?]		by insmod (pid 31)
input: KreaTV input as /devices/virtual/input/input0
ICS init 1 debug_flags 0x40 debug_chan 0x5 connect 0 watchdog 0 bpa2_part 'bigphysarea'
ICS: Using BPA2 partition 'bigphysarea'
Calling ICS_cpu_init(0, 0x7, 0x0)
insmod: can't insert 'ics_user.ko': No such file or directory
MME module init=1 debug_flags=0x0 pool_size=524288
insmod: can't insert 'mme_user.ko': No such file or directory
usbcore: registered new interface driver usbfs
usbcore: registered new interface driver hub
usbcore: registered new device driver usb
ehci_hcd: USB 2.0 'Enhanced' Host Controller (EHCI) Driver
ohci_hcd: USB 1.1 'Open' Host Controller (OHCI) Driver
stm_usb_probe: usb_phy_clk clock not found for stm-usb.0
stm-ehci stm-ehci.0: STMicroelectronics EHCI Host Controller
stm-ehci stm-ehci.0: new USB bus registered, assigned bus number 1
stm-ehci stm-ehci.0: irq 169, io mem 0xfe1ffe00
stm-ehci stm-ehci.0: USB 0.0 started, EHCI 1.00
usb usb1: configuration #1 chosen from 1 choice
hub 1-0:1.0: USB hub found
hub 1-0:1.0: 1 port detected
stm-ohci stm-ohci.0: STMicroelectronics OHCI Host Controller
stm-ohci stm-ohci.0: new USB bus registered, assigned bus number 2
stm-ohci stm-ohci.0: irq 168, io mem 0xfe1ffc00
usb usb2: configuration #1 chosen from 1 choice
hub 2-0:1.0: USB hub found
hub 2-0:1.0: 1 port detected
stm_usb_probe: usb_phy_clk clock not found for stm-usb.1
stm-ehci stm-ehci.1: STMicroelectronics EHCI Host Controller
stm-ehci stm-ehci.1: new USB bus registered, assigned bus number 3
stm-ehci stm-ehci.1: irq 143, io mem 0xfeaffe00
stm-ehci stm-ehci.1: USB 0.0 started, EHCI 1.00
usb usb3: configuration #1 chosen from 1 choice
hub 3-0:1.0: USB hub found
hub 3-0:1.0: 1 port detected
stm-ohci stm-ohci.1: STMicroelectronics OHCI Host Controller
stm-ohci stm-ohci.1: new USB bus registered, assigned bus number 4
stm-ohci stm-ohci.1: irq 142, io mem 0xfeaffc00
usb usb4: configuration #1 chosen from 1 choice
hub 4-0:1.0: USB hub found
hub 4-0:1.0: 1 port detected
PHY: 0:00 - Link is Up - 100/Full
usbcore: registered new interface driver usbhid
usbhid: v2.6:USB HID core driver
Initializing USB Mass Storage driver...
usbcore: registered new interface driver usb-storage
USB Mass Storage support registered.
Uniform Multi-Platform E-IDE driver
LXLOAD(video1)	: LX loaded => Base=0x40000000 - Last=0x400decdc - Size=912604
JFS: nTxBlock = 1174, nTxLock = 9394
MiPHY driver style MiPHY3-65 probed successfully
MiPHY3-65, c1.5 Claimed by sata-stm 
LXLOAD(audio1)	: LX loaded => Base=0x40300000 - Last=0x4047e834 - Size=1566772
scsi0 : sata-stm
ata1: SATA max UDMA/133 irq 72
ata1: SATA link down (SStatus 0 SControl 0)
udpfilter_kreatel initializing
Thu Jan  1 02:00:02 EET 1970
yaffs: dev is 32505858 name is "mtdblock2"
yaffs: passed flags ""
yaffs: Attempting MTD mount on 31.2, "mtdblock2"
yaffs: <4>block 4092 is marked bad
yaffs: <4>block 4093 is marked bad
yaffs: <4>block 4094 is marked bad
yaffs: <4>block 4095 is marked bad
Load module sttbx_core [?]		by insmod (pid 145)
Load module stavmem_core [?]		by insmod (pid 145)
AVMEM partition 0: start 48400000 size 3c00000
AVMEM partition 1: start 4f338000 size cc8000
Load module stclock_core [251]		by insmod (pid 145)
Load module stevt_core [?]		by insmod (pid 145)
Load module stcommon_core [?]		by insmod (pid 145)
Load module stpti4_core [?]		by insmod (pid 145)
Load module stclkrv_core [?]		by insmod (pid 145)
Load module stfdma_core [250]		by insmod (pid 145)
Load module stbuffer_core [?]		by insmod (pid 145)
Load module stinject_core [?]		by insmod (pid 145)
Load module stmerge_core [?]		by insmod (pid 145)
Load module stsmart_core [249]		by insmod (pid 145)
Load module stpio_core [?]		by insmod (pid 145)
Load module stdenc_core [?]		by insmod (pid 145)
Load module stlayer_core [?]		by insmod (pid 145)
Load module stvout_core [?]		by insmod (pid 145)
Load module stvtg_core [?]		by insmod (pid 145)
Load module stvid_core [?]		by insmod (pid 145)
Load module stvmix_core [?]		by insmod (pid 145)
Load module staudlx_core [248]		by insmod (pid 145)
Load module stvbi_core [?]		by insmod (pid 145)
Load module stblit_core [?]		by insmod (pid 145)
Module stapler_core (rev: STAPLER-REL_1.10.2) loaded by insmod (pid 145)
Load module sttkdma_core by insmod (pid 145)
Load module stttx_core [?]		by insmod (pid 145)
Load module stevt_ioctl [162]		by insmod (pid 145)
Load module stcommon_ioctl [160]	by insmod (pid 145)
Load module stpti4_ioctl [170]		by insmod (pid 145)
Load module stclkrv_ioctl [159]		by insmod (pid 145)
Load module stfdma_ioctl [163]		by insmod (pid 145)
Load module stbuffer_ioctl [182]	by insmod (pid 145)
Load module stinject_ioctl [183]	by insmod (pid 145)
Load module stmerge_ioctl [167]		by insmod (pid 145)
Load module stpio_ioctl [168]		by insmod (pid 145)
Load module stdenc_ioctl [161]		by insmod (pid 145)
Load module stlayer_ioctl [166]		by insmod (pid 145)
Load module stvout_ioctl [177]		by insmod (pid 145)
Load module stvtg_ioctl [178]		by insmod (pid 145)
Load module stvid_ioctl [175]		by insmod (pid 145)
Load module stvmix_ioctl [176]		by insmod (pid 145)
Load module stvbi_ioctl [174]		by insmod (pid 145)
Load module stblit_ioctl [158]		by insmod (pid 145)
Load module stttx_ioctl [181]		by insmod (pid 145)
Load module sttkdma_ioctl by insmod (pid 145)
Load module stsys_ioctl [172]		by insmod (pid 145)
stevt: Setting New buffer Size 8192

```
