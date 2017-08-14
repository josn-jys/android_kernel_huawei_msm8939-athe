#
# Makefile for the QCOM spcific video device drivers
# based on V4L2.
#

obj-$(CONFIG_MSM_VIDC_V4L2)     += vidc/
obj-$(CONFIG_MSM_WFD) += wfd/
obj-y += broadcast/
obj-$(CONFIG_DVB_MPQ) += dvb/

ifeq ($(CONFIG_MSM_CAMERA_MINIISP),y)
ccflags-y += -D _MSM_CAMERA_MINIISP_
obj-y += camera_v2_misp/
else
obj-$(CONFIG_MSMB_CAMERA) += camera_v2/
endif

obj-$(CONFIG_MSM_VPU) += vpu/
