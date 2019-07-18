# DMAPythonPi-top2
from gpiozero import LED
from time import sleep
t_flag = True
led_1 = LED(4)
led_2 = LED(17)
led_3 = LED(27)

while True:
    led_1.on()
    sleep(5)
    led_1.off()
    sleep(0)
    led_2.on()
    sleep(5)
    led_2.off()
    sleep(0)
    led_3.on()
    sleep(8)
    led_3.off()
