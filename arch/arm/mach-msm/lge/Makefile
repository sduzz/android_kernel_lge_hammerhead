obj-$(CONFIG_MACH_MSM8974_HAMMERHEAD) += board-8974-hammerhead.o
obj-$(CONFIG_MACH_MSM8974_HAMMERHEAD) += board-8974-hammerhead-gpiomux.o

obj-$(CONFIG_MACH_LGE) += devices_lge.o
obj-$(CONFIG_LGE_HANDLE_PANIC) += lge_handle_panic.o
obj-$(CONFIG_LGE_BLUETOOTH) += board-8974-rfkill.o
obj-$(CONFIG_WIFI_CONTROL_FUNC) += board-wifi-bcm.o

obj-$(CONFIG_LCD_KCAL) += lge_kcal_ctrl.o

CFLAGS_devices_lge.o += -Idrivers/staging/android

ifdef CONFIG_MACH_MSM8974_HAMMERHEAD_STRICT_ALIASING
CFLAGS_board-wifi-bcm.o := -fno-strict-aliasing
endif

