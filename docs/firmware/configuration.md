# 固件配置

## Wi-Fi 与 Snapserver

节点首次启动进入配网模式（AP），在浏览器中配置：

- Wi-Fi SSID / 密码
- Snapserver 地址（可选：订阅的 `stream_id`）
- 音频输出参数（采样率 / 位深 / 声道）

## 音频输出

默认 I2S 输出 48kHz / 16bit 立体声，可通过引脚配置适配不同 DAC / 功放（PCM5102 / TAS5805M 等）。

## 建议

- 关闭 Wi-Fi 省电模式（`power_save_mode`）
- 加大接收缓冲（如 500ms-1s），抵抗 Wi-Fi 抖动

> TODO：补充完整配置项、默认值与示例。
