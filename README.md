cat > README.md <<EOF
# cpp-template

A modern C++ project starter using CMake.

## Features

- Cross-platform C++17+ build system
- Organized `src/` and `include/` layout
- Local dependency management via `add_subdirectory`
- clangd support via compile_commands.json

## Getting Started

```bash
git clone --recurse-submodules https://github.com/youruser/cpp-template.git
cd cpp-template
mkdir build && cd build
cmake ..
make
./cpp-template
