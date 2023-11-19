Elegoo Neptune 4 Pro - Power usage
==================================
All the listed power numbers are the TOTAL USED at any given time/test.
The N4Pro has a "400W" power supply unit. The real manufacturer of that
recommends only running their power supplies at 80% of the rated value.
That means only using a maximum of 320W from a "400W" rated power supply!

The real "typical" maximums are going to be when the Hotend AND Beds are
being heated up, at the same time. You typically would NOT be printing at
this time. But you yourself MIGHT happen to Home the printer at that same
time - which would add some small extra power amount to the total.

You can see that the N4Pro reaches as high as the 375W region for various
cases of heating the Bed/s, or with the Hotend heating also. This is OVER
the manufacturers recommended "80% maximum" - that "320W" maximum. The
power supply will COPE with up to 400W, but its efficiency, operating
temperatures, Voltage stability, and lifespan will be compromised when
the load level is over that "320W".
It SHOULD have been supplied with a 500W power supply at least!

.

1. Powered on, fully booted, and sitting idle:
   
   11.0 W
   
   The X,Y,Z Axis have not been Homed, so the Stepper Motors are not in
   "Hold" mode now, thus less total power is in use - for now.


2. Home ALL.  The X&Y Axis move together, but then only the Z Axis moves to
   complete this:
   
   31W

3. Idle Power when the Steppers are being "Held", which is the more normal
   state they are typically in - especially after being "Homed" (all).
   
   22.5W

4. X or Y Axis motion - medium speed. Each Stepper Motor uses 5W - 7W more
   than at "hold" to move at a medium speed pace.

5. Z Axis motion. The Z Axis only uses 1W more than for HOLD, when moved.

6. Hotend Target 200degC - Max Heating being used:

   80W, for almost the whole way to Target Temp.

   It takes 1.1 minutes to reach Target Temp and then uses approx:

   40W regions in short runs, to maintain the Target Temp.

7. Heated Beds (BOTH) Target 60degC - Max heating being used.

   305W, reducing to the 272W region quite quickly as it heats up.
   
   It takes 2.5 Mins to reach target and uses 272W for the majority of the way.

8. Heated Bed - INNER. Target 60degC - Max heating being used:

   137W, reducing to 130W quite quickly as it heats up.

    It takes about 3 minutes to reach the Target Temp.

9. Heated Bed - OUTER. Target 60degC - Max heating being used:
   
   176W, for the majority of the time as it heats up.

10. BOTH the Hotend and the BOTH Heated Beds operating. Hotend 200DegC, Beds 60degC:

    360W, reducing to 340W quite quickly, then down to 295W for the main heating
    time (2mins approx).

    Then it can run across a range of just 40W to 200W, as it maintains the
    Target Temps.

11. One typical printing case. A reasonably large object that then uses
    reasonably large X & Y Axis moves:

    Heating up:

    Printing:
	
12. One typical printing case. A reasonably small object that then uses
    reasonably small X & Y Axis moves - The Elegoo supplied 18min Benchy.

    Heating up:  80W... then 330W... then 220W... then 50W...

    Not really excessive in the recommended maximum Power levels used.

    Printing:    55W... then 80W... then 92W... generally in the 78W - 85W region.

    But later in the print, about 50% region, it used 230W region for quite a long period.
    It would have been heating the Bed Heaters at maximums for that period.
	




