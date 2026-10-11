# Snapserver 安装

## Debian / Ubuntu / Armbian

```bash
sudo apt update
sudo apt install snapserver
sudo systemctl enable --now snapserver
```

## 多流配置（分区独立播放）

`/etc/snapserver.conf` 示例：

```ini
[stream]
source = pipe:///tmp/snapfifo_kitchen?name=Kitchen&sampleformat=48000:16:2

[stream]
source = pipe:///tmp/snapfifo_bedroom?name=Bedroom&sampleformat=48000:16:2
```

> TODO：补充 AirPlay（Shairport-Sync）、蓝牙（BlueALSA）音源接入与 systemd 模板。
