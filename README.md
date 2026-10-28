# Hi, I'm Andrea

I'm a software engineer in Rome. I studied control engineering at Politecnico
di Milano, and now I write C++ and Python at Leonardo, on an air traffic
monitoring system. I'm also a co-founder of AgriAI, a small startup that finds
plant diseases from field and drone photos.

Here I keep side projects where I build a small version of a real system from
scratch. Most of them are tested against a second implementation: the CPU
against a Python simulator, the two kite engines against each other.

## Projects

| Project | What I built |
|---|---|
| [flint](https://github.com/andval07/flint) | A RISC-V CPU in Verilog with a 5-stage pipeline. Every instruction it retires is compared with a Python simulator. It runs at 19.8 MHz on an iCE40 FPGA. |
| [moss](https://github.com/andval07/moss) | A small kernel for flint, about 960 lines of C and assembly. A `yield` to another process takes 280 cycles. |
| [ember](https://github.com/andval07/ember) | A compiler for a subset of C, written in Python. The code it makes runs on flint. With -O1 the sieve program needs 37% of the instructions it needs at -O0. |
| [acorn](https://github.com/andval07/acorn) | A key-value store in Go, with a B+tree and a write-ahead log. I tested crash recovery by cutting the log at 262 points and by killing the process during commits. |
| [wren](https://github.com/andval07/wren) | A toy web browser with only the Python standard library, HTTP client included. It shows example.com fine and Wikipedia more or less. |
| [kite](https://github.com/andval07/kite) | A small language with two engines, a tree-walking interpreter and a bytecode VM. The VM is 2.2x faster on fib(25). |

## Tools

The code here is Python, C, Go and Verilog. At work I use C++ and Python. From
university I also know MATLAB/Simulink, ROS2 and C++ on STM32, and on the ML
side PyTorch, YOLO, ONNX and TensorRT.

## Contact

Write me at andreavalen1@gmail.com or find me on
[LinkedIn](https://www.linkedin.com/in/andrea-valentino-b94a30220).
