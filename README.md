# Airsim Multi Drone Control With Keyboard

## Setup your airsim environment
```
{
    "SettingsVersion": 1.2,
    "SimMode": "Multirotor",

    "Vehicles": {
        "Drone1": {
          "VehicleType": "SimpleFlight",
          "X": 4, "Y": 0, "Z": -2,
      "Yaw": -180
        },
        "Drone2": {
          "VehicleType": "SimpleFlight",
          "X": 8, "Y": 0, "Z": -2
        }

    }
}
```

## Run Code in Multi Terminal

### Drone 1 Run

Control  w,a,s,d <br/>
W = + x-axis
S = - x-axis
D = + y-axis
A = - y-axis

```
python control.py
```

### Drone 2 Run
Control ı,k,j,l
```
python control2.py
```

![dronesphoto1](https://github.com/mkaraaslan-dev/airsim-multi-drone-control/blob/main/images/2021-05-16%2003-17-24.gif)
![dronesphoto2](https://github.com/mkaraaslan-dev/airsim-multi-drone-control/blob/main/images/2021-05-16%2003-15-38.gif)

