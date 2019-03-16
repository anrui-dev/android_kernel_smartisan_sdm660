#
# Makefile for the QCOM specific video device drivers
# based on V4L2.
#
ifdef CONFIG_VENDOR_SMARTISAN
obj-$(CONFIG_MSMB_CAMERA) += camera_v2_smartisan/
else
obj-$(CONFIG_MSMB_CAMERA) += camera_v2/
endif
obj-$(CONFIG_MSM_VIDC_V4L2) += vidc/
obj-y += sde/
obj-y += broadcast/
obj-$(CONFIG_DVB_MPQ) += dvb/
obj-$(CONFIG_MSM_AIS) += ais/
