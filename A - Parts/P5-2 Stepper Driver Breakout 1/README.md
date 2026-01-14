# P5-2 - Stepper Driver Breakout 1

Host board for three DRV8825 stepper driver modules (see part P5-2-2).
Thes boards are capable of microstepping. The breakout board connected the microstep
option pins M0, M1, M2 to !Sleep (called "Wake" here), so the boards are effectively
stuck in 1/32 step mode for maximum microstepping.

Connection numbers start at the red motor power wire and work around counter-clockwise.

Connections
	P5-2:1 	- Motor voltage (red wire). 
			8.2V up to 45V.
			2.5A maximum drive current at 24V and 25°C.

		:2 	- 0V (black wire)
			2.5A maximum drive current.

		:3  - Wake (yellow wire) 

		:4  - Driver 3 !Enable (white wire) (Enable low)
		:5  - Driver 3 Step (blue wire) 
		:6  - Driver 3 Direction (green wire)

		:7	- Driver 2 !Enable (white wire) (Enable low)
		:8  - Driver 2 Step (blue wire)
		:9  - Driver 2 Direction (green wire)

		:10 - Driver 1 !Enable (white wire) (Enable low)
		:11 - Driver 1 Step (blue wire)
		:12 - Driver 1 Direction (green wire)

		:13 - Driver 1 DRIVE B1
		:14 - Driver 1 DRIVE B2
		:15 - Driver 1 DRIVE A1
		:16 - Driver 1 DRIVE A2

		:17 - Driver 2 DRIVE B1
		:18 - Driver 2 DRIVE B2
		:19 - Driver 2 DRIVE A1
		:20 - Driver 2 DRIVE A2

		:21 - Driver 3 DRIVE B1
		:22 - Driver 3 DRIVE B2
		:23 - Driver 3 DRIVE A1
		:24 - Driver 3 DRIVE A2