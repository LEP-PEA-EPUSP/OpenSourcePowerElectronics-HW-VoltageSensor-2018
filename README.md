# Open Source Power Electronics - Hardware - Voltage Sensor Board- 2018

### Overview

This repository contains a isolated voltage acquisition and signal conditioning board. It is based on four separated LEM LV25 Hall effect sensor. Each one features its own operational amplifier for post-processing.

### Functionality

It features four voltage inputs with a -60V to 60V range. After conditioning, each output is in a 0 to 3V3 range, suitable for most embedded A/D converters.

### Description

The 100R burden resistor is connected to the current source output of the voltage sensor. A non-inverting buffer is connected to this node. A inverting adder for offset adjustment and a non-inverting amplifier follows next in the circuit. All stages are equipped with a low-pass filter to avoid aliasing problems. Additionally, 10K load resistors are added to each stage in order to minimize EMI effects. The output is clamped with two fast diodes for overvoltage protection.

### Licensing

Please refer to LEP-PEA-EPUSP homepage.
