PulseGuard – IoT-Based Heart Rate and Oxygen Monitoring System

PulseGuard is an embedded systems project focused on health-related parameter monitoring and microcontroller peripheral interfacing. The project includes embedded C modules for communication protocols, display interfacing, timing, interrupts, and ESP-01 communication support.

This repository contains the project source code, Keil µVision project files, system block diagram, and output screenshots for documentation.

📌 Project Overview

The goal of PulseGuard is to explore embedded systems development and hardware interfacing for a health-monitoring application.

The project includes modules for UART, LCD, I2C, SPI, RTC, timers, interrupts, keypad interfacing, and ESP-01 communication.

🎯 Objectives
Develop embedded C modules for microcontroller peripheral interfacing.
Demonstrate serial communication using UART.
Interface an LCD display and keypad.
Explore I2C and SPI communication protocols.
Implement RTC, timer, and interrupt functionality.
Support ESP-01-based communication.
Document the system architecture and project outputs.
✨ Key Features
Modular embedded C source code.
UART serial communication support.
LCD and keypad interfacing.
I2C and SPI peripheral communication.
RTC and timer modules.
Interrupt handling.
ESP-01 communication support.
System block diagram and output screenshots.

Note: Actual heart-rate and SpO₂ sensing capabilities depend on the connected hardware and verified implementation.

🛠️ Technologies Used
Component	Technology
Programming languages	C and ARM Assembly
Development environment	Keil µVision
Project format	Keil µVision .uvproj
Communication protocols	UART, I2C, SPI
Display interfacing	LCD
Input interfacing	Keypad
Timing modules	RTC and timers
Wireless communication support	ESP-01
Hardware platform	Refer to the project configuration for the exact microcontroller
🧩 System Block Diagram

The following image documents the PulseGuard system architecture.

!PulseGuard System Block Diagram

📷 Project Output Screenshots

The following images document project outputs and the data-uploading process.

Data Uploading

!PulseGuard Data Uploading

Output Screenshot 1

!PulseGuard Output 1

Output Screenshot 2

!PulseGuard Output 2

Output Screenshot 3

!PulseGuard Output 3

📂 Repository Structure
PulseGuard-IoT-Health-Monitoring/
├── README.md
├── .gitignore
├── doc/
│   └── images/
│       ├── block-diagram/
│       │   └── PulseGuard_Block_Diagram.jpg.jpeg
│       └── output-photos/
│           ├── output-imag-datauploading.jpeg
│           ├── output-imag1.jpeg
│           ├── output-imag2.jpeg
│           └── output-imag3.jpeg
└── majorproject_test/
    ├── majorproject_test.uvproj
    ├── main_pg.c
    ├── main_test.c
    ├── project_pg.h
    ├── all_defines.h
    ├── lcd.c
    ├── uart0.c
    ├── i2c.c
    ├── spi.c
    ├── rtc.c
    ├── timer0.c
    ├── Timer1.c
    ├── kpm.c
    ├── esp01.c
    └── ...


The structure above summarizes the known project files. Additional files may exist in the repository.

📦 Software Requirements
Keil µVision compatible with the supplied project configuration.
The appropriate device support package and compiler toolchain.
Compatible microcontroller hardware for hardware testing.
Required peripheral modules and connections, depending on the features being tested.
🚀 Getting Started
1. Clone the Repository

Open Git Bash and run:

git clone https://github.com/harsharamisetti18/PulseGuard-IoT-Health-Monitoring.git

2. Navigate to the Project Folder
cd PulseGuard-IoT-Health-Monitoring

3. Open the Keil Project

Open the following project file using a compatible Keil µVision installation:

majorproject_test/majorproject_test.uvproj

4. Verify Project Configuration

Before building the project:

Check the configured microcontroller and target device.
Verify the compiler and toolchain settings.
Confirm that all required source files are included.
Review the peripheral connections and hardware configuration.
5. Build and Test

Build the project in Keil µVision. If compatible hardware is available, test the implemented modules and verify their outputs.

Exact hardware connections, sensor configuration, and build steps should be confirmed against the project source code and circuit design.

📑 Project Modules
File	Purpose
main_pg.c	Main project source; verify the implemented functions in the source code
main_test.c	Test-related source file
project_pg.h	Project header file
all_defines.h	Project definitions and configuration
uart0.c	UART communication
lcd.c	LCD interfacing
i2c.c	I2C communication
spi.c	SPI communication
rtc.c	Real-time clock interfacing
timer0.c	Timer functionality
Timer1.c	Timer functionality
kpm.c	Keypad interfacing
esp01.c	ESP-01 communication support

Module descriptions are based on filenames and should be checked against the source code.

🔮 Future Enhancements
Integrate and validate heart-rate and SpO₂ sensor readings using compatible sensors.
Develop an IoT dashboard for remote health-data visualization.
Implement configurable alerts for abnormal readings.
Improve wireless data transmission and monitoring.
Document circuit connections and hardware requirements.
Add detailed module-level documentation and verified test results.
Improve error handling and communication reliability.
⚠️ Disclaimer

PulseGuard is an educational embedded systems project. It is not a certified medical device and must not be used for medical diagnosis, treatment, or emergency decision-making. Any health-related readings must be validated using appropriate equipment and methods.

👨‍💻 Author

Harsha

GitHub: @harsharamisetti18

📄 License

No license is specified in this repository. Unless a license is added, reuse and redistribution are subject to applicable copyright law.