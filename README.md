# C++ Calendar Console App

## Overview

This C++ console application provides a set of features for working with both Ethiopian and Gregorian calendars. It includes functionalities like monthly calendar display, date conversion, holiday and fasting date calculations, and finding the weekday for any given date.

## Features

- **Monthly Calendar Display**: View monthly calendars for both Ethiopian and Gregorian calendar systems.
- **Date Conversion**: Convert dates between Ethiopian and Gregorian calendars.
- **Holiday & Fasting Calculation**: Calculate the dates for holidays and fasting periods for any given year.
- **Weekday Finder**: Determine the weekday for any given date.

## Getting Started

### Prerequisites

To compile and run this application, you need:

- A C++ compiler (e.g., GCC, Clang, or MSVC)
- A terminal or command prompt

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/haileamlak/bahire-hasab-calendar-app.git
    cd bahire-hasab-calendar-app
    ```

2. **Compile the program**:
    ```bash
    g++ -o calendar-app main.cpp
    ```

3. **Run the program**:
    ```bash
    ./calendar-app
    ```

### Directory Structure

```plaintext
├── src
│   ├── main.cpp           # Main entry point of the application
│   ├── calendar.cpp       # Calendar-related logic (display, conversion, etc.)
│   ├── calendar.h         # Calendar class/interface declarations
│   ├── number_converter.cpp # Logic for number conversions between systems
│   ├── number_converter.h   # Number conversion class/interface declarations
│   ├── holidays.cpp       # Logic for calculating holidays and fasting periods
│   ├── holidays.h         # Holiday and fasting class/interface declarations
├── README.md              # Project documentation
└── LICENSE                # License file
```
