## Chiaki link Source : 
https://github.com/zicos77/chiaki

## Linux :
```
apt-get update -y
apt-get install git cmake python3-pip qt5-default qtmultimedia5-dev python3-pyqt5.qtopengl python-pyqt5.qtsvg libqt5svg5-dev pyqt5-dev python-pyqt5.qtsvg ffmpeg x264 libavcodec-dev libopus-dev openssl protobuf-compiler libssl-dev libsdl2-dev -y
pip3 uninstall protobuf -y
pip3 uninstall google -y
pip3 install google
pip3 install protobuf
git clone https://github.com/zicos77/chiaki.git
cd chiaki
git submodule update --init
mkdir build && cd build
cmake ../ -DCMAKE_INSTALL_PREFIX=/home/Chiaki_Bin
make
make install
cd /home/Chiaki_Bin
```

## All credit :
thestr4ng3r (Florian Märkl)
