# Install Dependencies

Please install dependencies required for the compilation of the analytical network simulator.

:::{warning}
Analytical network simulator doesn't support Windows as of now. For Windows machines, we recommend to use [Windows Subsystem for Linux (WSL)](https://learn.microsoft.com/en-us/windows/wsl/install).
:::

## macOS
You can install dependencies through `homebrew`.

:::{tip}
If your machine doesn't have homebrew installed, you can have it installed by following [this documentation](https://brew.sh).
:::

:::{code-block} console
$ brew update
$ brew upgrade
$ brew install cmake
:::

## Debian-based Linux
For Debian-based Linux distributions (including Ubuntu), you can install dependencies through `apt`.

:::{code-block} console
$ sudo apt update
$ sudo apt upgrade
$ sudo apt install cmake
:::
