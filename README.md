# Neptune-4-Pro---Power-usage-tests
Tests of how much Power the N4Pro uses for various operations it can do. 

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

You can see that the N4Pro never really runs over about 290W at the very
maximums you would ever really use at once.  That is under the manufacturers
recommended maximum, and should be low ripple/noise, good stability, and
good for long term lifespan.


1.	Powered on, fully booted, and sitting idle:
	11.0 W
	The X,Y,Z Axis have not been Homed, so the Stepper Motors are not in
	"Hold" mode now, thus less total power is in use - for now.

3.    Idle Power when the Steppers are being "Held", which is the more normal
    state they are typically in. Once Homed the Steppers are left "Held":
	22.5W

4.    Home ALL.  The X&Y Axis move together, but then only the Z Axis moves to 
    	complete this:
	31W

5.	X or Y Axis motion - medium speed. Each Stepper Motor uses 5W - 7W more
	than at "hold" to move at a medium speed pace.

6.	Z Axis motion. The Z Axis only uses 1W more than for HOLD, when moved.

7.	Hotend Target 200degC - Max Heating being used:
	80W, for almost the whole way to Target Temp.
	It takes 1.1 minutes to reach Target Temp and then uses approx:
	40W regions in short runs, to maintain the Target Temp.

8.	Heated Beds (BOTH) Target 60degC - Max heating being used.
	305W, reducing to the 272W region quite quickly as it heats up.
	It takes 2.5 Mins to reach target and uses 272W for the majority of the way.

9.	Heated Bed - INNER. Target 60degC - Max heating being used.
	375W, reducing to 360W quite quickly as it heats up.

10.	Heated Bed - OUTER. Target 60degC - Max heating being used.
	375W, reducing to 360W quite quickly as it heats up.

11.	BOTH the Hotend and the BOTH Heated Beds operating. Hotend 200DegC, Beds 60degC:


12.	One typical printing case. A reasonably large object that then uses
	reasonably large X & Y Axis moves:
	Heating up:
	Printing:
	

13.	One typical printing case. A reasonably small object that then uses
	reasonably small X & Y Axis moves:
	Heating up:
	Printing:
	




