# UNewHaven's Embedded Systems Class Example Code
This repository includes examples codes and a template for UNewHaven's ELEC3371 class, also known as the embedded systems class.

## Board
The board using for the examples are [MikroE's STM32 Board](https://www.mikroe.com/easymx-pro-stm32). The STM32 chipset is the [STM32F107VCT6](https://www.st.com/en/microcontrollers-microprocessors/stm32f107vc.html).
If you would like to use your own custom board, each example describes the required periferals and what IO's are used.

## Building Projects
### Building with MikroC
As the class is structured around [MikroE's STM32 Board](https://www.mikroe.com/easymx-pro-stm32), the examples can be compiled using their MikroC compiler. 

To use this compiler, load any example directory in their IDE, then press the compile button.

### Building with GCC
If you want to build the examples with a sane compiler, each example comes with a *MAKEFILE* and a linker file that allows the program to be built with GCC.

It is highly recommended to use a GNU/Linux system to build the examples with GCC. If you want to use Windows, all power to you, good luck getting the toolchains installed in a sane fashion.

## Template
Included in this repository, under the * directory, is a template for project submissions. This template folder includes a *main.c* file which includes some basic headers, and a *MAKEFILE* and a linker file in case you are building the program with GCC

## License
This repository and all it's contents are under the public domain. Have fun with it
