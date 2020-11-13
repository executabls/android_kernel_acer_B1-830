ifeq ($(TARGET_CUSTOMER),acer)
EXTRA_CFLAGS += -DACER
endif

include $(srctree)/drivers/misc/mediatek/Makefile.custom

# Linux driver folder
ccflags-y += -I$(srctree)/arch/arm/mach-$(MTK_PLATFORM)/$(ARCH_MTK_PROJECT)/touchpanel/ekth3386/
ccflags-y += -I$(srctree)/drivers/input/touchscreen/mediatek/ekth3386/
ccflags-y += -I$(srctree)/drivers/input/touchscreen/mediatek/

obj-y	+=  ekt2k_mtk10_62.o