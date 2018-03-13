##This is a hybrid fonts of Yahei and Consolas
sudo mkdir /user/share/fonts/truetype
cp YaheiConsolasHybrid1.12.ttf /usr/share/fonts/truetype
chown root:root YaheiConsolasHybrid1.12.ttf
sudo fc-cache -fv
