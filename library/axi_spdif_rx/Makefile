####################################################################################
####################################################################################
## Copyright 2011(c) Analog Devices, Inc.
## Auto-generated, do not modify!
####################################################################################
####################################################################################

M_DEPS += ../common/axi_ctrlif.vhd
M_DEPS += ../common/axi_streaming_dma_rx_fifo.vhd
M_DEPS += ../common/dma_fifo.vhd
M_DEPS += ../common/pl330_dma_fifo.vhd
M_DEPS += ../scripts/adi_env.tcl
M_DEPS += ../scripts/adi_ip.tcl
M_DEPS += axi_spdif_rx.vhd
M_DEPS += axi_spdif_rx_constr.xdc
M_DEPS += axi_spdif_rx_ip.tcl
M_DEPS += rx_decode.vhd
M_DEPS += rx_package.vhd
M_DEPS += rx_phase_det.vhd
M_DEPS += rx_status_reg.vhd

M_VIVADO := vivado -mode batch -source

M_FLIST := *.cache
M_FLIST += *.data
M_FLIST += *.xpr
M_FLIST += *.log
M_FLIST += component.xml
M_FLIST += *.jou
M_FLIST +=  xgui
M_FLIST += *.ip_user_files
M_FLIST += *.srcs
M_FLIST += *.hw
M_FLIST += *.sim
M_FLIST += .Xil



.PHONY: all clean clean-all
all: axi_spdif_rx.xpr


clean:clean-all


clean-all:
	rm -rf $(M_FLIST)


axi_spdif_rx.xpr: $(M_DEPS)
	-rm -rf $(M_FLIST)
	$(M_VIVADO) axi_spdif_rx_ip.tcl  >> axi_spdif_rx_ip.log 2>&1

####################################################################################
####################################################################################
