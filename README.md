#kernel_bcm21553-common

##How to build bcm21553 kernel

Basic knowledge of Linux and compiling is required to be able to build a kernel. You need Linux machine with git and toolchain installed.

##Setup build environment

In your home directory (~/) create the directories:

Open a terminal

     $ mkdir kernel
     $ cd kernel

Building a directory structure that will help keep us organized. The "mkdir" command creates a directory, and the "cd" command moves you into that directory.
The directory structure is complete. Now, you are ready to clone kernel code.

##Setting up repositories

Clone the main kernel repository, run this line in your terminal window:

    $ git clone https://github.com/mohammad92/kernel_bcm21553-common

##Toolchains

    $ git clone https://android.googlesource.com/platform/prebuilts/gcc/linux-x86/arm/arm-eabi-4.6

##Building

Open a terminal and type:

    $ cd kernel_bcm21553-common
    $ ./menu

---
bcm21553 kernel menu will appear

> bcm21553-common kernel build script
 
> b- build                           # type b will go to build menu.

> c- clean                           # type c will clean kernel directory.


> r- restart script                  # type r will restart menu.

> x- exit script                     # type x will exit menu.

---

build menu.

> Choose your device
 
>1- totoro                           # type 1 to compile totoro kernel.

>2- cooperve                         # type 2 to compile cooperve kernel.

>3- tassve                           # type 3 to compile tassve kernel.

>m- main menu

>x- exit script

###zImage will be coppied to ~/kernel directory if kernel successfully built.
