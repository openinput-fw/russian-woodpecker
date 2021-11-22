:hide-toc:

******************
russian-woodpecker
******************
*russian-woodpecker* is a usb HS (capable of 8kHz polling rate) 2.4GHz radio receiver dongle for use with input devices

Specifications
==============

* 8 kHz polling rate suppor
* 2.4GHz radio
* smol, but not that smol

Hardware
========

.. image:: assets/r0.1-boardview.png
   :width: 50%

* ATSAMS3U MCU as main controller
* nrf52810 MCU as radio receiver
   * SPI connection between MCUs
* USB C connector
* External antenna connector

State of the project
====================

First prototype.

.. admonition:: Roadmap

   - Initial design |:+1:|
   - First prototype manufactured and assembled |:hammer:|
   - Barebones firmware support
   - Documentation |:hammer:|
   - Hardware improvements / V1

   ========== ================
   |:+1:|     Done!
   |:hammer:| Work in progress
   ========== ================


.. toctree::
   :caption: External Links
   :hidden:

   Firmware <https://openinput.readthedocs.io>
   Issue Tracker <https://github.com/openinput-fw/russian-woodpecker/issues>
