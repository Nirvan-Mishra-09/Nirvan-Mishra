# Nirvan Mishra's Portfolio

## Education
### University of Maryland
**Masters of Engineering in Robotics minor in VLSI Design** | Maryland, USA | GPA: 3.6 / 4.0 | Dec 2024

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

### APB Slave Design and Verification 
**September 2024**
- **Tools:** System Verilog, Xilinx Vivado, Digital Design
- Implemented an APB (Advanced Peripheral Bus) slave module using Verilog, supporting basic read and write operations with error checking mechanisms.
- The module handles data transfer and status signaling, ensuring proper communication with the APB master, with state machine control for idle, read, and write states.
 
### 16 x 8 FIFO RTL Design and Verification
**August 2024**
- **Tools:** System Verilog, Xilinx Vivado, Digital Design
- Developed and verified a 16x8 FIFO (First-In-First-Out) memory buffer using SystemVerilog, utilizing constrained random verification (CRV) technique.
- Designed the 16x8 FIFO with 8-bit data width and 16-entry depth. Integrated control logic for read/write pointers, full and empty status flags.
  
### 32 Bit RISC-V Processor
**June - July 2024**
- **Tools:** Verilog, Xilinx Vivado, Digital Design
- Designed and implemented a single-cycle RISC-V processor in Verilog, featuring key components such as the ALU, control unit, instruction memory, program counter, register file, and data memory, to execute RV32I Base Integer Instructions.
- Executed R-type, I-type, and S-type instructions of the RV32I instruction set and developed comprehensive test cases in Verilog to verify the correct functionality of each instruction type.


### 32 Bit MAX Circuit
**April 2024**
- **Tools:** Cadence Virtuoso, Digital CMOS VLSI Design
- Formulated a sequential circuit to determine the maximum value among eight 4-bit numbers, utilizing a 2-bit counter, data selector, sorter unit, and memory elements to iteratively compare and track the maximum value over multiple clock cycles.
- Validated the circuit through simulations, ensuring accurate determination of the maximum value within four clock cycles, supported by detailed transistor-level schematics.

### 32-Bit Sorting Circuit
**March 2024**
- **Tools:** Cadence Virtuoso, Digital CMOS VLSI Design
- Devised an 8-input (4-bit) sorting circuit in Cadence Virtuoso using a bottom-up strategy, which improved sorting efficiency. This included designing a Comparator Circuit for bit-wise comparisons and a Swapping Circuit to arrange inputs in descending order, which reduced sorting time.
- Achieved a worst-case delay of 1.8ns and power consumption of 4mW, ensuring the design was both high-performance and energy-efficient.


### Advanced Logic Gate Optimization for Enhanced Performance in Digital Circuits
**May 2024**
- **Tools:** Cadence Virtuoso, Digital CMOS VLSI Design
- Constructed a combinational circuit to implement a complex Boolean expression with eight digital inputs (A-H) and one output (Y). The initial design utilized fundamental logic gates such as AND, OR, and NOT.
- Applied three key optimization techniques: CMOS gate sizing, alternative logic structures, and complex CMOS gates.
- Achieved reductions in worst-case delay (73%) and power consumption (70%) through optimized design, resulting in a decrease from 0.38 ns to 0.1 ns in delay and from 0.07 mW to 0.02 mW in power consumption.


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
