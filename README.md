# EKill-v2
A new EKill board, slightly modifed from Liam's previous board to support more motors and handle unexpected errors on the PWM line.

To run the simulation files in Sim_Parts, you should be able to open KillSwitch2.asc from LTSpice XVII, and it should work. If you really want to understand how the logic works, the best way is to simply monitor the capacitor voltage and compare it with the PWM wave. Change the time that the PWM wave is on from 1.45 ms to 1.5 ms and back to see the timing threshold in action.

Similarly, I have the Eagle libraries organized the way they are so that anyone can simply open the main eagle project and have it just work. Though it does sacrifice some neatness.

If you want to see the parts that the footprints in the board files correspond to, open up the sole excel file in Sim_Parts.


