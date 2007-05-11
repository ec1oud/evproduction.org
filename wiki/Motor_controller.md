---
title: b'Motor controller'
permalink: b'wiki/Motor_controller/'
layout: wiki
tags:
 - BEV components
 - Electric motors
---

An EV **motor controller** is a device or group of devices that serves
to govern in some predetermined manner the performance of a vehicle
drive [electric motor](electric_motor "wikilink"). A motor controller
might include a manual or automatic means for starting and stopping the
motor, selecting forward or reverse rotation, selecting and regulating
the speed, regulating or limiting the torque, and protecting against
overloads and faults.

Vehicle applications
--------------------

All types of engine-driven vehicles from automobiles, airplanes,
aircraft carriers and agricultural equipment to
[zambonis](/wiki/Ice_resurfacer "wikilink") may have electric motors to
perform a variety of functions. In [electric
vehicles](electric_vehicles "wikilink"),
[diesel-electric](diesel-electric "wikilink") vehicles, and [hybrid
vehicles](hybrid_vehicles "wikilink"), electric motors are used to
propel the vehicle. The motor controllers in vehicle applications are
integrated into the vehicle.

Types of motor controllers
--------------------------

An electric motor controller can be classified by the type of motor it
is to drive such as [permanent magnet](permanent_magnet "wikilink"),
[servo](servomechanism "wikilink"), series, separately excited, and
[alternating current](alternating_current "wikilink").

A motor controller is connected to a power source such as a battery pack
or power supply, and control circuitry in the form of analog or digital
input signals.

Specific motor controller descriptions
--------------------------------------

### H-bridge

DC motors are typically controlled by using a transistor configuration
called an "[H-bridge](/wiki/H-bridge "wikilink")". This consists of a minimum
of four mechanical or solid-state switches, such as two NPN and two PNP
transistors. One NPN and one PNP transistor are activated at a time.
Both NPN or PNP transistors can be activated to cause a short across the
motor terminals, which can be useful for slowing down the motor from the
back [EMF](electromotive_force "wikilink") it creates.

### Servo controllers

Most [servos](servomechanism "wikilink") are controlled using
[pulse-width modulation](pulse-width_modulation "wikilink") (PWM). How
long the pulse remains high (typically between 1 and 2 milliseconds)
determines where the motor will try to position itself. The controller
must know the motor's position in order to know how to move it. To find
the position of the motor some designs use [Hall effect
sensors](/wiki/Hall_effect_sensor "wikilink") to directly measure the
[rotor](/wiki/Rotor_(electric) "wikilink")'s position. Others measure the back
[EMF](electromotive_force "wikilink") in the undriven coils to infer the
rotor position, eliminating the need for separate Hall effect sensors,
and therefore are often called "sensorless" controllers. A [variable
resistor](potentiometer "wikilink") can also be used to determine the
motor's position.

### Stepper motor controllers

Stepper motors are moved by rotating which coil to apply electricity to
in a circular manner. They are controlled by a timing circuit. This
allows extremely accurate control by changing the clock speed for the
next firing. Typically these are used in printers where precise
positioning is necessary and must be done in the cheapest way possible.

### References

-   -   -   [Links to manufacturers, associations, and other
    resources](http://www.motorcontrol.com)
-   [Control Solutions, Inc.](http://www.controls.com) - Manufacturer of
    brushed DC motor controllers

Software
--------

-   [Parallel Port PWM/Encoder Linux
    Driver](http://cole.homedns.org/parallelport_pwm_driver.php) - a
    poor-mans motor controller software driver

See also
--------

-   [Motor Soft Starter](/wiki/Motor_Soft_Starter "wikilink")
-   [Direct on line starter](/wiki/Direct_on_line_starter "wikilink")
-   [Adjustable-speed drive](/wiki/Adjustable-speed_drive "wikilink")
-   [Electronic speed control](/wiki/Electronic_speed_control "wikilink")
-   [Variable-frequency drive](/wiki/Variable-frequency_drive "wikilink")
-   [Thyristor drive](/wiki/Thyristor_drive "wikilink")
-   [DC motor starter](/wiki/Electric_motor#DC_motor_starters "wikilink")
    section of [Electric motor](/wiki/Electric_motor "wikilink")

External links
--------------

### Battery electric vehicles

-   [Zilla motor controller](http://www.cafeelectric.com/).
