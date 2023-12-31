# ESP8266 BenQ Projektorsteuerung

![alt text](https://github.com/OperationJosef/smart-benq-projector-control/blob/main/Benq-Remote-mounted.png)

Dieses Projekt ermöglicht die einfache Steuerung eines BenQ-Projektors über einen ESP8266-Mikrocontroller und die Integration in dein Home Automation-System.

## Funktionen

- Ein- und Ausschalten des Projektors
- Abfrage des Projektorstatus
- Integration in Home Assistant

## Voraussetzungen

- ESP8266-Board (z.B. NodeMCU)
- RS232 TTL Adapter + Kabel - MAX3232 3V-5V Serial Port Converter Modul Female DB9
- BenQ-Projektor (in meinem fall W2700 oder HT3550)  mit serieller Schnittstelle

## Installation

1. Klone dieses Repository auf deinen Computer.
2. Passe die `benq-remote.yaml`-Datei an deine Konfiguration an.
3. Lade die ESPHome-Firmware auf deinen ESP8266-Mikrocontroller hoch.
4. Lade die uart_read_line_sensor.h Datei in folgendes Verzeichniss " /config/esphome " (Falls du HomeAssistant nutzt) 

## Konfiguration

In der `benq-remote.yaml`-Datei findest du Einstellungen, um die UART-Kommunikation mit deinem Projektor anzupassen. Passe sie an deine Projektoranforderungen an.

## Verwendung

1. Schalte deinen ESP8266-Mikrocontroller ein.
2. Verbinde dich mit dem ESPHome-Webinterface, um den Projektor zu steuern.
3. Integriere den Projektor in dein Home Assistant-System, um ihn von dort aus zu steuern.

## Beitrag

Wir begrüßen Fehlerberichte und Verbesserungsvorschläge. Wenn du zu diesem Projekt beitragen möchtest, erstelle einfach eine Issue oder einen Pull Request.

---

**Autor:** OperationJosef

__________________________________________________________________________________________________________________________________________________________________________________________________________

# ESP8266 BenQ Projector Control

This project enables easy control of a BenQ projector using an ESP8266 microcontroller and integration into your home automation system.

## Features

- Turn the projector on and off
- Query the projector status
- integration with Home Assistant

## Requirements

- ESP8266 board (e.g., NodeMCU)
- RS232 TTL Adapter + Kabel - MAX3232 3V-5V Serial Port Converter Modul Female DB9
- BenQ projector (in my case W2700 or HT3550) with a serial interface

## Installation

1. Clone this repository to your computer.
2. Customize the `benq-remote.yaml` file to match your configuration.
3. Upload the ESPHome firmware to your ESP8266 microcontroller.
4. Load the uart_read_line_sensor.h file into the following directory " /config/esphome " (if you use HomeAssistant)

## Configuration

In the `benq-remote.yaml` file, you will find settings to customize UART communication with your projector. Adjust them to fit your projector requirements.

## Usage

1. Power on your ESP8266 microcontroller.
2. Connect to the ESPHome web interface to control the projector.
3. Integrate the projector into your Home Assistant system for control from there.

## Contribution

We welcome bug reports and suggestions for improvement. If you'd like to contribute to this project, simply create an issue or a pull request.


---

**Autor:** OperationJosef

![alt text](https://github.com/OperationJosef/smart-benq-projector-control/blob/main/Benq-Remote-Overview%202.png)
![alt text](https://github.com/OperationJosef/smart-benq-projector-control/blob/main/Benq-Remote-Overview%201.png)
![alt text](https://github.com/OperationJosef/smart-benq-projector-control/blob/main/Benq-Remote-mounted.png)
