#
# Makefile for the msm networking support.
#

ccflags-$(CONFIG_MSM_MHI_DEBUG) := -DDEBUG
obj-$(CONFIG_MSM_RMNET_MHI) += msm_rmnet_mhi.o
obj-$(CONFIG_ECM_IPA) += ecm_ipa.o
obj-$(CONFIG_RNDIS_IPA) += rndis_ipa.o
obj-$(CONFIG_MSM_RMNET_BAM) += msm_rmnet_bam.o

CFLAGS_rndis_ipa.o := -I$(src)
