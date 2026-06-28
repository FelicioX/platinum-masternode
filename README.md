
# Platinum Masternode Installation

Scripts and tools for deploying and managing Platinum blockchain masternodes.

---

## 🖥 Masternode Manager

The images below show the Platinum Core wallet with the integrated masternode management interface.

### Network Peers

<img width="810" height="396" alt="a38bd7a8-4ff9-469f-b7ed-fff7b9fe1be4" src="https://github.com/user-attachments/assets/bfed56ca-badd-4bf7-b7f6-0ebc9070c108" />

### Masternode List

<img width="1025" height="410" alt="9428da6d-0b58-4569-8b20-8843d28cdc58" src="https://github.com/user-attachments/assets/45faadc3-639c-47b0-8644-481c51a1fd66" />

---

## 📋 Requirements

Before running the installation script, make sure your server meets the following requirements:

- Ubuntu 18.04 LTS or newer
- Root or sudo privileges
- Git
- curl
- wget
- Internet connection

---

## 🚀 Installation

```bash
sudo bash

git clone https://github.com/FelicioX/platinum-masternode.git

cd platinum-masternode

chmod +x mn_platinum.sh

./mn_platinum.sh
```

---

## ⚙ Example Configuration

Example `platinum.conf`

```ini
rpcuser=rpc_user
rpcpassword=your_secure_password

rpcport=54582
rpcallowip=127.0.0.1

daemon=1
listen=1
staking=0

connect=177.125.123.238
connect=157.230.223.211
connect=159.65.240.99
connect=157.230.132.231
connect=178.62.195.103
connect=138.68.85.71
connect=209.97.134.255
connect=159.203.9.176
```

---

## Default Ports

| Service | Port |
|---------|------|
| P2P | 22583 |
| RPC | 54582 |

---

## Features

- Automated masternode installation
- Blockchain synchronization
- RPC configuration
- Network peer configuration
- Masternode management
- Linux deployment script
- Platinum Core compatibility

---

## License

MIT License
