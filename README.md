# ASIC-Design-Flow-using-Openlane

![Screenshot 2023-08-24 130801](https://github.com/NiharGowdaS/ASIC-Design-Flow-using-Openlane/assets/77974814/bd3786bb-cf3c-4ed1-bfbf-7655b82d0256)


OpenLane is a open source software based on SKY130PDK library, it automates synthesis, placement, routing,CTS and physical verification. It provides a framework for automating and customizing the ASIC design flow, making it easier to create custom integrated circuits. This automation can significantly reduce design time and minimize errors.

 **Specification and Requirements:**
   - Define the project's requirements, including functionality, performance, power consumption, and area constraints.
   - 
 **RTL Design:**
   - Create the Register Transfer Level (RTL) design using hardware description languages like Verilog or VHDL.
   - Write the RTL code that describes the digital logic and functionality of the ASIC.

 **RTL Simulation:**
   - Simulate the RTL design to verify its correctness and functionality.
   - Ensure that the design meets the specified requirements.


 **Synthesis:**
   - Uses a synthesis tool ( Yosys) to convert RTL code into a gate-level netlist.
   - Optimize the design for area, power, and timing.

 **Floorplanning:**
   - Define the physical layout of the ASIC, specifying the location of major components, I/O pads, and power distribution.

 **Placement:**
   - Place the synthesized logic gates and components onto the chip's layout.
   - Ensure that placement adheres to the defined floorplan constraints.

 **Clock Tree Synthesis (CTS):**
   - Create a clock distribution network to ensure synchronous operation of all components.
   - Minimize clock skew and optimize for signal arrival times.

 **Routing:**
   - Establish the physical connections between the placed components using metal layers.
   - Optimize for minimal wirelength, avoiding congestion and crosstalk.

 **Static Timing Analysis (STA):**
   - Perform timing analysis to ensure that the design meets the required timing constraints.
   - Fix any violations by optimizing the design or adjusting clock frequencies.

 **Physical Verification:**
    - Run design rule checks (DRC) and layout versus schematic checks (LVS) to ensure that the layout adheres to manufacturing rules and matches the synthesized netlist.

 **Tape-Out:**
    - Prepare the final design files for manufacturing, including the GDSII file, which contains the layout information.
    - Verify that the design is ready for fabrication.

    **FINAL GDS VIEW**

   ![Screenshot 2023-08-24 131424](https://github.com/NiharGowdaS/ASIC-Design-Flow-using-Openlane/assets/77974814/d93fd03b-390c-4378-9d77-96396d0c6d02)



