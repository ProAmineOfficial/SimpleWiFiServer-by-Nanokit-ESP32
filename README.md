# WiFi Web Server LED Blink for NanoKit ESP32 [Pro_Amine IC]

This project is a simple web server implemented on the NanoKit ESP32 [Pro_Amine IC] development board using the Arduino framework. It allows you to control an LED connected to pin 33 via a web interface.

## Features

- Connects to a WiFi network
- Hosts a simple web server that can control an LED
- HTTP commands to turn the LED on and off

## Requirements

- NanoKit ESP32 [Pro_Amine IC] board
- PlatformIO
- A WiFi network

## Setup

1. Clone the repository to your local machine.
2. Open the project folder in Visual Studio Code with the PlatformIO extension installed.
3. Modify the `ssid` and `password` variables in `src/main.cpp` with your WiFi credentials.
4. Upload the project to your NanoKit ESP32 board using PlatformIO.

## Usage

1. After uploading the code, open the Serial Monitor in PlatformIO.
2. The IP address of the ESP32 will be printed on the Serial Monitor.
3. Open a web browser and navigate to `http://<Your_IP_Address>/H` to turn the LED on and `http://<Your_IP_Address>/L` to turn it off.

## Additional Resources

For more information, visit [Pro Amine Tech](https://proamine.tech/).

## License

This project is licensed under the MIT License - see the LICENSE file for details.


 This project demonstrates how to create a web server on an ESP32 development board that allows users to control an LED connected to GPIO pin 33. The project is set up using PlatformIO with the Arduino framework. Once connected to a WiFi network, the ESP32 hosts a web page that lets users turn the LED on and off by navigating to specific URLs.

Key Features:

Simple web server implementation.
Control an LED via HTTP requests.
Compatible with the NanoKit ESP32 [Pro_Amine IC] board.
This repository is perfect for beginners looking to explore IoT projects with ESP32 and PlatformIO. 
