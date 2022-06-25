# Deb Installer

Package Installer for Piscesys.

## Dependencies (For Ubuntu/Debian)

```shell
sudo apt install cmake debhelper qtbase5-dev qtdeclarative5-dev qtquickcontrols2-5-dev libqapt-dev libapt-pkg-dev
```

## Build

```shell
git clone https://github.com/cirily/debinstaller.git 
cd debinstaller
mkdir build
cd build
cmake -DCMAKE_INSTALL_PREFIX:PATH=/usr ..
make
sudo make install
```

## License

This project has been licensed by GPLv3.
