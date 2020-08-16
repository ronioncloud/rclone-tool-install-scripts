# clone-tool-install-scripts
====
Collection of commands to automate installation of a few cloning tools

A modified version of the [rclone](//github.com/rclone/rclone) 
Provide dynamic replacement sa file support for google drive operation

## rclone (beta)
```
curl https://rclone.org/install.sh | sudo bash -s beta
```

## gclone 
```
bash <(wget -qO- https://git.io/gclone.sh)
```

## fclone
```
wget https://github.com/mawaya/rclone/releases/download/fclone-v0.3.1/fclone-v0.3.1-linux-amd64.zip
cd fclone-v0.3.1-linux-amd64&&chmod a+x fclone
sudo mv fclone /usr/bin/
```

## AutoRclone
```
sudo git clone https://github.com/xyou365/AutoRclone && cd AutoRclone && sudo pip install -r requirements.txt
```
