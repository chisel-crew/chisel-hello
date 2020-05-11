# Welcome to Chisel Hardware Construction Language Demo !

[Chisel](https://www.chisel-lang.org/) is the next generation Hardware Construction Languge Embedded in [Scala](https://www.scala-lang.org/)

This project aims to run simulation and synthesis on a basic hardware component, implemented in [Chisel](https://www.chisel-lang.org/)

This will serve as a setup example for other projects and will help newcomers to evaluate `Chisel` as the next project design language


## Prerequesties 

1. This tutorial was tested for `Ubuntu 18.10` and does not guarantee seamless operation on other OS

2. Know the complexity <br>
`Chisel` requires a basic understanding and experience with both `Scala` and hardware design and is NOT suitable as the first introduction project for students and inexperienced users

3. Digital design experience is required <br>
You should be comfortable with basic to intermediate concepts of Hardware Design and have a hands-on-experience with `Verilog`, working with waveforms and debugging digital designs

## Installation

1. Install Java 11
```bash
  sudo apt install openjdk-11-jre openjdk-11-jdk
```
2. Install a Scala Build Tool (sbt) from [here](https://www.scala-sbt.org/1.x/docs/Installing-sbt-on-Linux.html) 

3. Install Verilator and GTKWave 
```bash
  sudo apt install build-essential verilator gtkwave
```

4. Optional - Install a `Visual Studio Code IDE` for a better code experience from [here](https://code.visualstudio.com/download)

## Starting up 

1. Clone a hello world project from Git: 
```bash
  git clone git@github.com:Neurodyne/chisel-hello.git
```
2. Run Chisel Tests with `sbt`. After running the `sim`, you can find `Verilog` and `VCD Dump` outputs in the `out` folder
```bash
  make sim
```

3. If you wish to get a `Verilog` representation only, you may run `emit`:
```bash
  make emit
```

4. View sim results with GTKWave [program](http://gtkwave.sourceforge.net/)
```bash
  make view
```

## Tech support 
1. Open issues in this repo
2. Visit `Chisel` and `FIRRTL` [website](https://www.chisel-lang.org/)
3. Join us on [Gitter](https://gitter.im/freechipsproject/chisel3)
