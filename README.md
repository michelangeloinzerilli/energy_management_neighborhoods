# Smart Energy Management for Future Neighborhoods

Project developed at **KTH Royal Institute of Technology** within the course *Energy Systems for Smart Cities*.

## Overview

This project investigates smart energy management strategies for a future residential neighborhood in Sweden composed of **12 single-family homes** equipped with:

- Photovoltaic generation
- Electric vehicles
- Heat pumps
- Battery storage
- Smart control systems

The analysis evaluates how different control strategies can improve:

- Energy costs
- PV self-consumption
- Peak power demand
- CO₂ emissions
- Occupant comfort

The project also explores the transition from individually managed smart homes to a centralized **energy community** with shared infrastructure and coordinated control.

## Methodology

The analysis is structured into three main levels:

### E-Level Analysis

The **E-level** evaluates individual, single-purpose control strategies for each technology.

The strategies considered are:

- **Self-consumption**
- **Price arbitrage**
- **Peak shaving**

These strategies are tested separately for:

- Electric vehicles
- Home batteries
- Heat pumps

The objective is to understand the individual effect of each control strategy before combining them.

### C-Level Analysis

The **C-level** combines the previously developed control strategies.

At this stage, the analysis considers:

- Combined battery control
- Combined EV control
- Combined heat pump control
- Multi-technology control
- Application of the controllers across all 12 households

The purpose is to evaluate how different technologies interact when their control strategies are applied simultaneously at household and neighborhood level.

### A-Level Analysis

The **A-level** investigates an integrated **energy community** for the full neighborhood.

The community-level model includes:

- Shared PV generation
- Centralized heat-pump operation
- Centralized battery storage
- Independent EVs
- A local microgrid
- Shared energy flows between households

The analysis compares decentralized smart homes with a centralized energy-community configuration and evaluates the effects on costs, self-consumption, emissions, peak power, and stakeholder interests.

## Repository Structure

The repository is organized into different files corresponding to the **E-, C-, and A-level analyses**.

Each file contains the relative **Polysun simulation files** configurations used to study the different smart-control strategies.

The main project results, control logic, KPI comparisons, and final recommendations are documented in the complete PDF report included in the repository.

## Main Control Strategies

The smart controllers are based on three main approaches:

- **Self-Consumption** – shifting electricity consumption toward periods of high local PV generation
- **Price Arbitrage** – shifting demand or storage operation according to electricity-price variations
- **Peak Shaving** – reducing maximum grid import by controlling flexible loads and storage

These strategies are applied individually and in combination to EVs, heat pumps, and batteries.

## Tools and Methods

**Polysun · Smart Energy Management · Electric Vehicles · Heat Pumps · Battery Energy Storage · Photovoltaics · Energy Communities · Price Arbitrage · Peak Shaving · Self-Consumption · Techno-Economic Analysis**

## Project Material

The repository contains:

- Polysun models for the different scenarios
- E-level analysis files
- C-level analysis files
- A-level analysis files
- Supporting data
- Complete project report with methodology and results

## License

Copyright © 2025. All rights reserved.

This repository is made publicly available for **portfolio and academic viewing purposes only**. No permission is granted to copy, modify, distribute, or reuse the original report, Polysun models, control strategies, analyses, or other materials developed by the project authors without prior written permission.

Third-party datasets, software, models, and externally sourced materials remain subject to the rights, licenses and restrictions of their respective owners.

## Author

**Michelangelo Inzerilli**  
EIT InnoEnergy, KTH Royal Institute of Technology and Universitat Politècnica de Catalunya