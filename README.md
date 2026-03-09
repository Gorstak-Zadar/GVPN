# 🌐 GVPN

> Python script to **connect to free VPN servers** from VPNGate API — selects closest server by ping, uses Windows `rasdial` for connection.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 📡 **VPNGate API** | Fetches server list from vpngate.net |
| 🏆 **Closest Server** | Sorts by ping, selects lowest |
| 🔌 **rasdial** | Uses Windows built-in VPN client |
| 📝 **Logging** | Logs to `vpn.log` |
| ⚙️ **Auto-Install** | Installs `requests` if missing |

---

## 📋 Requirements

| Requirement | Details |
|-------------|---------|
| **OS** | Windows (rasdial) |
| **Python** | 3.x |
| **requests** | `pip install requests` |

---

## 🚀 Usage

```bash
python GVpn.py
```

---

## ⚠️ Note

Uses free VPN servers; security and privacy vary. Use at your own risk.

---

<p align="center">
  <sub>🌐 Gorstak Utilities</sub>
</p>
