# SPDX-License-Identifier: GPL-2.0
obj-$(CONFIG_QCOM_GLINK_SSR) +=	glink_ssr.o
obj-$(CONFIG_QCOM_GSBI)	+=	qcom_gsbi.o
obj-$(CONFIG_QCOM_MDT_LOADER)	+= mdt_loader.o
obj-$(CONFIG_QCOM_PM)	+=	spm.o
obj-$(CONFIG_QCOM_SECURE_BUFFER) += secure_buffer.o
obj-$(CONFIG_QCOM_SMD_RPM)	+= smd-rpm.o
obj-$(CONFIG_QCOM_SMEM) +=	smem.o
obj-$(CONFIG_QCOM_SMEM_STATE) += smem_state.o
obj-$(CONFIG_QCOM_SMP2P)	+= smp2p.o
obj-$(CONFIG_QCOM_SMSM)	+= smsm.o
obj-$(CONFIG_QCOM_WCNSS_CTRL) += wcnss_ctrl.o
CFLAGS_scm.o :=$(call as-instr,.arch_extension sec,-DREQUIRES_SEC=1)
obj-$(CONFIG_QCOM_SCM)  +=      scm.o scm-boot.o
obj-$(CONFIG_MSM_RPM_SMD)   +=  rpm-smd.o
ifdef CONFIG_DEBUG_FS
obj-$(CONFIG_MSM_RPM_SMD)   +=  rpm-smd-debug.o
endif
