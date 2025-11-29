
# Exp 3 Experimental Verification of IV Characteristics of LED and LASER
# Fiber Optic LED Characteristics and Photo Detector Response

## 🎯 AIM
To study the IV characteristics of fiber optic LED and plot the graph of forward current v/s output optical energy and also to study the photo detector response.
---

## 🧰 EQUIPMENTS REQUIRED

	Link-B Kit with power supply.

	FCL-01 & FCL-02.

	Patch chords.

	20MHz Dual Channel Oscilloscope.

	1 MHz Function Generator.

	1 Meter Fiber Cable.

	Jumper to Crocodile wires.
 

---

## 📚 THEORY

In optical fiber communication system, electrical signal is first converted into optical signal with the help of E / O conversion device as LED. After this optical signal is transmitted through optical fiber, it is retrieved in its original electrical form with the help O / E conversion device as photo detector.


Different technologies employed in chip fabrication lead to significant variation in parameters for the various emitter diodes. All the emitters distinguish themselves in offering high output power coupled into the plastic fiber. Data sheets for LEDs usually specify electrical and optical characteristics, out of which are important peak wavelength of emission, conversion efficiency (usually specified in terms of power launched in optical fiber for specified forward current), optical rise and fall ties which put the limitation on operating frequency, maximum forward current through LED and typical forward voltage across LED.


Photodetectors usually comes in variety of forms like photoconductive, photovoltaic, transistor type output and diode type output. Here also characteristics to be taken into account are response time of the detector which puts the limitation on the operating frequency, wavelength sensitivity and responsively.
LED’s and LASER diodes are the commonly used sources in optical communication systems, whether the system transmits digital or analog signal. It is therefore, often necessary to use linear electrical to optical converter to allow its use in intensity modulation & high quality analog transmission systems.
LED's have a linear optical output with relation to the forward current over a certain region of operation. Numerical aperture refers to the maximum angle at the light incident on the fiber end is totally internally reflected and is transmitted properly along the Fiber. The cone formed by the rotations of this angle along the axis of the Fiber is the cone of acceptance of the Fiber. The light ray should strike the fiber end within its cone of acceptance; else it is refracted out of the fiber core.

---


## 🧪 PROCEDURE

	Refer to the block diagram and make the following connections.

	Keep all switch faults in OFF position.

	Slightly unscrew the cap of LED SFH756V (660nm). Do not remove the cap from the connector. Once the cap is loosened, insert the 1-meter fiber into the cap. Now tighten the cap by screwing it back.

	Slightly unscrew the cap of Photo Diode SFH250V. Do not remove the cap from the connector. Once the cap is loosened, insert the other end of fiber into the cap. Now tighten the cap by screwing it back.

	Keep the jumpers JP1 short for +12v, JP2 towards sine wave, JP3 short for +12 v & JP4 towards TX1on FCL-01.

	Keep switch SW2 in VI position on FCL-01.

	Connect voltmeter and current meter as per the polarities shown in the block diagram.

	Switch on the power supply.

	Keep the potentiometer P3 in its maximum position (anti-clockwise rotation). P3 is used to control current flowing through the LED.

	Keep the potentiometer P4 in its fully clockwise rotation.P4 is used to control bias voltage of the LED.

	To get the IV characteristics of LED, rotate P3 slowly and measure forward current and corresponding forward voltage. Take number of such readings for various current values and plot IV characteristics graph for the LED.

•	For each reading taken above, find out the power, which is product of I and V. This is the electrical power supplied to the LED. Data sheets for the LED specify optical power coupled into plastic fiber when forward current was 10 mA as 200 mW. This means that the electrical power at 10 mA current is converted into 200 mW of optical energy. Hence the efficiency of the LED comes out to be approx. 1.15%.

•	With this efficiency assumed, find out optical power coupled into plastic optical fiber for each of the reading. Plot the graph of forward current v/s output optical power of the LED.

•	Similarly measure the current at the detector.

•	Plot the graph of receiver current v/s output optical power of the LED.

•	Perform the above procedure again for all the combinations of Transmitter & Receiver.


---

## 🔌 CONNECTION DIAGRAM
<img width="1100" height="696" alt="image" src="https://github.com/user-attachments/assets/694a9b48-d625-4d30-b787-912151bc44db" />

---

## 📊 TABULATION

### LED Forward Characteristics
| **Forward Voltage Vf (V)** | **Forward Current If (mA)** |
| -------------------------- | --------------------------- |
| 1.5                        | 1.0                         |
| 1.6                        | 2.0                         |
| 1.7                        | 4.0                         |
| 1.8                        | 6.5                         |
| 1.9                        | 9.0                         |
| 2.0                        | 12.0                        |
| 2.1                        | 15.0                        |

---

## 📈 MODEL GRAPH
<img width="960" height="425" alt="image" src="https://github.com/user-attachments/assets/dd8326f5-a5d1-45ef-8bf6-db6da51560b8" />

---

## ✅ RESULT

<img width="510" height="610" alt="image" src="https://github.com/user-attachments/assets/7fd7700d-157c-49a7-97d6-2c9c1bc78b20" />

- The forward voltage and current characteristics of the fiber optic LED were successfully studied.
- The photo detector response was observed and analyzed.
