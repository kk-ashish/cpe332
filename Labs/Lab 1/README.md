# Lab 1 - GHDL and GTKWave

## Half Adder Example

### Files:
- `ha.vhdl`: Half Adder VHDL design
- `ha_tb.vhdl`: Testbench for Half Adder

### Run Commands:

```bash
ghdl -a ha.vhdl
ghdl -a ha_tb.vhdl
ghdl -e ha_tb
ghdl -r ha_tb --vcd=ha.vcd
gtkwave ha.vcd
```

### GTKWave Output:

![Half Adder GTKWave](<Desktop Screenshot 2025.03.29 - 17.19.42.56.png>)

---

## 4-to-1 Multiplexer Example

### Files:
- `mux.vhdl`: 4-to-1 Multiplexer VHDL design
- `mux_tb.vhdl`: Testbench for Multiplexer

### Run Commands:

```bash
ghdl -a mux.vhdl
ghdl -a mux_tb.vhdl
ghdl -e mux_tb
ghdl -r mux_tb --vcd=mux.vcd
gtkwave mux.vcd
```

### GTKWave Output:

![4-to-1 MUX GTKWave](<Desktop Screenshot 2025.03.29 - 17.22.03.75.png>)
---
