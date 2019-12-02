# OpenWrt luci feed

## Description

This is the OpenWrt "luci"-feed containing LuCI - OpenWrt Configuration Interface forked from openwrt/luci and Hostle/openwrt-luci-multi-user with multi user management.

## Usage

copy root directory to feeds/luci directory.excute
```shell
cd luci

cp -rf /path-to-project ./

patch -p1 < luci_17.01.patch #for lede-17.01 branch

patch -p1 < luci_18.06.patch #for openwrt-18.06 branch
```

## photoshots

![image](https://github.com/liudonghua/admin-multi-users-luci/blob/master/images/photoshot.jpg)
