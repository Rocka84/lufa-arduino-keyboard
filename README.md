# LUFA arduino keyboard firmware

This repo was made to be able to build [darran's Arduino USB Keyboard Firmware](https://web.archive.org/web/20120122114237/http://hunt.net.nz/users/darran/weblog/b3029/Arduino_UNO_Keyboard_HID_version_03.html)
from source.

See [Projects/arduino-keyboard](Projects/arduino-keyboard).

The version of LUFA this uses is _way outdated!_ So don't use it for other stuff. Anyways, here's the original readme.txt



                   _   _ _ ___ _
                  | | | | | __/ \
                  | |_| U | _| o | - The Lightweight USB
                  |___|___|_||_n_|    Framework for AVRs
                =========================================
                          Written by Dean Camera
                  dean [at] fourwalledcubicle [dot] com

                 http://www.fourwalledcubicle.com/LUFA.php
                =========================================

               LUFA is donation supported. To support LUFA,
             please donate at http://www.fourwalledcubicle.com.

                For Commercial Licensing information, see
               http://fourwalledcubicle.com/PurchaseLUFA.php


This package contains the complete LUFA library, demos, user-submitted
projects and bootloaders for use with compatible microcontroller models.
LUFA is a simple to use, lightweight framework which sits atop the hardware
USB controller in specific AVR microcontroller models, and allows for the
quick and easy creation of complex USB devices and hosts.

To get started, you will need to install the "Doxygen" documentation
generation tool. If you use Linux, this can be installed via the "doxygen"
package in your chosen package management tool - under Ubuntu, this can be
achieved by running the following command in the terminal:

   sudo apt-get install doxygen

Other package managers and distributions will have similar methods to
install Doxygen. In Windows, you can download a prebuilt installer for
Doxygen from its website, www.doxygen.org.

Once installed, you can then use the Doxygen tool to generate the library
documentation from the command line or terminal of your operating system. To
do this, open your terminal or command line to the root directory of the
LUFA package, and type the following command:

   make doxygen

Which will recursively generate documentation for all elements in the
library - the core, plus all demos, projects and bootloaders. Generated
documentation will then be available by opening the file "index.html" of the
created Documentation/html/ subdirectories inside each project folder.

The documentation for the library itself (but not the documentation for the
individual demos, projects or bootloaders) is also available as a separate
package from the project webpage for convenience if Doxygen cannot be
installed.
