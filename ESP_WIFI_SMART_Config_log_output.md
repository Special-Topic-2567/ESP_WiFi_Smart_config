ho 8 tail 4 room 4
load:0x40080404,len:3904
entry 0x40080640
I (31) boot: ESP-IDF v5.2.2-dirty 2nd stage bootloader
I (31) boot: compile time Sep 26 2024 15:27:36
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
I (96) esp_image: segment 0: paddr=00010020 vaddr=3f400020 size=209b0h (133552) map
I (151) esp_image: segment 1: paddr=000309d8 vaddr=3ffb0000 size=03b84h ( 15236) load
I (156) esp_image: segment 2: paddr=00034564 vaddr=40080000 size=0bab4h ( 47796) load
I (175) esp_image: segment 3: paddr=00040020 vaddr=400d0020 size=8c588h (574856) map
I (373) esp_image: segment 4: paddr=000cc5b0 vaddr=4008bab4 size=0ad7ch ( 44412) load
I (401) boot: Loaded app from partition at offset 0x10000
I (402) boot: Disabling RNG early entropy source...
I (413) cpu_start: Multicore app
I (422) cpu_start: Pro cpu start user code
I (422) cpu_start: cpu freq: 160000000 Hz
I (422) cpu_start: Application information:
I (425) cpu_start: Project name:     smart_config
I (430) cpu_start: App version:      1
I (435) cpu_start: Compile time:     Sep 26 2024 15:27:22
I (441) cpu_start: ELF file SHA256:  564465d17...
I (446) cpu_start: ESP-IDF:          v5.2.2-dirty
I (452) cpu_start: Min chip rev:     v0.0
I (456) cpu_start: Max chip rev:     v3.99 
I (461) cpu_start: Chip rev:         v3.0
I (466) heap_init: Initializing. RAM available for dynamic allocation:
I (473) heap_init: At 3FFAE6E0 len 00001920 (6 KiB): DRAM
I (479) heap_init: At 3FFB7E68 len 00028198 (160 KiB): DRAM
I (485) heap_init: At 3FFE0440 len 00003AE0 (14 KiB): D/IRAM
I (492) heap_init: At 3FFE4350 len 0001BCB0 (111 KiB): D/IRAM
I (498) heap_init: At 40096830 len 000097D0 (37 KiB): IRAM
I (506) spi_flash: detected chip: generic
I (509) spi_flash: flash io: dio
W (513) spi_flash: Detected size(4096k) larger than the size in the binary image header(2048k). Using the size in the binary image header.
I (527) main_task: Started on CPU0
I (537) main_task: Calling app_main()
I (587) wifi:wifi driver task: 3ffbfd94, prio:23, stack:6656, core=0
I (607) wifi:wifi firmware version: 3e0076f
I (607) wifi:wifi certification version: v7.0
I (607) wifi:config NVS flash: enabled
I (607) wifi:config nano formating: disabled
I (607) wifi:Init data frame dynamic rx buffer num: 32
I (617) wifi:Init static rx mgmt buffer num: 5
I (617) wifi:Init management short buffer num: 32
I (617) wifi:Init dynamic tx buffer num: 32
I (627) wifi:Init static rx buffer size: 1600
I (627) wifi:Init static rx buffer num: 10
I (637) wifi:Init dynamic rx buffer num: 32
I (637) wifi_init: rx ba win: 6
I (637) wifi_init: tcpip mbox: 32
I (647) wifi_init: udp mbox: 6
I (647) wifi_init: tcp mbox: 6
I (647) wifi_init: tcp tx win: 5760
I (657) wifi_init: tcp rx win: 5760
I (657) wifi_init: tcp mss: 1440
I (667) wifi_init: WiFi IRAM OP enabled
I (667) wifi_init: WiFi RX IRAM OP enabled
I (677) phy_init: phy_version 4791,2c4672b,Dec 20 2023,16:06:06
I (757) wifi:mode : sta (94:b5:55:f2:79:f4)
I (757) wifi:enable tsf
I (757) main_task: Returned from app_main()
I (807) smartconfig: SC version: V3.0.1
I (5647) wifi:ic_enable_sniffer
I (5647) smartconfig: Start to find channel...
I (5647) smartconfig_example: Scan done
I (23887) smartconfig: TYPE: ESPTOUCH
I (23887) smartconfig: T|AP MAC: 30:0a:c5:9e:94:9f
I (23887) smartconfig: Found channel on 11-0. Start to get ssid and password...
I (23897) smartconfig_example: Found channel
I (23947) smartconfig: TYPE: ESPTOUCH
I (23947) smartconfig: Found channel on 11-0. Start to get ssid and password...
I (23947) smartconfig_example: Found channel
I (35367) smartconfig: T|pswd: 50769475
I (35367) smartconfig: T|ssid: AIS 4G Hi-Speed Home WiFi_76947550769475
I (35367) smartconfig: T|bssid: 30:0a:c5:9e:94:9f
I (35367) wifi:ic_disable_sniffer
I (35377) smartconfig_example: Got SSID and password
I (35377) smartconfig_example: Set MAC address of target AP: 30:0a:c5:9e:94:9f 
I (35387) smartconfig_example: SSID:AIS 4G Hi-Speed Home WiFi_769475
I (35397) smartconfig_example: PASSWORD:50769475
I (35807) wifi:new:<11,0>, old:<11,0>, ap:<255,255>, sta:<11,0>, prof:1
I (35807) wifi:state: init -> auth (b0)
I (35817) wifi:state: auth -> assoc (0)
I (35827) wifi:state: assoc -> run (10)
I (35847) wifi:connected with AIS 4G Hi-Speed Home WiFi_769475, aid = 21, channel 11, BW20, bssid = 30:0a:c5:9e:94:9f
I (35847) wifi:security: WPA2-PSK, phy: bgn, rssi: -60
I (35877) wifi:pm start, type: 1

I (35877) wifi:dp: 1, bi: 102400, li: 3, scale listen interval from 307200 us to 307200 us
I (35937) wifi:AP's beacon interval = 102400 us, DTIM period = 1
I (36177) wifi:<ba-add>idx:0 (ifx:0, 30:0a:c5:9e:94:9f), tid:0, ssn:4, winSize:64
I (36887) esp_netif_handlers: sta ip: 192.168.1.148, mask: 255.255.255.0, gw: 192.168.1.1
I (36887) smartconfig_example: WiFi Connected to ap
I (39957) smartconfig_example: smartconfig over
I (153547) wifi:<ba-add>idx:1 (ifx:0, 30:0a:c5:9e:94:9f), tid:6, ssn:0, winSize:64
