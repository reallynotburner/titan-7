# Titan-7m

This is 7th CAD/CAM demonstration project from [Titans of CNC Academy](https://academy.titansofcnc.com/series/titan-building-blocks-mill-cnc).  The exciting new feature is that BOTH sides have contouring features, so you can't just flip the part and face it off to finish.  You must re-align your zeros after clamping the first side down and produce the mirror image of the other side.

I'm doing it in 1/3 scale.  The only CNC mill I can get time on is the desktop/crafty type.  If I did the part full size the milling operations would take longer than the [Makerspace](https://chescolibraries.org/using-the-library/makerspace/) is open per day.

## Files

- [Titan-7M Block Dovetailing.gcode](./Titan-7M%20Block%20Dovetailing.gcode) is to mill down a 4mm flat into the side of the raw stock.  Then I flip the part onto a parallel inserted into the flat and mill the next flat.  This makes the bar "T" shaped, providing a parallel and repeatable clamping feature for the next operations.

- [Titan-7M Facing.gcode](./Titan-7M%20Facing.gcode) is to mill the top surface flat, which is far easier to do with the dovetailing code above.  You don't have to run the code to completion but you can to reduce the material removal after you flip the part and finish it.

## Toolchain

- Autodesk Fusion 360
- Microsoft Code
- Carbide 3d Desktop Software
- Carbide 3d Desktop CNC Mill

## Todo's

- All the next operations need to be posted
- Figure out a way to document the process instructions, perhaps in markdown format
- Update the machine definition in Fusion 360 for the Nomad3, right now I have to manually edit and rename the files for it to run :/
- Consider including a .step file of the part.

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)