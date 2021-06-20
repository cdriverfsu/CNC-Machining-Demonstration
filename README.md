# CNC-Machining-Demonstration
Digital Media Fab Lab - CNC Machining Demonstration - Advanced Prototyping: Reverse/Flip-Machining for Two-Sided Objects

Toolpath Programming in Autodesk Fusion 360 for Machining with a Carbide 3D Nomad 883 Pro CNC Machine

< https://labs.art.fsu.edu/digital-media/resources-for-teaching/ >





Demonstration Videos 

< https://fsu-my.sharepoint.com/:f:/g/personal/cdriver_fsu_edu/EtPGq5jMax5Csll2YAxgiA0Bb7cdwTJ1iWzN49EIQE-EnQ?e=8P0Xnt >

  < 01 > Double-Sided Tape _ Graphite _ on Y-Platform 

  < 02 > Double-Sided Tape _ Graphite _ on Y-Platform _ Square Format 

  < 03 > CNC Demonstration - Attaching Material Stock & Installing Tool Bit 

  < 04 > Attaching Material Stock to Y-Platform & Tool Bit Installation 

  < 05 > Setting WCS for Facing Toolpath 

  < 06 > Full Simulation _ Side 00 _ Setup 12 

  < 07 > Side 00 _ Setup 12 _ Timelapse 

  < 08 > Full Simulation _ Side 01 _ Setup 13 

  < 09 > Side 01 _ Setup 13 _ Timelapse 

  < 10 > Complete _ Demonstration Object Basswood Prototype _ 00 

  < 11 > Tool Bit Change During Full Setup Program 

  < 12 > Variable _ Graphite _ Tool Bit Installation 

  < 13 > variable 03 _ Changing WCS location & Morphed Spiral Toolpath 




Prototype Files 

< Prototype _ Material Stock Vector Contour _ 80mm x 80mm x 6.35mm.ai >
is a vector of the material stock contour

  < https://fsu-my.sharepoint.com/:f:/g/personal/cdriver_fsu_edu/EqRFXYNYsK5Lh3ZcfJZDN7oBAv50xIKCtMcmlyMzJaO2KQ?e=M4YecF >

< platform _ 1001 _ 00.nc >
is a source code file for CNC machining aluminum, containing 8 toolpaths, and 4 tool bit changes, and one material stock part reversal/material stock flip




  tool bits;

  1/8" 2 flute square endmill

  1/8" 2 flute ballmill




  tool bits utilized in the < CNC Machining Demonstration >;

  Carbide3D #102 .125" flat cutter

  Carbide3D #101 .125" ball cutter

  < https://shop.carbide3D.com >




  toolpaths;

  Side 00, Facing, 1/8" 2 flute square endmill

  Side 00, Spiral, 1/8" 2 flute ballmill

  Side 00, Morphed Spiral, 1/8" 2 flute ballmill

  Side 00, Parallel, 1/8" 2 flute ballmill

  Material Part Reversal/Flip Material

  Side 01, Facing, 1/8" 2 flute square endmill

  Side 01, Spiral, 1/8" 2 flute ballmill

  Side 01, Parallel, 1/8" 2 flute ballmill

  Side 01, Morphed Spiral, 1/8" 2 flute ballmill




contact

Caitlin Driver, Digital Media Labs, Manager

Department of Art

530 West Call Street

Fine Arts Building 220

Tallahassee, Florida 32306-1150 

cdriver@fsu.edu
