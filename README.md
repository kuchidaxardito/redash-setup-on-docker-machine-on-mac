# Setup script for Redash with Docker on Docker Machine on MacOS

homebrew で次のパッケージをいれておく

* pwgen
* wgen

あとは同じ. `sh setup.sh`

Docker Machine のメモリを多めにとっておいたほうがよさげ

`docker-machine create -d virtualbox --virtualbox-memory "4096" redash`
