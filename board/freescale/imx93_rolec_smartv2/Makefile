#
# Copyright 2026 Rolec
#
# SPDX-License-Identifier:      GPL-2.0+
#

obj-y += imx93_rolec_smartv2.o

ifdef CONFIG_XPL_BUILD
obj-y += ../imx93_evk/spl.o
ifdef CONFIG_IMX9_DRAM_INLINE_ECC
obj-$(CONFIG_IMX93_ROLEC_SMARTV2_LPDDR4X) += ../imx93_evk/lpddr4x_timing_ecc.o ../imx93_evk/lpddr4x_timing_1866mts_ecc.o
else
obj-$(CONFIG_IMX93_ROLEC_SMARTV2_LPDDR4X) += ../imx93_evk/lpddr4x_timing.o ../imx93_evk/lpddr4x_timing_1866mts.o
endif
endif
