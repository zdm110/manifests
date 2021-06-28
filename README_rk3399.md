# Rockchip Linux SDK

The Default:

To initialize Linux source tree

The RK3399 chips

git clone https://github.com/rockchip-linux/repo 

For Firefly
./repo/repo init -u git@github.com:zdm110/manifests.git -b firefly-rk3399 -m rk3399_linux_firefly.xml

For Nanopi
./repo/repo init -u git@github.com:zdm110/manifests.git -b firefly-rk3399 -m rk3399_linux_nanopi.xml

./repo/repo sync -j4
