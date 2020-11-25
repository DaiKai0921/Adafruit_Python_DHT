#!/usr/bin/python3
import time
import Adafruit_DHT
GPIO_PIN = 4
while True:
	h0,t0 = Adafruit_DHT.read_retry(Adafruit_DHT.DHT11,GPIO_PIN)
	if h0 is not None and t0 is not None:
		print('Temp={0:0.1f}* Humidity={1:0.1f}%'.format(t0,h0))
	else:
		print('Failed to get reading. Try again!')
		sys.exit(1)
