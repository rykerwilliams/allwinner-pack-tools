allwinner-pack-tools
====================

To pack a LiveSuit image under linux, you need to pack tool from this repo.

To get the LiveSuit for Linux do something like the following:

mkdir cubie; cd cubie
git clone https://github.com/matson-hall/allwinner-pack-tools.git
cd allwinner-pack-tools
git checkout cubieboard
cp tools/Livesuit-linux.zip <destination>
cd <destination>
unzip Livesuit-linux.zip
cd LiveSuit_For_Linux64
chmod +x LiveSuit.run
./LiveSuit.run
