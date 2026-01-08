Project Title: Digital Up/Down Counter using CD40110 IC
Project Overview This project demonstrates a digital counter capable of counting numbers in both ascending and descending order (0 to 9) upon receiving a clock pulse. The circuit is designed around the CD40110 BE, a specialized CMOS Decade Up/Down Counter IC that features an integrated decoder and driver.

Key Working Principle Unlike standard counters that require separate Binary-Coded Decimal (BCD) counters (like the 74LS192) and 7-segment decoders (like the 74LS47), the CD40110 performs all these functions in a single chip.

Counting Up: When a clock pulse (via a push button or clock source) is applied to the Clock Up (CPU) pin, the internal logic increments the value.

Counting Down: When a pulse is applied to the Clock Down (CPD) pin, the value decrements.

Display: The IC outputs directly to a 7-Segment LED Display (typically Common Cathode) without needing external resistors or driver transistors for basic operation.

Key Features

Single-Chip Solution: Reduces circuit complexity and wiring by combining the counter, latch, and driver.

Dual Clock Inputs: Separate inputs for incrementing and decrementing.

Cascadable: Includes Borrow and Carry pins to easily chain multiple ICs for 2-digit (0-99) or 3-digit counters.

Typical Applications

Visitor counters (entering/exiting a room).

Digital scoreboards.

Parking lot capacity systems
