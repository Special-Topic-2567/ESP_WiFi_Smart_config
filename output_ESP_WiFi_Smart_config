I (31) boot: ESP-IDF v5.3 2nd stage bootloader
I (31) boot: compile time Sep 26 2024 15:16:27
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
I (83) boot:  2 factory          factory app      00 00 00010000 00100000
I (91) boot: End of partition table
I (95) esp_image: segment 0: paddr=00010020 vaddr=3f400020 size=20be8h (134120) map
I (150) esp_image: segment 1: paddr=00030c10 vaddr=3ffb0000 size=03e58h ( 15960) load
I (156) esp_image: segment 2: paddr=00034a70 vaddr=40080000 size=0b5a8h ( 46504) load
I (174) esp_image: segment 3: paddr=00040020 vaddr=400d0020 size=8db58h (580440) map
I (373) esp_image: segment 4: paddr=000cdb80 vaddr=4008b5a8 size=0bc48h ( 48200) load
I (404) boot: Loaded app from partition at offset 0x10000
I (404) boot: Disabling RNG early entropy source...
I (416) cpu_start: Multicore app
I (424) cpu_start: Pro cpu start user code
I (424) cpu_start: cpu freq: 160000000 Hz
I (425) app_init: Application information:
I (427) app_init: Project name:     ESP_WiFi_Smart_config
I (433) app_init: App version:      1
I (438) app_init: Compile time:     Sep 26 2024 15:15:15
I (444) app_init: ELF file SHA256:  23a0e3d23...
I (449) app_init: ESP-IDF:          v5.3
I (454) efuse_init: Min chip rev:     v0.0
I (458) efuse_init: Max chip rev:     v3.99
I (463) efuse_init: Chip rev:         v1.0
I (469) heap_init: Initializing. RAM available for dynamic allocation:
I (476) heap_init: At 3FFAE6E0 len 00001920 (6 KiB): DRAM
I (482) heap_init: At 3FFB82A8 len 00027D58 (159 KiB): DRAM
I (488) heap_init: At 3FFE0440 len 00003AE0 (14 KiB): D/IRAM
I (494) heap_init: At 3FFE4350 len 0001BCB0 (111 KiB): D/IRAM
I (501) heap_init: At 400971F0 len 00008E10 (35 KiB): IRAM
I (508) spi_flash: detected chip: generic
I (511) spi_flash: flash io: dio
W (515) spi_flash: Detected size(4096k) larger than the size in the binary image header(2048k). Using the size in the binary image header.
I (529) main_task: Started on CPU0
I (539) main_task: Calling app_main()
I (569) wifi:wifi driver task: 3ffc025c, prio:23, stack:6656, core=0
I (579) wifi:wifi firmware version: 0caa81945
I (579) wifi:wifi certification version: v7.0
I (579) wifi:config NVS flash: enabled
I (579) wifi:config nano formating: disabled
I (579) wifi:Init data frame dynamic rx buffer num: 32
I (589) wifi:Init static rx mgmt buffer num: 5
I (589) wifi:Init management short buffer num: 32
I (599) wifi:Init dynamic tx buffer num: 32
I (599) wifi:Init static rx buffer size: 1600
I (609) wifi:Init static rx buffer num: 10
I (609) wifi:Init dynamic rx buffer num: 32
I (609) wifi_init: rx ba win: 6
I (619) wifi_init: accept mbox: 6
I (619) wifi_init: tcpip mbox: 32
I (619) wifi_init: udp mbox: 6
I (629) wifi_init: tcp mbox: 6
I (629) wifi_init: tcp tx win: 5760
I (639) wifi_init: tcp rx win: 5760
I (639) wifi_init: tcp mss: 1440
I (639) wifi_init: WiFi IRAM OP enabled
I (649) wifi_init: WiFi RX IRAM OP enabled
I (649) phy_init: phy_version 4830,54550f7,Jun 20 2024,14:22:08
I (739) wifi:mode : sta (9c:9c:1f:d5:6a:00)
I (739) wifi:enable tsf
I (739) main_task: Returned from app_main()
I (789) smartconfig: SC version: V3.0.1
I (5629) wifi:ic_enable_sniffer
I (5629) smartconfig: Start to find channel...
I (5629) smartconfig_example: Scan done
I (36759) smartconfig: TYPE: ESPTOUCH
I (36759) smartconfig: T|AP MAC: 30:0a:c5:9e:94:9f
I (36759) smartconfig: Found channel on 11-0. Start to get ssid and password...
I (36759) smartconfig_example: Found channel
I (36969) smartconfig: TYPE: ESPTOUCH
I (36969) smartconfig: Found channel on 11-0. Start to get ssid and password...
I (36969) smartconfig_example: Found channel
I (42179) smartconfig: F|pswd: 50769475
I (42179) smartconfig: F|ssid: AIS 4G Hi-Speed Home WiFi_76947550769475
I (42179) smartconfig: F|bssid: 30:0a:c5:9e:94:9f
I (42179) wifi:ic_disable_sniffer
I (42179) smartconfig_example: Got SSID and password
I (42189) smartconfig_example: Set MAC address of target AP: 30:0a:c5:9e:94:9f 
I (42199) smartconfig_example: SSID:AIS 4G Hi-Speed Home WiFi_769475
I (42199) smartconfig_example: PASSWORD:50769475
I (42519) wifi:new:<11,0>, old:<11,0>, ap:<255,255>, sta:<11,0>, prof:1, snd_ch_cfg:0x0
I (42519) wifi:state: init -> auth (0xb0)
I (42529) wifi:state: auth -> assoc (0x0)
I (42549) wifi:state: assoc -> run (0x10)
I (42559) wifi:connected with AIS 4G Hi-Speed Home WiFi_769475, aid = 8, channel 11, BW20, bssid = 30:0a:c5:9e:94:9f
I (42559) wifi:security: WPA2-PSK, phy: bgn, rssi: -46
I (42569) wifi:pm start, type: 1

I (42579) wifi:dp: 1, bi: 102400, li: 3, scale listen interval from 307200 us to 307200 us
I (42589) wifi:AP's beacon interval = 102400 us, DTIM period = 1
I (43559) wifi:<ba-add>idx:0 (ifx:0, 30:0a:c5:9e:94:9f), tid:6, ssn:0, winSize:64
I (43569) wifi:<ba-add>idx:1 (ifx:0, 30:0a:c5:9e:94:9f), tid:0, ssn:4, winSize:64
I (44079) esp_netif_handlers: sta ip: 192.168.1.189, mask: 255.255.255.0, gw: 192.168.1.1
I (44079) smartconfig_example: WiFi Connected to ap
I (47149) smartconfig_example: smartconfig over
