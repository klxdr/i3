# i3 config

### adding layout indicator
create blocklet

copy layswitch to /usr/share/i3blocks/
chmod +x /usr/share/i3blocks/layswitch

cp /etc/i3blocks.conf ~/.i3blocks.conf

add
[layswitch]
interval=1

### additional installation

sudo apt install numlockx
sudo apt install i3lock


### xkb
xkb for each window source https://github.com/Zebradil/xkb-switch-i3

