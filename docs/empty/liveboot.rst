Booting the USB or DVD
===============

Now that you have Feren OS on a USB stick (or DVD), boot the computer from it.

1. Insert your USB stick (or DVD) into the computer.

2. Power on the computer.

3. Before your computer shows an error about there being No Operating Systems installed you should see your manufacturer's logo. Check the screen or your computer's documentation to know which key to press and instruct your computer to boot on USB (or DVD).

.. note::
	Most hardware has a special key you can press to select the boot device, and all of them have a special key to enter the BIOS/Firmware Configuration screen (from which you can define the boot order). Depending on the hardware, these special keys can be :kbd:`Escape`, :kbd:`F1`, :kbd:`F2`, :kbd:`F8`, :kbd:`F10`, :kbd:`F11`, :kbd:`F12`, or :kbd:`Delete`. On some hardware, that information is briefly written on the screen during the boot sequence.

4. When booted Feren OS will show a language select menu as depicted in the example shown below:

.. figure:: ../images/grubpreinstall.png
    :width: 1024px
    :align: center

    Feren OS's language select menu

5. Scroll with the up and down arrow keys to your language and press :kbd:`Enter` to start Feren OS from your USB stick (or DVD).


Booting with 'nomodeset' (for NVIDIA users)
-------------------------------------

If you have NVIDIA Graphics on your device, you may run into graphical issues when booting into Feren OS normally as the correct drivers for your hardware are not present by default in Feren OS.

However, there is a quick workaround. In both boot menus there is an option called "nomodeset". If you're having problems with booting Feren OS normally on NVIDIA hardware then simply select the :guilabel:`nomodeset` option instead and Feren OS should boot, albeit with some graphical deficiencies compared to what it looks like once properly installed and with the correct drivers installed onto it.


Next Steps
----------------

* `Accessibility <https://feren-os-user-guide.readthedocs.io/en/latest/empty/accessibility.html>`_
* `Installing Feren OS <https://feren-os-user-guide.readthedocs.io/en/latest/empty/install.html>`_