# Digital_Alarm_Clock
This project implements a 24-hour digital alarm clock using Verilog HDL.
The design supports loading the current time, setting an alarm, enabling/disabling the alarm, and generating a 1-second internal tick from a high-frequency clock.

# Features

1. 24-hour time format (HH:MM:SS)
2. Load current time (LD_time)
3. Set alarm time (LD_alarm)
4. Alarm enable (AL_ON) and alarm stop (STOP_al)
5. Internally generated 1-second clock from input clk
6. Timekeeping using hour, minute, and second counters
7. Alarm triggers when current time matches stored alarm time
8. All outputs provided in BCD format (H_out1, H_out0, M_out1, etc.)
9. Fully synthesizable sequential design
