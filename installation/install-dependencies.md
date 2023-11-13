# Install Dependencies

Please install the dependencies required for compiling the analytical network simulator.

:::{warning}
As of now, the analytical network simulator does not support Windows. For Windows machines, we recommend using [Windows Subsystem for Linux (WSL)](https://learn.microsoft.com/en-us/windows/wsl/install).
:::

## macOS
You can install dependencies through Homebrew.

:::{tip}
If your machine doesn't have Homebrew installed, you can install it by following [this documentation](https://brew.sh).
:::

:::{code-block} console
$ brew update
$ brew upgrade
$ brew install cmake
:::

## Debian-based Linux

For Debian-based Linux distributions (including Ubuntu), you can install dependencies through apt.

:::{code-block} console
$ sudo apt update
$ sudo apt upgrade
$ sudo apt install cmake
:::
