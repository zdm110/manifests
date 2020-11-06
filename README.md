# Rockchip Linux SDK

The Default:

To initialize Linux source tree

$ repo init --repo-url=https://github.com/rockchip-linux/repo --no-clone-bundle -u https://github.com/rockchip-linux/manifests

To synchronize the source code

$ repo sync --no-clone-bundle

--

The RK3288 chips


$ repo init --repo-url=https://github.com/rockchip-linux/repo --no-clone-bundle -u https://github.com/rockchip-linux/manifests -b master -m rk3288_linux.xml

$ repo sync --no-clone-bundle

--

The RK3399 chips

$ repo init --repo-url=https://github.com/rockchip-linux/repo --no-clone-bundle -u https://github.com/rockchip-linux/manifests -b master -m rk3399_linux.xml

$ repo sync --no-clone-bundle

--
