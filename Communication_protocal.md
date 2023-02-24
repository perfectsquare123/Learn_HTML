# Commmunication Protocal

### Format

[Key][motor direction][num_1][num_2][num_3]

```c
char aRxBuffer[5];

```

### Key

| Key |   Meaning   |
| --- | :---------: |
| S   |  Straight   |
| R   |    Right    |
| L   |    Left     |
| J   | Slide Right |
| K   | Slide Left  |

### Direction

| Dir | Meaning  |
| --- | :------: |
| F   | Forward  |
| B   | Backward |

### Magnitude

| Mag    | Meaning  |
| ------ | :------: |
| XXX    | Distance |
| \_\_\_ |  Angle   |
