import board
import digitalio

button = digitalio.DigitalInOut(board.GP16)
button.direction = digitalio.Direction.INPUT
button.pull = digitalio.Pull.UP

motor = digitalio.DigitalInOut(board.GP15)
motor.direction = digitalio.Direction.OUTPUT

led = digitalio.DigitalInOut(board.LED)
led.direction = digitalio.Direction.OUTPUT

while True:
    led.value = True
