# caffe-in-zynq
# ZynqNet: An FPGA-Accelerated Embedded Convolutional Neural Network

The fully trained CNN with .prototxt network description and pretrained weights can be found under [_TRAINED_MODEL](https://github.com/dgschwend/zynqnet/tree/master/_TRAINED_MODEL)

## ZynqNet FPGA Accelerator
The C/C++ source code for building the FPGA accelerator using High-Level Synthesis (Vivado HLS) can be found under [_HLS_CODE](https://github.com/dgschwend/zynqnet/tree/master/_HLS_CODE).

The compiled accelerator bitstream can be found under [_BITSTREAM](https://github.com/dgschwend/zynqnet/tree/master/_BITSTREAM).

The firmware for the Zynq XC-7Z045 ARM processors is stored under [_FIRMWARE](https://github.com/dgschwend/zynqnet/tree/master/_FIRMWARE).

## Netscope CNN Analyzer
The CNN analysis tool can be found in a separate repository here: [dgschwend/netscope](https://github.com/dgschwend/netscope)

## Copyright and License
ZynqNet is Copyright 2016 by David Gschwend.
All files in this repository are released under the GNU General Public License as found in the LICENSE file.
