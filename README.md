# Andrea Valentino

Software engineer in Rome. Here I build small systems from scratch: a CPU, a
kernel, a compiler, a database, a browser and a language.

## Focus

- Low-level software: a CPU, plus a kernel and a compiler that run on it
- Testing against a reference model, so two implementations must agree line by line
- Control and embedded software, from my M.Sc. and university projects
- Computer vision models running in production

## Background

- Software Engineer at Leonardo S.p.A., Air Traffic Monitoring Division (C++ and Python)
- Co-founder and software engineer at AgriAI, a startup for plant disease diagnosis
- M.Sc. and B.Sc. in Automation and Control Engineering, Politecnico di Milano

## Featured work

| Project | What I built |
|---|---|
| [flint](https://github.com/andval07/flint) | A 5-stage pipelined RISC-V CPU (RV32I + Zicsr) in Verilog, checked against a Python ISS on every retired instruction. CPI 1.22 on recursive fib, 19.8 MHz on an iCE40 UP5K. |
| [moss](https://github.com/andval07/moss) | A preemptive kernel in C for flint: up to 8 user processes, system calls and a RAM filesystem in a 13.6 KB image. A `yield` with a context switch takes 280 cycles. |
| [ember](https://github.com/andval07/ember) | A C subset compiler to RV32I in pure Python, with an optimizer and a linear-scan register allocator. At -O1 the sieve needs 37% of the -O0 instructions. |
| [acorn](https://github.com/andval07/acorn) | A key-value store in Go with a B+tree and a write-ahead log. Crash tests cut the log at 262 points and kill the process while it commits; 86% coverage. |
| [wren](https://github.com/andval07/wren) | A toy web browser with only the Python standard library: my own HTTP client, HTML and CSS parsers, layout and a tkinter window. 84 tests, all offline. |
| [kite](https://github.com/andval07/kite) | A small language with two engines, a tree-walking interpreter and a bytecode VM, that must give the same output. The VM is 2.2x faster on fib(25); 128 tests. |

## Toolkit

- **Languages:** C, C++, Python, Go, Verilog, C#, MATLAB
- **Hardware and embedded:** RISC-V, Icarus Verilog, Yosys, nextpnr, iCE40 FPGA, STM32, ROS2, Simulink
- **ML:** PyTorch, YOLO, OpenCV, ONNX, TensorRT
- **Tools:** Git, Docker, FastAPI, SQL, pytest, clang (zig cc)

## Contact

- Email: andreavalen1@gmail.com
- LinkedIn: [andrea-valentino-b94a30220](https://www.linkedin.com/in/andrea-valentino-b94a30220)
