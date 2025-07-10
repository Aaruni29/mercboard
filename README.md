# Mercboard – A Formula One Inspired Mechanical Keyboard

Mercboard is a fully custom mechanical keyboard designed and developed from the ground up using EasyEDA Pro. The project blends the world of electronics with the adrenaline of motorsports, specifically drawing inspiration from the Mercedes-AMG Petronas Formula 1 team. Unlike most PCBs that merely serve as functional platforms, Mercboard also tells a visual story. The silkscreen layer proudly features a meticulously integrated illustration of an F1 car, placed such that it flows through the switch matrix like it's racing across a digital track.

<img width="943" height="505" alt="Screenshot 2025-07-10 155016" src="https://github.com/user-attachments/assets/69d8555f-2d94-4bef-9072-f0710092ffa8" />

The design process was intense and personal. Over four days and twenty-one hours, every detail  from component selection to silkscreen layout — was crafted by hand, mostly during late-night design sprints fuelled by chai and deep focus. This is not just a mechanical keyboard PCB, it is a reflection of what happens when art and engineering are given equal importance.

<img width="779" height="406" alt="Screenshot 2025-07-10 154817" src="https://github.com/user-attachments/assets/7c647b12-084c-494a-99fd-fe422481e199" />

The core of the Mercboard is built around the ATmega32U4 microcontroller. This chip was selected for its reliability, native USB support, and seamless compatibility with open-source keyboard firmware platforms such as QMK and VIA. The keyboard uses a 5-row by 14-column matrix layout which enables a standard 65-key configuration. This offers a balance between compactness and usability, including the main alphanumeric cluster, arrow keys, and essential modifiers.


<img width="1026" height="484" alt="Screenshot 2025-07-10 154925" src="https://github.com/user-attachments/assets/b3b0ce46-b836-4e00-8cf4-d09ad41a2a44" />



The schematic was carefully drawn in EasyEDA Pro, ensuring that all passive components such as resistors, capacitors, and diodes were selected with practical sourcing and performance in mind. For the matrix, standard 1N4148 signal diodes were used, which are reliable and readily available. Pull-down resistors, decoupling capacitors, ESD protection components, and USB filtering circuitry were all included to make sure that the keyboard would be robust under daily use. The circuit was passed through multiple rounds of Electrical Rule Checks to ensure reliability, and each net was reviewed manually during layout to avoid signal integrity issues or routing congestion.

<img width="770" height="525" alt="Screenshot 2025-07-10 154530" src="https://github.com/user-attachments/assets/f5363ecd-122c-491b-8279-057a67d0031d" />

## BOM


| **Component**      | **Description**                         | **Qty**  | **Source**           | **Unit Price (INR)** | **Total (INR)** | **Unit Price (USD)** | **Total (USD)** |
| ------------------ | --------------------------------------- | -------- | -------------------- | -------------------- | --------------- | -------------------- | --------------- |
| **PCB**            | Custom PCB (Black, 1.6mm, HASL)         | 5        | JLCPCB               | ₹285.00              | ₹1425.00        | \$3.42               | \$17.10         |
| **PCBA**           | SMT Passive Assembly (Top side only)    | 2        | JLCPCB               | ₹905.00              | ₹1810.00        | \$5.42               | \$10.84         |
| **Shipping**       | JLCPCB Express Discounted (1.85kg)      | 1        | JLCPCB               | ₹2300.00             | ₹2300.00        | \$27.67              | \$27.67         |
| **MCU**            | ATmega32U4-AU (TQFP-44)                 | 2        | Shaarvi    | ₹320.00              | ₹640.00         | \$3.85               | \$7.70          |
| **Crystal**        | 16 MHz Crystal (SMD 3225)               | 2        |  LCSC       | ₹18.00               | ₹36.00          | \$0.22               | \$0.44          |
| **Caps/Resistors** | Supporting RLC (caps, pullups, etc.)    | Full set |  LCSC          | ₹90.00               | ₹90.00          | \$1.08               | \$1.08          |
| **USB Port**       | USB Micro-B Female (SMD)                | 2        | LCSC / JLCPCB PCBA   | ₹25.00               | ₹50.00          | \$0.30               | \$0.60          |
| **Switches**       | Gateron Yellow clones (budget)          | 65       | Meckeys | ₹20.00               | ₹1300.00        | \$0.24               | \$15.60         |
| **Keycaps**        | PBT 65% Keyset (OEM, non-backlit)       | 1 set    | NeoMacro | ₹1290.00             | ₹1290.00        | \$15.30              | \$15.30         |
| **Diodes**         | 1N4148 THT or SMD                       | 70       | Shaarvi      | ₹1.40                | ₹98.00          | \$0.017              | \$1.19          |
| **Reset Button**   | Tactile Button 6mm                      | 1        | Shaarvi      | ₹6.00                | ₹6.00           | \$0.07               | \$0.07          |
| **OLED Display**   | 0.91" I²C OLED (SSD1306, 128×32, 4-pin) | 1        |  Amazon.in  | ₹190.00              | ₹190.00         | \$2.28               | \$2.28          |
| **Cable**          | USB-A to USB Micro braided (1.5m)       | 1        | Amazon.in            | ₹225.00              | ₹225.00         | \$2.70               | \$2.70          |


| **Currency** | **Total**      |
| ------------ | -------------- |
| INR          | ₹10,860.00     |
| USD          | **\$129.93**  |



The PCB design was where the real personality of the project took shape. Components were placed not only for electrical convenience but also to work around the space needed for the silkscreen art. The F1 car artwork was vectorized and then imported into the silkscreen layer manually, using EasyEDA’s graphical editing tools. Every trace was routed with care, avoiding any clash with the visual elements of the car. Unlike automated designs, this board was routed completely by hand. Tracks were nudged millimeter by millimeter, vias repositioned, and layers tweaked so the art and the circuit could live together in harmony.

<img width="634" height="589" alt="Screenshot 2025-07-10 155318" src="https://github.com/user-attachments/assets/7eb04650-fdda-48eb-9dac-a920920f571b" />
<img width="473" height="472" alt="image" src="https://github.com/user-attachments/assets/854e0926-e482-4983-82e2-ca4e66d93c39" />
<img width="541" height="331" alt="image" src="https://github.com/user-attachments/assets/d68a61da-2f9b-4947-947d-a160153b0f86" />
