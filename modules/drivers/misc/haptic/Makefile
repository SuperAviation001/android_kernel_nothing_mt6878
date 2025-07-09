# SPDX-License-Identifier: GPL-2.0
#
# Makefile for the input core drivers.
#

# Each configuration option enables a list of files.

obj-$(CONFIG_HAPTIC_DRV)		+= haptic.o
haptic-y		:= haptic_drv.o \
	                   rt6010.o \

ifeq ($(CONFIG_HAPTIC_DRV_RICHTAP),y)
haptic-y += richtap_drv.o
endif
