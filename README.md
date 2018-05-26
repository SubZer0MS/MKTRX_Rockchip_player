# MKTRX_Rockchip_player
The Rockchip player example for ASUS Tinker board modified to add additional features

# Build
sudo apt-get install qt5-default qt5-qmake libegl1-mesa libgles2-mesa qtmultimedia5-dev libqt5multimediawidgets5 libqt5multimedia5-plugins libqt5multimedia5

export QT_SELECT=5

qmake -project & qmake & make
