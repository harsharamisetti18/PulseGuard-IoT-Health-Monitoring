

\# PulseGuard - IoT-Based Heart Rate and Oxygen Monitoring System



\## Project Overview



PulseGuard is an embedded systems project designed to monitor health-related parameters using microcontroller-based hardware and communication interfaces.



The project source code includes modules for UART, LCD, I2C, SPI, RTC, timers, interrupts, keypad interfacing, and ESP-01 communication.



\## Objectives



\- Develop embedded C modules for peripheral interfacing.

\- Demonstrate serial communication using UART.

\- Interface LCD, keypad, RTC, and timer peripherals.

\- Explore I2C and SPI communication.

\- Support ESP-01-based communication functionality.



\## Technologies Used



\- \*\*Programming languages:\*\* C and ARM Assembly

\- \*\*Development environment:\*\* Keil µVision project (`.uvproj`)

\- \*\*Microcontroller platform:\*\* Confirm the exact controller from the project hardware and configuration

\- \*\*Communication interfaces:\*\* UART, I2C, SPI

\- \*\*Peripheral modules:\*\* LCD, keypad, RTC, timers, interrupts, and ESP-01



\## Repository Structure



```text

PulseGuard-IoT-Health-Monitoring/

├── README.md

├── .gitignore

└── majorproject\_test/

&#x20;   ├── majorproject\_test.uvproj

&#x20;   ├── main\_pg.c

&#x20;   ├── main\_test.c

&#x20;   ├── project\_pg.h

&#x20;   ├── all\_defines.h

&#x20;   ├── lcd.c

&#x20;   ├── uart0.c

&#x20;   ├── i2c.c

&#x20;   ├── spi.c

&#x20;   ├── rtc.c

&#x20;   ├── timer0.c

&#x20;   ├── Timer1.c

&#x20;   ├── kpm.c

&#x20;   ├── esp01.c

&#x20;   └── ...

```



\## Software Requirements



\- Keil µVision compatible with the project configuration

\- The appropriate device support package and toolchain

\- Compatible microcontroller hardware for testing



\## How to Open the Project



1\. Clone or download this repository.

2\. Open `majorproject\_test/majorproject\_test.uvproj` in a compatible Keil µVision installation.

3\. Check the target device, toolchain, and project settings.

4\. Review the source files and required hardware connections.

5\. Build the project and test it on compatible hardware.



\## Project Modules



| Module | Purpose |

|---|---|

| `uart0.c` | UART communication |

| `lcd.c` | LCD interfacing |

| `i2c.c` | I2C communication |

| `spi.c` | SPI communication |

| `rtc.c` | Real-time clock interfacing |

| `timer0.c`, `Timer1.c` | Timer functionality |

| `kpm.c` | Keypad interfacing |

| `esp01.c` | ESP-01 communication support |



Module descriptions are based on filenames and should be verified against the source code.



\## Future Enhancements



\- Integrate and document validated heart-rate and SpO2 sensor readings.

\- Add an IoT dashboard for remote monitoring.

\- Implement configurable alerts for abnormal readings.

\- Include circuit diagrams, hardware photographs, and demonstration results.

\- Add verified setup instructions and test results.



\## Disclaimer



This project is intended for educational and prototyping purposes. It is not a certified medical device and should not be used for medical diagnosis or treatment.



\## Author



\*\*Harsha\*\*



GitHub: \[@harsharamisetti18](https://github.com/harsharamisetti18)

