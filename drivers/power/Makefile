power_supply-objs := power_supply_core.o

ifeq ($(CONFIG_SYSFS),y)
power_supply-objs += power_supply_sysfs.o
endif

ifeq ($(CONFIG_LEDS_TRIGGERS),y)
power_supply-objs += power_supply_leds.o
endif

ifeq ($(CONFIG_POWER_SUPPLY_DEBUG),y)
EXTRA_CFLAGS += -DDEBUG
endif

obj-$(CONFIG_POWER_SUPPLY)	+= power_supply.o

obj-$(CONFIG_PDA_POWER)		+= pda_power.o
obj-$(CONFIG_APM_POWER)		+= apm_power.o
obj-$(CONFIG_WM831X_POWER)	+= wm831x_power.o
obj-$(CONFIG_WM8350_POWER)	+= wm8350_power.o

obj-$(CONFIG_BATTERY_DS2760)	+= ds2760_battery.o
obj-$(CONFIG_BATTERY_DS2782)	+= ds2782_battery.o
obj-$(CONFIG_BATTERY_DS2784)	+= ds2784_battery.o
obj-$(CONFIG_BATTERY_PMU)	+= pmu_battery.o
obj-$(CONFIG_BATTERY_OLPC)	+= olpc_battery.o
obj-$(CONFIG_BATTERY_TOSA)	+= tosa_battery.o
obj-$(CONFIG_BATTERY_WM97XX)	+= wm97xx_battery.o
obj-$(CONFIG_BATTERY_BQ27x00)	+= bq27x00_battery.o
obj-$(CONFIG_BATTERY_DA9030)	+= da9030_battery.o
obj-$(CONFIG_BATTERY_MAX17040)	+= max17040_battery.o
obj-$(CONFIG_CHARGER_PCF50633)	+= pcf50633-charger.o
#obj-$(CONFIG_BATTERY_MSM)	+= msm_battery.o
ifeq ($(CONFIG_MACH_EUROPA),y)
obj-$(CONFIG_BATTERY_MSM)	+= europa_battery.o
endif
ifeq ($(CONFIG_MACH_COOPER),y)
obj-$(CONFIG_BATTERY_MSM)	+= cooper_battery.o
endif
ifeq ($(CONFIG_MACH_GIOATT),y)
obj-$(CONFIG_BATTERY_MSM)	+= gioatt_battery.o
endif
ifeq ($(CONFIG_MACH_BENI),y)
obj-$(CONFIG_BATTERY_MSM)	+= beni_battery.o
endif
ifeq ($(CONFIG_MACH_TASS),y)
obj-$(CONFIG_BATTERY_MSM)	+= tass_battery.o
endif
ifeq ($(CONFIG_MACH_TASSTMO),y)
obj-$(CONFIG_BATTERY_MSM)	+= tasstmo_battery.o
endif
ifeq ($(CONFIG_MACH_TASSMCT),y)
obj-$(CONFIG_BATTERY_MSM)	+= tasstmo_battery.o
endif
ifeq ($(CONFIG_MACH_TASSVTR),y)
obj-$(CONFIG_BATTERY_MSM)	+= tasstmo_battery.o
endif
ifeq ($(CONFIG_MACH_TASSATT),y)
obj-$(CONFIG_BATTERY_MSM)	+= tassatt_battery.o
endif
ifeq ($(CONFIG_MACH_GT2),y)
obj-$(CONFIG_BATTERY_MSM)	+= gt2_battery.o
endif
ifeq ($(CONFIG_MACH_FLIPBOOK),y)
obj-$(CONFIG_BATTERY_MSM)	+= flipbook_battery.o
endif
ifeq ($(CONFIG_MACH_LUCAS),y)
obj-$(CONFIG_BATTERY_MSM)	+= lucas_battery.o
endif
ifeq ($(CONFIG_MACH_CALLISTO),y)
obj-$(CONFIG_BATTERY_MSM)	+= callisto_battery.o
endif
