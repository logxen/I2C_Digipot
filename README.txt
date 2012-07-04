This is a simple 1 layer breakout board for the MAX5387 dual digipot.


Bill of Materials:

1x - 1.5" x 0.75" single sided copper clad board (pcb)
1x - MAX5387 dual digipot ic, 14 pin tssop (main ic)
1x - 0.1uF tantalum cap, 1206 (power filter)
2x - 4.7kOhm, 1206 (pull-ups for i2c bus)
1x - 1x4 0.1" pin header (i2c bus: vcc, scl, sda, gnd)
2x - 1x5 0.1" pin header (digipot ports: vcc, high, wiper, low, gnd)


NOTES:

- the .png file has descriptive layers, the .bmp is just the b/w copper mask for etching

- In order to fit everything in one layer the port headers are reversed 
    from one another, so look for the connections to the ground plane
    to make sure each port is wired in the correct direction.