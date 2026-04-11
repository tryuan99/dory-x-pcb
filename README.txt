# Fabrication Notes

- IPC spec: IPC6012F class 2
- Surface finish: Immersion tin
- Solder mask color: Blue
- Silk screen color: White
- For vias-in-pads, use non-conductive epoxy filling with copper cap and planarization.
- Tented vias are marked in the Gerber files.
- There are no features on the bottom silk screen.
- Impedance control is necessary between the top layer (GTL) and the second layer (G1), which sandwich the Rogers RO4350B dielectric. Impedance control type: microstrip, target impedance: 50 Ohms, width: 16.65 mil.