# BombDefusalGame
This was our endsem project for the course of PIS where we created a 2 player game where people collaborate under a time trial to defuse a bomb , where one person cannot look at the bomb and the other person cannot look at the defusing manual

## Project Overview

`DIS_FIN_PROJ` is an Arduino-based project that logs real-time clock (RTC) data to an SD card. This project demonstrates how to interface an Arduino with an RTC module to record timestamped data.

## Features

- Real-Time Clock (RTC) integration.
- SD card logging.
- Displays and stores date and time data.

## Hardware Requirements

- Arduino board (e.g., Uno, Mega).
- RTC module (e.g., DS3231).
- SD card module.
- SD card.
- Connecting wires.

## Software Requirements

- Arduino IDE.
- Required libraries:
  - `SPI`
  - `SD`
  - `Wire`
  - `RTClib`

## Setup

1. **Hardware Setup**:
   - Connect the RTC module to the Arduino.
   - Connect the SD card module to the Arduino.
   - Ensure that the SD card is properly formatted and inserted into the module.

2. **Software Setup**:
   - Clone this repository.
   - Open `DIS_FIN_PROJ.ino` in the Arduino IDE.
   - Install the required libraries via the Arduino Library Manager.

3. **Upload the Code**:
   - Connect your Arduino to the computer.
   - Select the appropriate board and port from the Arduino IDE.
   - Upload the sketch to the Arduino.

## Usage

Once the setup is complete:
- The Arduino will log the current date and time to the SD card every second.
- The logged data can be found in a file named `datalog.txt` on the SD card.

## Troubleshooting

- **Initialization failed**: Ensure the SD card is properly connected and formatted.
- **RTC lost power**: Check the RTC module’s battery.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributions

Contributions are welcome. Please open an issue or submit a pull request.

## Acknowledgments

- Arduino community and library authors.

## Contact

For any inquiries, please contact [Your Name] at [your-email@example.com].
