# Current research

## Automated tools for S-parameter Analysis (Winter 2025 - Present)
Goals:
* Identify the most common "pathological" design flaws in high speed serial channels
* Characterize the S-parameter signatures of each flaw
* Use machine learning techniques to identify pathological design structures from their S-parameter signatures
* Infrastructure for training a variety of machine learning models using S-parameter data


# Past Projects

### [Bluetooth Page Turning Pedal (2022)](https://github.com/SamMcD-S/PageTurner.git)
As a musician who reads music from an Ipad, a bluetooth page-turning pedal is a important tool to overcoming awkward (fast) page turns. Despite their internal simplicity, bluetooth page-turning pedals are surprisingly expensive, often costing between 75 and 100$. In this project, I design a simple and inexpensive alternative.
### [Merkle Tree File Verification System (2024)](https://github.com/SamMcD-S/Mkltree.git)
The "mklutil" is a proof-of-concept version control system, designed specifically to quickly verify the contents of a directory in a space aware (and fast) manner. This version of the project uses the djb2 hash to quicky identify modifications to tracked files based on their contents -- and not their "last-changed" metadata tags.
### [Ultimate Bode Analyzer (2023)](https://github.com/SamMcD-S/UltimateBode.git)
A Software Defined Instrument (SDI), using the Digilent AD3 (or AD2), that demonstrates a template for building future instruments using the AD3. The Bode Analyzer is implemented, and evaluated here.
### Voltage Glitch Attack (2022)
In this project, I built open-source modules to run a voltage glitch on the Basys 3 FPGA development board. I demonstrate that my "crowbar" voltage glitch attack can cause unpredictable behavior on an Arduino.
### [Fast Fractal Explorer (2021-22)](https://github.com/SamMcD-S/FastFractalExplorer.git)
The Fast Fractal Explorer (FFE) allows any user to explore fractals in high fidelity. By maintaining a constant resolution and allowing the user to specify new viewing windows, the FFE allows a responsive user interface, even on less powerful computers. This project shows the Mandelbrot Set by default,but can be extended to support other fractals too. The FFE demonstrates the MEX/C interface.
### Spectre Attack
This is a generic Spectre Attack, heavily based on the attack from Seed Labs (https://seedsecuritylabs.org). 
However, the aforementioned attack relies heavily on x86 intrinsic instructions, such as clflush, and rdtscp. To avoid this dependence, my Spectre attack project uses a pthread timer, and a generic cache-evict method.
Contributions:
* A timing gadget that utilizes pthread timers, as opposed to architecture specific timing instructions
* An (in progress) toolkit to determine the cache configuration of a computer, and perform cache-clearing operations.


## Publications:

[Ange-Thierry Ishimwe, Sam McDiarmid-Sterling, Zack McKevitt, and Tamara Silbergleit Lehman.
“SSMR: Statically Detecting Speculation Safe Memory Regions to Mitigate Transient Execution Attacks.”
Proceedings of the 35th ACM SIGPLAN International Conference on Compiler Construction](https://dl.acm.org/doi/10.1145/3771775.3786272)


<!--
### Audio Electronics
What makes "Audiophile" gear so expensive? How can I better interpret the specifications of the gear I use to understand effects on my listening experience. 

Throughout this project, I'll build measurement tools to aid a quantitative analisys of the devices I test. I firmly believe that if a difference can't be measured, it can't be heard!
-->

