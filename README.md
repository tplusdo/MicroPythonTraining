# A first-level heading
## A second-level heading
### ESP32 MicroPython project 1 - "Hello World"
Printing a text is the "Hello World" equivalent program. 

In this exercise, you instruct an ESP32 to send a custom message using MicroPython programming. 
You will send "Hello World"
You will send "Hello, ESP32"
```python
print("Hello, ESP32!")
```

```python
import time
from machine import Pin

led=Pin(2,Pin.OUT)

while True:
  led.value(1)
  time.sleep(0.5)
  led.value(0)
  time.sleep(0.5)
```
