# sherBLOCK: a portable, DIY isothermal incubator.

<p align="center">
<img width="635" height="320" alt="sherBLOCK_5x" src="https://github.com/user-attachments/assets/30881fb8-7763-4c0f-a63b-72c7404489b2" />
</p>

The sherBLOCK is a portable DIY isothermal heater designed for tube incubation in the field. It can be assembled in two models of varying power output: sherBLOCK and sherBLOCK+. Both models operate at 12V DC and can be powered by a barrel jack wall adapter or a cigarette lighter car plug, allowing on-the-go use and application of molecular biology protocols in remote areas. They are controlled by an Arduino Nano microcontroller, which can be reprogrammed to match user-specific needs. The standard sherBLOCK model is limited to a current of 2A, meaning it has a lower maximum incubation temperature ceiling of around 60°C. Meanwhile, the sherBLOCK+ can withstand currents of up to 10A, allowing it to reach temperatures well above 95°C. 

The sherBLOCK can be assembled to fit a variety of tube sizes (0.2, 0.5, 1.5, 5, and 15mL tubes). Other components, such as heaters, can also be replaced to meet your demands as long as they fit the sizing and power specifications of the model. Components that deviate in sizing may require adjustments to the 3D printing files.

<img width="2133" height="1580" alt="IMG_3496" src="https://github.com/user-attachments/assets/196ce725-fc49-48ab-b990-b90faa20ee89" />

To assemble the sherBLOCK, first check the Bill Of Materials (BOM) of the corresponding model you want to build: [sherBLOCK BOM](<sherBLOCK BOM.xlsx>), [sherBLOCK+ BOM](<sherBLOCK+ BOM.xlsx>). The BOM contains a list of the components and tools that you will need for the assembly, along with the bulk and per unit costs and a link where you can source them from. The enclosure of the sherBLOCK must be 3D printed and cannot be directly purchased, so ensure that you have access to a 3D printer or 3D printing services before purchasing any components or filament. Further, the sherBLOCK+ reaches higher temperatures than most 3D printing materials can tolerate, so it must be printed with high-quality ASA filament which not all 3D printers can work with. Be aware that most components are purchased from Amazon, so seller variability may result in items running out of stock or no longer being offered. If you encounter issues obtaining the parts listed in our BOM, reach out to us through our email (pjlemgruber@ucdavis.edu), we are happy to help!

<details>
  <summary>View a simplified sherBLOCK BOM</summary>

  | Materials | Bulk amount | Bulk cost | Amount | Cost |
| --- | --- | --- | --- | --- |
| **Interactive elements** |  |  |  |  |
| Arduino Nano | 2 | $9.99 | 1 | $5.00 |
| DS18B20 w/ adapter | 2 | $9.99 | 1 | $5.00 |
| 12V Heating Plate PTC | 4 | $16.19 | 1 | $4.05 |
| OLED display | 1 | $21.00 | 1 | $21.00 |
| Heat block | 1 | $35.99 | 1 | $35.99 |
| **Wiring** |  |  |  |  |
| 12V Power Adapter | 1 | $7.29 | 1 | $7.29 |
| Female Power Jack DC | 5 | $4.99 | 1 | $1.00 |
| MOSFET IRF540N N-Channel | 10 | $7.99 | 1 | $0.80 |
| Breadboard | 3 | $5.98 | 1 | $2.00 |
| Jumper wires | 1 pack | $8.99 | 14 | $0.50 |
| 18 AWG Stranded Wire | 100 ft | $16.95 | 1 foot | $0.17 |
| Buck converter | 1 | $6.99 | 1 | $6.99 |
| 2 Screw Barrier Block terminal | 1 | $0.89 | 1 | $0.89 |
| 3 way PCB terminal | 10 | $7.99 | 1 | $0.80 |
| 220 Ohm resistors | 100 | $5.99 | 1 | $0.06 |
| 4.7k Ohm resistors | 100 | $5.99 | 1 | $0.06 |
| 100k Ohm resistors | 100 | $5.99 | 1 | $0.06 |
| **Nuts and bolts** |  |  |  |  |
| 10mm M3 nylon screws |  |  | 4 | $0.08 |
| 45mm M3 steel screws |  | $8.99 | 2 | $0.04 |
| 65mm M3 steel screws |  | $10.00 | 4 | $0.80 |
| 20mm M5 screws |  | included | 4 | $0.08 |
| M3 nylon hex nuts |  | included | 12 | $0.24 |
| M3 steel hex nuts |  | included | 6 | $0.12 |
| **Filament and printed parts** |  |  |  |  |
| sherBLOCK base |  |  | 64g | $1.27 |
| sherBLOCK lid |  |  | 49g | $0.99 |
| Support for barrel jack adapter |  |  | 3.3g | $0.07 |
| **Total cost:** | Bulk | $198.18 | Unit | **$95.35** |

