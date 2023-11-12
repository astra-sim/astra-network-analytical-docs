# Compile Analytical Network Simulator

:::{warning}
If any of the below step fails, please make sure you have properly installed all required dependencies.
:::

## Overivew
You can compile analytical network simulator as a standalone binary through CMake.
:::{code-block} console
:lineno-start: 1
$ mkdir build
$ cd build
$ cmake ..
$ cmake --build . --config=Release -j$(nproc)
:::

## Additional Options

### Build in Debug Mode
You can pass `--config=Debug` in line 4 of the compilation to compile binary in a debug mode, which enables assertions and debugger usage.
:::{code-block} console
:lineno-start: 4
$ cmake --build . --config=Debug -j$(nproc)
:::

### Compilation Target
If you want to compile a specific analytical network simulator, you can pass `-DBUILDTARGET=<target>` option at line 3 when using CMake. Currently, target could be `congestion_unaware` or `congestion_aware`. Default option is `all`.
:::{code-block} console
:lineno-start: 3
$ cmake .. -DBUILDTARGET=congestion_unaware
:::
