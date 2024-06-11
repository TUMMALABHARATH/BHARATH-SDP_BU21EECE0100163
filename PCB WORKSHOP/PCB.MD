                                                   

                  Summer Internship

                  PCB Workshop

Contents:
1.	Team Members
2.	Introduction to PCB
3.	Process of PCB Design
4.	Circuits Designed
5.	Comparison of Simulation and Hardware Result
6.	Applications
7.	Conclusion

Team Members:
1.	K. Koushik               - BU21EECE0100195
2.	J. Dheeraj                - BU21EECE0100305
3.	N. Harsha Vardhan   - BU21EECE0100186
4.	S. Moinuddhin          - BU21EECE0100381  
5.	M. Lok Vignesh         - BU21EECE0100099
6.	T. Bharath                - BU21EECE0100163



Introduction:
What is PCB?
PCB is a copper laminated and non-conductive Printed Circuit Board, in which all electrical and electronic components are connected together in one common board with physical support for all components with a base of board. When PCB is not developed, at that time all components are connected with a wire which increases complexity and decreases the reliability of the circuit, In this way, we cannot make a very large circuit like a motherboard. In PCB, all components are connected without wires, all components are connected internally, it will reduce the complexity of the overall circuit design. PCB is used to provide electricity and connectivity between the components, by which it functions the way it was designed. PCBs can be customized for any specifications to user requirements. It can be found in many electronic devices like; TVs, Mobile, Digital cameras, and Computer parts like; Graphic cards, motherboards, etc. It is also used in many fields like; medical devices, industrial machinery, automotive industries, lighting, etc.
Process of PCB design:
1. Understand the electrical parameters.
Before starting a PCB design, you should know and understand the electrical parameters of the system, including:
•	Current maximums
•	Voltages
•	Signal types
•	Capacitance limitations
•	Impedance characteristics
•	Shielding considerations
•	Type and location of circuit components and connectors
•	Detailed net wire listing and schematic

2. Creating the schematic.
One of the first steps is always creating a schematic, which refers to the design at the electrical level of the board’s purpose and function. At this point, it’s not yet a mechanical representation.

3. Use a schematic capture tool to create your PCB layout.
The right PCB provider will work with principal engineers to develop a schematic with a software platform such as Mentor PADS, Allegro, or Altium, which shows you exactly how your board will operate and where the components will be placed. After you create your schematic, the mechanical engineer will load the design and determine how it will fit in the intended device.

4. Design your PCB stackup.
This is important to consider early on in the PCB design stage due to impedance, which refers to how much and how quickly electricity can travel down a trace. The stackup plays a role in how the mechanical engineer can design and fit the PCB into the device.

5. Define design rules and requirements.
This step is largely dictated by standards and acceptability criteria from the IPC, which is the industry association for PCB and electronics manufacturing. These standards tell you everything you need to know regarding PCB manufacturing. An important tip: Find a PCB layout provider who is extremely familiar with IPC standards; this can help you avoid major revisions and project delays.

6. Place your components.
In many cases, the customer and PCB provider will discuss design and layout guidelines when it comes to the placement of components. For example, there may be standards indicating that certain components cannot be placed near others because they create electrical noise in the circuit. The PCB provider will have data sheets on every component (in most cases these are connectors), which will then be placed in the mechanical layout and sent to the customer for approval.

7. Insert drill holes.
This step is driven by the components and a connection. About half of the flex circuits on the market are double-sided, which means they have connection to the drill hole on the bottom layer.

8. Route the traces.
After you’ve placed the components and drill holes, you’re ready to route the traces, which means connecting segments of the path.





9. Add labels and identifiers.
Now is the time to add any labels, identifiers, markings, or reference designators to the layout. Reference designators are helpful in showing where specific components will go on the board.
10. Generate design/layout files.
This is the final step in the layout process. These files contain all the information pertaining to your printed circuit board, and once they have been generated, your PCB is now ready for fabrication, manufacturing and assembly. 

Circuits: 
 
   LED ON & OFF: 

 TinkerCAD-

                


EasyEDA-

            



2D Design-

                                      


3D Design-

                      



   HALF ADDER: TinkerCAD

                 


EasyEDA-
                        


2D Design-
                          

3D Design-
                     

Analog Circuit: Inverting Amplifier Circuit(op-amp)
 Software-
                     

Hardware-
                     

Digital Circuit: 8x3 Encoder
 Software-
                     
Hardware-
                    

Comparison of Simulation and Hardware Results:
1. Inverting Op-Amp:
Simulation Results-
•	Gain: The simulation typically matches this value closely, assuming ideal conditions. 
•	Frequency Response: Ideal frequency response, with a flat gain up to a certain cutoff frequency dictated by the op-amp’s bandwidth. 
•	Phase Response: Shows an ideal 180° phase shift between input and output. 
•	Distortion and Noise: Minimal or no distortion and noise due to ideal components and conditions. 
Hardware Results-
•	Gain: Practical gain might slightly differ due to component tolerances and non-ideal behavior of real resistors and op-amps. 
•	Frequency Response: Real-world frequency response might show deviations at higher frequencies due to parasitic elements and the finite gain-bandwidth product of the op-amp. 
•	Phase Response: Similar to simulation at low frequencies, but may show deviations at higher frequencies due to real op-amp limitations. 
•	Distortion and Noise: Presence of noise and potential distortion due to external interference, power supply imperfections, and inherent non-linearities in the op-amp.

2.	8x3 Encoder: 
Simulation Results-

•	Logical Operation: Encoder functions as expected, providing correct 3-bit binary outputs for each of the 8 input combinations.
•	 Timing: Ideal timing with no propagation delay, assuming perfect logic gates. 
•	Power Consumption: Negligible or ideal power consumption values provided by the simulation tool. 
Hardware Results-

•	Logical Operation: Encoder correctly converts 8 input signals to corresponding 3-bit binary outputs, though minor deviations might occur due to real-world signal integrity issues. 
•	Timing: Real-world timing includes propagation delays, which are absent in ideal simulations. These delays depend on the actual logic family and physical layout. 
•	Power Consumption: Actual power consumption is higher than simulated values due to leakage currents and other non-ideal factors in real components. 
Applications of PCB:
•	Smartphones 
•	Computers (desktops, laptops, tablets) 
•	Home appliances 
•	Engine Control Units (ECUs) 
•	Infotainment systems in vehicles 
•	Automotive safety systems (airbags, ABS, ADAS) 
•	Diagnostic medical equipment (MRI, CT scanners, X-ray machines) 
•	Medical monitoring devices (heart rate monitors, glucose meters, blood pressure monitors) 
Conclusion:
The PCB workshop provided an in-depth understanding of the principles and practices involved in designing and fabricating printed circuit boards. Participants gained hands-on experience in using PCB design software, selecting appropriate materials and components, and understanding the manufacturing process. The workshop emphasized the importance of precision and attention to detail, ensuring that designs are both functional and manufacturable. By the end of the workshop, attendees were equipped with the skills necessary to create efficient, reliable, and high-quality PCBs for various applications, bridging the gap between theoretical knowledge and practical implementation. This experience will undoubtedly enhance their capability to innovate and excel in electronics design and development.





 
