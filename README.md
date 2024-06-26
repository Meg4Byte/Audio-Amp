# Audio-Amp
Audio amplifier design and simulation in MicroCap-12 

<p align="center">
  <img src="https://github.com/Meg4Byte/Audio-Amp/assets/121357383/06ed1c49-b9c9-40ae-8fb3-c6125215c91d">
</p>

## Table of Contents

- [Project Description](#project-description)
- [Sub-blocks](#sub-blocks)
  - [Input filter](#input-filter)
  - [Op-amp](#op-amp)
  - [Bias circuit](#bias-circuit)
  - [AB stage (power amplifier)](#ab-stage-power-amplifier)
  - [Output filter](#output-filter)
  - [Negative feedback](#negative-feedback)
- [Schematic](#schematic)
- [Installation Instructions](#installation-instructions)
- [Usage Instructions](#usage-instructions)
   - [Open the Project](#open-the-project)
   - [Run the Simulation](#run-the-simulation)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
  
## Project Description

This project simulates an audio amplifier using MicroCap12.Requirements are as follows : 

Design an audio amplifier. It must contain a voltage amplification stage and an AB output stage. Implement the amplification stage using transistors or op-amps, with freedom of choice. Implement the AB output stage using transistors. The transistor can be bipolar or MOSFET. Select all components and explain their choice, show the calculation of critical components. Calculate the maximum efficiency coefficient. Perform circuit simulation in Microcap. Use DC analysis to check the quiescent currents of the amplifier. Use transient simulations to verify the circuit's operation, find the maximum input voltage, and measure the circuit gain in the linear regime. Use AC analysis to check the bandwidth of the amplifier. The speaker parameters are resistance R = 8Ω and power P = 40W.

Note:Detailed documentation is also in the repository if you wish to know how to calculate parameters of each sub-block.In the following sections there will only be brief description of each sub-block with general formulas. 

## Sub-blocks

The circuit contains the following important sub-blocks:

1. Input filter
2. Op-amp
3. Bias circuit
4. AB stage (power amplifier)
5. Output filter
6. Negative feedback

In the following section each block is discussed briefly.

#### Input filter

#### Op-amp

#### Bias circuit

#### AB stage (power amplifier)

#### Output filter

#### Negative feedback

## Schematic 


<p align="center">
  <img src="https://github.com/Meg4Byte/Audio-Amp/assets/121357383/4b6435d9-10c4-4822-9e3d-7681a68e7ca5">
</p>



## Installation Instructions

1. **Install MicroCap12:**
   - Download and install MicroCap12 from MicroCap's official website

2. **Clone the Repository:**
   ```bash
   git clone https://github.com/Meg4Byte/Audio-Amp.git

## Usage Instructions

 #### Open the Project:
   - Launch MicroCap12 , click on the open project icon in top left corner and open the project file .

 #### Run the Simulation:
   - Click on the 'Analysis' button to start the desired analysis .
   - Run DC ,Dynamic DC , Transient , AC analysis and find transfer function of the circuit. 
   - Observe the output waveforms and tweak each sub-block's elements to get desired performance .
   - Change input signals and observe the behaviour of the circuit .

## Contributing

 - If you'd like to contribute to this project, please follow these guidelines:
 
 - Fork the repository on GitHub
 
 - Clone your forked repository to your local machine
 
 - Create a new branch for your feature or bug fix
 
 - Make your changes and commit them
 
 - Push your changes to your fork on GitHub
 
 - Create a pull request to submit your contribution
 
## License 

This project is licensed under the MIT License. You are free to use, modify, and distribute this code at your own discretion.

## Contact

For questions or feedback, feel free to reach out at petnenadd_d@uns.ac.rs .

