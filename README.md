# i3 config
create blocklet

copy layoutindicator to /usr/share/i3blocks/
chmod +x /usr/share/i3blocks/layoutindicator

cp /etc/i3blocks.conf ~/.i3blocks.conf

add
[layoutindicator]
interval=1

### additional installation

sudo apt install numlockx
sudo apt install i3lock


