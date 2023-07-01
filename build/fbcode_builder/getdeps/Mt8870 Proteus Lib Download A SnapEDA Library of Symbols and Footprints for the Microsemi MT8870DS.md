# How to Add MT8870 DTMF Decoder IC in Proteus 8.0?
 
Proteus 8.0 is a popular software for designing and simulating electronic circuits. However, it does not have some components in its library, such as the MT8870 DTMF decoder IC. The MT8870 is a device that decodes dual-tone multi-frequency (DTMF) signals, which are commonly used in telephone systems. In this article, we will show you how to add the MT8870 DTMF decoder IC in Proteus 8.0 and use it in your projects.
 
## Step 1: Download the MT8870 Proteus Library
 
The first step is to download the MT8870 Proteus library from a reliable source. One such source is SnapEDA[^2^], which is a free online Proteus CAD library of symbols, footprints, and 3D models for millions of electronic components. You can search for the MT8870 DTMF decoder IC by part number or keyword and download the Proteus schematic symbol and PCB footprint for free.
 
**DOWNLOAD ✸✸✸ [https://t.co/mlnajTYNtl](https://t.co/mlnajTYNtl)**


 
## Step 2: Import the MT8870 Proteus Library
 
The next step is to import the MT8870 Proteus library into your Proteus software. To do this, you need to copy the downloaded files (MT8870.LIB and MT8870.IDX) into the LIBRARY folder of your Proteus installation directory. Then, you need to restart your Proteus software and open the Library Manager. You should see the MT8870 DTMF decoder IC in the list of available components.
 
## Step 3: Use the MT8870 DTMF Decoder IC in Your Circuit
 
The final step is to use the MT8870 DTMF decoder IC in your circuit. You can drag and drop the component from the Library Manager onto your schematic and connect it according to your design. The MT8870 has five outputs (Q1-Q4 and STD) that indicate the decoded DTMF digit and a valid signal. You can also use a TestPin component to simulate the input DTMF signal in Proteus ISIS.
 
### Conclusion
 
In this article, we have shown you how to add the MT8870 DTMF decoder IC in Proteus 8.0 and use it in your projects. This way, you can design and simulate circuits that involve DTMF decoding, such as telephone systems, remote control devices, or security systems. We hope you found this article helpful and informative.
 
How to download Mt8870 library for Proteus,  Mt8870 DTMF decoder library for Proteus simulation,  Mt8870 Proteus library free download link,  Mt8870 Proteus library installation guide,  Mt8870 Proteus library error fix,  Mt8870 Proteus library compatibility issues,  Mt8870 Proteus library alternative sources,  Mt8870 Proteus library features and benefits,  Mt8870 Proteus library tutorial and examples,  Mt8870 Proteus library review and feedback,  Mt8870 DTMF module for Proteus simulation,  Mt8870 DTMF module schematic and PCB design,  Mt8870 DTMF module interfacing with Arduino,  Mt8870 DTMF module interfacing with PIC microcontroller,  Mt8870 DTMF module interfacing with Raspberry Pi,  Mt8870 DTMF module applications and projects,  Mt8870 DTMF module datasheet and specifications,  Mt8870 DTMF module price and availability,  Mt8870 DTMF module online purchase options,  Mt8870 DTMF module troubleshooting tips,  How to use Mt8870 in Proteus software,  How to simulate Mt8870 in Proteus software,  How to test Mt8870 in Proteus software,  How to debug Mt8870 in Proteus software,  How to optimize Mt8870 in Proteus software,  How to connect Mt8870 with other components in Proteus software,  How to create custom symbols and models for Mt8870 in Proteus software,  How to import and export Mt8870 files in Proteus software,  How to update and upgrade Mt8870 in Proteus software,  How to customize and configure Mt8870 in Proteus software,  What is Mt8870 and how does it work,  What is Proteus and how does it work,  What is the difference between Mt8870 and other DTMF decoders,  What are the advantages and disadvantages of using Mt8870 in Proteus software,  What are the best practices and tips for using Mt8870 in Proteus software,  What are the common problems and solutions for using Mt8870 in Proteus software,  What are the latest developments and trends for using Mt8870 in Proteus software,  What are the future prospects and opportunities for using Mt8870 in Proteus software,  What are the related resources and references for using Mt8870 in Proteus software,  What are the frequently asked questions and answers for using Mt8870 in Proteus software
  
## Step 4: Build a DTMF Decoder Circuit
 
To decode the DTMF tones generated by the tone generator circuit, we need another circuit that uses the MT8870 DTMF decoder IC. The MT8870 is a device that converts DTMF signals into 4-bit binary outputs. It has an inbuilt op-amp and band-split filter to separate the low and high frequencies of the DTMF signal. It also has a code detector and frequency circuits to identify the DTMF digit and produce the corresponding binary output.
 
### DTMF Decoder Circuit Description (Check DTMF Decoder Circuit in the circuit diagram tab 2)
 
- DTMF tone input is given to inverting terminal IN- (2) of built-in op-amp through 10 ÂµF coupling capacitor
- Two 100 K Ohm resistors connected as shown with pins IN- (2) and GS (3) selects gain of op-amp
- A 3.579 MHz crystal with two capacitors C1 & C2 is connected to crystal terminals 7 and 8
- The binary outputs Q1-Q4 are available at pins 11, 12, 13 and 14 respectively
- The STD pin (15) is a delayed steering output that goes high when a valid DTMF signal is detected
- The INH pin (5) is an inhibit input that can be used to disable the detection of tones representing characters A, B, C and D
- The PDN pin (9) is a power down input that can be used to reduce the power consumption of the IC
- The VCC pin (18) is connected to 5V supply and the GND pin (10) is connected to ground

Here is the snap of DTMF decoder circuit setup. The circuit is built on a breadboard and connected to a speaker that generates DTMF tones. The binary outputs are displayed on four LEDs.
 ![DTMF decoder circuit setup](https://www.engineersgarage.com/wp-content/uploads/2014/12/DTMF-decoder-circuit.jpg) 
### Operation:
 
The circuit works as follows:

- When a DTMF tone is applied to the input of the IC, it passes through the op-amp and the band-split filter that separates the low and high frequencies of the tone
- The low frequency is fed to row frequency detector and the high frequency is fed to column frequency detector
- The code detector compares the detected frequencies with the standard DTMF frequencies and produces a 4-bit binary code corresponding to the pressed key
- The binary code is available at Q1-Q4 pins and can be read by a microcontroller or any other device
- The STD pin goes high when a valid DTMF signal is detected and stays high until the signal ends
- The INH pin can be used to inhibit the detection of tones representing characters A, B, C and D by applying a logic high signal
- The PDN pin can be used to power down the IC by applying a logic low signal

### Conclusion:
 
In this article, we have shown you how to build a DTMF tone generator and decoder circuits using MT8870 and 91214B ICs. These circuits can be used for various applications such as remote control, home automation, security systems, etc. We hope you enjoyed this article and learned something new.
 8cf37b1e13
 