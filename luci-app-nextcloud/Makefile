

include $(TOPDIR)/rules.mk

PKG_VERSION:=1.1.1-20240822
PKG_RELEASE:=5

LUCI_TITLE:=LuCI support for nextcloud
LUCI_PKGARCH:=all
LUCI_DEPENDS:=+lsblk +docker +dockerd +luci-lib-taskd

define Package/luci-app-nextcloud/conffiles
/etc/config/nextcloud
endef

include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature
