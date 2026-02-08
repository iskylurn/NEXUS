# Nexus Node Setup

![image](https://framerusercontent.com/images/rj7WYEn8kN0pgryMvb583AzieU.png)

| X        | Minimum              |
|------------------|----------------------------|   -  https://app.nexus.xyz/ - Sign up for the site using the wallet or email address in the upper right corner.
| **CPU**          | 4+ |
| **RAM**          | 8+                     |
| **SSD**      | 50+ GB                   |
| **Internet**      | 50+ |
| **Ubuntu**      | Ubuntu 24 |
  

-  ## 1. Install core tools for building the node : 

```bash
sudo apt update && sudo apt upgrade -y
```
```bash
sudo apt install curl iptables build-essential git -y
```

-  ## 2. Install Rust & Cargo : 

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
source $HOME/.cargo/env
```
