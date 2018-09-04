Simple Genesis 3-button to PC-Engine adapter
============================================

Untested, schematic-only so far

Genesis Controller
==================

|Pin | Type | Name (Select=GND) | Name (Select=+5V) |
|----|------|-------------------|-------------------|
|1   | Out  | Up                | Up                |
|2   | Out  | Down              | Down              |
|3   | Out  | Gnd               | Left              |
|4   | Out  | Gnd               | Right             |
|5   |      | +5VDC             | +5VDC             |
|6   | Out  | Button A          | Button B          |
|7   | In   | Select            | Select            |
|8   |      | Ground            | Ground            |
|9   | Out  | Start             | Button C          |


PC-Engine Controller
====================

|Pin | Type | Name (Select=GND) | Name (Select=+5V) |
|----|------|-------------------|-------------------|
|1   |      | +5VDC             | +5VDC             |
|2   | Out  | Button B (I)      | Up                |
|3   | Out  | Button C (II)     | Right             |
|4   | Out  | Button A (Sel)    | Down              |
|5   | Out  | Start             | Left              |
|6   | In   | Select            | Select            |
|7   | In   | /Enable           | /Enable           |
|8   |      | Ground            | Ground            |
