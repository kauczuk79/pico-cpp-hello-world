# Install

```
apt install cmake gcc-arm-none-eabi build-essential
cmake .
```

# Build

```
rm ./*.bin ./*.dis ./*.elf* ./*.hex ./*.uf2
make hello_world
```