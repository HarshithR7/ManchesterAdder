# 8-Bit Manchester Adder Using Pass Transistors
 
The development of an 8-bit Manchester adder using pass transistor logic in Cadence Virtuoso represents a significant advancement in digital circuit design. This innovative approach achieved remarkable improvements in power efficiency, area utilization, and speed compared to traditional CMOS technology. The optimized circuit design utilized only 208 transistors, with each 1-bit adder requiring just 26 transistors, resulting in a compact layout and reduced power consumption.

Post-layout simulations revealed impressive performance metrics for the adder. The circuit demonstrated a power dissipation of 17.591 μW and a propagation delay of 411.099 pSec, showcasing its high-speed capabilities and energy efficiency. These results underscore the potential of pass transistor logic in creating fast and power-efficient digital circuits.

A key aspect of the design was the implementation of all basic logic gates (NAND, NOR, INVERTER, EX-OR) using pass transistors. This approach further minimized the transistor count and optimized overall circuit efficiency, contributing to the adder's compact size and improved performance characteristics.

To ensure the manufacturability and correctness of the layout, thorough design verification was conducted through Design Rule Check (DRC) and Layout Versus Schematic (LVS) checks. These steps are crucial in the integrated circuit design process, validating that the physical layout adheres to manufacturing constraints and accurately represents the intended circuit schematic.

Finally, comprehensive post-layout validation was performed using Quantus Extraction. This step was essential in validating the design's performance characteristics and accounting for parasitic effects that can impact circuit behavior in real-world applications. The validation process provides confidence in the adder's ability to meet its performance targets when fabricated.
