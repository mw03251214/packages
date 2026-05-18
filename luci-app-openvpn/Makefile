#
# Copyright (C) 2008-2014 The LuCI Team <luci@lists.subsignal.org>
#
# This is free software, licensed under the Apache License, Version 2.0 .
#

include $(TOPDIR)/rules.mk

PKG_NAME:=luci-app-openvpn
PKG_VERSION:=1.0

LUCI_TITLE:=LuCI Support for OpenVPN
LUCI_DEPENDS:=+luci-base +luci-compat +openvpn-openssl

# include ../../luci.mk
include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature
