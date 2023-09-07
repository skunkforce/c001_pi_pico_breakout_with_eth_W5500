# edgy_board number c001
This design is part of the [edgy board project](https://github.com/skunkforce/edgy_boards).

![](/board/board.png)

This design is a composition of edgies.
```mermaid
graph LR
    b018(b018 RP2040)-- SPI -->b078(b078 Ethernet MAC+PHY)
    b018--> b096(b096 MAC ID)

```
# getting started
This repository uses submodules. After cloning use the command 

```$ git submodule update --init --recursive```

to pull the submodules before opening the project with kicad. 

# Tests
Tests can be found in [TESTS.md](TESTS.md)

