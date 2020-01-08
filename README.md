# Temperature_Controlled_Fan

The main aim of this project is to calculate and monitor the surrounding temperature and change the speed of the fan as temperature changes i.e. the speed should increase with a rise in temperature and should decrease with a drop in temperature. The temperature would be displayed through the LCD which is interfaced by the 8051 microcontroller. The FAN is controlled by a PWM wave given to it by the microcontroller, the power given to the fan is lesser in low temperature and greater in high temperature.

# Objective

The objective of this project is to make a Fan whose speed is controlled by temperature. The idea behind the project is that we have a temperature sensor which senses the temperature and give the output in analog form which then is fed to ADC to convert it to digital signal (with values in HEX format), the output of ADC is given to the microcontroller. Now according to the temperature we are going to control speed of the dc fan which depends on the technique Pulse width modulation, as the width varies, the delay varies as a result of that the speed of the fan varies accordingly.

#	Benefits

By controlling the speed of the fan at different temperature’s we save a lot of energy throughout the day. Instead of a fan running at full speed all day which requires a lot of energy, if the speed is controlled and given as necessary we can save a lot of energy.

# Working

	 The main principle behind the working is PWM i.e. pulse width modulation.

	 It is a technique for controlling the power output given to different electric devices.

	 The average value of voltage (and current) fed to the load is controlled by turning the switch between supply and load on and off at a fast pace. The longer the switch is on compared to the off periods, the higher the power supplied to the load is.

	 So if the switch is on for a longer time then more power will be delivered to the fan and it will rotate faster.

	 We can program the micro controller in such a way that when the temperature is higher, the switch remains on for a longer duration and when it is lower, switch remains on for a shorter duration.

# Components

	Microcontroller AT89C52

	ADC0804

 16*2 LCD Display

	Temperature Sensor LM35

	Resistors

	Capacitors

	Diodes

	Crystal Oscillator 12MHz

	Electric Fan

	Voltage Regulator (7805)

	Potentiometer (10K)

