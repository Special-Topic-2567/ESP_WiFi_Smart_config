```
ho 8 tail 4 room 4
load:0x40080404,len:3904
entry 0x40080640
I (31) boot: ESP-IDF v5.2.2 2nd stage bootloader
I (31) boot: compile time Sep 26 2024 15:12:31
I (31) boot: Multicore bootloader  
I (35) boot: chip revision: v1.0   
I (39) boot.esp32: SPI Speed      : 40MHz
I (43) boot.esp32: SPI Mode       : DIO
I (48) boot.esp32: SPI Flash Size : 2MB
I (52) boot: Enabling RNG early entropy source...
I (58) boot: Partition Table:      
I (61) boot: ## Label            Usage          Type ST Offset   Length
I (69) boot:  0 nvs              WiFi data        01 02 00009000 00006000
I (76) boot:  1 phy_init         RF data          01 01 0000f000 00001000
I (84) boot:  2 factory          factory app      00 00 00010000 00100000
I (91) boot: End of partition table
I (95) esp_image: segment 0: paddr=00010020 vaddr=3f400020 size=20988h (133512) map
I (150) esp_image: segment 1: paddr=000309b0 vaddr=3ffb0000 size=03b84h ( 15236) load
I (155) esp_image: segment 2: paddr=0003453c vaddr=40080000 size=0badch ( 47836) load
I (174) esp_image: segment 3: paddr=00040020 vaddr=400d0020 size=8c588h (574856) map
I (372) esp_image: segment 4: paddr=000cc5b0 vaddr=4008badc size=0ad54h ( 44372) load
I (401) boot: Loaded app from partition at offset 0x10000
I (401) boot: Disabling RNG early entropy source...
I (412) cpu_start: Multicore app   
I (421) cpu_start: Pro cpu start user code
I (421) cpu_start: cpu freq: 160000000 Hz
I (421) cpu_start: Application information:
I (424) cpu_start: Project name:     ESP_WiFi_Smart_config_121        
I (431) cpu_start: App version:      1
I (435) cpu_start: Compile time:     Sep 26 2024 15:12:05
I (441) cpu_start: ELF file SHA256:  0922ecc9f...
I (446) cpu_start: ESP-IDF:          v5.2.2
I (451) cpu_start: Min chip rev:     v0.0
I (456) cpu_start: Max chip rev:     v3.99
I (461) cpu_start: Chip rev:         v1.0
I (466) heap_init: Initializing. RAM available for dynamic allocation:
I (473) heap_init: At 3FFAE6E0 len 00001920 (6 KiB): DRAM
I (479) heap_init: At 3FFB7E68 len 00028198 (160 KiB): DRAM
I (485) heap_init: At 3FFE0440 len 00003AE0 (14 KiB): D/IRAM
I (491) heap_init: At 3FFE4350 len 0001BCB0 (111 KiB): D/IRAM
I (498) heap_init: At 40096830 len 000097D0 (37 KiB): IRAM
I (506) spi_flash: detected chip: generic
I (509) spi_flash: flash io: dio   
W (513) spi_flash: Detected size(4096k) larger than the size in the binary image header(2048k). Using the size in the binary image header.  
I (527) main_task: Started on CPU0
I (537) main_task: Calling app_main()
I (587) wifi:wifi driver task: 3ffbfe18, prio:23, stack:6656, core=0  
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
I (657) wifi_init: tcp tx win: 5760
I (657) wifi_init: tcp rx win: 5760
I (657) wifi_init: tcp mss: 1440   
I (667) wifi_init: WiFi IRAM OP enabled
I (667) wifi_init: WiFi RX IRAM OP enabled
I (677) phy_init: phy_version 4791,2c4672b,Dec 20 2023,16:06:06       
I (767) wifi:mode : sta (9c:9c:1f:d6:8b:34)
I (767) wifi:enable tsf
I (767) main_task: Returned from app_main()
I (817) smartconfig: SC version: V3.0.1
ets Jun  8 2016 00:22:57

rst:0x1 (POWERON_RESET),boot:0x13 (SPI_FAST_FLASH_BOOT)
configsip: 0, SPIWP:0xee
clk_drv:0x00,q_drv:0x00,d_drv:0x00,cs0_drv:0x00,hd_drv:0x00,wp_drv:0x00
mode:DIO, clock div:2
load:0x3fff0030,len:7172
load:0x40078000,len:15540
load:0x40080400,len:4
0x40080400: _init at ??:?

ho 8 tail 4 room 4
load:0x40080404,len:3904
entry 0x40080640
I (31) boot: ESP-IDF v5.2.2 2nd stage bootloader
I (31) boot: compile time Sep 26 2024 15:12:31
I (31) boot: Multicore bootloader  
I (35) boot: chip revision: v1.0   
I (39) boot.esp32: SPI Speed      : 40MHz
I (43) boot.esp32: SPI Mode       : DIO
I (48) boot.esp32: SPI Flash Size : 2MB
I (52) boot: Enabling RNG early entropy source...
I (58) boot: Partition Table:      
I (61) boot: ## Label            Usage          Type ST Offset   Length
I (69) boot:  0 nvs              WiFi data        01 02 00009000 00006000
I (76) boot:  1 phy_init         RF data          01 01 0000f000 00001000
I (84) boot:  2 factory          factory app      00 00 00010000 00100000
I (91) boot: End of partition table
I (95) esp_image: segment 0: paddr=00010020 vaddr=3f400020 size=20988h (133512) map
I (150) esp_image: segment 1: paddr=000309b0 vaddr=3ffb0000 size=03b84h ( 15236) load
I (155) esp_image: segment 2: paddr=0003453c vaddr=40080000 size=0badch ( 47836) load
I (174) esp_image: segment 3: paddr=00040020 vaddr=400d0020 size=8c588h (574856) map
I (372) esp_image: segment 4: paddr=000cc5b0 vaddr=4008badc size=0ad54h ( 44372) load
I (401) boot: Loaded app from partition at offset 0x10000
I (401) boot: Disabling RNG early entropy source...
I (412) cpu_start: Multicore app   
I (421) cpu_start: Pro cpu start user code
I (421) cpu_start: cpu freq: 160000000 Hz
I (421) cpu_start: Application information:
I (424) cpu_start: Project name:     ESP_WiFi_Smart_config_121        
I (431) cpu_start: App version:      1
I (435) cpu_start: Compile time:     Sep 26 2024 15:12:05
I (441) cpu_start: ELF file SHA256:  0922ecc9f...
I (446) cpu_start: ESP-IDF:          v5.2.2
I (451) cpu_start: Min chip rev:     v0.0
I (456) cpu_start: Max chip rev:     v3.99
I (461) cpu_start: Chip rev:         v1.0
I (466) heap_init: Initializing. RAM available for dynamic allocation:
I (473) heap_init: At 3FFAE6E0 len 00001920 (6 KiB): DRAM
I (479) heap_init: At 3FFB7E68 len 00028198 (160 KiB): DRAM
I (485) heap_init: At 3FFE0440 len 00003AE0 (14 KiB): D/IRAM
I (491) heap_init: At 3FFE4350 len 0001BCB0 (111 KiB): D/IRAM
I (498) heap_init: At 40096830 len 000097D0 (37 KiB): IRAM
I (506) spi_flash: detected chip: generic
I (509) spi_flash: flash io: dio   
W (513) spi_flash: Detected size(4096k) larger than the size in the binary image header(2048k). Using the size in the binary image header.  
I (527) main_task: Started on CPU0
I (537) main_task: Calling app_main()
I (587) wifi:wifi driver task: 3ffbfe18, prio:23, stack:6656, core=0  
I (607) wifi:wifi firmware version: 3e0076f
I (607) wifi:wifi certification version: v7.0
I (607) wifi:config NVS flash: enabled
I (607) wifi:config nano formating: disabled
, ap:<255,255>, sta:<11,0>, prof:1
I (23767) wifi:state: init -> auth (b0)
I (23767) wifi:state: auth -> assoc (0)
I (23777) wifi:state: assoc -> run (10)
I (23797) wifi:connected with AIS 4G Hi-Speed Home WiFi_769475, aid = 7, channel 11, BW20, bssid = 30:0a:c5:9e:94:9f
I (23797) wifi:security: WPA2-PSK, phy: bgn, rssi: -45
I (23827) wifi:pm start, type: 1

I (23827) wifi:dp: 1, bi: 102400, li: 3, scale listen interval from 307200 us to 307200 us
I (23897) wifi:AP's beacon interval = 102400 us, DTIM period = 1
I (24827) esp_netif_handlers: sta ip: 192.168.1.182, mask: 255.255.255.0, gw: 192.168.1.1
I (24827) smartconfig_example: WiFi Connected to ap
I (25177) wifi:<ba-add>idx:0 (ifx:0, 30:0a:c5:9e:94:9f), tid:0, ssn:4, winSize:64
I (27887) smartconfig_example: smartconfig over
I (86987) wifi:<ba-add>idx:1 (ifx:0, 30:0a:c5:9e:94:9f), tid:6, ssn:0, winSize:64
```
