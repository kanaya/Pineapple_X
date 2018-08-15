# Pineapple X

## Descirption

Pineapple X is a universal MIDI/DMX512A computer. The default program of Pinapple X converts MIDI signal to DMX512A signal in real time.

## Overview

Velocity data of MIDI Turn On of channel 0 note 60 is convreted to brightness data of DMX512A slot 0.

| MIDI Note Number | DMX512A Slot | Control |
|------------------|--------------|---------|
| 60               | 0            | A0      |
| 61               | 1            | A1      |
| 62               | 2            | A2      |
| 63               | 3            | A3      |
| 64               | 4            | A4      |
| 65               | 5            | A5      |
| 66               | 6            | B0      |
| 67               | 7            | B1      |
| 68               | 8            | B2      |
| 69               | 9            | B3      |
| 70               | 10           | B4      |
| 71               | 11           | B5      |


## MPU Pinout

| LPC1760 |Function  | Connection       |
|---------|----------|------------------|
| p5      | MOSI1    | LCD              |
| p6      | MISO1    | ---              |
| p7      | SCK1     | LCD              |
| p8      |          | Take-over SW     |
| p9      | TX1/SDA1 | MIDI OUT         |
| p10     | RX1/SCL1 | MIDI IN          |
| p11     | MOSI2    |                  |
| p12     | MISO2    |                  |
| p13     | TX2/SCK2 | DMX OUT          |
| p14     | RX2      | DMX IN           |
| p15     | Analog   | Control          |
| p16     | Analog   | Control          |
| p17     | Analog   | Control          |
| p18     | Analog   | Control          |
| p19     | Analog   | Control          |
| p20     | Analog   | Control          |
| P21     | PWM      | Indicator        |
| p22     | PWM      | Indicator        |
| p23     | PWM      | Indicator        |
| p24     | PWM      | Indicator        |
| p25     | PWM      | Indicator        |
| p26     | PWM      | Indicator        |
| p27     | RX3/SCL2 | BT               |
| p28     | TX3/SDA2 | BT               |
| p29     | TD       | Bank selector SW |
| p30     | RD       | Bank selector    |
|         | D+       | USB              |
|         | D-       | USB              |
|         | TD+      |                  |
|         | TD-      |                  |
|         | RD+      |                  |
|         | RD-      |                  |
