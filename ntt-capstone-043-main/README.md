# Hack Computer Architecture

**Nand to Tetris – I · ETCCNT301**

A hands-on implementation of the Hack computer architecture using HDL, Hack assembly, and Python.

## Student details

| Field | Details |
|---|---|
| Name | Aryan Kumar |
| Roll number | 2501010043 |
| Personal number | K = 43 |
| Course | Nand to Tetris – I (ETCCNT301) |
| University | K.R. Mangalam University |

## Personalized specifications

| Calculation | Result |
|---|---|
| K mod 3 | 1 — line-numbered assembler error messages |
| K mod 4 | 3 |
| Rectangle width | 64 pixels |
| Rectangle height | 20 rows |
| Starting row | 43 |
| Starting screen address | 17760 |
| Words per row | 4 |

The starting address is calculated as `16384 + (32 × 43) = 17760`. The program writes four 16-bit words per row, then advances by 28 words to the next screen row.

## Project files

- `CPU.hdl`, `Memory.hdl`, `Computer.hdl` — Hack hardware implementation
- `assembler.py`, `test_assembler.py` — two-pass assembler and unit tests
- `Box.asm`, `Box.hack` — personalized keyboard-controlled rectangle
- Official Nand2Tetris test scripts and comparison files
- `REPORT-TEMPLATE.md` — project report template

## Quick start

```bash
python assembler.py Box.asm
python -m unittest -v test_assembler.py
```

Open the project in the Nand2Tetris Hardware Simulator to run the supplied hardware tests. Load `Box.hack` in the CPU Emulator to test the keyboard-controlled rectangle.

## Verification

Hardware Simulator runs, unit-test results, official assembler comparisons, and CPU Emulator screenshots should be completed locally and recorded with genuine results. Do not mark simulator tests as passed until they have actually been run.

**K.R. Mangalam University**  
*School of Engineering & Technology*
