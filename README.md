# ROCK 4SE PWM Fan

Public Home Assistant app repository for a temperature-controlled PWM fan
controller for the Radxa ROCK 4 SE.

## Installation

1. Open Home Assistant.
2. Go to Settings → Apps → App store.
3. Open Repositories.
4. Add:

   https://github.com/josefseger/rock4se-pwm-fan

5. Reload the app store.
6. Install ROCK 4SE PWM Fan.
7. Configure MQTT before starting it.

## Supported hardware

- Radxa ROCK 4 SE
- Rockchip RK3399
- AArch64 Home Assistant OS

## Binary status

The current release contains the recovered and verified AArch64 executable
from the working version 1.1.1 installation.

Binary SHA-256:

1253f8c498f8450fb3fc2a66039147a1988feff9d4c957bca3f5a6538ef9eb41

## Warning

The app accesses RK3399 PWM registers through `/dev/mem`. It must not be used
on unrelated hardware.
