ho 8 tail 4 room 4
load:0x40080404,len:3904
entry 0x40080640
I (31) boot: ESP-IDF v5.2.2 2nd stage bootloader
I (31) boot: compile time Sep 26 2024 15:26:01
I (31) boot: Multicore bootloader
I (35) boot: chip revision: v3.0
I (39) boot.esp32: SPI Speed      : 40MHz
I (44) boot.esp32: SPI Mode       : DIO
I (48) boot.esp32: SPI Flash Size : 2MB
I (53) boot: Enabling RNG early entropy source...
I (58) boot: Partition Table:
I (62) boot: ## Label            Usage          Type ST Offset   Length
I (69) boot:  0 nvs              WiFi data        01 02 00009000 00006000
I (77) boot:  1 phy_init         RF data          01 01 0000f000 00001000
I (84) boot:  2 factory          factory app      00 00 00010000 00100000
I (92) boot: End of partition table
I (96) esp_image: segment 0: paddr=00010020 vaddr=3f400020 size=20988h (133512) map
I (150) esp_image: segment 1: paddr=000309b0 vaddr=3ffb0000 size=03b84h ( 15236) load
I (156) esp_image: segment 2: paddr=0003453c vaddr=40080000 size=0badch ( 47836) load
I (175) esp_image: segment 3: paddr=00040020 vaddr=400d0020 size=8c588h (574856) map
I (372) esp_image: segment 4: paddr=000cc5b0 vaddr=4008badc size=0ad54h ( 44372) load
I (401) boot: Loaded app from partition at offset 0x10000
I (401) boot: Disabling RNG early entropy source...
I (413) cpu_start: Multicore app
I (421) cpu_start: Pro cpu start user code
I (421) cpu_start: cpu freq: 160000000 Hz
I (422) cpu_start: Application information:
I (424) cpu_start: Project name:     smart_config
I (430) cpu_start: App version:      1
I (434) cpu_start: Compile time:     Sep 26 2024 15:25:00
I (440) cpu_start: ELF file SHA256:  6d4192dde...
I (446) cpu_start: ESP-IDF:          v5.2.2
I (451) cpu_start: Min chip rev:     v0.0
I (455) cpu_start: Max chip rev:     v3.99
I (460) cpu_start: Chip rev:         v3.0
I (465) heap_init: Initializing. RAM available for dynamic allocation:
I (472) heap_init: At 3FFAE6E0 len 00001920 (6 KiB): DRAM
I (478) heap_init: At 3FFB7E68 len 00028198 (160 KiB): DRAM
I (484) heap_init: At 3FFE0440 len 00003AE0 (14 KiB): D/IRAM
I (491) heap_init: At 3FFE4350 len 0001BCB0 (111 KiB): D/IRAM
I (497) heap_init: At 40096830 len 000097D0 (37 KiB): IRAM
I (505) spi_flash: detected chip: generic
I (508) spi_flash: flash io: dio
W (512) spi_flash: Detected size(4096k) larger than the size in the binary image header(2048k). Using the size in the binary image header.
I (526) main_task: Started on CPU0
I (536) main_task: Calling app_main()
I (586) wifi:wifi driver task: 3ffbfe18, prio:23, stack:6656, core=0
I (606) wifi:wifi firmware version: 3e0076f
I (606) wifi:wifi certification version: v7.0
I (606) wifi:config NVS flash: enabled
I (606) wifi:config nano formating: disabled
I (606) wifi:Init data frame dynamic rx buffer num: 32
I (616) wifi:Init static rx mgmt buffer num: 5
I (616) wifi:Init management short buffer num: 32
I (616) wifi:Init dynamic tx buffer num: 32
I (626) wifi:Init static rx buffer size: 1600
I (626) wifi:Init static rx buffer num: 10
I (636) wifi:Init dynamic rx buffer num: 32
I (636) wifi_init: rx ba win: 6
I (636) wifi_init: tcpip mbox: 32
I (646) wifi_init: udp mbox: 6
I (646) wifi_init: tcp mbox: 6
I (656) wifi_init: tcp tx win: 5760
I (656) wifi_init: tcp rx win: 5760
I (656) wifi_init: tcp mss: 1440
I (666) wifi_init: WiFi IRAM OP enabled
I (666) wifi_init: WiFi RX IRAM OP enabled
I (676) phy_init: phy_version 4791,2c4672b,Dec 20 2023,16:06:06
I (766) wifi:mode : sta (24:d7:eb:10:74:60)
I (766) wifi:enable tsf
I (766) main_task: Returned from app_main()
I (826) smartconfig: SC version: V3.0.1
I (5666) wifi:ic_enable_sniffer
I (5666) smartconfig: Start to find channel...
I (5666) smartconfig_example: Scan done
I (12796) smartconfig: TYPE: ESPTOUCH
I (12796) smartconfig: T|AP MAC: 30:0a:c5:9e:94:9f
I (12796) smartconfig: Found channel on 11-0. Start to get ssid and password...
I (12796) smartconfig_example: Found channel
I (17186) smartconfig: T|pswd: 50769475
I (17186) smartconfig: T|ssid: AIS 4G Hi-Speed Home WiFi_76947550769475
I (17186) smartconfig: T|bssid: 30:0a:c5:9e:94:9f
I (17186) wifi:ic_disable_sniffer
I (17186) smartconfig_example: Got SSID and password
I (17196) smartconfig_example: Set MAC address of target AP: 30:0a:c5:9e:94:9f
I (17206) smartconfig_example: SSID:AIS 4G Hi-Speed Home WiFi_769475
I (17206) smartconfig_example: PASSWORD:50769475
I (17556) wifi:new:<11,0>, old:<11,0>, ap:<255,255>, sta:<11,0>, prof:1
I (17556) wifi:state: init -> auth (b0)
I (17606) wifi:state: auth -> assoc (0)
I (17666) wifi:state: assoc -> run (10)
I (17696) wifi:connected with AIS 4G Hi-Speed Home WiFi_769475, aid = 20, channel 11, BW20, bssid = 30:0a:c5:9e:94:9f
I (17696) wifi:security: WPA2-PSK, phy: bgn, rssi: -50
I (17726) wifi:pm start, type: 1

I (17726) wifi:dp: 1, bi: 102400, li: 3, scale listen interval from 307200 us to 307200 us
I (17796) wifi:AP's beacon interval = 102400 us, DTIM period = 1
I (17816) wifi:<ba-add>idx:0 (ifx:0, 30:0a:c5:9e:94:9f), tid:0, ssn:4, winSize:64
I (18726) esp_netif_handlers: sta ip: 192.168.1.167, mask: 255.255.255.0, gw: 192.168.1.1
I (18726) smartconfig_example: WiFi Connected to ap
I (21776) smartconfig_example: smartconfig over
