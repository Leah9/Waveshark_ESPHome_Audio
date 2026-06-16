# 🌊 Waveshark ESP32-S3 Audio Board — ESPHome Config

> A working configuration for streaming audio via Music Assistant / SendSpin on the Waveshark ESP32-S3 board.

[![ESPHome Version](https://img.shields.io/badge/ESPHome-2026.5.3-blue)]()
[![Board](https://img.shields.io/badge/ESP32--S3-Waveshark-green)]()
[![License](https://img.shields.io/badge/License-MIT-orange)]()

---

## ⚙️ Setup Requirements

- **ESPHome Version:** `2026.5.3` (tested & confirmed)
- **Home Assistant Integration:** Music Assistant + SendSpin
- **Secrets:** Ensure your ESPHome `secrets` names in ESPHome match the config or update accordingly.

---

## 📦 Configuration Files

| File | Purpose |
|------|---------|
| `WorkingBackup.yaml` | Minimal config for basic functionality and board verification |
|  *(coming soon)* | Expanded features with more integrations enabled |

### Device Naming

The device name displayed in Music Assistant / SendSpin is configured by changing the `id` under the sendspin section:

> 💡 Change `sendspin_hub` to any unique identifier you prefer.

```yaml
sendspin:
id: sendspin_hub
task_stack_in_psram: true
```

---

## 🛠 Quick Start

1. Clone or download the configuration files
2. Update `secrets` with your Wi-Fi credentials and other secrets
3. Flash `WorkingBackup.yaml` first to verify board functionality
4. Expand to full config once base functionality is confirmed

---

## 🚧 Roadmap

Additional features are being added as they're tested on the HA installation:

- [ ] Micro wake word support
- [ ] Home Assistant announcements
- [ ] LED status indicators
- [ ] Power optimization for battery/solar operation

---

## 🤝 Contributing / Questions

---

*Built with 🎵 and ESPHome vibes.*