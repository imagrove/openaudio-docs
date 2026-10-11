# 固件烧录

将 OpenAudio 固件烧录到 ESP32 节点。

## 方式一：Web 一键烧录（推荐）

> TODO：接入 Web Installer（基于 ESP Web Tools）。

## 方式二：本地编译烧录

```bash
# 需先安装 ESP-IDF
idf.py set-target esp32s3
idf.py build
idf.py -p /dev/ttyUSB0 flash monitor
```

> TODO：补充分区表、DAC/I2S 引脚配置与常见报错。
