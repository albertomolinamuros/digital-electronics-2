# Lab 6: Alberto Molina Muros

### ASCII

1. Complete the table with selected ASCII codes.

   | **Char** | **Decimal** | **Hexadecimal** | **Binary** |
   | :-: | :-: | :-: | :-: |
   | `a` | 97 | 0x61 | `0b0110_0001` |
   | `b` | 98 | 0x62 | `0b0110_0010` |
   | `c` | 99 | 0x63 | `0b0110_0011` |
   | `0` | 48 | 0x30 | `0b0011_0000` |
   | `1` | 49 | 0x31 | `0b0011_0001` |
   | `2` | 50 | 0x32 | `0b0011_0010` |
   | `Esc` | 27 | 0x1b | `0b0110_0010` |
   | `Space` | 32 | 0x20 | `0b0110_0010` |
   | `Tab` | 9 | 0x9 | `0b0000_1001` |
   | `Backspace` | 8 | 0x8 | `0b0000_1000` |
   | `Enter` | 13,10 | 0xd, 0xa  | `0b0000_1101, 0b0000_1010` |

### UART communication

2. Draw a timing diagram of the output from UART/USART when transmitting three character data `De2` in 4800 7O2 mode (7 data bits, odd parity, 2 stop bits, 4800&nbsp;Bd). The image can be drawn on a computer (by [WaveDrom](https://wavedrom.com/) for example) or by hand. Name all parts of timing diagram.

   ![1](https://user-images.githubusercontent.com/114478568/200431367-4b716a0c-81ef-4092-90c2-aea542a1e1e7.jpg)


3. Draw a flowchart for function `uint8_t get_parity(uint8_t data, uint8_t type)` which calculates a parity bit of input 8-bit `data` according to parameter `type`. The image can be drawn on a computer or by hand. Use clear description of individual algorithm steps.

   ![2](https://user-images.githubusercontent.com/114478568/200431402-cbe28116-e1f3-4066-9a6e-53b0ddc633d2.jpg)
![140805807-ceec8aa0-e03b-4b9b-9b06-189160d989ea](https://user-images.githubusercontent.com/114478568/200431418-406aaca6-448d-4cf2-b00b-7c28de00df94.jpg)
