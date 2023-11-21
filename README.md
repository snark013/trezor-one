# trezor-one

Trezor One cryptocurrency wallet.

![](https://github.com/snark013/trezor-one/blob/main/imgs/3builds.png)

Modified version of the original one from https://github.com/trezor/trezor-hardware

Modifications include -
- all R and C components of size 0603
- other buttons
- USB type-C connector

![](https://github.com/snark013/trezor-one/blob/main/imgs/pcb.png)

As a result, the board is a bit longer and the case had to be modified as well.
The circuitry and firmware are original (only added two resistors to the circuit to allow the USB host to detect the connected device by the type-C connector).
