---
title: b'Motor controller'
permalink: b'wiki/Motor_controller/'
layout: wiki
tags:
 - Automation
 - BEV components
 - Electrical engineering
 - Electrical engineering
 - Electric motors
 - Electromagnetic components
 - Power components
 - Power electronics
---

A **motor controller** is a device or group of devices that serves to
govern in some predetermined manner the performance of an [electric
motor](electric_motor "wikilink"). A motor controller might include a
manual or automatic means for starting and stopping the motor, selecting
forward or reverse rotation, selecting and regulating the speed,
regulating or limiting the torque, and protecting against overloads and
faults.

Scope of motor controller applications
--------------------------------------

The scope of motor control technology must be very wide to accommodate
the wide variety of motor applications.

### Domestic applications

Electric motors are used domestically in [personal care
products](small_appliance "wikilink"),
[small](small_appliance "wikilink") and
[large](major_appliance "wikilink") appliances, and residential heating
and cooling equipment. In most domestic applications, the motor
controller functions are built into the product. In some cases, such as
bathroom ventilation fans, the motor is controlled by a switch on the
wall. Some appliances have provisions for controlling the speed of the
motor. Built-in circuit breakers protect some appliance motors, but most
are unprotected except that the household fuse or circuit breaker panel
disconnects the motor if it fails.

### Office equipment, medical equipment etc.

There is a wide variety of motorized office equipment such as personal
computers, computer peripherals, copy machines and fax machines as well
as smaller items such as electric pencil sharpeners. Motor controllers
for these types of equipment are built into the equipment. Some quite
sophisticated motor controllers are used to control the motors in
computer disc drives. Medical equipment may include very sophisticated
motor controllers.

### Commercial applications

Commercial buildings have larger heating ventilation and air
conditioning ([HVAC](/wiki/HVAC "wikilink")) equipment than that found in
individual residences. In addition, motors are used for elevators,
escalators and other applications. In commercial applications, the motor
control functions are sometimes built into the motor-driven equipment
and sometimes installed separately.

### Industrial applications

Many industrial applications are dependent upon motors (or machines),
which range from the size of your thumb to the size of a railroad
locomotive. The motor controllers can be built into the driven
equipment, installed separately, installed in an enclosure along with
other machine control equipment or installed in motor control centers.
Motor control centers are multi-compartment steel enclosures designed to
enclose many motor controllers. It is also common for more than one
motor controller to operate a number of motors in the same application.
In this case the controllers communicate with each other so they can
work the motors together as a team.

### Vehicle applications

All types of engine-driven vehicles from automobiles, airplanes,
aircraft carriers and agricultural equipment to
[zambonis](/wiki/Ice_resurfacer "wikilink") may have electric motors to
perform a variety of functions. In [electric
vehicles](electric_vehicles "wikilink"),
[diesel-electric](diesel-electric "wikilink") vehicles, and [hybrid
vehicles](hybrid_vehicles "wikilink"), electric motors are used to
propel the vehicle. The motor controllers in vehicle applications are
integrated into the vehicle.

### Power tools

[Power tools](/wiki/Power_tools "wikilink") such as drills, saws and sanders
are widely used by home owners, hobbyists, construction and repair
trades people, and industrial workers. Both portable and stationary
power tools usually have built in motor controllers and often include an
adjustable speed feature.

### Hobby equipment

A variety of hobbies make use of specialized motorized equipment that is
similar to domestic appliances or portable tools.

[Radio controlled (R/C)](/wiki/Radio_control "wikilink")
[models](scale_model "wikilink") may include fairly sophisticated motor
controllers. The motor controllers are ultimately built into the
equipment, but the hobbyist may purchase the controller separately or
construct it.

[Robotics](/wiki/Robot "wikilink") is another area in which the hobbyist may
purchase a motor controller as a separate item or construct it.

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
