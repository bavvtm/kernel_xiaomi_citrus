# SPDX-License-Identifier: GPL-2.0-only

ccflags-y += -I$(srctree)/techpack/camera-xiaomi/drivers/cam_utils
ccflags-y += -I$(srctree)/techpack/camera-xiaomi/drivers/cam_req_mgr
ccflags-y += -I$(srctree)/techpack/camera-xiaomi/drivers/cam_core
ccflags-y += -I$(srctree)/techpack/camera-xiaomi/drivers/cam_cdm
ccflags-y += -I$(srctree)/techpack/camera-xiaomi/drivers/cam_sync
ccflags-y += -I$(srctree)/techpack/camera-xiaomi/drivers/cam_ope
ccflags-y += -I$(srctree)/techpack/camera-xiaomi/drivers/cam_ope/ope_hw_mgr
ccflags-y += -I$(srctree)/techpack/camera-xiaomi/drivers/cam_ope/ope_hw_mgr/ope_hw
ccflags-y += -I$(srctree)/techpack/camera-xiaomi/drivers/cam_ope/ope_hw_mgr/ope_hw/bus_wr
ccflags-y += -I$(srctree)/techpack/camera-xiaomi/drivers/cam_ope/ope_hw_mgr/ope_hw/bus_rd
ccflags-y += -I$(srctree)/techpack/camera-xiaomi/drivers/cam_ope/ope_hw_mgr/ope_hw/top
ccflags-y += -I$(srctree)/techpack/camera-xiaomi/drivers/cam_ope/fw_inc
ccflags-y += -I$(srctree)/techpack/camera-xiaomi/drivers
ccflags-y += -I$(srctree)/techpack/camera-xiaomi/drivers/cam_cpas/include
ccflags-y += -I$(srctree)/techpack/camera-xiaomi/drivers/cam_smmu/

obj-$(CONFIG_SPECTRA_CAMERA) += ope_dev.o ope_soc.o ope_core.o top/ bus_rd/ bus_wr/
