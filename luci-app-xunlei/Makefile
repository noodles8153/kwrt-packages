

include $(TOPDIR)/rules.mk

PKG_VERSION:=1.0.3-20240822
PKG_RELEASE:=7

LUCI_TITLE:=LuCI support for Xunlei
LUCI_PKGARCH:=all
LUCI_DEPENDS:=+lsblk +docker +dockerd +luci-lib-taskd

define Package/luci-app-xunlei/conffiles
/etc/config/xunlei
endef

include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature
