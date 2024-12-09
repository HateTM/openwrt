#Owned by DairyMan@Whirlpool
#
#Copyright GNU act.
include $(TOPDIR)/rules.mk

PKG_NAME:=rooter
PKG_VERSION:=4.500
PKG_RELEASE:=1

PKG_MAINTAINER:=Created by DM/makefile by Cobia@whirlpool
include $(INCLUDE_DIR)/package.mk

define Package/rooter
  SECTION:=utils
  CATEGORY:=ROOter
  SUBMENU:=Basic Support
  DEPENDS:=+luci +luci-app-ddns +luci-compat \
 		+kmod-usb-net +kmod-usb-net-huawei-cdc-ncm +kmod-usb-net-cdc-ether +kmod-usb-acm \
		+kmod-usb-net-qmi-wwan  +kmod-usb-net-rndis +kmod-usb-serial-qualcomm \
		+kmod-usb-net-sierrawireless +kmod-usb-ohci +kmod-usb-serial +kmod-nls-utf8 \
		+kmod-usb-serial-option +kmod-usb-serial-sierrawireless \
		+kmod-usb-uhci +kmod-usb2 +iptables \
		+usb-modeswitch +wireless-tools \
		+luci-proto-qmi +luci-proto-mbim +mbim-utils +qmi-utils +umbim +uqmi \
		+kmod-rt2800-usb +xxd +kmod-tcp-bbr +ddns-scripts \
		+464xlat +luci-app-openvpn +luci-proto-wireguard \
		+ca-bundle +ca-certificates \
		+luci-app-ksmbd +kmod-usb-storage \
		+luci-app-sqm +kmod-sched-cake +luci-app-nft-qos \
		+openvpn-easy-rsa +openvpn-openssl +luci-app-wol \
		+usbmuxd +libusbmuxd-utils +libimobiledevice-utils +kmod-usb-net-ipheth \
		+luci-ssl +usbutils +openssl-util +ethtool \
		+nano +picocom +wget +luci-app-vpnbypass +qfirehose
  TITLE:=ROOter support for usbmodems
  PKGARCH:=all
endef

define Package/rooter/description
  Helper scripts to enable ROOter to manage usb modem interfaces
endef


define Build/Compile
endef

$(eval $(call BuildPackage,rooter))
