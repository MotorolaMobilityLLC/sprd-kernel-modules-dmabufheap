#
# sprd-dmabuf.ko
#
# Kbuild: for kernel building external module
#
# Note:
# - Please refer to modules/sample/Kbuild to find out what should be
#   done is this Kbuild file
#

#
# Source List
#
KO_MODULE_NAME := sprd-dmabuf
KO_MODULE_PATH := $(src)
KO_MODULE_SRC  :=

KO_MODULE_SRC += $(wildcard $(KO_MODULE_PATH)/*.c)

#
# Build Options
#
ccflags-y := \
	-I$(srctree)/include/linux \
	-I$(srctree)/include/uapi/linux \
	-I$(src)

#
# Final Objects
#
obj-m := $(KO_MODULE_NAME).o
