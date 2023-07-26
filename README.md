# Current-starved-ring-oscillator-Cadance-VLSI

Ring Oscillator is a type of oscillator circuit used for generating a continuous oscillating output signal. It consists of an odd number of inverter stages (usually three or more) connected in a ring configuration. Each inverter stage takes the output of the previous stage and feeds it back as the input to the next stage, creating a closed-loop.

A Current Starved Ring Oscillator is a specific type of ring oscillator circuit designed to operate with reduced current supply. It is commonly used in low-power and energy-efficient integrated circuits where minimizing power consumption is a critical concern.Each inverter stage drives the input of the next stage, forming a closed-loop feedback system. This feedback loop causes the circuit to oscillate and generate a continuous output signal.

The Current starved ring oscillator with only PMOS Source circuit is developed as an alternate arrangement from the circuit in  where the NMOS current sinks are eliminated from the conventional circuit and transistors M10-M12 are the PMOS current sources.The term "current sinks" usually refers to electronic components or circuits that absorb current from the circuit and provide a controlled path for current to flow into them.The PDP is a product of the power consumption and the propagation delay of the circuit. The propagation delay of the circuit is the inverse of the oscillating frequency, so the PDP is calculated using at Vctrl= 1 V and VDD = 0.5 V. The units are mentioned in brackets. So, to calculate Power delay produck ,we use, 𝑃𝐷𝑃(fJ) = 𝑝𝑜𝑤𝑒𝑟(nW)/𝑚𝑎𝑥𝑖𝑚𝑢𝑚 𝑓𝑟𝑒𝑞𝑢𝑒𝑛𝑐𝑦 (MHz).I calculate the Average Power, Maximum frequency, Power delay product. In this project i use 12 transistor. 
 
![image](https://github.com/johir95/Current-starved-ring-oscillator-Cadance-VLSI/assets/90377555/c24e9d3c-f76c-4846-8071-9a5e2488abcb)
       Figure:CSRO with only PMOS Source

![image](https://github.com/johir95/Current-starved-ring-oscillator-Cadance-VLSI/assets/90377555/1a46db3b-0084-4ff8-96f7-49a3e1fc7cb8)
      Figure: Schematic diagram


