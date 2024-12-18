# Powerboard v10

This is a repository containing the design files and user manual for the Powerboard v10.

This was developed by a collaboration between Ambimat Electronics and the University of Pennsylvania.

To purchase, please order from this link: [Ambimat Electronics Powerboard Purchase Link](https://orders.ambimat.com/product/f1tenth-power-board/). \
Reach out to neel.shah@ambimat.com in case there is any issue with the website.

## Repository layout

### Explanation of important files/folders

- ```USERMANUAL_Powerboard_v10.pdf```: Contains a description of the capabilities of the board. 
  - Relevant to everyone looking to purchase/fabricate/modify the existing design.
- ```hardware_design_files\```: Folder containing the bill of materials, schematics, PCB layout files (Altium), and gerber files.
    - Relevant if you want to get the board fabricated yourself.
- ```mechanical_specifications\```: Folder containing the mechanical drawings.
    - Relevant if you want to design a mount or any physical support for this powerboard.

### File layout
```
.
│   README.md
│   USERMANUAL_Powerboard_v10.pdf
│
├───hardware_design_files
│   │   BOM.xlsx
│   │   schematics.pdf
│   │
│   ├───gerber_files
│   │   ├───DrillData
│   │   │       AE170_PDU_02.04-RoundHoles.TXT
│   │   │       AE170_PDU_02.04-SlotHoles.TXT
│   │   │       AE170_PDU_02.04.DRL
│   │   │       AE170_PDU_02.04.DRR
│   │   │
│   │   └───GerberData
│   │           AE170_PDU_02.04.apr
│   │           AE170_PDU_02.04.G1
│   │           AE170_PDU_02.04.G2
│   │           AE170_PDU_02.04.GBL
│   │           AE170_PDU_02.04.GBO
│   │           AE170_PDU_02.04.GBP
│   │           AE170_PDU_02.04.GBS
│   │           AE170_PDU_02.04.GD1
│   │           AE170_PDU_02.04.GM1
│   │           AE170_PDU_02.04.GTL
│   │           AE170_PDU_02.04.GTO
│   │           AE170_PDU_02.04.GTP
│   │           AE170_PDU_02.04.GTS
│   │
│   └───layout
│           1. BD.SchDoc
│           2. Input Section.SchDoc
│           3. Buck Boost_19V.SchDoc
│           4. Buck Boost_12V.SchDoc
│           5. Buck_5V1A.SchDoc
│           6. Revision History.SchDoc
│           AE170_PDU_02.04.PcbDoc
│           AE170_PDU_02.04.PrjPcb
│
└───mechanical_specifications
        diagram.DXF
        diagram.pdf
```
