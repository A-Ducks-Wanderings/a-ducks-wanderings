# A Duck's Wanderings

A work-in-progress game featuring Charles the Duck.

Our Discord: https://discord.gg/YqReqJr7We

Current instructions on how to install on Debian:

`sudo apt-get install libboost-regex-dev libboost-locale-dev build-essential autoconf automake cmake git gitk git-gui vim vim-scripts libsdl2-dev libcairo-dev libsdl2-image-dev libsdl2-ttf-dev libsdl2-mixer-dev libboost-filesystem-dev libglew-dev libvorbis-dev libglm-dev`

`git clone https://github.com/anura-engine/anura.git --recurse-submodules`

`cd anura`

`git submodule init`

`git submodule update`

run `make` or `make -j$(nproc)`

`git clone https://github.com/A-Ducks-Wanderings/a-ducks-wandering.git modules/a-ducks-wanderings`

then run `./anura --log-file=a-ducks-wanderings.txt --module=a-ducks-wanderings`