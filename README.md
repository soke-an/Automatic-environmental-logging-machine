import time
import board
import busio
import adafruit_ads1x15.ads1115 as ADS
from adafruit_ads1x15.analog_in import Analog
import adafruit_sht31d
import mysql.connector

mydb=mysql.connector.connect
