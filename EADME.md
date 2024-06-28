# Rust Shellcode-Injector

This project is a collection of various methods for injecting shellcode, implemented in Rust and utilizing native Windows system calls. The aim is to provide a comprehensive toolkit for understanding and demonstrating the mechanics of shellcode injection in a safe and educational context. The injector performs key steps: identifying the target process, allocating memory within the target process, writing the shellcode into this memory, and finally executing the shellcode within the context of the target process. By leveraging Rust and native Windows API, this project ensures both safety and performance, making it a valuable resource for learning and experimentation.

Disclaimer: This tool is intended for educational purposes only. Unauthorized use against systems without permission is illegal and unethical.

## Usage

Clone the Repository and let cargo get the dependencies
```Powershell
PS > cargo build
```

Cargo will compile the binary and will store in in the directory `.\target\debug\` relative to your repository root 
To execute it, run the following comand
```Powershell
PS > .\target\debug\shellcode_injector.exe
```
