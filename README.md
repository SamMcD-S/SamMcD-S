# Portfolio
This repository demonstrates my current and past projects. While most of the projects relate to computer architecture or audio electronic design, I've also included a few miscellaneous embedded pojects. 

Any material in this repository is intended to be open source, and can be freely reused for educational (or other non-profitable) purposes. Nevertheless, please share your interest or questions with me via email at sammcdiarmidsterling@icloud.com.

## Current Projects
### Spectre Attack
This is a generic Spectre Attack, heavily based on the attack from Seed Labs (https://seedsecuritylabs.org). 
However, the aforementioned attack relies heavily on x86 intrinsic instructions, such as clflush, and rdtscp. To avoid this dependence, my Spectre attack project uses a pthread timer, and a generic cache-evict method.
Contributions:
* A timing gadget that utilizes pthread timers, as opposed to architecture specific timing instructions
* An (in progress) toolkit to determine the cache configuration of a computer, and perform cache-clearing operations.
  
### Voltage Glitch Attack
In this project, I built open-source modules to run a voltage glitch on the Basys 3 FPGA development board. Demonstrations are also documented here.
### [Bluetooth Page Turning Pedal](https://github.com/SamMcD-S/PageTurner.git)
As a musician who reads music from an Ipad, a bluetooth page-turning pedal is a important tool to overcome awkward (or just fast) page turns. Despite their internal simplicity, bluetooth page-turning pedals are surprisingly expensive, often costing between 75 and 100$. In this project, I design a simple and inexpensive alternative.
## Current Research
### Spectre Attack Mitigation
Over the past year, I have worked in the Computer Architecture Lab at CU Boulder on a more-efficient defense against the Spectre Attack. I will update this section of the portfolio at a later time.
Key skills and tools I have used during this research:
  - I have modified the GCC Compiler, adding a new instruction.
  - I have used the gem5 Processor Simulator
### Audio Electronics
What makes "Audiophile" gear so expensive? How can I better interpret the specifications of the gear I use to understand effects on my listening experience. 

Throughout this project, I'll build measurement tools to aid a quantitative analisys of the devices I test. I firmly believe that if a difference can't be measured, it can't be heard!
  
  

