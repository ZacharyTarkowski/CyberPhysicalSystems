# CyberPhysicalSystems
Servomotor closed loop control project

Note: You need to solder a wire to the middle pin of the servo potentiometer to implement closed loop control. 
Otherwise its open loop and you don't actually know where your servo arm is after you detatch it

Sweep characterizes most values your ADC will read from the servo potentiometer. "Gentle" changes, ramping up and down.
Swing characterizes steady state values read by the ADC, at 180 and 0 degrees. Should swing significantly higher than the 180 steady state because of the rapid change.
Basic feedback is moving the arm back to 180 after moving it past a certain degree.

