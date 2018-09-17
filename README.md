Simple Genesis 3-button to PC-Engine adapter
============================================

Tested on breadboard, test PCBs incoming

![PCB Front][pcb_front]

[pcb_front]: https://github.com/rattboi/gen-to-pce-controller-adapter/raw/master/images/3d-render.png "Front PCB"

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
|2   | Out  | Button C (I)      | Up                |
|3   | Out  | Button B (II)     | Right             |
|4   | Out  | Button A (Sel)    | Down              |
|5   | Out  | Start             | Left              |
|6   | In   | Select            | Select            |
|7   | In   | /Enable           | /Enable           |
|8   |      | Ground            | Ground            |

PC-Engine Extension Wiring
==========================

|Pin | Color |
|----|-------|
|1   | Brown |
|2   | Red   |
|3   | Orange|
|4   | Yellow|
|5   | Green |
|6   | Blue  |
|7   | Purple|
|8   | Black |
