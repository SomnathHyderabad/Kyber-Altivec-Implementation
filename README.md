# Kyber-Altivec-Implementation
PowerPC SIMD i.e. Altivec based Kyber C-code

The code is run on NXP T20280 chip which has e6500 PowerPC core. The Altivec is the SIMD complied instructions of PowerPC. After applying Altivec, the performance of the Kyber-Crystal algorithm has improved by 45.5% and 37.4% for Encryption and Decryption respectively. We have integrated HMAC for incorporating cyphertext integrity and BCH to handle the induced errors in noisy channel.

To compile the code, we need the PowerPC QEMU. However to get the exact cycle count we need T20280 NXP chip based hardware. 

We have run the run this application on Linux4.1.8 Kernel.
