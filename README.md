# Open Ledger Node Setup

This repository contains the setup guide and necessary commands for running an Open Ledger Node on a VPS with the specified configuration.

## Requirements

- **VPS** with the following specifications:
  - **RAM:** 4 GB
  - **CPU:** 2 AMD vCPU
  - **Location:** Singapore

## How to Run the Open Ledger Node

Follow these steps to install and run the Open Ledger Node on your VPS:

### 1. **Login to Your VPS**
Login to your VPS using SSH with your credentials:
- **Username:** `root`
- **Password:** Your VPS password

### 2. **Create a Screen Session**
Run the following command to create a screen session:
```bash
screen -Rd openledger
```
3. Download and Install the Script
- Copy and paste the following command into the terminal to download and run the installation script:
```bash
wget -qO- https://raw.githubusercontent.com/dipdown/Node-Crypto/refs/heads/main/OpenLedger/open-ledger.sh | bash
```
- Wait for the installation to complete.

4. Access Remote Desktop
- To interact with the Open Ledger Node:
- PC: Open Remote Desktop Connection.
- Mobile: Use the RDClient app.
- Login with the Username root and the VPS password.

5. Download Open Ledger Node File
- Once logged into the RDP session, open the terminal and run the following command to download the node package:
```bash
wget https://cdn.openledger.xyz/openledger-node-1.0.0-linux.zip
```

6. Extract the Node Files
- Navigate to the directory where the openledger-node-1.0.0-linux.zip file is located using the file manager in your RDP session, right-click the file, and select Extract Here.

7. Run the Node
- Go back to the terminal and run the following command to start the node:
```bash
openledger-node --no-sandbox
```

8. Setup Open Ledger
- Follow the on-screen prompts:
- Login with your Google Account.
- Click Connect and wait until the indicator turns green.

## Done!
## Your Open Ledger Node is now running. ✅

> Notes
- If you don't have a VPS, you can buy one first.
- Make sure to secure your VPS credentials and backup your files.

> License
- This project is licensed under the MIT License - see the LICENSE file for details.
```bash
Jika kamu ingin menggunakan file ini di GitHub, cukup simpan sebagai `README.md` di repositorimu dan push ke GitHub. Jika ada perubahan atau tambahan yang ingin kamu buat, beri tahu saya!
```
