# Inverter Design using Cadence Virtuoso

This repository contains the design files for an inverter (NOT gate) created using Cadence Virtuoso. The design includes schematic, layout, and simulation files.

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Design Details](#design-details)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Introduction

This project provides a detailed design of a CMOS inverter using Cadence Virtuoso. An inverter is a fundamental building block in digital electronics, used to invert the input signal. This repository includes all necessary files to view, simulate, and analyze the inverter design.

## Prerequisites

Before you begin, ensure you have the following installed on your machine:

- Cadence Virtuoso
- A Unix-based operating system (Linux or macOS recommended)
- Basic knowledge of VLSI design and Cadence tools

## Installation

To set up the project on your local machine, follow these steps:

1. **Clone the repository**:
    ```sh
    git clone https://github.com/harshavardan1403/inverter_Design.git
    ```

2. **Navigate to the project directory**:
    ```sh
    cd inverter_Design
    ```

3. **Setup your Cadence environment**:
    Make sure your Cadence environment is properly configured. This usually involves sourcing the Cadence setup script. For example:
    ```sh
    source /path/to/cadence/setup.sh
    ```

## Usage

To open and simulate the inverter design, follow these steps:

1. **Start Cadence Virtuoso**:
    ```sh
    virtuoso &
    ```

2. **Open the Library Manager**:
    - Navigate to `File > Library Manager`.

3. **Access the Project**:
    - In the Library Manager, navigate to the `inverter_lib` library.

4. **Open the Schematic**:
    - Find and double-click the `Inverter_TB` cell and open the `schematic` view.

5. **Run Simulations**:
    - Open the ADE (Analog Design Environment) to set up and run simulations. Load the provided simulation files to perform DC, AC, and transient analyses.

## Design Details

### Schematic

The schematic view of the inverter includes the following components:
- PMOS transistor
- NMOS transistor
- Input and output pins

### Layout

The layout view includes:
- Properly drawn PMOS and NMOS transistors
- Metal interconnections
- DRC and LVS clean checks

### Simulations

The simulation setup includes:
- DC Analysis
- Transient Analysis
- AC Analysis

These simulations verify the correct functionality of the inverter, including its voltage transfer characteristics and dynamic response.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these steps:

1. **Fork the repository**.
2. **Create a new branch** (`git checkout -b feature-branch`).
3. **Make your changes and commit them** (`git commit -m 'Add some feature'`).
4. **Push to the branch** (`git push origin feature-branch`).
5. **Open a pull request**.

