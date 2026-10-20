# LoRa_voicecomm-esp32
Long-range voice transmission on ESP32 using LoRa and PCM.

# LoRa Wireless Voice Communication on ESP32

Real-time voice transmission over LoRa using PCM encoding.

## What it does
This project presents the design and implementation of a digital voice communication system using ESP32 microcontrollers and LoRa (SX1278) modules. The system transmits real-time voice data wirelessly using Pulse Code Modulation (PCM). The transmitter captures analog voice through a MAX4466 microphone preamplifier, converts it into digital samples using ESP32’s Analog-to-Digital Converter (ADC), and transmits the data packets via the LoRa transceiver at 433 MHz. The receiver ESP32 reconstructs the signal using its Digital-to-Analog Converter (DAC), amplifies it using an LM386 amplifier, and plays it through a speaker. The setup successfully demonstrates long-range, low-power, and low-cost voice transmission, establishing a foundation for remote communication devices such as digital walkie-talkies and IoT voice nodes.

## Key details
- Microcontroller: ESP32
- Radio: LoRa 
- Audio: sampling rate : 433 Mhz
- Range tested: 10 m

## How it works
<img width="825" height="368" alt="image" src="https://github.com/user-attachments/assets/c87e102b-fd39-410f-9a67-71437503bd9c" />


## Results
<img width="1180" height="720" alt="image" src="https://github.com/user-attachments/assets/2c51fb4e-579f-4783-a750-2b08c1306e5e" />
<img width="987" height="756" alt="image" src="https://github.com/user-attachments/assets/a08c686c-6a54-47ab-8ee8-9460c6457d23" />


