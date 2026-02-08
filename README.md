# Nexus Node Setup

![image](https://framerusercontent.com/images/rj7WYEn8kN0pgryMvb583AzieU.png)

-  ## https://app.nexus.xyz/ - Sign up for the site using the EVM Wallet or Email address in the upper right corner. :

| X        | Minimum              |
|------------------|----------------------------|
| **CPU**          | 4+ |
| **RAM**          | 8+                     |
| **SSD**      | 50+ GB                   |
| **Internet**      | 50+ |
| **Ubuntu**      | Ubuntu 24 |
  

-  ## 1. Install Core Tools : 

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
