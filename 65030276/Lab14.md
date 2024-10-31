PS C:\KS_Lab\smart_config> & set IDF_PATH='c:\Users\anda2\esp\v5.3.1\esp-idf'
PS C:\KS_Lab\smart_config> & 'C:\Users\anda2\.espressif\python_env\idf5.3_py3.11_env\Scripts\python.exe' 'c:\Users\anda2\esp\v5.3.1\esp-idf\tools\idf_monitor.py' -p COM5 -b 115200 --toolchain-prefix xtensa-esp32-elf- --target esp32 'c:\KS_Lab\smart_config\build\smart_config.elf'
--- Warning: GDB cannot open serial ports accessed as COMx
--- Using \\.\COM5 instead...
--- esp-idf-monitor 1.5.0 on \\.\COM5 115200
--- Quit: Ctrl+] | Menu: Ctrl+T | Help: Ctrl+T followed by Ctrl+H
+
B��J☻↕��ѹesp32: SPI Spe�ets Jul 29 2019 12:21:46

rst:0x1 (POWERON_RESET),boot:0x13 (SPI_FAST_FLASH_BOOT)
configsip: 0, SPIWP:0xee
clk_drv:0x00,q_drv:0x00,d_drv:0x00,cs0_drv:0x00,hd_drv:0x00,wp_drv:0x00
mode:DIO, clock div:2
load:0x3fff0030,len:7176
load:0x40078000,len:15564
ho 0 tail 12 room 4
load:0x40080400,len:4
--- 0x40080400: _init at ??:?

load:0x40080404,len:3904
entry 0x40080640
I (31) boot: ESP-IDF v5.3.1 2nd stage bootloader
I (31) boot: compile time Nov  1 2024 05:05:53
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
I (96) esp_image: segment 0: paddr=00010020 vaddr=3f400020 size=20de4h (134628) map
I (150) esp_image: segment 1: paddr=00030e0c vaddr=3ffb0000 size=03f00h ( 16128) load
I (157) esp_image: segment 2: paddr=00034d14 vaddr=40080000 size=0b304h ( 45828) load
I (175) esp_image: segment 3: paddr=00040020 vaddr=400d0020 size=8df9ch (581532) map
I (374) esp_image: segment 4: paddr=000cdfc4 vaddr=4008b304 size=0c048h ( 49224) load
I (406) boot: Loaded app from partition at offset 0x10000
I (406) boot: Disabling RNG early entropy source...
I (418) cpu_start: Multicore app
I (426) cpu_start: Pro cpu start user code
I (426) cpu_start: cpu freq: 160000000 Hz
I (426) app_init: Application information:
I (429) app_init: Project name:     smart_config
I (434) app_init: App version:      1
I (439) app_init: Compile time:     Nov  1 2024 05:05:20
I (445) app_init: ELF file SHA256:  2602d6a0a...
I (450) app_init: ESP-IDF:          v5.3.1
I (455) efuse_init: Min chip rev:     v0.0
I (459) efuse_init: Max chip rev:     v3.99
I (464) efuse_init: Chip rev:         v3.0
I (469) heap_init: Initializing. RAM available for dynamic allocation:
I (477) heap_init: At 3FFAE6E0 len 00001920 (6 KiB): DRAM
I (482) heap_init: At 3FFB8358 len 00027CA8 (159 KiB): DRAM
I (489) heap_init: At 3FFE0440 len 00003AE0 (14 KiB): D/IRAM
I (495) heap_init: At 3FFE4350 len 0001BCB0 (111 KiB): D/IRAM
I (502) heap_init: At 4009734C len 00008CB4 (35 KiB): IRAM
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
I (710) wifi:mode : sta (94:b5:55:f3:98:00)
I (710) wifi:enable tsf
I (720) main_task: Returned from app_main()
I (770) smartconfig: SC version: V3.0.1
I (5600) wifi:ic_enable_sniffer
I (5600) smartconfig: Start to find channel...
I (5600) smartconfig_example: Scan done
I (136000) smartconfig: TYPE: ESPTOUCH
I (136000) smartconfig: T|AP MAC: a8:02:db:e2:51:44
I (136000) smartconfig: Found channel on 4-0. Start to get ssid and password...
I (136010) smartconfig_example: Found channel
I (138970) smartconfig: T|pswd: 220646
I (138970) smartconfig: T|ssid: NUI_2.4G
I (138970) smartconfig: T|bssid: a8:02:db:e2:51:44
I (138970) wifi:ic_disable_sniffer
I (138980) smartconfig_example: Got SSID and password
I (138980) smartconfig_example: Set MAC address of target AP: a8:02:db:e2:51:44
I (138990) smartconfig_example: SSID:NUI_2.4G
I (139000) smartconfig_example: PASSWORD:220646
I (139660) wifi:new:<4,0>, old:<4,0>, ap:<255,255>, sta:<4,0>, prof:1, snd_ch_cfg:0x0
I (139660) wifi:state: init -> auth (0xb0)
I (139670) wifi:state: auth -> assoc (0x0)
I (139680) wifi:state: assoc -> run (0x10)
I (149680) wifi:state: run -> init (0xcc00)
I (149690) wifi:new:<4,0>, old:<4,0>, ap:<255,255>, sta:<4,0>, prof:1, snd_ch_cfg:0x0
I (152110) wifi:new:<4,0>, old:<4,0>, ap:<255,255>, sta:<4,0>, prof:1, snd_ch_cfg:0x0
I (152110) wifi:state: init -> auth (0xb0)
I (152130) wifi:state: auth -> assoc (0x0)
I (152140) wifi:state: assoc -> run (0x10)
I (155240) wifi:state: run -> init (0xfc0)
I (155250) wifi:new:<4,0>, old:<4,0>, ap:<255,255>, sta:<4,0>, prof:1, snd_ch_cfg:0x0
I (157670) wifi:new:<4,0>, old:<4,0>, ap:<255,255>, sta:<4,0>, prof:1, snd_ch_cfg:0x0
I (157670) wifi:state: init -> auth (0xb0)
I (157690) wifi:state: auth -> assoc (0x0)
I (157700) wifi:state: assoc -> run (0x10)
I (167700) wifi:state: run -> init (0xcc00)
I (167710) wifi:new:<4,0>, old:<4,0>, ap:<255,255>, sta:<4,0>, prof:1, snd_ch_cfg:0x0
I (170140) wifi:new:<4,0>, old:<4,0>, ap:<255,255>, sta:<4,0>, prof:1, snd_ch_cfg:0x0
I (170140) wifi:state: init -> auth (0xb0)
I (170150) wifi:state: auth -> assoc (0x0)
I (170160) wifi:state: assoc -> run (0x10)
I (173250) wifi:state: run -> init (0xfc0)
