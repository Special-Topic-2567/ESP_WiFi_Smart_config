<<<<<<< HEAD
| Supported Targets | ESP32 | ESP32-C2 | ESP32-C3 | ESP32-C6 | ESP32-S2 | ESP32-S3 |
| ----------------- | ----- | -------- | -------- | -------- | -------- | -------- |

# smartconfig Example

This example shows how ESP32 connects to a target AP with ESPTOUCH.

## How to use example

### Hardware Required

Download ESPTOUCH APP from app store:
[Android source code](https://github.com/EspressifApp/EsptouchForAndroid)
[iOS source code](https://github.com/EspressifApp/EsptouchForIOS) is available.

### Configure the project

```
idf.py menuconfig
```

### Build and Flash

Build the project and flash it to the board, then run monitor tool to view serial output:

```
idf.py -p PORT flash monitor
```

(To exit the serial monitor, type ``Ctrl-]``.)

See the Getting Started Guide for full steps to configure and use ESP-IDF to build projects.

## Example output

* Make sure your phone connect to the target AP (2.4GHz).
* Open ESPTOUCH app and input password. There will be success message after few sec.

Here is an example of smartconfig console output.
```
I (372) wifi: mode : sta (24:0a:c4:00:44:86)
I (422) smartconfig: SC version: V2.6.6
I (3802) wifi: ic_enable_sniffer
I (3802) sc: SC_STATUS_FIND_CHANNEL
I (234592) smartconfig: TYPE: ESPTOUCH
I (234592) smartconfig: T|PHONE MAC:68:3e:34:88:59:bf
I (234592) smartconfig: T|AP MAC:a4:56:02:47:30:07
I (234592) sc: SC_STATUS_GETTING_SSID_PSWD
I (239922) smartconfig: T|pswd: 123456789
I (239922) smartconfig: T|ssid: IOT_DEMO_TEST
I (239922) smartconfig: T|bssid: a4:56:02:47:30:07
I (239922) wifi: ic_disable_sniffer
I (239922) sc: SC_STATUS_LINK
I (239932) sc: SSID:IOT_DEMO_TEST
I (239932) sc: PASSWORD:123456789
I (240062) wifi: n:1 0, o:1 0, ap:255 255, sta:1 0, prof:1
I (241042) wifi: state: init -> auth (b0)
I (241042) wifi: state: auth -> assoc (0)
I (241052) wifi: state: assoc -> run (10)
I (241102) wifi: connected with IOT_DEMO_TEST, channel 1
I (244892) event: ip: 192.168.0.152, mask: 255.255.255.0, gw: 192.168.0.1
I (244892) sc: WiFi Connected to ap
I (247952) sc: SC_STATUS_LINK_OVER
I (247952) sc: Phone ip: 192.168.0.31
I (247952) sc: smartconfig over
```
=======
# ESP_WiFi_Smart_config

1. เปิดโปรแกรมตัวอย่าง `smart_config`
2. build, flash และ monitor โปรแกรม
3. ดาวน์โหลด application `ESPTouch`
4. เชื่อมมือถือเข้ากับ WiFi access point
5. ทำการ config โดยการป้อน WiFi password


บันทึก output log ส่งขึ้น github 


![image](https://github.com/user-attachments/assets/470f5279-a7b3-436e-a2b9-077d21b2e7a7)



![image](https://github.com/user-attachments/assets/12094242-d7eb-43a9-818a-8902c5a5b294)



![image](https://github.com/user-attachments/assets/73104400-f596-472e-a57d-61dff2c474b2)


![image](https://github.com/user-attachments/assets/05488ab1-ff0f-44ba-a9c1-4dd35b24d70e)


![image](https://github.com/user-attachments/assets/7e4a1961-c881-43a4-98e8-72cf5993a322)

![460391218_1444711516162806_69295526798896405_n](https://github.com/user-attachments/assets/f336eb5d-d64d-4864-a77f-644b528c7714)

![460509625_9027644577265335_6489010242228799938_n](https://github.com/user-attachments/assets/0ddfc18b-bca9-4360-ae98-b42657cc7b33)


![461295444_2916137565220397_1351007937772917759_n](https://github.com/user-attachments/assets/001d2399-6701-4488-84f9-48aac83f1cb3)




https://github.com/AnchisaPhetnoi/smart_config.git






>>>>>>> 6576252ae34a6e88211ea5255cf0202a1334c18a
