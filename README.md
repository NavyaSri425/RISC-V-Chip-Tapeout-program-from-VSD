# 🖥️ RISC-V Reference SoC Tapeout Program VSD (VLSI System Design)
# Week 0 - Setup and Tools Installation
## **System Requirements 🌐**
 - 6GB RAM
 - 50 GB HDD
 - Ubuntu 20.04+
 - 4vCPU
# 🛠️ Tools Check ⚙️

## Yosys 
```bash
$ sudo apt-get update
$ git clone https://github.com/YosysHQ/yosys.git
$ cd yosys
$ sudo apt install make (If make is not installed please install it)
$ sudo apt-get install build-essential clang bison flex \
 libreadline-dev gawk tcl-dev libffi-dev git \
 graphviz xdot pkg-config python3 libboost-system-dev \
 libboost-python-dev libboost-filesystem-dev zlib1g-dev
$ make config-gcc
$ make
$ sudo make install
```
![image alt](https://github.com/NavyaSri425/RISC-V-Chip-Tapeout-program-from-VSD/blob/1a08c948991aa07b78405415344432764e77c311/yosys%20installation.png)


## Iverilog
```bash
Steps to install iverilog
sudo apt-get update
sudo apt-get install iverilog
```
![image alt](https://github.com/NavyaSri425/RISC-V-Chip-Tapeout-program-from-VSD/blob/189c89f0f03383d27ef6df907d70178c9ca5b5e4/iverilog.png)


## Gtkwave 
```bash
Steps to install gtkwave
sudo apt-get update
sudo apt install gtkwave
```
![image alt](https://github.com/NavyaSri425/RISC-V-Chip-Tapeout-program-from-VSD/blob/189c89f0f03383d27ef6df907d70178c9ca5b5e4/Gtkwave.png)


## Key Learning points 🎯
 - Installed open-source tools (i.e. yosys,iverilog,gtkwave )
 - Learned about basic **environment setup** for RTL design and synthesis.
 - Prepared the system for upcoming RTL → GDSII flow experiments.
