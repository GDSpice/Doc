.. _symbols_library:

Symbols Library
===============

Welcome to the DSpice Symbols Library documentation. Here you will find detailed 
descriptions, netlist formats, and usage guides for all available schematic components.

Each symbol in DSpice is more than just a graphical icon; it is a smart object that encapsulates:

- **Visual Representation:** IEEE/ANSI-compliant schematic symbols with color-coded terminals (green squares).
- **Netlist Mapping:** Automatic translation of schematic placements into valid ngspice syntax.
- **Parameter Management:** Support for both basic values (e.g., Resistance, Voltage) and advanced parameters (e.g., TC1, Rser) via symbol modification.
- **Hierarchical Organization:** Components are categorized into logical folders such as ``Basic``, ``Sources``, ``Semiconductors``, and ``etc..`` for efficient navigation.


The library is organized into functional categories to help you find components quickly.

Basic Components
----------------

Fundamental passive elements used in circuit design.

.. toctree::
   :maxdepth: 1

   basic/Resistor
   # basic/Capacitor
   # basic/Inductor

Source Components
-----------------

Independent voltage and current sources for powering circuits.

.. toctree::
   :maxdepth: 1

   sources/Vdc
   # sources/Vac
   # sources/Idc


