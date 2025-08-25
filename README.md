# cyberstormmk1notes

## Components

For fun there are no disignators on the silkcreen, it seems like there is no silkscreen at all.

### Main module

- DS1010S - 50ns delay line
  - datasheet: https://www.analog.com/media/en/technical-documentation/data-sheets/DS1010.pdf
  - used pins:
    - 1 - in1
    - 4 - tap 2
    - 5 - tap 4, through 0R resistor - seems to go to scsi module connector
        - Also goes to cclk jumper
    - 6 - tap 6, through 0R resistor - seems to go to scsi module connector
    - 7 - tap 8, through 0R resistor - seems to go to scsi module and red dot pal
    - 8 - gnd
    - 13 - tap 3, through 0R resistor - white dot pal
      - Also goes to cclk jumper
    - 16 - vcc
- S74FCT191TS1 x 2
- S74FCT573ATQ x 6
- 55AF33F
- QS3245Q


  ext90 signal is present on the resistor near the jumper near the rom socket closest to the cpu connecter, near the unpopulated plcc footprint (not the foo bar ones)

#### PALs

Under cpu module:
- DMACI - red dot
- STRTI - purple dot
- STRBI - blue dot
- TERMI - yellow dot

visible with cpu module mounted:
- RACI - green dot
- CASI - white dot, bodge wire
- DMAPI - no dot?
- ??? - red dot
- EROMI - blue dot

### CPU module

- 50MHz osc
- S74FCT573ATQ x 16
- 22V10H-7JC/5 x 3
- 74F20D

Connector pinout

- A == row closest to edge of board
- D == row closest to CPU

| Row |  0  |   6  |   7  |   8  |
|-----|-----|------|------|------|
| A   |     |      |  A3  |  A7  |
| B   |     |  A1  |  A5  |      |
| C   |     |  A0  |  A4  |      |
| D   |     |  A2  |  A6  |      |



