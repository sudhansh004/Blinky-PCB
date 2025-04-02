# LED blinking circuit using 7555 timer IC


This project contains the KiCad PCB design files for a simple led blinking circuit using a 7555 Timer IC. The circuit blinks the LED at a fixed frequency using an **astable multivibrator configuration**.

## Circuit Description:
The 7555 Timer is configured in astable mode, where:
- The timing components (resistors and capacitor) determine the LED's blinking frequency.
- The output of the 7555 IC toggles between HIGH and LOW, turning the LED on and off.

## Files Included
- **Schematic (.sch)** – Circuit design in KiCad.
- **PCB Layout (.kicad_pcb)** – PCB design file.
- **BOM (Bill of Materials)** – List of components used.
- **Gerber Files** – For PCB manufacturing.
- **Custom Footprints & Symbols** – Custom-designed KiCad library files.

## Components Used:
- 7555 Timer IC
- Resistors X 3 (0805 SMD)
- Capacitor (0805 SMD)
- LED (0805 SMD)
- Power supply (S8211-46R Battery Holder SMD)
  
## Custom Footprints & Symbols:
This project includes custom-designed footprints and symbols to enhance the PCB layout and schematic clarity:
- 7555 IC symbol for schematic in the symbols folder (you can also find it pre-existing in newer versions of KiCad).
- Footprints for the Battery holder in the myown.pretty folder.
Add the libraries to your library manager and it'll be available in your editor.

## How to Use:
1. Open the project in KiCad.
2. Modify component values if needed.
3. Generate and export Gerber files for PCB fabrication.
4. Assemble components and test the circuit.




Here you go now feel free to submit issues or improvements via pull requests! 