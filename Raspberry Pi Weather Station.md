# **Raspberry Pi Weather Station**
it monitors temperature, pressure and humidity over internet.Firstly DHT11 sensor senses the Humidity & Temperature Data and BM180 sensor measures the atmospheric pressure. Secondly Raspberry Pi reads the DHT11 sensor module’s output by using single wire protocol and BM180 pressure sensor’s output by using I2C protocol and extracts both sensors values into a suitable number in percentage (humidity), Celsius scale (temperature), hectoPascal or millibar (pressure). Thirdly, these values are sent to ThingSpeak server by using inbuilt Wi-Fi of Raspberry Pi 3. And finally ThingSpeak analyses the data and shows it in a Graph form. A LCD is also used to display these values locally.

###### ***BM180 sensor***
its a low-cost sensing solution for measuring barometric pressure. The sensor is soldered onto a PCB with a 3.3V regulator, I2C level shifter and pull-up resistors on the I2C pins.

###### ***difference in I2C and 1-wire protocol***
I2C protocol: Shorter distance,Much faster, Multi-master. I2C devices will have 4 wires (GND & power plus SCK clock & SDA data). 1-wire protocol: Longer distance, Slower, Strictly master-slave. it can get by with only 2 (data and GND) if the devices are powered in parasitic mode, meaning they draw power from the data line; alternatively they need GND, power and data.
