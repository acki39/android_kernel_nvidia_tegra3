#
# Makefile for sensor chip drivers.
#

obj-$(CONFIG_THERMAL)		+= thermal_sys.o
obj-$(CONFIG_SPEAR_THERMAL)		+= spear_thermal.o
obj-$(CONFIG_CPU_THERMAL)		+= cpu_cooling.o
obj-$(CONFIG_SPEAR_THERMAL)		+= spear_thermal.o
obj-$(CONFIG_RCAR_THERMAL)	+= rcar_thermal.o
obj-$(CONFIG_PWM_FAN)		+= pwm_fan.o
obj-$(CONFIG_FAIR_SHARE)		+= fair_share.o
obj-$(CONFIG_STEP_WISE)			+= step_wise.o
obj-$(CONFIG_THERMAL_GOV_PID)			+= pid_thermal_gov.o
obj-$(CONFIG_USER_SPACE)		+= user_space.o
#Derrick.Liu add two coolers
obj-y					+=qic_fps_cooler.o
obj-y					+=qic_chg_cooler.o
#Derrick.Liu add two coolers