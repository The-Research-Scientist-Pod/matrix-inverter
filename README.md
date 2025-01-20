# Matrix Inverter

A C++ application for matrix inversion with an interactive GUI. This tool provides an intuitive interface for defining matrix elements and computing their inverses using multiple methods.

## Features

- Interactive GUI for matrix input and visualization
- Support for matrices up to 10x10
- Multiple inversion methods (Gauss-Jordan elimination, LU decomposition)
- Real-time computation and display
- Error handling for singular matrices
- Save/Load matrix configurations

## Building from Source

### Prerequisites

- C++17 compatible compiler
- CMake 3.15 or higher
- Qt 6.2 or higher
- Catch2 (for testing)

### Build Instructions

#### Linux/macOS
```bash
mkdir build
cd build
cmake ..
make
```

#### Windows
```bash
mkdir build
cd build
cmake ..
cmake --build . --config Release
```

## Project Structure

- `src/core/` - Core matrix operations implementation
- `src/gui/` - Qt-based user interface
- `tests/` - Unit tests and test utilities
- `examples/` - Example usage and demonstrations
- `docs/` - Documentation and user guide

## Testing

To run the tests:
```bash
cd build
ctest
```

## Contributing

Contributions are welcome! Please read our [Contributing Guidelines](CONTRIBUTING.md) before submitting pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Authors

- Suf Shehu - Initial work
