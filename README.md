# Dawn Validator Auto Miner

#### Siapkan Bahan Bahan

- Install Extension Dawn dan Sudah Punya Akun
- Token Bot Father
- ID Telegram
- Ip Proxy (Optional)
- Mainkan

### 1. Install

```
bash <(curl -s https://file.winsnip.xyz/file/uploads/DawnBot.sh)
```
### 2. Check Log dan Restart

```
#check log
sudo journalctl -u dawnbot -f
```

```
#restart
sudo systemctl restart dawnbot
```

### 3. Hapus Validator

```
sudo systemctl stop dawnbot && \
sudo systemctl disable dawnbot && \
sudo rm /etc/systemd/system/dawnbot.service && \
sudo systemctl daemon-reload && \
sudo rm -rf /root/DawnBot 
```

