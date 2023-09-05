# HDC Tools Zephyr Projects

This contains source code and a build system to develop HDC Tools Firmware
with the Zephyr RTOS.

## Quick start environment setup

### Run Setup Script

A bare git installation can be setup with the install script `setup_zephyr.py`.
This script will create a virtual environment, install west and other build
dependencies.

Run `python3 setup_zephyr.py`.

### Activate venv

Activate the virtual environment using the shortcut.

`source activate`

### Build example project to validate everything is working

Build an example project.

`west build -p always -b nucleo_g474re sdk/zephyr/samples/basic/blinky`
