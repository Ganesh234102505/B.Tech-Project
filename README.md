
# Smart Charging System for Electric Vehicles

## Overview

This project involves the design and implementation of a Smart Charging System for Electric Vehicles (EVs) using solar energy. The system includes a solar charging station equipped with Maximum Power Point Tracking (MPPT) and radiance tracking capabilities to optimize solar energy usage for charging EVs. The system also incorporates energy management features to ensure efficient and sustainable charging.

## Project Structure

- **Introduction**
  - Overview of solar energy and its significance in renewable energy sources.
  - Literature survey covering relevant research and existing solutions.
  - Challenges in implementing solar charging stations.
  - Objective and organization of the report.

- **Solar Charging Station**
  - Explanation of the charging station's structure and components.
  - Different types of charging stations and their functionality.
  - Design and working principles of the charging station.

- **Radiance Tracking**
  - Details of the solar radiance tracking system used to optimize energy capture.
  - Components involved, including PV cells, DC motor, motor driver, and Arduino.
  - Construction and working mechanism of the radiance tracking system.
  - Algorithm and program code for implementing radiance tracking.

- **Energy Management**
  - Introduction to the energy management system and its importance.
  - Circuit diagram and explanation of components used.
  - Working principle and algorithm for managing energy between PV cells, batteries, and loads.
  - Program code for energy management and state of charge (SOC) estimation.

- **Results**
  - Summary of the system's performance, including the benefits of variable angle tracking and SOC-based load prioritization.
  
- **Conclusion**
  - Final thoughts on the significance of the project and potential for future development.

- **References**
  - List of references and academic papers that were consulted during the project.

## How to Use

1. **Hardware Setup**: 
   - Assemble the solar charging station as per the design specifications provided in the report.
   - Ensure all components, including PV cells, DC motor, motor driver, and Arduino, are connected correctly.
   
2. **Software Setup**:
   - Install the Arduino IDE on your computer.
   - Load the provided Arduino code into the Arduino Uno for controlling the motor based on solar radiance tracking.
   - Upload the energy management code to handle SOC-based load prioritization and battery management.

3. **Running the System**:
   - Place the solar panel in an outdoor area with sufficient sunlight.
   - Power up the system and monitor the performance through the Arduino serial monitor.
   - The system will automatically track the sun to maximize solar energy capture and manage charging based on battery SOC.

4. **Testing and Validation**:
   - Compare the system’s performance with the expected results mentioned in the report.
   - Adjust parameters in the code if necessary to optimize the system’s efficiency.

## Future Work

- Expand the system to support fast charging and integration with smart grids.
- Implement advanced algorithms for better energy management and efficiency.
- Explore the use of different battery technologies to enhance storage capacity.

## Contributors

- I. Eswara Manikanta
- M. Ganesh
- P. Jagadeesh
- Saadique Mehboob


