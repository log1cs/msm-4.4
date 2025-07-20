dtb-$(CONFIG_ARCH_SDM660) += \
    ../qcom/sdm660-mtp.dtb \
    ../qcom/sdm630-mtp.dtb \
    ../qcom/sdm660-qrd.dtb \
    ../qcom/sdm630-pm660a-qrd.dtb

# FIH platform
ifeq ($(CONFIG_MACH_FIH),y)
dtb-$(CONFIG_FIH_B2N) += \
    platform/B2N/sdm660-mtp-b2n-preEVT.dtb \
    platform/B2N/sdm660-mtp-b2n-EVT.dtb \
    platform/B2N/sdm660-mtp-b2n-EVT1.5.dtb \
    platform/B2N/sdm660-mtp-b2n-DVT-QC.dtb \
    platform/B2N/sdm660-mtp-b2n-DVT-TI.dtb \
    platform/B2N/sdm636-mtp-b2n-preEVT.dtb

dtb-$(CONFIG_FIH_C1N) += \
    platform/C1N/sdm660-cdp-c1n-preEVT.dtb \
    platform/C1N/sdm660-cdp-c1n-EVT.dtb \
    platform/C1N/sdm660-mtp-c1n-preEVT.dtb \
    platform/C1N/sdm660-mtp-c1n-EVT.dtb \
    platform/C1N/sdm660-mtp-c1n-EVT2.0.dtb \
    platform/C1N/sdm660-mtp-c1n-EVT2.1.dtb \
    platform/C1N/sdm630-cdp-c1n-preEVT.dtb \
    platform/C1N/sdm630-cdp-c1n-EVT.dtb \
    platform/C1N/sdm630-mtp-c1n-preEVT.dtb \
    platform/C1N/sdm630-mtp-c1n-EVT.dtb \
    platform/C1N/sdm630-mtp-c1n-EVT2.0.dtb \
    platform/C1N/sdm630-mtp-c1n-EVT2.1.dtb

dtb-$(CONFIG_FIH_CTL) += \
    platform/CTL/sdm636-mtp-ctl-EVT.dtb \
    platform/CTL/sdm636-mtp-ctl-DVT.dtb

dtb-$(CONFIG_FIH_DRG) += \
    platform/DRG/sdm636-mtp-drg-preEVT.dtb \
    platform/DRG/sdm636-mtp-drg-EVT.dtb \
    platform/DRG/sdm636-mtp-drg-DVT1.5.dtb \
    platform/DRG/sdm660-mtp-drg-pro-EVT.dtb

dtb-$(CONFIG_FIH_PL2) += \
    platform/PL2/sdm660-mtp-pl2-preEVT.dtb \
    platform/PL2/sdm630-mtp-pl2-preEVT.dtb \
    platform/PL2/sdm630-mtp-pl2-EVT1.5.dtb \
    platform/PL2/sdm630-mtp-pl2-EVT1.5-CD.dtb \
    platform/PL2/sdm630-mtp-pl2-dvt.dtb

dtb-$(CONFIG_FIH_TAS) += \
    platform/TAS/sdm660-mtp-tas-preEVT.dtb \
    platform/TAS/sdm660-mtp-tas-EVT.dtb \
    platform/TAS/sdm660-mtp-tas-PVT.dtb \
    platform/TAS/sdm660-mtp-tas-MP.dtb
endif # CONFIG_MACH_FIH

# Longcheer platform
ifeq ($(CONFIG_MACH_LONGCHEER),y)
dtbo-$(CONFIG_LC_DDV) += \
	ddv-sdm660-mtp-overlay.dtbo

ddv-sdm660-mtp-overlay.dtbo-base := sdm660-mtp.dtb

dtbo-$(CONFIG_LC_SLD) += \
	sld-sdm636-mtp-overlay.dtbo

sld-sdm636-mtp-overlay.dtbo-base := sdm636-mtp.dtb
endif