</details>

<details>
  <summary>View a simplified sherBLOCK+ BOM</summary>

| Materials | Bulk amount | Bulk cost | Amount | Cost |
| --- | --- | --- | --- | --- |
| **Interactive elements** |  |  |  |  |
| Arduino Nano | 2 | $9.99 | 1 | $5.00 |
| DS18B20 w/ adapter | 2 | $9.99 | 1 | $5.00 |
| 12V Heating Plate | 4 | $16.29 | 1 | $4.08 |
| OLED display | 1 | $23.00 | 1 | $23.00 |
| Heat block | 1 | $35.99 | 1 | $35.99 |
| Silicone rubber stovetop feet | 16 | $8.29 | 4 | $2.10 |
| **Wiring** |  |  |  |  |
| 12V 10A Power Adapter 2.5x5.5mm | 1 | $22.00 | 1 | $22.00 |
| 10A Power Jack connector | 1 | $1.86 | 1 | $1.86 |
| MOSFET IRLB3813 | 1 | $2.81 | 1 | $2.81 |
| Breadboard | 3 | $5.98 | 1 | $2.00 |
| Jumper wires | 1 pack | $8.99 | 14 | $0.50 |
| Heat shrink tubing | 1 pack | $7.00 | 5 | $0.06 |
| 16 AWG Stranded Wire | 100 ft | $15.95 | 1 foot | $0.16 |
| Buck converter | 1 | $6.99 | 1 | $6.99 |
| 2 Screw Barrier Block terminal | 1 | $0.89 | 1 | $0.89 |
| 3 way PCB terminal | 10 | $7.99 | 1 | $0.80 |
| 220 Ohm resistors | 100 | $5.99 | 1 | $0.06 |
| 4.7k Ohm resistors | 100 | $5.99 | 1 | $0.06 |
| 100k Ohm resistors | 100 | $5.99 | 1 | $0.06 |
| **Nuts and bolts** |  |  |  |  |
| 12mm M3 nylon screws |  | $9.99 | 10 | $0.20 |
| 45mm M3 steel screws |  | $8.99 | 2 | $0.04 |
| 65mm M3 steel screws |  | $10.00 | 4 | $0.80 |
| 20mm M5 screws |  |  | 4 | $0.08 |
| M3 nylon hex nuts |  |  | 10 | $0.20 |
| M3 steel hex nuts |  |  | 6 | $0.12 |
| **ASA filament** | 1kg | $20.00 |  |  |
| sherBLOCK+ base |  |  | UPDATE | UPDATE |
| sherBLOCK+ lid |  |  | UPDATE | UPDATE |
| Support for 10A adapter |  |  | UPDATE | UPDATE |
| **Total cost:** |  | $250.96 |  | **$114.86** |

</details>

Once you have acquired the necessary materials and tools for your sherBLOCK model, you can follow our [assembly guide](<sherBLOCK assembly guide.pdf>) for a step-by-step manual on how to assemble your own sherBLOCK. The guide has pictures of all the components, as well as images to complement most instructions.

We welcome you to make modifications to the sherBLOCK and share them here so others can access them. 

This project is held under the GNU General Public Licence v3.0. Please keep in mind that by choosing to use or engage with the materials of this project, you are doing so at your own risk. The sherBLOCK includes heaters and sensitive electronics, making it a potential fire hazard. Please exercise caution when engaging with the materials provided here and use them responsibly. 

View the 3D models:
[enclosure base](<Print files/sherBLOCK_10A_v1.5-Base Base body.stl>),
[lid](<Print files/sherBLOCK_10A_v1.5-Fused lidFused lid body.stl>), and
[power adapter](<Print files/sherBLOCK_10A_v1.5-10A adapter enclosureadapter enclosure body.stl>).
