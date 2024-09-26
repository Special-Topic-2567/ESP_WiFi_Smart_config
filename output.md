```
load:0x40080404,len:3904     
entry 0x40080640
I (31) boot: ESP-IDF v5.3.1 2nd stage bootloader
I (31) boot: compile time Sep 26 2024 15:19:32
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
I (95) esp_image: segment 0: paddr=00010020 vaddr=3f400020 size=20de4h (134628) map
I (150) esp_image: segment 1: paddr=00030e0c vaddr=3ffb0000 size=03f00h ( 16128) load
I (156) esp_image: segment 2: paddr=00034d14 vaddr=40080000 size=0b304h ( 45828) load
I (174) esp_image: segment 3: paddr=00040020 vaddr=400d0020 size=8df9ch (581532) map
I (374) esp_image: segment 4: paddr=000cdfc4 vaddr=4008b304 size=0c048h ( 49224) load
I (405) boot: Loaded app from partition at offset 0x10000
I (405) boot: Disabling RNG early entropy source...
I (417) cpu_start: Multicore app
I (425) cpu_start: Pro cpu start user code
I (425) cpu_start: cpu freq: 160000000 Hz
I (426) app_init: Application information:
I (428) app_init: Project name:     smart_config
I (434) app_init: App version:      1
I (438) app_init: Compile time:     Sep 26 2024 15:19:02
I (444) app_init: ELF file SHA256:  e160c722f...
I (449) app_init: ESP-IDF:          v5.3.1
I (454) efuse_init: Min chip rev:     v0.0
I (459) efuse_init: Max chip rev:     v3.99 
I (464) efuse_init: Chip rev:         v1.0
I (469) heap_init: Initializing. RAM available for dynamic allocation:
I (476) heap_init: At 3FFAE6E0 len 00001920 (6 KiB): DRAM
I (482) heap_init: At 3FFB8358 len 00027CA8 (159 KiB): DRAM
I (488) heap_init: At 3FFE0440 len 00003AE0 (14 KiB): D/IRAM
I (494) heap_init: At 3FFE4350 len 0001BCB0 (111 KiB): D/IRAM
I (501) heap_init: At 4009734C len 00008CB4 (35 KiB): IRAM
I (509) spi_flash: detected chip: generic
I (512) spi_flash: flash io: dio
W (516) spi_flash: Detected size(4096k) larger than the size in the binary image header(2048k). Using the size in the binary image header.
I (530) main_task: Started on CPU0
I (540) main_task: Calling app_main()
I (560) wifi:wifi driver task: 3ffc0180, prio:23, stack:6656, core=0
I (560) wifi:wifi firmware version: ccaebfa
I (560) wifi:wifi certification version: v7.0
I (560) wifi:config NVS flash: enabled
I (560) wifi:config nano formating: disabled
I (570) wifi:Init data frame dynamic rx buffer num: 32
I (570) wifi:Init static rx mgmt buffer num: 5
I (580) wifi:Init management short buffer num: 32
I (580) wifi:Init dynamic tx buffer num: 32
I (580) wifi:Init static rx buffer size: 1600
I (590) wifi:Init static rx buffer num: 10
I (590) wifi:Init dynamic rx buffer num: 32
I (600) wifi_init: rx ba win: 6
I (600) wifi_init: accept mbox: 6
I (600) wifi_init: tcpip mbox: 32
I (610) wifi_init: udp mbox: 6
I (610) wifi_init: tcp mbox: 6
I (610) wifi_init: tcp tx win: 5760
I (620) wifi_init: tcp rx win: 5760
I (620) wifi_init: tcp mss: 1440
I (630) wifi_init: WiFi IRAM OP enabled
I (630) wifi_init: WiFi RX IRAM OP enabled
I (640) phy_init: phy_version 4830,54550f7,Jun 20 2024,14:22:08
I (720) wifi:mode : sta (58:bf:25:8c:14:64)
I (720) wifi:enable tsf
I (720) main_task: Returned from app_main()
I (780) smartconfig: SC version: V3.0.1
W (2050) wifi:exceed max band, 2g, ngroup:4
I (5610) wifi:ic_enable_sniffer
I (5610) smartconfig: Start to find channel...
I (5620) smartconfig_example: Scan done
I (56110) smartconfig: TYPE: ESPTOUCH
I (56110) smartconfig: T|AP MAC: 30:0a:c5:9e:94:9f
I (56110) smartconfig: Found channel on 11-0. Start to get ssid and password...
I (56120) smartconfig_example: Found channel
I (56310) smartconfig: TYPE: ESPTOUCH
I (56310) smartconfig: Found channel on 11-0. Start to get ssid and password...
I (56310) smartconfig_example: Found channel
I (60130) smartconfig: F|pswd: 50769475
I (60130) smartconfig: F|ssid: AIS 4G Hi-Speed Home WiFi_76947550769475
I (60130) smartconfig: F|bssid: 30:0a:c5:9e:94:9f
I (60140) wifi:ic_disable_sniffer
I (60140) smartconfig_example: Got SSID and password
I (60140) smartconfig_example: Set MAC address of target AP: 30:0a:c5:9e:94:9f 
I (60150) smartconfig_example: SSID:AIS 4G Hi-Speed Home WiFi_769475
I (60160) smartconfig_example: PASSWORD:50769475
W (60170) wifi:Password length matches WPA2 standards, authmode threshold changes from OPEN to WPA2
I (61680) wifi:new:<11,0>, old:<11,0>, ap:<255,255>, sta:<11,0>, prof:1, snd_ch_cfg:0x0
I (61680) wifi:state: init -> auth (0xb0)
I (61700) wifi:state: auth -> assoc (0x0)
I (61710) wifi:state: assoc -> run (0x10)
I (61730) wifi:connected with AIS 4G Hi-Speed Home WiFi_769475, aid = 1, channel 11, BW20, bssid = 30:0a:c5:9e:94:9f
I (61730) wifi:security: WPA2-PSK, phy: bgn, rssi: -50
I (61750) wifi:pm start, type: 1

I (61750) wifi:dp: 1, bi: 102400, li: 3, scale listen interval from 307200 us to 307200 us
I (61830) wifi:AP's beacon interval = 102400 us, DTIM period = 1
I (62760) esp_netif_handlers: sta ip: 192.168.1.198, mask: 255.255.255.0, gw: 192.168.1.1
I (62760) smartconfig_example: WiFi Connected to ap
I (62900) wifi:<ba-add>idx:0 (ifx:0, 30:0a:c5:9e:94:9f), tid:6, ssn:0, winSize:64
I (62910) wifi:<ba-add>idx:1 (ifx:0, 30:0a:c5:9e:94:9f), tid:0, ssn:4, winSize:64
I (65800) smartconfig_example: smartconfig over
```
