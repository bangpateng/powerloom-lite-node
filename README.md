<p align="center">
  <img height="250" height="250" src="https://github.com/bangpateng/powerloom-lite-node/assets/38981255/7b334d46-0a49-4d13-81c3-4208d44b216d">

| Join My Sosial Media  | |
| :------------: | :------------: |
| Telegram Group  | [Link](https://t.me/bangpateng_group "Link")  |
| Telegram Chat  | [Link](https://t.me/bangpateng_airdrop "Link")  |
| Twitter  | [Link](https://www.twitter.com/bangpateng_com "Link")  |
|  Youtube | [Link](https://www.youtube.com/c/BangPateng/ "Link")  |
|  Website | [Link](http://www.bangpateng.com "Link")  |
</p>

# POWERLOOM LITE NODE TUTORIAL

- Powerloom Documentation : https://powerloom.network/mint-docs/
- Powerloom Snapshotter Lite Node Rewards Mechanism : https://www.notioniframe.com/fce9931c52cb402fb40987c1f0f80875

### Local System Requirements
For users running the node on personal hardware, the minimum specifications are:

- RAM: At least 4 GB.
- CPU Core: Minimum of 4 Cores
- Disk Space: A minimum of 40 GB.
- Operating System: Windows, macOS, or Linux.
- Python: Ensure Python 3.10 or newer is installed.

### Requirements for Virtual Private Server (VPS)
For those choosing a VPS solution (like AWS, GCP, DigitalOcean, etc.):

- RAM: A minimum of 4 GB.
- CPU Core: Minimum of 4 Cores
- Disk Space: At least 40 GB.
- Operating System: Windows or Linux.
- Python: Ensure Python 3.10 or newer is installed.


## Install Node Powerloom Lite Node

```
apt install -y git && apt install -y screen && curl -fsSL https://get.docker.com -o get-docker.sh && sudo sh get-docker.sh && git clone -b simulation_mode https://github.com/PowerLoom/snapshotter-lite powerloom
```

```
cd powerloom
```
```
screen -S node
```
```
./build.sh
```

## Isi Data Data :

- **SOURCE_RPC_URL Isi :**   Untuk Isi Ini, Kalian Bisa Buat RPC API Sendiri di : https://docs.infura.io/dashboard/create-api (Nanti Salin Link https nya) Untuk Isi Data ini
- **SIGNER_ACCOUNT_ADDRESS Isi :** Memanfaatkan dompet burner untuk alamat akun penandatangan (Gunakan New Wallet)
- **SIGNER_ACCOUNT_PRIVATE_KEY Isi :** Gunakan kunci pribadi dari dompet burner Anda.
- - **Slot_ID :** Masukan ID NFT Kalian

- Save Screen : ```CTRL + A + D```

**TAMBAHAN OPTIONAL**
- Kembali ke Screen : ```screen -r node```

**CATATAN :**
Disarankan untuk menjalankan build.sh di sesi screen atau tmux agar proses terus berjalan bahkan setelah Anda menutup terminal.
