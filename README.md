## About This Repository
A lightweight, modular command-line calculator written in modern C++17, built to demonstrate secure software engineering principles, automated supply-chain security monitoring, and open-source best practices.

## Key Features
- **Clean Architecture:** Separates core arithmetic logic (`calculator.h` / `calculator.cpp`) from the execution interface (`main.cpp`).
- **Robust Error Handling:** Includes exception safety checks (such as handling division-by-zero errors gracefully).
- **Standardized Build System:** Configured with `CMake` for cross-platform compilation and ease of setup.
- **Security & Compliance:** Features automated supply-chain monitoring via OpenSSF Scorecard and adheres to open-source governance standards.

## Building and Running
To compile and run the project locally using CMake:
```bash
mkdir build
cd build
cmake ..
make
./cpp_calculator
