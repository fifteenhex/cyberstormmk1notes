# cyberstormmk1notes

## Components

For fun there are no disignators on the silkcreen, it seems like there is no silkscreen at all.

### Main module

- DS1010S - 50ns delay line
  - datasheet: https://www.analog.com/media/en/technical-documentation/data-sheets/DS1010.pdf
  - used pins:
    - 1
    - 4
    - 5
    - 6
    - 7
    - 8
    - 13
    - 16
- S74FCT191TS1 x 2
- S74FCT573ATQ x 6
- 55AF33F
- QS3245Q
  

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



