#
# Makefile for misc devices that really don't fit anywhere else.
#

obj-$(CONFIG_IBM_ASM)		+= ibmasm/
obj-$(CONFIG_AD525X_DPOT)	+= ad525x_dpot.o
obj-$(CONFIG_AD525X_DPOT_I2C)	+= ad525x_dpot-i2c.o
obj-$(CONFIG_AD525X_DPOT_SPI)	+= ad525x_dpot-spi.o
obj-$(CONFIG_INTEL_MID_PTI)	+= pti.o
obj-$(CONFIG_ATMEL_SSC)		+= atmel-ssc.o
obj-$(CONFIG_ATMEL_TCLIB)	+= atmel_tclib.o
obj-$(CONFIG_BMP085)		+= bmp085.o
obj-$(CONFIG_BMP085_I2C)	+= bmp085-i2c.o
obj-$(CONFIG_BMP085_SPI)	+= bmp085-spi.o
obj-$(CONFIG_DUMMY_IRQ)		+= dummy-irq.o
obj-$(CONFIG_ICS932S401)	+= ics932s401.o
obj-$(CONFIG_LKDTM)		+= lkdtm.o
obj-$(CONFIG_TIFM_CORE)       	+= tifm_core.o
obj-$(CONFIG_TIFM_7XX1)       	+= tifm_7xx1.o
obj-$(CONFIG_PHANTOM)		+= phantom.o
obj-$(CONFIG_SENSORS_BH1780)	+= bh1780gli.o
obj-$(CONFIG_SENSORS_BH1770)	+= bh1770glc.o
obj-$(CONFIG_SENSORS_APDS990X)	+= apds990x.o
obj-$(CONFIG_SGI_IOC4)		+= ioc4.o
obj-$(CONFIG_ENCLOSURE_SERVICES) += enclosure.o
obj-$(CONFIG_KGDB_TESTS)	+= kgdbts.o
obj-$(CONFIG_SGI_XP)		+= sgi-xp/
obj-$(CONFIG_SGI_GRU)		+= sgi-gru/
obj-$(CONFIG_CS5535_MFGPT)	+= cs5535-mfgpt.o
obj-$(CONFIG_HP_ILO)		+= hpilo.o
obj-$(CONFIG_APDS9802ALS)	+= apds9802als.o
obj-$(CONFIG_ISL29003)		+= isl29003.o
obj-$(CONFIG_ISL29020)		+= isl29020.o
obj-$(CONFIG_SENSORS_TSL2550)	+= tsl2550.o
obj-$(CONFIG_DS1682)		+= ds1682.o
obj-$(CONFIG_TI_DAC7512)	+= ti_dac7512.o
obj-$(CONFIG_UID_STAT)		+= uid_stat.o
obj-$(CONFIG_C2PORT)		+= c2port/
obj-$(CONFIG_HMC6352)		+= hmc6352.o
obj-y				+= eeprom/
obj-y				+= cb710/
obj-$(CONFIG_SPEAR13XX_PCIE_GADGET)	+= spear13xx_pcie_gadget.o
obj-$(CONFIG_VMWARE_BALLOON)	+= vmw_balloon.o
obj-$(CONFIG_ARM_CHARLCD)	+= arm-charlcd.o
obj-$(CONFIG_PCH_PHUB)		+= pch_phub.o
obj-y				+= ti-st/
obj-y				+= lis3lv02d/
obj-y				+= carma/
obj-$(CONFIG_USB_SWITCH_FSA9480) += fsa9480.o
obj-$(CONFIG_ALTERA_STAPL)	+=altera-stapl/
obj-$(CONFIG_INTEL_MEI)		+= mei/
obj-$(CONFIG_VMWARE_VMCI)	+= vmw_vmci/
obj-$(CONFIG_LATTICE_ECP3_CONFIG)	+= lattice-ecp3-config.o
obj-$(CONFIG_SRAM)		+= sram.o
obj-y				+= mic/
obj-$(CONFIG_GENWQE)		+= genwqe/
obj-$(CONFIG_QSEECOM) += qseecom.o
obj-$(CONFIG_PROFILER) += profiler.o
obj-$(CONFIG_HDCP_QSEECOM) += hdcp.o
obj-$(CONFIG_CAPSENSE_CYPRESS) += cypress/
ifdef CONFIG_COMPAT
obj-$(CONFIG_QSEECOM) += compat_qseecom.o
endif
obj-$(CONFIG_ECHO)		+= echo/
obj-$(CONFIG_VEXPRESS_SYSCFG)	+= vexpress-syscfg.o
obj-$(CONFIG_CXL_BASE)		+= cxl/
obj-y				+= qcom/
obj-$(CONFIG_TI_DRV2667) += ti_drv2667.o
obj-$(CONFIG_USB_EXT_TYPE_C_PERICOM)	+= type-c-pericom.o
obj-$(CONFIG_USB_EXT_TYPE_C_TI)		+= type-c-ti.o
obj-$(CONFIG_QPNP_MISC) 	+= qpnp-misc.o
obj-$(CONFIG_UID_SYS_STATS) += uid_sys_stats.o
obj-$(CONFIG_MEMORY_STATE_TIME) += memory_state_time.o
obj-$(CONFIG_APDS9930)		+= apds993x.o
obj-$(CONFIG_UID_SYS_STATS) += uid_sys_stats.o
obj-$(CONFIG_MEMORY_STATE_TIME) += memory_state_time.o
obj-$(CONFIG_HAPTIC_DRV2605)	+= drv2605.o
obj-$(CONFIG_HAPTIC_DRV2624)	+= drv2624.o
obj-$(CONFIG_C55_CTRL) += c55_ctrl.o
obj-$(CONFIG_MMI_FACTORY) += mmi-factory.o
obj-$(CONFIG_DROPBOX) += dropbox.o
obj-$(CONFIG_HOB_SHARED_RAM) += hob_ram_mmap.o
obj-$(CONFIG_ALSA_TO_H2W) += alsa-to-h2w-headset.o
obj-$(CONFIG_MOT_UTAG) += utag/
obj-$(CONFIG_SENSORS_MOTOSH) += moto-sensorhub/
obj-$(CONFIG_DROPBOX) += dropbox.o
obj-$(CONFIG_FUSB302) += fusb302/
obj-$(CONFIG_FUSB302_LEGACY) += fusb302_legacy/
obj-$(CONFIG_MODS_CODEC_BUS) += mods_codec_bus.o
obj-$(CONFIG_MODS_USB_EXT_BRIDGE) += usb_ext_bridge.o
obj-$(CONFIG_HD3SS460_MUX) += hd3ss460_mux.o
obj-$(CONFIG_USB3813) += usb3813_hub.o
obj-$(CONFIG_MODS_MODBUS_EXT) += modbus_ext.o
obj-$(CONFIG_FSUSB42_MUX) += fsusb42_mux.o
obj-$(CONFIG_SENSORS_STML0XX) += stml0xx/
obj-$(CONFIG_TPS61280) += tps61280.o
obj-$(CONFIG_MOTOMODS) += motomods/
obj-$(CONFIG_DTV_FC8300) += moto-dtv-fc8300/

# TODO: remove me b/62058353
subdir-ccflags-y += \
	-Wno-ignored-attributes
	
