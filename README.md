# HighTemperatureDetector

# Materials:

- Temperature Sensor: Measures the temperature.
- LED: Light-emitting diode to indicate temperature.
- Resistor: Used to limit the current to the LED.
- Power Supply: Provides voltage for the circuit.
-  Microcontroller (Arduino): Used for processing the sensor data and controlling the LED.


  # How It Works:

# Temperature Sensor (DS18B20):

- The DS18B20 outputs a digital signal, and it does not require an analog-to-digital converter (ADC) to interface with a microcontroller or other digital systems.
  
- The temperature sensor continuously measures the temperature of the environment or system it's monitoring.
  
- It can measure temperatures from -55°C to +125°C (−67°F to +257°F), with an accuracy of ±0.5°C in the range of -10°C to +85°C.
  
- The temperature sensor measures the ambient temperature and provides an output voltage proportional to the temperature.
  

# Arduino:

- The analog signal from the temperature sensor is read by the Arduino's analog-to-digital converter (ADC).
  
- The microcontroller processes this signal and converts it into a temperature value.

# LED:

- Based on the processed temperature, the microcontroller can turn the LED on/off or adjust its brightness.
  
- The LED is meant to turn on when a  when the temperature exceeds 30 degree Celcius, the microcontroller will switch the LED on.
  
- The LED is connected in series with a current-limiting resistor to prevent it from burning out. The value of the resistor is typically calculated based on the LED's forward voltage and the supply voltage.
  
- The cathode (long leg) of the LED to ground
  
- The anode (long leg) of the LED to a digital output pin

![IMG_6938](https://github.com/user-attachments/assets/18f7538e-1a42-4714-a0db-c819668fe03d)

![IMG_6940](https://github.com/user-attachments/assets/17328589-a98c-40cc-b893-0f812111faf6)
