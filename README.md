# Nirvan Mishra's Portfolio

## Education
### University of Maryland
**Masters of Engineering in Robotics** | Maryland, USA | GPA: 3.6 / 4.0 | Present

### IET-DAVV
**Bachelors of Engineering in Electronics and Instrumentation** | M.P, India | GPA: 8.0 / 10 | June 2021

#### Courses:
- Digital CMOS VLSI Design
- Embedded Software Development
- Digital Electronics
- Path Planning
- Perception
- Python Application for Robotics
- Controls
- Deep Learning in Computer Vision
- Reinforcement Learning

## Skills
**Languages:** Verilog, System Verilog, C/C++, Matlab, Perl, Python (TensorFlow, Keras, Pandas, Scikit-learn, OpenCV)  
**Robotics:** ROS 1, ROS 2, Gazebo, MoveIt  
**Software:** Cadence Virtuoso, Xilinx Vivado, Linux, ModelSIM, Altium  
**Dev Boards:** Arduino UNO, ESP32 

## Concepts
- STA (Static Timing Analysis)
- FIFO (First-In-First-Out)
- Computer/VLSI Architecture
- CDC (Clock Domain Crossing)
- Digital Electronics
- Verilog
- System Verilog
- RTL Development
- RTL Coding
- RISC-V ISA Architecture

## Experience

### Innovative Solutions
**FPGA Intern** | Ghaziabad, UP | July 2022 - Dec 2022

- Designed and implemented SPI (Serial Peripheral Interface) and UART (Universal Asynchronous Receiver-Transmitter) IP cores using Verilog.  
- Verified the functionality of the SPI and UART IPs through comprehensive testbenches developed in SystemVerilog.
- Deployed and tested the designed IPs on a Xilinx Nexys Artix-7 FPGA, utilizing the Vivado Design Suite to synthesize, implement, and validate the hardware functionality.



## VLSI Projects

### 16 x 8 FIFO RTL Design and Verification
**August 2024**
- **Tools:** System Verilog, Xilinx Vivado, Digital Design
- Programmed and Verified a 16x8 FIFO Memory Buffer in SystemVerilog, implementing robust state machine control with full and empty flag indicators, improving data handling efficiency by 30%
- Defined a comprehensive testbench using advanced UVM concepts, including driver, monitor, and scoreboard, to validate FIFO operations and ensure data integrity, increasing verification coverage by 25%.
  
### 32 Bit RISC-V Processor
**May - June 2024**
- **Tools:** Verilog, Xilinx Vivado, Digital Design
- Designed a single-cycle RISC-V processor in Verilog, incorporating essential components such as ALU, control unit, instruction memory, program counter, register file, and data memory.
- Executed the RISC-V RV32I instruction set, covering R-type, I-type, and S-type instructions, for RV32I Base Integer Instructions.
- Developed multiple test cases to test and verify the functionality of each instruction type, integrated datapath elements and control logic using Verilog.

### 32 Bit MAX Circuit
**April 2024**
- **Tools:** Cadence Virtuoso, Digital CMOS VLSI Design
- Created a sequential circuit to find the maximum value among eight 4-bit numbers (X0..X7), utilizing a counter and memory elements for continuous tracking over multiple clock cycles.
- Developed a 2-bit counter, data selector, sorter unit, and memory file. The sorter unit compared and swapped inputs to determine the maximum value iteratively.
- Validated the circuit through simulations, achieving accurate maximum value determination within four clock cycles, supported by detailed transistor-level schematics.

### 32-Bit Sorting Circuit
**March 2024**
- **Tools:** Cadence Virtuoso, Digital CMOS VLSI Design
- Devised an 8-input (4-bit) sorting circuit in Cadence Virtuoso using a bottom-up strategy, improving sorting efficiency by 25%.
- Designed a Comparator Circuit for bit-wise A-B comparison, generating signals for greater than, less than, and equal conditions, and a Swapping Circuit to rearrange inputs in descending order, reducing sorting time by 15%.
- Achieved a worst-case delay of 1.8ns and power consumption of 4mW, ensuring a high-performance and energy-efficient design.

### Advanced Logic Gate Optimization for Enhanced Performance in Digital Circuits
**May 2024**
- **Tools:** Cadence Virtuoso, Digital CMOS VLSI Design
- Constructed a combinational circuit to implement a complex Boolean expression with eight digital inputs (A-H) and one output (Y). The initial design utilized fundamental logic gates such as AND, OR, and NOT.
- Applied three key optimization techniques: CMOS gate sizing, alternative logic structures, and complex CMOS gates.
- Achieved reductions in worst-case delay (73%) and power consumption (70%) through optimized design, resulting in a decrease from 0.38 ns to 0.1 ns in delay and from 0.07 mW to 0.02 mW in power consumption.

### 8x3 Bit Priority Encoder
**March 2021**
- **Tools:** Verilog, Xilinx Vivado, Digital Design
- Formulated the encoder logic at the register-transfer level (RTL) using Verilog HDL, reducing development time by 30%.
- Employed the priority encoder’s logic at behavioral, structural, and gate levels, and wrote a comprehensive test bench.

### Robotics Projects
#### Autonomous Navigation in Indoor Environment using Reinforcement Learning
**April 2024**
- Explored the application of reinforcement learning for autonomous navigation of a TurtleBot3 robot in complex indoor environments.
- Evaluated the effectiveness of Deep Q-Networks and Deep SARSA algorithms in enabling efficient and safe navigation towards designated goals while avoiding collisions.
- Conducted a comparative assessment of these two deep reinforcement learning techniques, focusing on training the robot agent to navigate effectively considering both path optimality and obstacle avoidance in a dynamic setting.

#### Leader Follower Robot with Dynamic Obstacle Avoidance
**April 2023**
- Directed the creation of a leader-following robot system, emphasizing precise coordination between the leader and follower robots to ensure seamless operation in various environments.
- Incorporated a dynamic obstacle avoidance mechanism utilizing Computer Vision, specifically leveraging OpenCV’s color detection technique, to enhance the robots’ ability to navigate complex environments in real-time.
- Designed and implemented efficient communication protocols between the leader and follower robots, ensuring low-latency and reliable data transmission for synchronized movement and responsive interaction.

#### Time Series Prediction
**December 2023**
- Modeled RNN, LSTM, and 1-D CNN architectures to forecast household electricity consumption, using the "AEP hourly" dataset provided by AEP (American Electric Power).
- Analyzed model performance metrics (e.g., accuracy, mean squared error) to select the optimal model for precise forecasting of future consumption.
- Utilized advanced data preprocessing techniques, such as normalization and feature engineering, to enhance the predictive capabilities of the models and ensure robust performance across varying consumption patterns and environmental factors.

#### Path Planning
**April 2023**
- Programmed a Python-based solution to find the shortest route on a given 2D map using Dijkstra’s algorithm, ensuring optimal pathfinding in a 2D grid environment.
- Implemented A* algorithm for both 2D and 3D pathfinding using TurtleBot3, leveraging ROS1 and Gazebo for simulation, achieving efficient and accurate navigation in complex environments.
- Evaluated the efficiency of Rapidly Exploring Random Trees (RRT) and RRT-A* algorithms for motion planning, considering both Euclidean and Manhattan metric functions, to determine their respective strengths in navigating complex environments.
  
## Certificates
- SystemVerilog for Verification Part 1: Fundamentals
  ![SystemVerilog_completion](https://github.com/user-attachments/assets/c51a16ce-5d39-40df-adb5-c749bff88cf6)
