# rclone-tool-scripts
A few commands to automate installation of a few cloning tools.

### rclone (beta):
```
curl https://rclone.org/install.sh | sudo bash -s beta
```

### gclone:
```
sudo su -c "bash <(wget -qO- https://git.io/gclone.sh)" root
```

### fclone:
``` 
sudo curl -fsSL https://git.io/fclone.sh | sudo bash
```

### AutoRclone:
```
sudo git clone https://github.com/xyou365/AutoRclone && cd AutoRclone && sudo pip install -r requirements.txt
```

Sources:
* [rclone](//github.com/rclone/rclone)
* [gclone](//github.com/donwa/gclone)
* [fclone](//github.com/mawaya/rclonee)
* [AutoRclone](//github.com/xyou365/AutoRclone)
