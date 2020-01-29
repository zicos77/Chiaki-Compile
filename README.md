## Chiaki link Source : 
https://github.com/zicos77/chiaki

## linux commands :
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
## Windows:
# Software :
Git
# 
Visual Studio 2017 or 2019 (for the commands below in version 2017)
# 
mingw64
# Commands :
```
git clone -q --branch=master https://github.com/zicos77/chiaki.git C:\chiaki
git submodule update --init --recursive
call "C:\Program Files (x86)\Microsoft Visual Studio\2017\Community\VC\Auxiliary\Build\vcvarsall.bat" x64
C:\msys64\usr\bin\bash -lc "cd \"%APPVEYOR_BUILD_FOLDER%\" && scripts/appveyor.sh"
```
## Credit :
thestr4ng3r (Florian Märkl)
