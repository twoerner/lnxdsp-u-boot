# SPDX-License-Identifier: GPL-2.0+
#
# (C) Copyright 2000-2007
# Wolfgang Denk, DENX Software Engineering, wd@denx.de.

# There are many options which enable SPI, so make this library available
ifdef CONFIG_$(SPL_TPL_)DM_SPI
obj-y += spi-uclass.o
obj-$(CONFIG_CADENCE_QSPI) += cadence_qspi.o cadence_qspi_apb.o
obj-$(CONFIG_SANDBOX) += spi-emul-uclass.o
obj-$(CONFIG_SOFT_SPI) += soft_spi.o
obj-$(CONFIG_SPI_MEM) += spi-mem.o
obj-$(CONFIG_TI_QSPI) += ti_qspi.o
else
obj-y += spi.o
obj-$(CONFIG_SPI_MEM) += spi-mem-nodm.o
endif

obj-$(CONFIG_ADI_SPI3) += adi_spi3.o
obj-$(CONFIG_ADI_SPI3_DM) += adi_spi3_dm.o
obj-$(CONFIG_SC59X_SPI) += sc59x_spi.o
obj-$(CONFIG_SC58X_SPI) += sc58x_spi.o
obj-$(CONFIG_SC57X_SPI) += sc57x_spi.o
obj-$(CONFIG_ALTERA_SPI) += altera_spi.o
obj-$(CONFIG_ATH79_SPI) += ath79_spi.o
obj-$(CONFIG_ATMEL_QSPI) += atmel-quadspi.o
obj-$(CONFIG_ATMEL_SPI) += atmel_spi.o
obj-$(CONFIG_BCM63XX_HSSPI) += bcm63xx_hsspi.o
obj-$(CONFIG_BCM63XX_SPI) += bcm63xx_spi.o
obj-$(CONFIG_BCMSTB_SPI) += bcmstb_spi.o
obj-$(CONFIG_CF_SPI) += cf_spi.o
obj-$(CONFIG_DAVINCI_SPI) += davinci_spi.o
obj-$(CONFIG_DESIGNWARE_SPI) += designware_spi.o
obj-$(CONFIG_EXYNOS_SPI) += exynos_spi.o
obj-$(CONFIG_FSL_DSPI) += fsl_dspi.o
obj-$(CONFIG_FSL_ESPI) += fsl_espi.o
obj-$(CONFIG_FSL_QSPI) += fsl_qspi.o
obj-$(CONFIG_ICH_SPI) +=  ich.o
obj-$(CONFIG_KIRKWOOD_SPI) += kirkwood_spi.o
obj-$(CONFIG_MESON_SPIFC) += meson_spifc.o
obj-$(CONFIG_MPC8XX_SPI) += mpc8xx_spi.o
obj-$(CONFIG_MPC8XXX_SPI) += mpc8xxx_spi.o
obj-$(CONFIG_MTK_SNFI_SPI) += mtk_snfi_spi.o
obj-$(CONFIG_MT7621_SPI) += mt7621_spi.o
obj-$(CONFIG_MSCC_BB_SPI) += mscc_bb_spi.o
obj-$(CONFIG_MVEBU_A3700_SPI) += mvebu_a3700_spi.o
obj-$(CONFIG_MXC_SPI) += mxc_spi.o
obj-$(CONFIG_MXS_SPI) += mxs_spi.o
obj-$(CONFIG_NXP_FSPI) += nxp_fspi.o
obj-$(CONFIG_ATCSPI200_SPI) += atcspi200_spi.o
obj-$(CONFIG_OCTEON_SPI) += octeon_spi.o
obj-$(CONFIG_OMAP3_SPI) += omap3_spi.o
obj-$(CONFIG_PIC32_SPI) += pic32_spi.o
obj-$(CONFIG_PL022_SPI) += pl022_spi.o
obj-$(CONFIG_RENESAS_RPC_SPI) += renesas_rpc_spi.o
obj-$(CONFIG_ROCKCHIP_SPI) += rk_spi.o
obj-$(CONFIG_SANDBOX_SPI) += sandbox_spi.o
obj-$(CONFIG_SPI_SIFIVE) += spi-sifive.o
obj-$(CONFIG_SPI_SUNXI) += spi-sunxi.o
obj-$(CONFIG_SH_QSPI) += sh_qspi.o
obj-$(CONFIG_STM32_QSPI) += stm32_qspi.o
obj-$(CONFIG_STM32_SPI) += stm32_spi.o
obj-$(CONFIG_TEGRA114_SPI) += tegra114_spi.o
obj-$(CONFIG_TEGRA20_SFLASH) += tegra20_sflash.o
obj-$(CONFIG_TEGRA20_SLINK) += tegra20_slink.o
obj-$(CONFIG_TEGRA210_QSPI) += tegra210_qspi.o
obj-$(CONFIG_UNIPHIER_SPI) += uniphier_spi.o
obj-$(CONFIG_XILINX_SPI) += xilinx_spi.o
obj-$(CONFIG_ZYNQ_SPI) += zynq_spi.o
obj-$(CONFIG_ZYNQ_QSPI) += zynq_qspi.o
obj-$(CONFIG_ZYNQMP_GQSPI) += zynqmp_gqspi.o
