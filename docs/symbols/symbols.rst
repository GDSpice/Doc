.. _symbols_library:

Symbols Library
===============

Welcome to the DSpice Symbols Library documentation. Here you will find detailed 
descriptions, netlist formats, and usage guides for all available schematic components.

The library is organized into functional categories to help you find components quickly.

Basic Components
----------------

Fundamental passive elements used in circuit design.

.. toctree::
   :maxdepth: 1

   basic/Resistor
   basic/Capacitor
   basic/Inductor

Source Components
-----------------

Independent voltage and current sources for powering circuits.

.. toctree::
   :maxdepth: 1


   sources/Vdc
   sources/Idc
   sources/Vsin
   sources/Isin

.. note::
   All symbols support advanced parameter modification. 
   See individual component pages for details on adding parameters like 
   ``TC1``, ``TC2``, ``IC``, or ``Rser`` directly to the symbol definition.


