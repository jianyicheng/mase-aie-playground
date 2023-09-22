# Interface for passing MASE AIE design files to HACC

In order to develop AIE kernels on the Versal ACAP devices, a set of Xilinx software packages are required in the environment.
Unfortunately, these packages are only available on request, which makes the current development challenging.
The only path at the moment is to develop on HACC but it does not allow installing any additional packgaes.

The current short-term plan is to develop designs in MASE environments and push the intermeidate files to this repo.
Then they can be fetched by HACC and downloaded onto the physical AIE devices.

In the long run, we plan to hopefully obtain the packages and install them on beholder to resolve this issue.
