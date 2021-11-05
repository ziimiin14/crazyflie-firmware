# Crazyflie Firmware  [![CI](https://github.com/bitcraze/crazyflie-firmware/workflows/CI/badge.svg)](https://github.com/bitcraze/crazyflie-firmware/actions?query=workflow%3ACI)

This project contains the source code for the firmware used in the Crazyflie bolt for KRATOS monocopter application.
### Clone the repo
```
git clone https://github.com/ziimiin14/crazyflie-firmware.git
git checkout kratos-branch
```

Three main areas are being modified:

1) [power_distribution_stock.c](https://github.com/ziimiin14/crazyflie-firmware/blob/kratos-branch/src/modules/src/power_distribution_stock.c) 
2) [stabilizer.c](https://github.com/ziimiin14/crazyflie-firmware/blob/kratos-branch/src/modules/src/stabilizer.c)
3) [stabilizer_types.h](https://github.com/ziimiin14/crazyflie-firmware/blob/kratos-branch/src/modules/interface/stabilizer_types.h)

To check out what code lines are being modified/changed:
```
git diff ffc66a77414ca5355f579a0ab5facdaeea926e4a c5eb6aa2f5af1f0fc8ad4ecb21f4fd34f7cf8487
```

### Crazyflie 1.0 support

The 2017.06 release was the last release with Crazyflie 1.0 support. If you want
to play with the Crazyflie 1.0 and modify the code, please clone this repo and
branch off from the 2017.06 tag.

## Building and Flashing
See the [building and flashing instructions](https://www.bitcraze.io/documentation/repository/crazyflie-firmware/master/building-and-flashing/build/) in the github docs folder.

## Official Documentation

Check out the [Bitcraze crazyflie-firmware documentation](https://www.bitcraze.io/documentation/repository/crazyflie-firmware/master/) on our website.


## License

The code is licensed under LGPL-3.0