### MycroftSkillInstaller

## Installation
```bash
sudo apt-get install qml-module-qmltermwidget
git clone https://github.com/AIIX/MycroftSkillInstaller
```
Build instructions:

- git clone https://github.com/AIIX/MycroftSkillInstaller/
-  mkdir build
-  cd build
- cmake .. -DCMAKE_INSTALL_PREFIX=/usr -DCMAKE_BUILD_TYPE=Release -DKDE_INSTALL_LIBDIR=lib -DKDE_INSTALL_USE_QT_SYS_PATHS=ON
-  make
- sudo make install
