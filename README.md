# dronekit-python-solo

[![Windows Build status](https://img.shields.io/appveyor/ci/3drobotics/dronekit-sitl.svg?label=windows)](https://ci.appveyor.com/project/3drobotics/dronekit-sitl/branch/master) [![OS X Build Status](https://img.shields.io/travis/dronekit/dronekit-sitl.svg?label=os%20x)](https://travis-ci.org/dronekit/dronekit-sitl) [![Linux Build Status](https://img.shields.io/circleci/project/dronekit/dronekit-sitl.svg?label=linux)](https://circleci.com/gh/dronekit/dronekit-sitl)

Solo-specific DroneKit functions.


## Installing

Install from Github:

```
pip2 install dronekit-solo -UI
```


## API

```
from dronekit import connect
from dronekit_solo import SoloVehicle

vehicle = connect('127.0.0.1:14550', vehicle_class=SoloVehicle)
print vehicle.gopro_status
```

## License

dronekit-solo is licensed as MIT/Apache-2.0
