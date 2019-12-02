# OpenWrt luci feed

## Description

This is the OpenWrt "luci"-feed containing LuCI - OpenWrt Configuration Interface sourced from [openwrt/luci](https://github.com/openwrt/luci) and [Hostle/openwrt-luci-multi-user](https://github.com/Hostle/openwrt-luci-multi-user) with multi user management.

## Usage

copy root directory to feeds/luci directory.excute
``` shella
cd luci

cp -rf /path-to-project ./

patch -p1 < luci_17.01.patch #for lede-17.01 branch

patch -p1 < luci_18.06.patch #for openwrt-18.06 branch

make package/symlinks-install

```

Please reference to [openWrt](https://github.com/openwrt/openwrt) for build firmware.

## photoshots

![image](https://github.com/liudonghua/admin-multi-users-luci/blob/master/images/photoshot.png)
