# CM25-2430-Driver
Arduino motor driver for cheap CM25-2430 brushless dc motors from Aliexpress.


| Wire  | Function |
| ------------- | ------------- |
| Black  | Motor negative supply  |
| Red  | Motor positive supply (12V/24V)  |
| White  | Speed control, PWM signal 0-5 [V] (15-25 [KHz]) |
| Yellow  | Feedback, 12 ticks per revolution  |
| Orange  | Direction, 1-> CCW, 0->CW (internally pulled high)|
