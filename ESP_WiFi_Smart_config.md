rst:0x1 (POWERON_RESET),boot:0x13 (SPI_FAST_FLASH_BOOT)
configsip: 0, SPIWP:0xee
clk_drv:0x00,q_drv:0x00,d_drv:0x00,cs0_drv:0x00,hd_drv:0x00,wp_drv:0x00
mode:DIO, clock div:2
load:0x3fff0030,len:7176
load:0x40078000,len:15564
ho 0 tail 12 room 4
load:0x40080400,len:4
0x40080400: _init at ??:?

load:0x40080404,len:3904
entry 0x40080640
I (31) boot: ESP-IDF v5.3.1-dirty 2nd stage bootloader
I (31) boot: compile time Sep 26 2024 15:29:13
I (31) boot: Multicore bootloader
I (36) boot: chip revision: v3.0
I (40) boot.esp32: SPI Speed      : 40MHz
I (44) boot.esp32: SPI Mode       : DIO
I (49) boot.esp32: SPI Flash Size : 2MB
I (53) boot: Enabling RNG early entropy source...
I (59) boot: Partition Table:
I (62) boot: ## Label            Usage          Type ST Offset   Length
I (70) boot:  0 nvs              WiFi data        01 02 00009000 00006000
I (77) boot:  1 phy_init         RF data          01 01 0000f000 00001000
I (85) boot:  2 factory          factory app      00 00 00010000 00100000
I (92) boot: End of partition table
I (96) esp_image: segment 0: paddr=00010020 vaddr=3f400020 size=20de4h (134628) map
I (151) esp_image: segment 1: paddr=00030e0c vaddr=3ffb0000 size=03f00h ( 16128) load
I (157) esp_image: segment 2: paddr=00034d14 vaddr=40080000 size=0b304h ( 45828) load
I (175) esp_image: segment 3: paddr=00040020 vaddr=400d0020 size=8df9ch (581532) map
I (375) esp_image: segment 4: paddr=000cdfc4 vaddr=4008b304 size=0c048h ( 49224) load
I (406) boot: Loaded app from partition at offset 0x10000
I (406) boot: Disabling RNG early entropy source...
I (418) cpu_start: Multicore app
I (427) cpu_start: Pro cpu start user code
I (427) cpu_start: cpu freq: 160000000 Hz
I (427) app_init: Application information:
I (430) app_init: Project name:     smart_config
I (435) app_init: App version:      1
I (439) app_init: Compile time:     Sep 26 2024 15:27:39
I (445) app_init: ELF file SHA256:  a34d219a8...
I (450) app_init: ESP-IDF:          v5.3.1-dirty
I (456) efuse_init: Min chip rev:     v0.0
I (460) efuse_init: Max chip rev:     v3.99
I (465) efuse_init: Chip rev:         v3.0
I (471) heap_init: Initializing. RAM available for dynamic allocation:
I (478) heap_init: At 3FFAE6E0 len 00001920 (6 KiB): DRAM
I (484) heap_init: At 3FFB8358 len 00027CA8 (159 KiB): DRAM
I (490) heap_init: At 3FFE0440 len 00003AE0 (14 KiB): D/IRAM
I (496) heap_init: At 3FFE4350 len 0001BCB0 (111 KiB): D/IRAM
I (503) heap_init: At 4009734C len 00008CB4 (35 KiB): IRAM
I (510) spi_flash: detected chip: generic
I (513) spi_flash: flash io: dio
W (517) spi_flash: Detected size(4096k) larger than the size in the binary image header(2048k). Using the size in the binary image header.
I (531) main_task: Started on CPU0
I (541) main_task: Calling app_main()
I (571) wifi:wifi driver task: 3ffc030c, prio:23, stack:6656, core=0
I (581) wifi:wifi firmware version: ccaebfa
I (581) wifi:wifi certification version: v7.0
I (581) wifi:config NVS flash: enabled
I (581) wifi:config nano formating: disabled
I (581) wifi:Init data frame dynamic rx buffer num: 32
I (591) wifi:Init static rx mgmt buffer num: 5
I (591) wifi:Init management short buffer num: 32
I (601) wifi:Init dynamic tx buffer num: 32
I (601) wifi:Init static rx buffer size: 1600
I (611) wifi:Init static rx buffer num: 10
I (611) wifi:Init dynamic rx buffer num: 32
I (621) wifi_init: rx ba win: 6
I (621) wifi_init: accept mbox: 6
I (621) wifi_init: tcpip mbox: 32
I (631) wifi_init: udp mbox: 6
I (631) wifi_init: tcp mbox: 6
I (631) wifi_init: tcp tx win: 5760
I (641) wifi_init: tcp rx win: 5760
I (641) wifi_init: tcp mss: 1440
I (651) wifi_init: WiFi IRAM OP enabled
I (651) wifi_init: WiFi RX IRAM OP enabled
I (661) phy_init: phy_version 4830,54550f7,Jun 20 2024,14:22:08
I (731) wifi:mode : sta (94:b5:55:f6:f5:7c)
I (731) wifi:enable tsf
I (741) main_task: Returned from app_main()
I (791) smartconfig: SC version: V3.0.1
I (5621) wifi:ic_enable_sniffer
I (5621) smartconfig: Start to find channel...
I (5631) smartconfig_example: Scan done
