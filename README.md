# A Duck's Wanderings

A work-in-progress game featuring Charles the Duck.



Current instructions on how to install on Debian:

`sudo apt-get install libboost-regex-dev libboost-locale-dev build-essential autoconf automake cmake git gitk git-gui vim vim-scripts libsdl2-dev libcairo-dev libsdl2-image-dev libsdl2-ttf-dev libsdl2-mixer-dev libboost-filesystem-dev libglew-dev libvorbis-dev`
`git clone https://github.com/anura-engine/anura.git`
`git submodule init`
`git submodule update`
run `make` or `make -j$(nproc)`
`cd modules`
`git clone https://github.com/frogatto/frogatto.git`
`git clone https://github.com/A-Ducks-Wanderings/a-ducks-wanderings.git`

navigate into anura/modules and rename `frogatto` to `frogatto4`

then run `./anura --log-file=a-ducks-wanderings.txt --module=frogatto4 --module=a-ducks-wanderings`