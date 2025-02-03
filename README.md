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
```
python control.py
```

### Drone 2 Run

```
python control2.py
```

