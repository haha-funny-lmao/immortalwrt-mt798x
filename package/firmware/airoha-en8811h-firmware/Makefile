#
# Copyright (C) 2016 MediaTek
#
# This is free software, licensed under the GNU General Public License v2.
# See /LICENSE for more information.
#

include $(TOPDIR)/rules.mk

PKG_NAME:=airoha-en8811h-firmware
PKG_RELEASE:=1
PKG_LICENSE:=GPL-2.0

include $(INCLUDE_DIR)/package.mk

define Package/airoha-en8811h-firmware
  SECTION:=firmware
  CATEGORY:=Firmware
  TITLE:=Airoha EN8811H firmware 
endef

define Package/airoha-en8811h-firmware/description
  This package install Airoha EN8811H firmware.
endef

define Package/airoha-en8811h-firmware/config
endef

define Build/Compile
endef

define Package/airoha-en8811h-firmware/install
	$(INSTALL_DIR) $(1)/lib/firmware/
	$(INSTALL_DATA) ./files/EthMD32.dm.bin $(1)/lib/firmware/
	$(INSTALL_DATA) ./files/EthMD32.DSP.bin $(1)/lib/firmware/
endef

$(eval $(call BuildPackage,airoha-en8811h-firmware))
