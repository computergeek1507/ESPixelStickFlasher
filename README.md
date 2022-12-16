### ESPixelStickFlasher

Flash ESPixelStick Firmware and settings. Requires esptool.py

### Building
Uses C++23, QT 5.15, spdlog, and cMake 3.20.

```git clone https://github.com/computergeek1507/ESPixelStickFlasher.git```

To build on Windows, use Visual Studio 2022

```VS2022.bat```

If you get a qt cmake error, update the QT location in batch file.

To build on Linux with g++(tested on Mint Linux 21).

```
mkdir build
cd build
cmake ..
cmake --build .
./ESPixelStickFlasher
```
