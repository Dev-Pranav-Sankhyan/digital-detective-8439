# Mission 5 - Numbers and data

## 1. Task / objective
Convert numbers between decimal, binary, and hexadecimal formats, verify them with Python, build a mini converter script, and understand how text is encoded.

## 2. Work completed
I manually converted the required numbers, tested them in the Python interactive shell, wrote the `number_converter.py` script, and answered the questions about text encoding.

### Task 5.1 - Convert numbers by hand
| Question | Your working and answer |
| :--- | :--- |
| Convert decimal 13 to binary. | 13/2=6 R1, 6/2=3 R0, 3/2=1 R1, 1/2=0 R1 -> **1101** |
| Convert decimal 25 to binary. | 25/2=12 R1, 12/2=6 R0, 6/2=3 R0, 3/2=1 R1, 1/2=0 R1 -> **11001** |
| Convert binary 1010 to decimal. | (1x8) + (0x4) + (1x2) + (0x1) = 8 + 2 -> **10** |
| Convert binary 1101 to decimal. | (1x8) + (1x4) + (0x2) + (1x1) = 8 + 4 + 1 -> **13** |
| Convert hexadecimal A to decimal. | A directly equals **10** in base 16 |
| Convert hexadecimal 1F to decimal. | (1x16) + (15x1) = 16 + 15 -> **31** |
| Convert binary 1111 to hexadecimal. | 1111 in binary is 15 in decimal, which is **F** in hex |

### Task 5.2 Verify using Python
*   `bin(13)` -> Result: `'0b1101'` (Matches manual)
*   `int('1010', 2)` -> Result: `10` (Matches manual)
*   `int('A', 16)` -> Result: `10` (Matches manual)
*   `hex(0b1111)` -> Result: `'0xf'` (Matches manual)

### Task 5.3 Build a small number converter
*   **What the functions do:** `bin()` converts an integer to a binary string starting with `0b`. `hex()` converts an integer to a hexadecimal string starting with `0x`.

| Test number | Binary output | Hexadecimal output |
| :--- | :--- | :--- |
| 10 | 0b1010 | 0xa |
| 100 | 0b1100100 | 0x64 |
| 255 | 0b11111111 | 0xff |

### Task 5.4 - How is text stored?
*   **ASCII Codes:** The uppercase 'A' is 65, and lowercase 'a' is 97.
*   **Why encoding is needed:** Computers only understand numbers (0s and 1s), so we need a standard encoding system to map numbers to the human letters they represent.
*   **Non-ASCII character:** The ₹ (Rupee) symbol or emojis like 😀.

## 3. Commands / tools used
*   **Python 3**: Used the interactive shell to test `bin()`, `hex()`, and `int()` functions.
*   **VS Code & Git**: For coding the converter and saving the work.

## 4. My understanding
Computers process everything as binary under the hood. Decimal is what humans use (base 10), binary is what hardware uses (base 2), and hexadecimal (base 16) is just a much shorter way for programmers to write out long binary numbers. Text encoding like ASCII just acts as a translation dictionary between those numbers and letters.

## 5. Difficulties faced
None really, the conversions were straightforward once I remembered the formulas.

## 6. How I resolved them
N/A.

## 7. Evidence / files
*   `mission-05-numbers-data/README.md` (this file)
*   `mission-05-numbers-data/number_converter.py` (the working script)

## 8. Commit details
Commit message used: "Build number converter and practise data representation". Pushed to GitHub.