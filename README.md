# clone-tool-scripts
Collection of commands to automate installation of a few cloning tools

## rclone (beta)
```
curl https://rclone.org/install.sh | sudo bash -s beta
```

## gclone
```
sudo su -c "bash <(wget -qO- https://git.io/gclone.sh)" root
```

## fclone
```
sudo su -c "bash <(wget -qO- https://yuuu.uno/fclone.sh)" root
```

## AutoRclone
```
sudo git clone https://github.com/xyou365/AutoRclone && cd AutoRclone && sudo pip install -r requirements.txt
```
