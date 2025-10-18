---
title: Component Selections
---

**Voltage Regulator**

1. L7805CV IC REG LINEAR 5V 1.5A TO220

    ![](image.png)

    * $0.50/each
    * [link to product](https://www.digikey.com/en/products/detail/stmicroelectronics/L7805CV/585964)

    | Pros                                      | Cons                                                             |
    | ----------------------------------------- | ---------------------------------------------------------------- |
    | Inexpensive component                     | Limited to 1.5 Ampere output              |
    | Large operating temperature range         | Heats up quickly                   |
    | Meets through hole mount constraint of project |

1. LT323AT#PBF IC REG LINEAR 5V 3A TO220-3

    ![](image-1.png)

    * $8.94/each
    * [Link to product](https://www.digikey.com/en/products/detail/analog-devices-inc/LT323AT-PBF/888959)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | Large output current                                             | Very expensive      |
    | Large operating temperature range                                 | Slow shipping speed |
    | 100% Burn-in Thermal Limit |

    1. LM1084IT-5.0/NOPB IC REG LINEAR 5V 5A TO220-3

    ![](image-2.png)

    * $2.83/each
    * [Link to product](https://www.digikey.com/en/products/detail/texas-instruments/LM1084IT-5-0-NOPB/363556)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | Massive output current                                             | Slightly expensive      |
    | Low dropout voltage                                 | Poor load regulation in cold temperatures |
    | Current limiting and thermal protection |

**Choice:** Option 3: LM1084IT-5.0/NOPB IC REG LINEAR 5V 5A TO220-3

**Rationale:** The TI voltage regulator is more expensive, but has an output of 5 Amperes, ensuring the all components will have sufficient power. It's also cheaper than the LT323AT#PBF from Analog Devices Inc., despite having a larger current output.

**Operational Amplifier**

1. MCP6004-I/P IC OPAMP GP 4 CIRCUIT 14DIP

    ![](image-3.png)

    * $0.59/each
    * [link to product](https://www.digikey.com/en/products/detail/microchip-technology/MCP6004-I-P/523060)

    | Pros                                      | Cons                                                             |
    | ----------------------------------------- | ---------------------------------------------------------------- |
    | Inexpensive component                     | Pins are hard to reposition              |
    | Multiple circuits available for use       | Takes up large space on PCB                   |
    | Small voltage swing |

1. MCP6004-E/P IC OPAMP GP 4 CIRCUIT 14DIP

    ![](image-4.png)

    * $0.65/each
    * [Link to product](https://www.digikey.com/en/products/detail/microchip-technology/MCP6004-E-P/683200)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | Larger operating temperature range                                | Pins are hard to reposition      |
    | Also inexpensive, but not as much as MCP6004-I/P                  | Takes up large space on PCB |
    | Meets through hole mount constraints for project |

    1. MCP601-I/P IC OPAMP GP 1 CIRCUIT 8DIP

    ![](image-5.png)

    * $0.62/each
    * [Link to product](https://www.digikey.com/en/products/detail/microchip-technology/MCP601-I-P/305930)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | Smaller IC                                             | Only 1 circuit available      |
    | Larger gain bandwidth                                 | Large noise voltage density below 20 Hz |
    | Slightly cheaper than MCP6004-E/P |

**Choice:** Option 3: MCP601-I/P

**Rationale:** The smaller volume and larger gain bandwidth make the MCP601-I/P much more suitable. The device doesn't need more than 1 operational amplifier and since all 3 choices are roughly the same price, the choice became clear.