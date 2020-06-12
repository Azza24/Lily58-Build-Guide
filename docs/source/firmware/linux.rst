Linux (Arch)
============
Downloading QMK firmware
########################
You need several dependencies before you're able to run QMK toolbox.

Installing homebrew
*******************
If you already have homebrew installed you can skip this step.
To install these dependencies you need to install homebrew. 
To do this simply paste the following command in your terminal and press enter
.. code-block:: 
        /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)" 

Installing your dependencies
****************************
To install the dependencies paste the following lines into your terminal separated by an enter.
.. code-block::
        brew install libusb
        brew tap osx-cross/avr
        brew tap PX4/homebrew-px4
        brew update
        brew install avr-gcc
        brew install dfu-programmer
        brew install gcc-arm-none-aebi
        brew install avr-dude

If you're curious what all these dependencies do, you can look them up on the home brew website.

Installing QMK
**************
Finally we arrive on downloading the actual QMK firmware.
You can download it at `this <https://github.com/qmk/qmk_toolbox/releases>`_ link.
Scroll down to assets and download the QMK.Toolbox.app.zip.
Unzip the file and place it in your applications folder.

Flashing your keyboard
######################
Some instructions to flash your keyboard here.
