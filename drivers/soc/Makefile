# SPDX-License-Identifier: GPL-2.0
#
# Makefile for the Linux Kernel SOC specific device drivers.
#

obj-$(CONFIG_ARCH_ACTIONS)	+= actions/
obj-$(CONFIG_ARCH_AT91)		+= atmel/
obj-y				+= bcm/
obj-$(CONFIG_ARCH_DOVE)		+= dove/
obj-$(CONFIG_MACH_DOVE)		+= dove/
obj-y				+= fsl/
obj-$(CONFIG_ARCH_GEMINI)	+= gemini/
obj-$(CONFIG_ARCH_MXC)		+= imx/
obj-$(CONFIG_SOC_XWAY)		+= lantiq/
obj-y				+= mediatek/
obj-y				+= amlogic/
obj-y				+= qcom/
obj-y				+= renesas/
obj-$(CONFIG_ARCH_ROCKCHIP)	+= rockchip/
obj-$(CONFIG_SOC_SAMSUNG)	+= samsung/
obj-$(CONFIG_ARCH_SUNXI)	+= sunxi/
obj-$(CONFIG_ARCH_TEGRA)	+= tegra/
obj-$(CONFIG_SOC_TI)		+= ti/
obj-$(CONFIG_ARCH_U8500)	+= ux500/
obj-$(CONFIG_PLAT_VERSATILE)	+= versatile/
obj-y				+= xilinx/
obj-$(CONFIG_ARCH_ZX)		+= zte/
obj-y                           += oplus/
#ifdef VENDOR_EDIT
obj-$(CONFIG_OPLUS_SYSTEM_KERNEL)	+= oplus/system/
#endif /* VENDOR_EDIT */

#ifdef OPLUS_FEATURE_SENSOR_SMEM
obj-y						+= oplus/sensor/
#endif
#ifdef OPLUS_FEATURE_SENSOR_CRASH_MONITOR
obj-$(CONFIG_OPLUS_FEATURE_SENSOR_CRASH_MONITOR)	+= oplus/oplus_slpirst/
#endif

#ifdef OPLUS_FEATURE_POWERINFO_STANDBY
obj-$(CONFIG_OPLUS_WAKELOCK_PROFILER) += oplus/owakelock/
#endif /* OPLUS_FEATURE_POWERINFO_STANDBY */

#ifdef OPLUS_FEATURE_ESIM
obj-y += oplus/misc/
#endif /* OPLUS_FEATURE_ESIM */
