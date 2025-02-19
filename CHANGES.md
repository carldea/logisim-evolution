[![Logisim-evolution](artwork/logisim-evolution-logo.svg)](https://github.com/logisim-evolution/logisim-evolution)

# Changes #

* v3.6.0 (2021-09-05)
  * Introducing project logo.
  * Fixed project loader to correctly handle hex values with a 1 in bit 63rd.
  * Added TTL74x34 hex buffer gate.
  * Made pins' tooltips more descriptive for 74161.
  * Added new component LED Bar.
  * Added 74157 and 74158: Quad 2-line to1-line selectors.
  * Added option to configure canvas' and grid's colors.
  * Added DIP switch state visual feedback for ON state.
  * Augmented direction verbal labels (East, North, etc), with corresponding arrow symbols.
  * Application title string now adds app name/version at the very end of the title.
  * Added option to configure size of connection pin markers.
  * Added TTL 74x139: dual 2-line to 4-lines decoders.
  * Fixed missing port on DotMatrix.
  * Combined `Select Location` from Plexers and `Gate Location` from Wiring to one attribute.
    * Breaks backwards comparability for Transistors and Transmission Gates.
      When opening old .circ files, they will have the default `Select Location` ("Bottom/Left").
  * Replace DarkLaf with FlatLaf for better compatibility.
  * Adds "Rotate Left" context menu action.
  * Display "Too few inputs for table" if Karnaugh Map has only 1 input.
  * HexDisplay is stays blank if no valid data is fed instead of showing "H" [#365].
  * Project's "Dirty" (unsaved) state is now also reflected by adding `*` marker to the window title.
  * Support for `AnimatedIcon` has been completely removed.
  * Canvas Zoom controls new offer wider range of zoom and three level of granularity.
  * Added predefined quick zoom buttons.
  * Tons of code cleanup and internal improvements.
  * Added duplicated component placement on same location refusal
  * Fixed pin duplication on load in case a custom apearance is used for a circuit
  * Added LED-array support for FPGA-boards
  * Improved partial placement on FPGA-boards for multi-pin components
  * Fixed several small bugs
  * Each circuit will now remember, restore, and save:
    * The last tick-frequency used for simulation
    * The last download frequency used
  * Removed obsolete VHDL-Architecture attribute from circuit

* v3.5.0 (2021-05-25)
  * Many code-cleanups, bug fixes and again the chronogram.
