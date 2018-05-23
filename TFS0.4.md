* sudo apt-get install git autoconf build-essential pkg-config automake libboost-all-dev libgmp3-dev libxml2-dev liblua5.1-0-dev libmysqlclient-dev libssl-dev libsqlite3-dev unzip

* git clone --recursive https://github.com/profile/repository.git

* cd otserv_folder

* sudo chmod -R 777 src

* cd src

* ./autogen.sh

* ./configure --enable-mysql --enable-root-permission --enable-server-diag

* ./build.sh