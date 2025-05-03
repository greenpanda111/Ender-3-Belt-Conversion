# Ender-3-Belt-Conversion

The goal of this project is to convert a Creality Ender 3 into a belt printer with 45° gantry, belt driven Y axis, direct drive extruder, Marlin firmware, and octoprint integration. My main inspiration for this was [Rob Mink's BabyBelt](https://github.com/robmink/babybeltpro?tab=readme-ov-file) but after obtaining an Ender 3 for £10, I wanted to dream bigger. There are a few existing conversion kits that I will take designs from and mix together to create a base. However, there are some improvements of my own I will make. Please see the sources below for more information.

---

# Info 

3D printers with belts offer a couple incredibly unique advantages over typical coreXY or belt slinger style 3D printers. By having an effectivey infinite Z axis, you are able to continuously print the same model over and over with the only limit being your filament. This is accomplished by the conveyor belt being able to translate the completed model to the end of the build area, where the belt will loop back around under the bed, causing the belt to peel away from the model and allowing it to fall off the end of the bed. By placing a container at the end of the belt, you can easily mass produce components. Additionally, by tilting the gantry by 45° you can print infinitely long models while ensuring that as the model extends off the belt, the released portion is completed.

There are some disadvantages and current challenges of belt printers that should be noted. The 45° gantry tilt decreases the maximum build height. Additionally, belt printers struggle a lot with adhesion. There are many different belt designs: some use steel shim and PET sheet while others use fabrics. The problem is that due to belt printers being lesser known, there has been a lot less R&D done in to them and they have not been perfected for hobbyists yet. There are a small handful of conversion kits that sell belts too but I may look into developing my own belts.

---

# Specification

- [ ] Covert Gantry Angle to 45°
- [ ] Y Axis Belt Conversion
- [ ] Conveyor Belt Bed
- [ ] Direct Drive Extruder
- [ ] Custom Marlin Firmware
- [ ] OctoPrint Integration

---

# Sources:
### - Baby Belt: 
https://github.com/robmink/babybeltpro?tab=readme-ov-file
### - EnderLoop: 
https://github.com/mcsgroi/EnderLoop?tab=readme-ov-file
### - Ender EZ Belt:
https://www.printables.com/model/255684-ender-ez-belt-3d-printer-conversion/comments
### - Belt3DPrinterKit Belts:
https://belt3dprinterkit.com/products/blue-conveyor-belt-improved-adhesion?variant=42418349310103
