

include $(TOPDIR)/rules.mk

PKG_VERSION:=1.0.3-20240822
PKG_RELEASE:=5

LUCI_TITLE:=LuCI support for Gogs
LUCI_PKGARCH:=all
LUCI_DEPENDS:=+lsblk +docker +dockerd +luci-lib-taskd

define Package/luci-app-gogs/conffiles
/etc/config/gogs
endef

include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature
