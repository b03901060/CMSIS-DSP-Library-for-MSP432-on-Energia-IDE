# CMSIS-DSP-Library-for-MSP432-on-Energia-IDE
This project provides you a way to use the CMSIS-DSP library on MSP432 board when using Energia IDE.

## Prerequisites:

You must have Energia installed. In Energia, install the package "Energia MSP 432 boards" and make sure the package "Energia MSP 432 EMT RED boards" is not installed.

## Usages:

Download the packages provided in this repository.

Go to the path where you installed Energia, find where your Energia packages are stored (i.e. ~/.energia15/packages). Place all the files you have downloaded in the same manner as they are organized when downloaded.

To use the DSP library, put:

`#include<arm_math.h>`

on top of your Energia sketch.
